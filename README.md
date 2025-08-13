# DIO - Trilha .NET - Programação orientada a objetos
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de orientação a objetos, da trilha .NET da DIO.

## Contexto
Você é responsável por modelar um sistema que trabalha com celulares. Para isso, foi solicitado que você faça uma abstração de um celular e disponibilize maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## Proposta
Você precisa criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 
Você deve criar as suas classes de acordo com o diagrama abaixo:

![Diagrama classes](Imagens/diagrama.png)

## Regras e validações
1. A classe **Smartphone** deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.
2. A classe **Nokia** e **Iphone** devem ser classes filhas de Smartphone.
3. O método **InstalarAplicativo** deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.

## Solução
Status: Concluída.

A solução foi implementada conforme o diagrama e as regras propostas, com uma classe base abstrata para o smartphone e implementações específicas para duas marcas, incluindo a sobrescrita do método de instalação de aplicativos. O programa é um console app em .NET 6 e demonstra as operações básicas de um celular (ligar, receber ligação, instalar aplicativos, etc.).

### Como executar
Pré-requisitos:
- .NET 6 SDK instalado

Passos:
1. Abra o projeto em sua IDE de preferência ou via terminal.
2. No terminal, navegue até a pasta do projeto de console (onde está o arquivo .csproj do aplicativo).
3. Execute:
   - dotnet restore
   - dotnet build
   - dotnet run

Alternativamente, você pode executar diretamente pela IDE usando a configuração de execução padrão.

### Observações
- O foco da implementação é demonstrar os conceitos de abstração, herança e polimorfismo.
- As mensagens no console auxiliam a visualizar o comportamento específico de cada modelo.