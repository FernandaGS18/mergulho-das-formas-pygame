# 🐟 Mergulho das Formas — Jogo Educativo em Python & Pygame

Mergulho das Formas é um jogo educativo 2D onde o jogador controla um peixe no fundo do mar com o objetivo de capturar formas geométricas específicas indicadas na tela no menor tempo possível.

---

## 🎯 Objetivos do Projeto
- **Educativo:** Auxiliar na identificação e diferenciação de formas geométricas (círculo, triângulo, quadrado, trapézio, losango, hexágono).
- **Técnico:** Aplicar conceitos de Programação Orientada a Objetos (POO), Gerenciamento de Estados de Jogo, Detecção de Colisões e Persistência de Dados com SQLite.

---

## 🛠️ Tecnologias Utilizadas
- **Python:** Linguagem principal do projeto.
- **Pygame:** Biblioteca para renderização gráfica, controle de eventos e física.
- **SQLite3:** Banco de dados relacional para armazenamento do ranking (Top 5 melhores tempos).

---

## ⚙️ Funcionalidades do Jogo
- 👤 **Registro de Jogador:** Inserção de nome/apelido antes de iniciar a partida.
- 🎯 **Objetivos Aleatórios:** A cada partida, novos alvos e quantidades de formas são solicitados.
- ❤️ **Gerenciamento de Vidas:** Pegar uma forma incorreta faz o jogador perder vidas.
- 🏆 **Ranking em Tempo Real:** Banco de dados SQLite que salva e exibe os 5 menores tempos de vitória.
- 🔄 **Gerenciador de Estados:** Telas de Menu Inicial, Partida, Vitória e Game Over.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python 3 instalado no seu computador.

### Passo a Passo

1. Baixe os arquivos do repositório.
2. Instale a biblioteca Pygame pelo terminal/prompt de comando:
```bash
pip install pygame
