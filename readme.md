# Yu-Gi-Oh | Jo-Ken-Po Edition

## Descrição

Este projeto é um jogo de Jo-Ken-Po (Pedra, Papel e Tesoura) temático de Yu-Gi-Oh, criado para explicar conceitos de lógica de programação aplicados a jogos utilizando tecnologias web. O jogo apresenta uma interface interativa onde o usuário pode escolher cartas para duelar contra o computador, cada carta representando um dos elementos do Jo-Ken-Po. A proposta é demonstrar técnicas como gerenciamento de estado, funções limpas e organização de código.

## Tecnologias Utilizadas

- **HTML5:** Estrutura da interface do jogo.
- **CSS3:** Estilização customizada com arquivos separados para reset, botões, containers/frames e estilos principais, utilizando imagens, bordas e backgrounds temáticos.
- **JavaScript (ES6+):** Lógica do jogo, manipulação de DOM, controle de estado, áudio, animações e interações do usuário.
- **Assets:** Vídeos, áudios e imagens temáticas de Yu-Gi-Oh para enriquecer a experiência visual e sonora.

## Estrutura de Pastas

```
├── index.html
├── readme.md
├── src
│   ├── assets
│   │   ├── audios/
│   │   ├── cursor/
│   │   ├── favicon/
│   │   ├── icons/
│   │   ├── rpg/
│   │   └── video/
│   ├── scripts
│   │   └── engine.js
│   └── styles
│       ├── buttons.css
│       ├── containers_and_frames.css
│       ├── main.css
│       └── reset.css
```

- **index.html**: Página principal do jogo.
- **src/assets/**: Recursos visuais e sonoros utilizados na interface.
- **src/scripts/engine.js**: Toda lógica do jogo é centralizada neste arquivo.
- **src/styles/**: CSS modularizado para diferentes aspectos da interface (reset, botões, containers/frames, estilos principais).

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/GeovanniJDA/Yu-Gi-Oh.git
   ```
2. Abra o arquivo `index.html` diretamente no navegador de sua preferência.

## Funcionalidades

- Escolha de cartas pelo usuário com visualização de detalhes.
- Computador realiza escolha aleatória de carta.
- Sistema de pontuação Win/Lose.
- Feedback visual e sonoro para cada duelo.
- Interface responsiva e temática.

## Conceitos Abordados

- Armazenamento e gerenciamento de estado manual
- Funções limpas e modulares
- Organização de código em arquivos e pastas
- Manipulação de DOM
- Utilização de assets para experiência completa

## Autor

GeovanniJDA

---

Sinta-se à vontade para contribuir ou sugerir melhorias!
