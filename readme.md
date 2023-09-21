# Documentação da API
Definir um local do computador para criar a pasta do projeto
```
mkdir NOME_PROJETO
```
Acessar a pasta do projeto
```
cd NOME_PROJETO
```
Abrir a pasta no VSCode
```
code . 
```
Iniciar gerenciador de pacote node
```
npm init -y
```
Criar o arquivo .gitignore
```
touch .gitignore
```
Criar o arquivo .env
```
touch .env
```
Instalar os pacotes oara rodar a API
```
npm i express nodemon dotenv
```
* express: será o servidor da api
* nodemon: Atualizar os arquivos alterados sem parar o servidor
* dotenv: Gerenciador de variáveis de ambiente

Adicionar pastas e arquivos no .gitignore
```
node_modules
.env
```