# Máquinas de Turing e Limites Computacionais

Este documento resume as etapas da atividade prática de Teoria da Computação, focada no estudo, desenvolvimento e simulação de uma Máquina de Turing.

## 🧠 O que foi feito?
A atividade abordou a base teórica e prática do modelo matemático criado por Alan Turing. Exploramos os componentes da máquina (fita, cabeçote, estados e regras de transição), sua importância histórica para a criação do computador moderno e como ela é a representação matemática exata do que chamamos de algoritmo.

## ⚙️ Simulação Prática
Utilizando o simulador [turingmachine.io](https://turingmachine.io/), construímos as regras de uma máquina capaz de reconhecer o padrão lógico `0ⁿ1ⁿ` (palavras com a mesma quantidade de zeros e uns, em ordem). 

A lógica implementada utiliza um sistema de marcação alternada:
1. A máquina lê o primeiro `0` e o substitui por `X`.
2. Avança para a direita até o primeiro `1` e o substitui por `Y`.
3. Retorna à esquerda e repete o ciclo até acabarem os zeros.
4. Faz uma varredura final. Se todos os números formaram pares exatos, a palavra é **aceita**. Se sobrar algum número sem par, a máquina trava e **rejeita** a entrada.

### 🧪 Testes Realizados
* **Entradas Aceitas:** `01` e `000111`.
* **Entradas Rejeitadas:** `0111` (A máquina travou e rejeitou corretamente ao identificar a sobra do número 1).

## 🛑 Limites da Computação
Finalizamos a atividade com uma reflexão sobre a capacidade de resolução de problemas dos computadores. Concluímos que a própria lógica possui limites matemáticos intransponíveis. Existem problemas que não podem ser divididos em um passo a passo exato, provando que a limitação da computação não está na potência do hardware, mas no fato de que nem tudo pode ser transformado em código.
