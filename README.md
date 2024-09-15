# To-do List - Projeto Fullstack

Este projeto é composto por duas partes: **Frontend** (Next.js) e **Backend** (Node.js). A seguir, estão as instruções para configurar e rodar ambos os repositórios em sua máquina local.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado o seguinte:

- **Git**: Para clonar os repositórios.
- **Node.js**: Versão LTS (Recomenda-se a v18.x.x ou superior).
- **npm** e **yarn**: Para instalar dependências e rodar scripts.

## Clonando os Repositórios

Você precisará clonar os dois repositórios: o repositório do frontend (Next.js) e o repositório do backend (Node.js).

1. **Clone o repositório do Frontend:**

```bash
git clone https://github.com/usuario/frontend-repo.git
```

2. **Clone o repositório do Backend**

```bash
git clone https://github.com/usuario/backend-repo.git
```

## Configuração do Frontend

1. **Navegue até o diretório do frontend:**

```bash
cd To-do-list---frontend
```

2. **Instale as dependências:**

```bash
npm install
#ou
yarn install
```

3. **Execute o servidor de desenvolvimento:**

```bash
yarn dev
```

## Configuração do Backend

1. **Navegue até o repositório do backend:**

```bash
cd To-do-list---backend
```

2. **Instale as dependências:**

```bash
npm install
#ou
yarn install
```

3. **Crie um arquivo ```.env``` na raiz do projeto e configure as variáveis de ambiente. Um exemplo do arquivo ```.env``` pode ser:**

```.env
DATABASE_URL="mysql://youruser:yourpassword@port/database"
JWT_SECRET=suasenha
```

4. **Execute o servidor de desenvolvimento:**

```bash
yarn dev
```

## Conclusão

Agora, com ambos os servidores rodando, você pode acessar a aplicação frontend no navegador e ela se comunicará com o backend.

## Tecnologias Utilizadas

<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain-wordmark.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain-wordmark.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-plain.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-plain-wordmark.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-plain-wordmark.svg" width="40" height="40"/>
</div>
