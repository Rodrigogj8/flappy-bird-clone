# Flappy Bird Clone 🐦

Um clone do famoso jogo Flappy Bird desenvolvido em Python usando Pygame. Este projeto recria a mecânica clássica do jogo original, onde você controla um pássaro que precisa voar entre canos sem colidir.

## 🎮 Como Jogar

- **Barra de Espaço**: Faz o pássaro pular
- **Objetivo**: Passe pelos canos sem colidir e marque o máximo de pontos possível
- **Game Over**: O jogo termina se o pássaro tocar no chão, no topo da tela ou nos canos

## 🚀 Como Executar

### Pré-requisitos

- Python 3.6 ou superior
- Pygame instalado

### Instalação

1. Clone ou baixe este repositório
2. Instale o Pygame:

```bash
pip install pygame
```

3. Execute o jogo:

```bash
python FlappyBird.py
```

## 📁 Estrutura do Projeto

```
Jogo/
├── FlappyBird.py          # Arquivo principal do jogo
├── imgs/                  # Pasta com as imagens do jogo
│   ├── base.png          # Imagem do chão
│   ├── bg.png            # Imagem de fundo
│   ├── bird1.png         # Pássaro - frame 1
│   ├── bird2.png         # Pássaro - frame 2
│   ├── bird3.png         # Pássaro - frame 3
│   └── pipe.png          # Imagem dos canos
└── README.md             # Este arquivo
```

## 🎯 Características do Jogo

- **Física Realista**: O pássaro cai com gravidade e tem movimento de rotação natural
- **Animações Suaves**: Sistema de animação com 3 frames para o bater de asas
- **Sistema de Pontuação**: Pontos são marcados ao passar pelos canos
- **Detecção de Colisão**: Sistema preciso de colisão usando máscaras do Pygame
- **Geração Procedural**: Os canos são gerados com alturas aleatórias

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**: Linguagem de programação
- **Pygame**: Biblioteca para desenvolvimento de jogos
- **Sistema de Classes**: Código organizado em classes (Passaro, Cano, Chao)

## 🎨 Recursos Visuais

O jogo utiliza sprites pixelados que remetem ao estilo clássico do Flappy Bird original, com:

- Fundo com gradiente azul
- Pássaro amarelo com animação de voo
- Canos verdes com geração aleatória de altura
- Chão com textura repetitiva

## 🔧 Possíveis Melhorias

- Sistema de high score persistente
- Menu principal e tela de game over
- Efeitos sonoros e música de fundo
- Diferentes níveis de dificuldade
- Sistema de power-ups

## 📝 Sobre o Desenvolvimento

Este projeto foi desenvolvido como uma recriação do Flappy Bird, focando na implementação das mecânicas básicas do jogo original. O código está estruturado de forma modular, facilitando futuras expansões e melhorias.

---
