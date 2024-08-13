# Nest Clean

## Project Setup - Configuração do Projeto

#### Executar o comando para clonar o projeto

##### Abrir o terminal em uma pasta desejada e executar o comando abaixo

```sh
git clone https://github.com/RamonPessoaDev/ignite-nest-clean
```

#### 1º Executar esse comando após clonar o projeto para instalação das dependências

```sh
pnpm add
```

#### 2º Caso não tenha o pnpm

```sh
npm i -g pnpm
```

### 3º Após isso executar o comando do 1º passo<br><br>

### 4º Criar um arquivo .env, seguindo o arquivo de ajuda .env.example<br><br>

### 5º Ter o dcoker instalado na máquina e executar o comando

```sh
docker compose up -d
```

### 6º Após isso executar o comando para criar as tabelas no banco de dados

```sh
pnpm prisma migrate dev
```

### 7º Iniciar o projeto localmente

```sh
pnpm start:dev
```

## Principais tecnologias utilizadas

- NestJS 💻
- Docker ⚡
