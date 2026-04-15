# Desafio Estacionamento

Este projeto é um sistema de estacionamento simples em C# (.NET) que permite cadastrar veículos, remover veículos e listar os veículos estacionados.

## Descrição

O programa solicita ao usuário o preço inicial do estacionamento e o preço por hora. Em seguida, exibe um menu com as seguintes opções:

1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

Ao remover um veículo, o sistema pede a placa e a quantidade de horas que o veículo permaneceu no estacionamento, calcula o valor total e remove o veículo da lista.

## Estrutura do projeto

- `Program.cs` - ponto de entrada do aplicativo e interface de menu.
- `Models/Estacionamento.cs` - classe responsável pela lógica de adicionar, remover e listar veículos.
- `Informações Desafio.txt` - descrição do exercício original.

## Como executar

1. Abra o terminal na pasta do projeto `C:\DesafioEstacionamento`.
2. Execute o comando:

```bash
dotnet run
```

3. Siga as instruções exibidas na tela:
   - Informe o preço inicial
   - Informe o preço por hora
   - Use as opções do menu para gerenciar os veículos

## Funcionalidades

- Adicionar veículo por placa
- Remover veículo por placa
- Calcular valor total ao remover veículo
- Listar veículos estacionados
- Finalizar execução

## Observações

- A placa do veículo é armazenada em uma lista de strings.
- O cálculo do valor total é feito com a fórmula:

```text
valorTotal = precoInicial + precoPorHora * horas
```

- Ao remover um veículo, o sistema verifica se a placa existe antes de efetuar a remoção.

## Requisitos

- .NET SDK instalado
- Sistema operacional compatível com .NET
