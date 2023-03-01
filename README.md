# make1-your-buguer
<p align="center">
  <a href="#">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technology">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-back-end">Back-End</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-installation">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  

 
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=49AA26&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

# 💻 Project:
This project was created with the Quasar framework, which is a user registration.

## 🚀 Technology:

Front-end:
* HMTL
* SCSS
* JAVASCRIPT
* vue.js

Back-end:
* db.json
```
{
  "ingredientes": {
    "paes": [
      {
        "id": 1,
        "tipo": "Italiano Branco"
      },
      {
        "id": 2,
        "tipo": "3 Queijos"
      },
      {
        "id": 3,
        "tipo": "Parmesão e Orégano"
      },
      {
        "id": 4,
        "tipo": "Integral"
      }
    ],
    "carnes": [
      {
        "id": 1,
        "tipo": "Maminha"
      },
      {
        "id": 2,
        "tipo": "Alcatra"
      },
      {
        "id": 3,
        "tipo": "Picanha"
      },
      {
        "id": 4,
        "tipo": "Veggie burger"
      }
    ],
    "opcionais": [
      {
        "id": 1,
        "tipo": "Bacon"
      },
      {
        "id": 2,
        "tipo": "Cheddar"
      },
      {
        "id": 3,
        "tipo": "Salame"
      },
      {
        "id": 4,
        "tipo": "Tomate"
      },
      {
        "id": 4,
        "tipo": "Cebola roxa"
      },
      {
        "id": 4,
        "tipo": "Pepino"
      }
    ]
  },
  "status": [
    {
      "id": 1,
      "tipo": "Solicitado"
    },
    {
      "id": 2,
      "tipo": "Em produção"
    },
    {
      "id": 3,
      "tipo": "Finalizado"
    }
  ],
  "burgers": [
    {
      "nome": "Matheus Battisti",
      "carne": "Picanha",
      "pao": "Italiano Branco",
      "opcionais": [
        "Bacon",
        "Salame",
        "Cebola roxa"
      ],
      "status": "Finalizado",
      "id": 1
    },
    {
      "nome": "João Coelho",
      "carne": "Maminha",
      "pao": "3 Queijos",
      "opcionais": [
        "Salame",
        "Cebola roxa"
      ],
      "status": "Solicitado",
      "id": 4
    }
  ]
}
```
## 🔖 Back-End:
run backend:
```
npm run backend
```

## 🔖 Installation
A Vue Project

## Install the dependencies

```
yarn install
npm install
```

### Compiles and hot-reloads for development
```
yarn run serve
npm run serve
```

### Compiles and minifies for production
```
yarn build
npm build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
