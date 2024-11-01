# 🐦 Jogo do Pássaro em Pygame

Um jogo estilo "Flappy Bird" desenvolvido em Python usando a biblioteca Pygame. Controle um pássaro, desvie dos obstáculos e acumule pontos! 🎮

## 📋 Pré-requisitos

- Python 3.7+
- Biblioteca `pygame`

Para instalar o `pygame`, use:
```bash
pip install pygame
```

## 🚀 Início Rápido

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/jogo-passaro.git
   cd jogo-passaro
   ```

2. Execute o jogo:
   ```bash
   python main.py
   ```

## 🕹️ Controles

- Pressione `ESPAÇO` para fazer o pássaro pular.
- Desvie dos canos e mantenha-se no ar para marcar pontos!

## 📂 Estrutura do Projeto

- `main.py` - Arquivo principal que inicializa o jogo.
- `imgs/` - Contém as imagens usadas para o pássaro, canos, chão e fundo.

## 🖼️ Recursos Visuais

- **Pássaro:** Animação usando três imagens para simular o bater de asas.
- **Cano:** Movimentação contínua para a esquerda com posicionamento aleatório.
- **Chão:** Movimento horizontal contínuo, com reposicionamento para uma transição suave.

## 🔧 Funcionalidades

- **Pontuação:** Mostrada no topo da tela com fonte `arial` e atualizada ao passar por cada conjunto de canos.
- **Colisões:** Detectadas usando máscaras, permitindo uma detecção de colisão precisa entre o pássaro e os canos.
- **Animação do pássaro:** Imagens alternadas para simular o bater de asas.

## 🛠️ Como Funciona o Código

- **Classe `Passaro`** 🐤: Gerencia o pássaro, incluindo animação, movimento e colisão.
- **Classe `Cano`** 🌵: Gerencia os canos, incluindo posicionamento e detecção de colisão.
- **Classe `Chao`** 🌍: Define e move o chão do jogo.
- **Função `desenhar_tela`** 🖼️: Renderiza o fundo, canos, chão, pássaro e pontuação.
- **Função `main`** 🎮: Função principal do jogo que controla o loop e as interações.

## 🎯 Objetivo do Jogo

A missão é simples: passe pelos canos sem bater e ganhe pontos ao desviar dos obstáculos! Boa sorte! 🍀

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usá-lo e modificá-lo.
