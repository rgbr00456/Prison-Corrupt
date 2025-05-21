# 🎮 Prision Corrupt – Jogo em Assembly RISC-V

> Projeto acadêmico desenvolvido em Assembly RISC-V utilizando a ferramenta RARS.  
> "Prision Corrupt" é um jogo em que o jogador precisa escapar de uma prisão corrompida, enfrentando obstáculos e inimigos em um ambiente de baixa abstração.

---

## 🧠 Sobre o Projeto

Este jogo foi inteiramente desenvolvido em linguagem **Assembly RISC-V**, como parte do projeto da disciplina de Organização de Computadores. Nele, buscamos explorar o potencial da linguagem de máquina para criar lógica de movimentação, colisão, pontuação e interações gráficas simples com o terminal.

---

## 🚀 Como executar

### Pré-requisitos

- [Java 8+](https://www.java.com/)
- RARS customizado: [`Rars16_Custom1.jar`](./Rars16_Custom1.jar)

### Instruções

1. Baixe o RARS customizado ou use o incluído neste repositório.
2. Arraste o arquivo ".s" para cima do RARS e espere que a janela com a tela inicial do jogo abra.

## 🗂 Estrutura do Projeto
```
prision_corrupt/
├── prision corrupt.s             # Código principal do jogo
├── cheats/
│   ├── cheats.s                  # Código auxiliar (trapaças)
│   └── sprites/                  # Sprites e assets em Assembly
│       ├── atack1.s
│       ├── char.s
│       ├── floorCompleted.s
│       └── ...
├── Rars16_Custom1.jar           # Ferramenta personalizada RARS
├── fpgrars-x86_64.exe           # Executável auxiliar
└── Relatório do Jogo [...].pdf # Documentação em PDF
```
## 📘 Documentação

Leia o Relatório do Jogo em Assembly RISC-V (PDF) incluído neste repositório para entender o funcionamento interno, a lógica, os desafios enfrentados e decisões de arquitetura.

## 👨‍💻 Autores

Projeto desenvolvido por mim, Daniel de Oliveira Morais e Rafael Mileo Moreira Krauss Guimarães na Universidade de Brasília – UnB
📍 Curso: Ciência da Computação | Disciplina: Introdução aos Sistemas Computacionais

## 📜 Licença

Este projeto foi desenvolvido para fins educacionais e está sob a licença MIT.
Sinta-se à vontade para estudar, modificar e evoluir este jogo para aprender mais sobre baixo nível!


