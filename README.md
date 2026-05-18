# 🧟 Último Suspiro - Jogo de Aventura em Texto

**Último Suspiro** é um jogo de aventura baseado em texto (*text-based adventure*) desenvolvido inteiramente em **C++**. 

Na história, você interpreta um estudante de engenharia que ficou até tarde na biblioteca da faculdade desenvolvendo um projeto de algoritmos. Ao tentar sair, descobre que um apocalipse zumbi tomou conta do campus. Seu objetivo é explorar os cenários, fazer as escolhas certas, sobreviver e encontrar a cura definitiva para o vírus.

---

## 🎮 Como Jogar

O jogo funciona através de escolhas numeradas no terminal:
1. Ao iniciar, você recebe um total de **3 vidas**.
2. Cada cenário apresenta caminhos ou decisões diferentes (ex: ir para o laboratório de informática, refeitório, auditório, etc.).
3. Algumas escolhas são seguras ou te fazem avançar, enquanto decisões erradas farão você ser cercado por zumbis e perder uma vida.
4. O jogo termina se você perder todas as suas vidas (**Game Over**) ou se conseguir explorar o caminho correto que leva ao laboratório secreto (**Vitória**).

---

## 🛠️ Conceitos Práticos Aplicados

Este projeto foi construído para consolidar fundamentos essenciais de lógica de programação e algoritmos:
* **Funções e Escopo:** Modularização do código, onde cada cenário do mapa é controlado por uma função específica (ex: `escolhaBiblioteca()`, `escolhaAuditorio()`).
* **Estruturas de Decisão Dinâmicas:** Uso intensivo de `switch/case` e condicionais `if/else` para o gerenciamento de rotas e fluxo da história.
* **Recursividade Controlada:** Chamadas de funções interligadas para simular a livre movimentação do jogador entre as salas e corredores do campus.
* **Gerenciamento de Estados Globais:** Controle em tempo real do sistema de pontuação e integridade do jogador através da variável global de vidas.

---

## 📂 Estrutura de Arquivos

O projeto possui uma arquitetura simples de arquivo único, ideal para execução rápida:
```text
├── main.cpp         # Código-fonte principal com a lógica e cenários do jogo
└── README.md        # Documentação do repositório
