# Task Painel (Pedro)

## Introdução

A task a qual fui designado, consistia em realizar uma pagina web que reproduzisse um video em full screen e em loop vindo diretamente do Youtube.

# Passo à Passo para:

## Criação do projeto

-   Instalação do GIT

-   Criação de uma pasta no PC

-   Abertura da pasta com o `VSCode`

-   Criação de um arquivo `README.md`

-   Digitação sobre as informações da task

## Criação do projeto

-   Execução do Git Bash

-   `git config --global user.name` para identificar o nome de quem realizou o commit

-   `git config --global user.email` para identificar o email de quem realizou o commit

-   `git init` para inicializar o repositório

-   `git add README.md` para colocar o arquivo na área de stagging

-   `git commit -m "first commit"` para de fato dar o commit no repositório

-   `git branch -M "main"` para alterar o nome da branch principal de `master` para `main`

## Criação do repositório no GitHub

-   Clicar em "Repositories"

-   Clicar em "New"

-   Dar um nome ao Repositório

-   Definir se o mesmo vai ser `Public` ou `Private`

-   Clicar em `Create repository`

## Criação do repositório remoto

-   Ainda no Git Bash

-   `git remote add origin <link do repositório>` para criar a conexão remota

-   `git push -u origin main` para enviar os arquivos do repositório local para o repositório remoto

# Desenvolvimento

## Desafios Enfrentados

No que diz respeito ao desenvolvimento de código em `HTML` e `CSS`, não enfrentei desafios significativos, uma vez que já havia estudaod projetos semelhantes previamente, por meio da plataforma de ensino `OneBitCode`. Um desses projetos consistiu na criação de uma [landing page](https://youtu.be/0GFaqwE32sU), na qual a primeira `section` continha um vídeo em loop, ocupando toda a extensão da mesma. Em contrapartida, a utilização do `Git` representou um desafio maior para mim. Tive dificuldades, principalmente, com os comandos, visto que esta foi minha primeira experiência com o software.

## Soluções Implementadas

Durante o desenvolvimento, estava utilizando a tag `<video>` para a exibição do video, e percebi que usar essa tag para reproduzir o video localmente não era o intuito do projeto. Através de pesquisas, percebi que a tag `<video>` poderia ser substituída pela tag `<iframe>`, permitindo a implementação direta dos vídeos do YouTube. Além disso, aproveitei a oportunidade para estudar o Git e o GitHub, de modo que ambos deixassem de ser um desafio.

## Lições Aprendidas

Durante o processo, aprendi bastante sobre o Git e o GitHub, desde o primeiro commit até o pull request. Também descobri quando e como usar a tag `<iframe>` no HTML, o que foi muito útil para integrar conteúdo externo ao meu projeto. Essas foram algumas das lições mais valiosas que levei dessa experiência.
