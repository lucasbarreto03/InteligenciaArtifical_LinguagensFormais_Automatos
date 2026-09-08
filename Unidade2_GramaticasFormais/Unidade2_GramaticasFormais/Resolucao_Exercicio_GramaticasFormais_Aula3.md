# Bloco 1 (Derivação)

Dada G1: `S → aS ∣ b`

### A) Gere a palavra aaab.

### B) Explique como você sabe que a derivação terminou.

**A)**  
`S ⇒ aS ⇒ aaS ⇒ aaaS ⇒ aaab`

**B)**  
A derivação terminou porque não há mais símbolos não terminais, como `S`, na palavra. Restam somente símbolos terminais, formando `aaab`.

---

# Bloco 2 (GLC)

Dada G2: `S → aSb ∣ ε`

### A) Gere a palavra aaabbb.

### B) É possível gerar aabbb? Justifique.

**A)**  
`S ⇒ aSb ⇒ aaSbb ⇒ aaaSbbb ⇒ aaabbb`

**B)**  
A palavra `aabbb` possui 2 letras `a` e 3 letras `b`. Como a quantidade precisa ser igual, não é possível gerar `aabbb`.

---

# Bloco 3 (Classificação)

Classifique como Regular ou Livre de Contexto:

`S → aA ∣ A → b`

### Resposta:

A gramática é **Regular**, pois suas produções seguem o formato de um terminal seguido, no máximo, de um não terminal.
