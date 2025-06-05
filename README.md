# Projeto Batalha Naval em C

Este projeto simula o posicionamento de navios e aplicação de habilidades especiais em um tabuleiro 10x10 do jogo Batalha Naval, utilizando vetores bidimensionais e estruturas de repetição. O código está dividido em três níveis de complexidade: **Novato**, **Aventureiro** e **Mestre**.

---

## Funcionalidades

### 🏅 Nível Novato
- Posiciona dois navios manualmente:
  - Um **vertical**
  - Um **horizontal**
- Exibe as **coordenadas dos navios** usando `printf`
- Uso de **vetores bidimensionais**

### 🏅 Nível Aventureiro
- Tabuleiro expandido para **10x10**
- Posiciona **quatro navios**, incluindo:
  - Dois navios diagonais (principal e secundária)
- Exibe o **tabuleiro completo**
  - `0` = posição livre
  - `3` = posição ocupada por navio

### 🏅 Nível Mestre
- Implementa **habilidades especiais** com padrões:
  - **Cone**
  - **Cruz**
  - **Octaedro**
- Uso de **loops aninhados** para preencher áreas
- Exibe tabuleiros com áreas atingidas por habilidades:
  - `0` = não atingido
  - `1` = atingido

---

## Estrutura do Projeto

- `main()` – Execução principal e chamadas de funções.
- `exibirMatrizInt()` – Função auxiliar para imprimir tabuleiros.
- `habilidadeCone()` – Aplica padrão em cone.
- `habilidadeCruz()` – Aplica padrão em cruz.
- `habilidadeOctaedro()` – Aplica padrão em forma de cruz com diagonais.

---

## Como Executar

1. Compile o programa com um compilador C, como `gcc`:
   ```bash
   gcc -o batalha batalha_naval.c

   - Execute o programa: ./batalha
   
