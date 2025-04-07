# ⚽Champions League

## Descrição
Uma API REST desenvolvida com Node.js e Express que disponibiliza os clubes e jogadores da Champions League. A API permite criar, ler, 
atualizar e excluir informações de jogadores, além de listar os clubes. Projeto desenvolvido durante a Formação Node.js da DIO.

## Rotas da Api
### 👤 Rota dos jogadores
- GET /api/players: Retorna uma lista de todos os jogadores.

``` js
[
   {
    "id": 1,
    "name": "Lionel Messi",
    "club": "Inter Miami",
    "nationality": "Argentina",
    "position": "Forward",
    "statistics": {
      "Overall": 93,
      "Pace": 80,
      "Shooting": 92,
      "Passing": 91,
      "Dribbling": 95,
      "Defending": 34,
      "Physical": 65
    }
  },
  {
    "id": 2,
    "name": "Cristiano Ronaldo",
    "club": "Al Nassr",
    "nationality": "Portugal",
    "position": "Forward",
    "statistics": {
      "Overall": 88,
      "Pace": 81,
      "Shooting": 92,
      "Passing": 78,
      "Dribbling": 84,
      "Defending": 34,
      "Physical": 75
    }
  },
]
````

### 🏟️ Rotas de Clubes
- GET /api/clubs: Retorna uma lista de todos os clubes.

``` js
[
  {
    "id": 1,
    "name": "Real Madrid"
  },
  {
    "id": 2,
    "name": "Barcelona"
  },
]
````

## Tecnologias
- [Express](https://expressjs.com/)
- [CORS](https://www.npmjs.com/package/cors)
- [@types/node](https://www.npmjs.com/package/@types/node)
- [tsup](https://www.npmjs.com/package/tsup)
- [tsx](https://www.npmjs.com/package/tsx)
- [TypeScript](https://www.typescriptlang.org/)
- [@types/cors](https://www.npmjs.com/package/@types/cors)
- [@types/express](https://www.npmjs.com/package/@types/express)

## Como Utilizar
1. Clone este repositório.
2. Instale as dependências usando npm install.
3. Inicie o servidor executando npm start:dev.
4. Acesse os endpoints fornecidos para listar os jogadores e os clubs.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
