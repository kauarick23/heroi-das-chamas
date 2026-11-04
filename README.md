# Herói das Chamas

## Sobre o projeto
**Herói das Chamas** é um mini jogo de navegação desenvolvido como parte do desafio **HTML - Casa Virtual**. O jogador assume o papel de um(a) bombeiro(a) que precisa entrar em uma casa em chamas e encontrar a pessoa que ainda está em um dos cômodos.

O jogo começa na rua, em frente à casa. A cada etapa, o jogador visualiza o cômodo em que está e escolhe uma das opções de navegação disponíveis. A missão termina quando ele chega ao segundo quarto.

## Objetivo
Explorar a casa por meio das portas e da janela, seguindo as opções apresentadas em cada página, até encontrar o segundo quarto e concluir o resgate.

## Tecnologias utilizadas
- **HTML5:** estrutura das páginas e navegação entre os cômodos.
- **Links (`<a>`):** permitem que o jogador escolha para onde ir.

O projeto utiliza somente HTML, sem CSS e sem JavaScript. Cada cômodo é representado por um arquivo HTML independente.

## Estrutura dos arquivos
```text
heroi_das_chamas/
├── index.html       # Rua: início do jogo
├── sala.html        # Sala
├── corredor.html    # Corredor
├── cozinha.html     # Cozinha
├── banheiro.html    # Banheiro
├── quarto1.html     # Primeiro quarto
├── quarto2.html     # Segundo quarto: conclusão da missão
└── README.md        # Documentação do projeto
