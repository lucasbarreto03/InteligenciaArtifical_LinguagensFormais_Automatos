# Exercício 1

Considere:

Σ = a, b, c

Responda:

- Quantos símbolos existem no alfabeto? 
- Quais são os símbolos? 
- O símbolo a pertence ao alfabeto? 
- O símbolo d pertence ao alfabeto?
- Escreva uma palavra formada por símbolos desse alfabeto. 

### Respostas

- Existem 3 símbolos no alfabeto.
- Os símbolos são `a`, `b` e `c`.
- Sim, o símbolo `a` pertence ao alfabeto.
- Não, o símbolo `d` não pertence ao alfabeto.
- `Babaca`

---


# Exercício 2


Considere:

Σ = 0,1

Classifique cada sequência como palavra válida ou não válida:

| Sequência | Válida? | Justificativa |
|---|---|---|
| 0101 | Sim | Todos os símbolos fazem parte do alfabeto. |
| 00110 | Sim | A sequência utiliza somente símbolos permitidos no alfabeto. |
| 012 | Não | O símbolo `2` não está presente no alfabeto. |
| 111 | Sim | A sequência é formada apenas por símbolos do alfabeto. |
| 10a | Não | O símbolo `a` não faz parte do alfabeto. |

---

# Exercício 3

Considere:

Σ = 0,1

Determine se as afirmações são verdadeiras ou falsas:

Justifique cada resposta.

| Sequência | Válida? | Justificativa |
|---|---|---|
| 0 ∈ Σ | Sim | O símbolo `0` faz parte do alfabeto. |
| 1 ∈ Σ | Sim | O símbolo `1` pertence ao alfabeto. |
| 01 ∈ Σ | Não | O alfabeto possui somente `0` e `1`, e `01` é uma sequência, não um símbolo individual do alfabeto. |
| 01 ∈ Σ∗ | Sim | `01` pode ser formada utilizando os símbolos do alfabeto. |
| 2 ∈ Σ | Não | O símbolo `2` não está presente no alfabeto. |
| 101 ∈ Σ∗ | Sim | `101` é uma palavra que pode ser formada com os símbolos do alfabeto. |

---

# Exercício 4

Considere:

L=0, 01, 011, 0111

Determine se cada palavra pertence à linguagem:


| Sequência | Válida? | Justificativa |
|---|---|---|
| 0 ∈ L | Sim | A palavra está presente na linguagem. |
| 01 ∈ L | Sim | Essa palavra faz parte da linguagem. |
| 0111 ∈ L | Sim | A palavra está incluída na linguagem. |
| 10 ∈ L | Não | A palavra não pertence à linguagem. |
| 111 ∈ L | Não | Essa palavra não está presente na linguagem. |
| 011 ∈ L | Sim | A palavra está presente na linguagem. |

---

# Exercício 5

Considere: L=bn∣n≥1

- Escreva as cinco primeiras palavras. Para n=1,2,3,4,5

`b¹ = b`

`b² = bb`

`b³ = bbb`

`b⁴ = bbbb`

`b⁵ = bbbbb`

Resposta: `b, bb, bbb, bbbb, bbbbb`.

As cinco primeiras palavras são `b`, `bb`, `bbb`, `bbbb` e `bbbbb`.

- Explique o significado de bn.

A notação `bⁿ` indica que o símbolo `b` é repetido `n` vezes. Como `n ≥ 1`, a palavra deve possuir pelo menos um símbolo `b`.

- A palavra bbbbbb pertence à linguagem?

A palavra `bbbbbb` possui 6 símbolos `b`, portanto:

`bbbbbb = b⁶`

Como `6 ≥ 1`, a palavra pertence à linguagem.

- A palavra vazia (ε) pertence à linguagem?

Não, porque `n` precisa ser maior que 1.

---

# Exercício 6

Explique, com suas próprias palavras, a diferença entre: L=∅ L=ε

`L = ∅` representa uma linguagem vazia, sem nenhuma palavra. Já `L = {ε}` representa uma linguagem formada por uma única palavra, a palavra vazia `ε`.

Depois responda:

- Qual delas possui uma palavra? 
- Qual delas não possui nenhuma palavra? 
- Qual é o comprimento da palavra ε? 

| Pergunta | Resposta |
|---|---|
| Qual delas possui uma palavra? | A segunda. |
| Qual delas não possui nenhuma palavra? | A primeira. |
| Qual é o comprimento da palavra ε? | 0 símbolos. |

---

# Exercício 7

Considere: G=(S,A,0,1,P,S) com: P=S→0A, A→1

Identifique:

- O conjunto de variáveis. V = {S, A}
- O conjunto de terminais. T = {0, 1}
- O conjunto de produções. P = {S → 0A, A → 1}
- O símbolo inicial. S
- Qual palavra pode ser gerada por essa gramática? 01

| Item | Resposta |
|---|---|
| O conjunto de variáveis. | `V = {S, A}` |
| O conjunto de terminais. | `T = {0, 1}` |
| O conjunto de produções. | `P = {S → 0A, A → 1}` |
| O símbolo inicial. | `S` |
| Qual palavra pode ser gerada por essa gramática? | `01` |

---

# Exercício 8

Considere: S→0S Começando com S:

- Aplique a regra uma vez.
- Aplique a regra duas vezes.
- Aplique a regra três vezes. 
- Escreva a sequência completa de derivação. 

| Etapa | Derivação |
|---|---|
| Aplique a regra uma vez. | `S → 0S` |
| Aplique a regra duas vezes. | `S → 0S → 00S` |
| Aplique a regra três vezes. | `S → 0S → 00S → 000S` |
| Escreva a sequência completa de derivação. | `S → 0S → 00S → 000S` |

---

# Exercício 9

Utilizando: G:{S→aSS→b gere: aaab Escreva todos os passos da derivação.

| Etapa | Derivação |
|---|---|
| 1 | `S → aS` |
| 2 | `S → aS → aaS` |
| 3 | `S → aS → aaS → aaaS` |
| 4 | `S → aS → aaS → aaaS → aaab` |
