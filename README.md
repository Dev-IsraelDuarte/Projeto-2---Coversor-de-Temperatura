# ConversorTemperatura

Aplicação de console desenvolvida em C# para converter temperaturas
entre Celsius e Fahrenheit.

## Objetivo

O projeto permite realizar conversões de graus Celsius para Fahrenheit e
de Fahrenheit para Celsius.

## Como executar

### Pré-requisito

-   Ter o SDK do .NET instalado.

### Executar a aplicação

Abra o terminal na pasta principal do projeto (`ConversorTemperatura`) e
execute:

``` bash
dotnet run --project .\ConversorTemperatura.App\ConversorTemperatura.App.csproj
```

Informe a temperatura em Celsius quando solicitado. O programa
apresentará o valor correspondente em Fahrenheit.

## Testes automatizados

O projeto utiliza testes unitários com xUnit para verificar as
conversões nos dois sentidos:

-   Celsius para Fahrenheit.
-   Fahrenheit para Celsius.

Para executar os testes, use:

``` bash
dotnet test .\ConversorTemperatura.sln
```

Para verificar a compilação da solução:

``` bash
dotnet build .\ConversorTemperatura.sln
```

## Estrutura do projeto

``` text
ConversorTemperatura/
├── ConversorTemperatura.sln
├── ConversorTemperatura.App/
│   ├── Program.cs
│   └── ConversorTemperatura.cs
└── ConversorTemperatura.Tests/
    └── ConversorTemperaturaTests.cs
```

## Resultado esperado

A aplicação deve apresentar a conversão de Celsius para Fahrenheit. Os
testes automatizados verificam também a conversão inversa, de Fahrenheit
para Celsius, e devem ser executados sem falhas.