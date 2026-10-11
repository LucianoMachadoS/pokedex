# 🔴 Pokédex

Pokédex web que consome a [PokeAPI](https://pokeapi.co/) e mostra os Pokémon com número, nome, tipos e arte oficial, carregando mais itens sob demanda.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)


## ✨ Funcionalidades

- Busca a lista de Pokémon na PokeAPI com paginação (`offset` / `limit`)
- Busca os detalhes de cada Pokémon **em paralelo** com `Promise.all`
- Cartões coloridos de acordo com o tipo do Pokémon
- Botão **"Carregar mais"** para exibir novos Pokémon sem recarregar a página

## 🧱 Como está organizado

| Arquivo | Responsabilidade |
|---|---|
| `pokemon-model.js` | Classe `Pokemon` (modelo dos dados) |
| `poke-api.js` | Chamadas à API e conversão da resposta para o modelo |
| `main.js` | Monta o HTML dos cartões e controla a paginação |
| `estilos.css` | Layout e cores por tipo |

## 🚀 Como rodar

Não precisa instalar nada:

```bash
git clone https://github.com/LucianoMachadoS/pokedex.git
```

Abra o `pokedex.html` no navegador (ou use a extensão Live Server do VS Code).

## 📚 O que aprendi

Consumo de API REST com `fetch`, Promises encadeadas, requisições paralelas e separação do código em camadas (modelo, serviço e tela).

---
Feito por [Luciano Machado](https://github.com/LucianoMachadoS)
