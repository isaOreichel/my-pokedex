
# 🔴 My Pokédex — React

Um projeto educacional para aprender **React (Frontend)** consumindo a **PokeAPI**, uma API pública gratuita de Pokémon.

O objetivo é construir uma Pokédex moderna, interativa e escalável enquanto aprende os principais conceitos do React e integração com APIs.

---

## 📚 Índice

* Visão Geral
* Estrutura do Projeto
* Pré-requisitos
* Instalação e Setup
* Tecnologias Utilizadas
* Arquitetura da Aplicação
* Consumo da PokeAPI
* Conceitos de React
* Como Executar
* Roadmap
* Troubleshooting
* Dicas de Estudo
* FAQ

---

## 📌 Visão Geral

Esta aplicação consome dados da **PokeAPI** para exibir:

* Lista de Pokémons
* Imagens oficiais
* Tipos
* Busca por nome
* Estados de carregamento e erro

Tudo isso usando **React com Vite**, **Axios** e **Tailwind CSS**.

---

## 🏗 Estrutura do Projeto

```
my-pokedex/
├── src/
│   ├── components/
│   │   ├── PokemonCard.jsx
│   │   └── PokemonDetail.jsx
│   ├── pages/
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```

---

## ✅ Pré-requisitos

* Node.js (v14 ou superior)
* npm ou yarn
* Visual Studio Code ou outro editor

Verifique:

```
node --version
npm --version
```

---

## 🚀 Instalação e Setup

```bash
cd c:\Users\isaol\repositorio\my-pokedex
npm create vite@latest . -- --template react
npm install
```

---

## ⚙️ Tecnologias Utilizadas

* React
* Vite
* Axios
* Tailwind CSS
* PokeAPI

---

## 🧠 Arquitetura da Aplicação

A aplicação segue a estrutura:

```
App.jsx → Axios → PokeAPI → Estado → Componentes → Interface
```

---

## 🌐 Consumo da PokeAPI

API utilizada:

```
https://pokeapi.co/api/v2/pokemon
```

A aplicação busca:

* Nome
* ID
* Imagem
* Tipos

---

## ⚛️ Conceitos de React

| Conceito  | Função                 |
| --------- | ---------------------- |
| Component | Interface reutilizável |
| JSX       | HTML dentro do JS      |
| useState  | Gerencia dados         |
| useEffect | Executa ações          |
| Props     | Envia dados            |
| map()     | Cria listas            |

---

## ▶️ Como Executar

```bash
npm run dev
```

Acesse:

```
http://localhost:5173
```

---

## 🗺 Roadmap

### Básico

* Página de detalhes
* Filtro por tipo
* Busca avançada

### Intermediário

* Favoritos
* Paginação
* React Router

### Avançado

* Testes
* Context API
* Deploy

---

## 🐛 Troubleshooting

Pokémon não aparece?

* Pressione F12
* Veja o Console
* Teste a API:
  [https://pokeapi.co/api/v2/pokemon/1](https://pokeapi.co/api/v2/pokemon/1)

---

## 💡 Dicas

* Use console.log
* Leia os erros
* Teste tudo
* Aprenda no ritmo certo

---

## ❓ FAQ

**Preciso saber JavaScript?**
Sim.

**Preciso de backend?**
Não. A PokeAPI funciona direto no frontend.

**Onde faço deploy?**
Vercel, Netlify ou GitHub Pages.
