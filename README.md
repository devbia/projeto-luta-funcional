# 🥊 Projeto Luta (Programação Funcional)

Este é um projeto simples de um jogo de luta em JavaScript, desenvolvido utilizando programação funcional ao invés de classes.

## 🚀 Funcionalidades

- Sistema de batalha entre dois personagens
- Barra de vida dinâmica
- Botões de ataque para cada personagem
- Cálculo de dano com fator aleatório
- Log exibindo as ações da luta

## 🧠 Conceitos aplicados

- Programação funcional (uso de funções ao invés de classes)
- Factory functions para criação de personagens
- Imutabilidade parcial com spread operator
- Manipulação do DOM
- Eventos (click)
- Lógica de jogo

## ⚙️ Como funciona

Os personagens são criados através de funções, como:

- `createKnight`
- `createSorcerer`
- `createLittleMonster`
- `createBigMonster`

Essas funções retornam objetos com atributos como vida, ataque e defesa :contentReference[oaicite:0]{index=0}

A lógica da batalha é controlada por um objeto `stage`, que gerencia:

- Atualização da interface
- Execução dos ataques
- Controle da luta

## 📁 Estrutura
/assets
/css
style.css
/js
functions.js
script.js
index.html

## ▶️ Como executar

Basta abrir o arquivo `index.html` no navegador :contentReference[oaicite:1]{index=1}

## 📌 Observação

Projeto criado para fins de estudo, com foco em entender a diferença entre Programação Orientada a Objetos (POO) e Programação Funcional
