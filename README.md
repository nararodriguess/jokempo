# 🪨📄✂️ Jokenpo

Jogo de Jokenpô (Pedra, Papel e Tesoura) desenvolvido em linguagem C, onde o jogador enfrenta o computador em uma partida simples via terminal.

## 🎮 Como funciona

O jogador escolhe entre Pedra, Papel ou Tesoura digitando uma das opções no terminal. O computador sorteia sua jogada aleatoriamente e o resultado é exibido na tela. Entradas inválidas encerram o jogo automaticamente.

## 🛠️ Tecnologias

- Linguagem C
- Biblioteca `stdio.h` — entrada e saída no terminal
- Biblioteca `stdlib.h` — geração de números aleatórios
- Biblioteca `time.h` — seed aleatória baseada no horário

## ▶️ Como compilar e executar

**Pré-requisitos:** ter o GCC instalado.

**1. Clone o repositório**
```bash
git clone https://github.com/nararodriguess/jokenpo
cd jokenpo
```

**2. Compile**
```bash
gcc jokenpo.c -o jokenpo
```

**3. Execute**
```bash
./jokenpo
```

**Ou compile e execute em um único comando:**
```bash
gcc jokenpo.c -o jokenpo && ./jokenpo
```

## 📚 Atividade acadêmica

Projeto desenvolvido como atividade prática da disciplina de programação em linguagem C.
