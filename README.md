# DIO - Trilha .NET - Fundamentos

Curso em .NET realizado pela DIO (www.dio.me)

## Desafio de projeto
Construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Descrição 
Para representar o sistema de estacionamento e permitir as operações de adicionar, remover e listar os veículos, o objeto foi representado através da Classe Estacionamento:
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

A classe contém três variáveis, sendo:

**precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

**precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

**veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

**AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

**RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

**ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Para acesso aos métodos, foi desenvolvido um menu interativo (switch case) com as seguintes ações:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

## IDE
Visual Studio Code - Version 1.87.2

Desenvolvedora: Avany Souza

