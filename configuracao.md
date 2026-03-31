# Configuração do Ambiente

Este documento descreve o passo a passo realizado em aula para configurar o ambiente de desenvolvimento.

## 1. Instalação das ferramentas

Foram instaladas as seguintes ferramentas:

- Git
- Node.js
- VS Code

O Node.js permite executar JavaScript fora do navegador e o npm é utilizado para gerenciar pacotes do projeto.

## 2. Verificação das instalações

Após a instalação, foram utilizados os seguintes comandos no terminal:

node -v  
npm -v  
git --version  

Esses comandos servem para verificar se as ferramentas foram instaladas corretamente.

## 3. Clonar o repositório

Foi utilizado o comando:

git clone <url-do-repositorio>

Em seguida, acessamos a pasta do projeto:

cd nome-do-projeto

## 4. Instalar dependências

Dentro da pasta do projeto, executamos:

npm install

Esse comando instala todas as dependências listadas no arquivo package.json do projeto.

## 5. Executar o projeto

Para iniciar o projeto, utilizamos:

npm start

ou

npm run dev

## 6. Acessar o sistema

Após iniciar o servidor, acessamos no navegador:

http://localhost:3000

## 7. Considerações finais

- Sempre executar npm install ao baixar o projeto
- Utilizar a versão LTS do Node.js (mais estável)
- Verificar se as portas utilizadas estão disponíveis
