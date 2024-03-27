# modulo1-web-blazor

## 

[Introdução ao desenvolvimento para a Web com o Blazor](https://learn.microsoft.com/pt-br/training/modules/blazor-introduction/)

##

## Objetivos de aprendizagem
Ao final deste módulo, você saberá como:

- Avalie se o Blazor é apropriado para seu próximo projeto de desenvolvimento na Web.
- Descreva como o Blazor funciona para a criação de aplicativos Web.

## Verificação do ambiente

**Verificando o(s) framewok(s) instalado(s) ou disponível(is):**

`$ dotnet --list-sdks`

    5.0.400 [C:\Program Files\dotnet\sdk]
    7.0.400 [C:\Program Files\dotnet\sdk]
    8.0.101 [C:\Program Files\dotnet\sdk]

**Instalando um SDK de preferência**

Suponha que minha aplicação obrigatoriamente rode no .NET 6, assim, podemos instaká-lo através do comando:

`winget install Microsoft.DotNet.SDK.6`

## Instalando a aplicação

**Comando de criação de criação de um aplicativo blazor básico:**
- `dotnet new blazor`: cria uma nova aplicação do blazor
- `-o`: criação da nova pasta chamada "modulo1-web-blazor" onde será instalado o aplicativo
- `-f net8.0`: força que a aplicação faça uso do framework .NET de versão 8.0

    $ dotnet new blazor -o modulo1-web-blazor -f net8.0

**Construção da solução:**

    $ dotnet build

**Colocando a solução para rodar:**

    $ dotnet watch

Após o comando acima, deverá abrir automaticamente uma página no seu navegador padrão, muito provavelmente abrirá no endereço local: http://localhost:5106/

## Material de Suporte


## Agradecimentos:

- Microsoft
- ao IBGE
