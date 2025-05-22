# 📄 Documentação do Projeto: Tetris em Python com Pygame

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Tetris_Logo.svg" alt="Tetris Logo" width="200">
  <p><em>Implementação do clássico jogo Tetris com Pygame</em></p>
</div>

---

## 🎮 1. Visão Geral
**Tecnologia:** Python 3.10+ + Pygame 2.5+  
**Objetivo:** Criar uma versão modular e funcional do Tetris com recursos básicos e capacidade de expansão.  

### 🔍 O que é Tetris?
Jogo de quebra-cabeça criado em 1984 por Alexey Pajitnov, onde o jogador organiza peças geométricas (tetrominós) em um grid para formar linhas completas.  

**Curiosidade:** Tetris possui efeitos terapêuticos comprovados para a mente!

---

## ⚙️ 2. Funcionalidades Principais
### 🕹️ Motor do Jogo
- Geração aleatória de 7 tetrominós com rotações  
- Controles: 
  - ←/→ (movimento), ↑ (rotação), ↓ (queda rápida)  
- Detecção de colisões e limites do grid  
- Sistema de pontuação e níveis (dificuldade progressiva)  

### 🎨 Interface
- Menu inicial, tela de pausa e game over  
- Renderização do grid e peças coloridas  
- Efeitos sonoros e registro de *high score*  

---

## 📂 3. Arquitetura do Código
```plaintext
📁 tetris_pygame/
├── 📄 main.py            # Ponto de entrada (inicialização do jogo)
├── 📁 game/
│   ├── 📄 tetromino.py   # Lógica das peças e rotações
│   ├── 📄 grid.py        # Gerenciamento do grid e colisões
│   └── 📄 score.py       # Pontuação e níveis
├── 📁 ui/
│   ├── 📄 menus.py       # Telas (início, pausa)
│   └── 📄 render.py      # Renderização gráfica
└── 📁 assets/
    ├── 📁 sounds/        # Efeitos sonoros
    └── 📁 fonts/         # Fontes do jogo
