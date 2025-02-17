# Task 2 Do (T2D)

🌎 Aplicação Web com frontend e backend desenvolvidos com o intuito de melhorar a gerência de projetos em trabalhos colaborativos, usando uma interface moderna e intuitiva

- [ ] TODO: Banner da aplicação

## Equipe de Desenvolvimento

| Nome                                                  | Funções             |
| :---------------------------------------------------- | :------------------ |
| [swshadows](https://github.com/swshadows)             | 🎲 Backend & Design |
| [leonardosilva97](https://github.com/leonardosilva97) | 🎲                  |
| [EndrewDias](https://github.com/EndrewDias)           | 🎲                  |
| [David-TM12](https://github.com/David-TM12)           | 🎲                  |

## Inicialização

<div align=center>

### Requisitos

[Node.js](https://nodejs.org/) & [MySQL](https://www.mysql.com)

</div>

- Use os comandos para clonar o repositório

  ```bash
  git clone https://github.com/swshadows/t2d.git
  cd t2d
  ```

#### Backend

- Crie um arquivo em `backend` chamado `.env`

  ```bash
  SESSION_SECRET="" # Pode ser uma string qualquer, ex: secret
  DATABASE_URL="mysql://USERNAME:PASSWORD@localhost:3306/t2d?schema=public" # Substitua USERNAME e PASSWORD pelo user e senha do seu banco
  ```

- Rode os seguintes comandos

  ```bash
  cd ./backend        # Acessa a pasta do backend
  npm install         # Instala as dependências
  npm run db:migrate  # Inicializa o banco de dados
  npm run dev         # Inicializa a API da aplicação
  ```

#### Frontend

- [ ] TODO: Todo resto dos comandos de inicialização

### Outros Links

<div align="center">
  <a href="https://www.figma.com/file/CDndKafGEFGguqoAbOHAy6/t2d?node-id=0%3A1&t=uzCfg4433CiQfOc2-1">
    <img width=40 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg">
    <p>Protótipo no Figma</p>
  </a>
</div>
