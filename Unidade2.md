# Anotações Unidade ll

### Operações adicionais sobre proposições

## Implicação lógica

------



### Definição 

-  *Uma proposição P(p,q,r) implica com uma proposição Q(p,q,r), se Q(p,q,r) for verdadeira e se também todas as vezes P(p,q,r) for verdadeira*

- *Verificamos na ultima coluna da tabela verdade da proposição P, se elas é verdadeira. Se, na linha da tabela verdade de Q, for verdadeiro também, então "P implica Q"*


##### Notação que P(p,q,r...) implica com Q(p,q,r...) é: 

- P (p, q, r,...) ⇒ Q (p, q, r,...)
  

------


### Propriedades da implicação lógica

##### A implicação lógica tem as propriedades reflexiva e transitiva:

* Reflexiva: P (p, q, r,...) ⇒ P (p, q, r,...)

- Transitiva: Se P(p, q, r,...) ⇒ Q (p, q, r,...) e
  Q (p, q, r,...) ⇒ R (p, q, r,...), então
  P (p, q, r,...) ⇒ R (p, q, r,...)

**Exemplos:**

A tabela-verdade da proposição (p v q) ou ~p:

|  p   |  q   | p v q |  ~p  | (p v q) ^ ~p |
| :--: | :--: | :---: | :--: | :----------: |
|  V   |  V   |   V   |  F   |      F       |
|  V   |  F   |   V   |  F   |      F       |
|  F   |  V   |   V   |  V   |      V       |
|  F   |  F   |   F   |  V   |      F       |

Essa proposição é verdadeira somente na linha 3 e, nessa mesma linha, a proposição “q” também é
verdadeira.

Logo, tem-se uma implicação lógica:
(p ∨ q) ∧ ~p ⇒ q

------

### Tautologias e implicação lógica

- Proposição P(p,q,r...) implica com a proposição Q(p,q,r...), ou seja: P (p, q, r,...)⇒
  ⇒ Q (p, q, r,...)
  - Se e somente se a condicional: P (p, q, r,...) → Q (p, q, r,...) é tautológica

- Então toda implicação lógica é correspondente a uma condicional tautológica e vice-versa


Partindo daí, se P (p, q, r,...) ⇒ Q (p, q, r,...), então, também se tem: P (Po, Qo, Ro,...) ⇒ Q (Po, Qo, Ro,...) Quaisquer que sejam a proposições Po, Qo, Ro,...

**OBS** : os símbolos → e ⇒ são distintos (o primeiro é de operação lógica) e (o segundo é de relação ou seja implicação)

**Exemplo:**

- A condicional p ∧ ~p → q é tautológica, pois a última coluna da sua tabela-verdade apresenta somente valores verdadeiros:

|  p   |  q   |  ~p  | p ^ ~p | p ^ ~p → q |
| :--: | :--: | :--: | :----: | :--------: |
|  V   |  V   |  F   |   F    |     V      |
|  V   |  F   |  F   |   F    |     V      |
|  F   |  V   |  V   |   F    |     V      |
|  F   |  F   |  V   |   F    |     V      |

------



### Equivalência lógica

##### Definição

Duas ou mais proposições são logicamente equivalentes quando suas proposições possuem a mesma tabela-verdade. De maneira mais formal, tem-se:

- Uma proposição P (p, q, r,...) é logicamente equivalente ou apenas equivalente
  a uma proposição Q (p, q, r,...) se as tabelas-verdade dessas duas proposições
  são idênticas (ALENCAR FILHO, 2002).

A notação para uma proposição P (p, q, r,...) ser equivalente a uma proposição Q (p, q, r,...) é dada por: P (p, q, r,...) ⇔ Q (p, q, r,...)

### Propriedades da equivalência lógica

A equivalência lógica tem as seguintes propriedades: é reflexiva, simétrica e transitiva

**Em símbolos:**

Reflexiva:  P (p, q, r,...) ⇔ P (p, q, r,...)

Simétrica: Se P (p, q, r,...) ⇔ Q (p, q, r,...) , Q (p, q, r,...) ⇔ P(p, q, r,...)

Transitiva: Se P (p, q, r,...) ⇔ Q (p, q, r,...), Q (p, q, r) ⇔ R (p, q, r,...),
P (p, q, r) ⇔ R (p, q, r,...)

**Exemplo:**

As proposições ~~p e p são equivalentes, isto é, ~~p ⇔ p (regra da dupla negação). É o que demonstra a tabela-verdade:

|                p                 |  ~p  |               ~~p                |
| :------------------------------: | :--: | :------------------------------: |
| <span style="color:red">V</span> |  F   | <span style="color:red">V</span> |
| <span style="color:red">F</span> |  V   | <span style="color:red">F</span> |

Vendo as colunas em vermelho, a dupla negação equivale à afirmação.

### Tautologias e equivalência lógica

- A proposição P(p,q,r...) é equivalente à proposição Q(p,q,r...), isto é: P (p, q, r,...) ⇔ Q (p, q, r,...)

- Se e somente se a bicondicional: P (p, q, r,...) ↔ Q (p, q, r,...) **é tautológica**

Então, toda equivalência lógica corresponde a uma bicondicional tautológica e vice-versa

Se P (p, q, r,...) ⇔ Q (p, q, r,...), então também se tem:  P (Po, Qo, Ro,...) ⇔ Q (Po, Qo, Ro,...)

Quaisquer que sejam as proposições Po, Qo, Ro,...

------

### Proposições associadas a uma condicional

- Dada a condicional p → q, chamam-se proposições associadas a p → q as três seguintes proposições condicionais que contêm p e q: 


  **a) Proposição recíproca** de p → q: q → p

  **b) Proposição contrária** de p → q: ~p → ~q

  **c) Proposição contrapositiva** de p → q: ~q → ~ p

  

  A tabela-verdade dessas quatro proposições são:

|  p   |  q   | p → q | q → p | ~p → ~q | ~ q → ~p |
| :--: | :--: | :---: | :---: | :-----: | :------: |
|  V   |  V   |   V   |   V   |    V    |    V     |
|  V   |  F   |   F   |   V   |    V    |    F     |
|  F   |  V   |   V   |   F   |    F    |    V     |
|  F   |  F   |   V   |   V   |    V    |    V     |

  E demonstram duas importantes propriedades:

  - A condicional p → q e a sua contrapositiva ~q → ~p são equivalentes, ou seja: p → q ⇔ ~p → ~q

  - A recíproca q → p e a contrária ~p → ~q da condicional p → q são equivalentes, ou seja: q → p ⇔ ~p → ~q

- As mesmas tabelas-verdade também demonstram que a condicional p → q e a sua recíproca q → p ou a sua contrária ~p → ~q não são equivalentes.

- A contrária de p → q também é denominada a inversa de p → q, e a contrapositiva de p → q é a contrária da recíproca de p → q, por isso também é denominada contrarrecíproca de p → q. Também se diz que p → q é a direta em relação às associadas

**Exemplos adaptados de Alencar Filho (2002):**

1. Seja a condicional relativa a um quadrilátero Q:
p → q: se Q é quadrado, então Q é retângulo
2. A recíproca dessa proposição é:
    q → p: se Q é retângulo, então é quadrado.

------

### Negação conjunta de duas proposições

A conjunção de duas proposições p e q negadas é proposição "não p e não q". Esse tipo de negação é denominado de negação conjunta

**Em símbolos:**  ~ p ∧ ~ q

- A negação conjunta de duas proposições p e q também se indica pela notação p ↓ q, em que é apresentada uma seta para baixo. Note que o sentido da seta é contrário ao vértice do símbolo de conjunção, ou seja, seta para baixo, o vértice para cima.

- **Em símbolos**:
  p ↓ q ⇔ ~p ∧ ~ q
  - Como a proposição “~p ∧ ~q” é verdadeira somente no caso em que p e q são ambas falsas, então a tabela-verdade de  “p ↓ q” é a seguinte

|  P   |  q   | p ↓ q |
| :--: | :--: | :---: |
|  V   |  V   |   F   |
|  V   |  F   |   F   |
|  F   |  V   |   F   |
|  F   |  F   |   V   |

### Negação disjunta de duas proposições 

- A negação disjunta de duas proposições p e q é a proposição “não p ou não q”, isto é, simbolicamente “~p ∨ ~ q” 

- A negação disjunta de duas proposições p e q também se indica pela notação “p ↑ q”. Note que o sentido da seta é contrário ao vértice do símbolo de disjunção, ou seja, seta para cima, o vértice para baixo.

  - **Em símbolos**: p ↑ q ⇔ ~p ∨ ~ q

    - Como a proposição “~p ∨ ~ q” é falsa somente no caso em que p e q são ambas verdadeiras, então
      a tabela-verdade de “p ↑ q” é a seguinte :

      |  p   |  q   | p↑q  |
      | :--: | :--: | :--: |
      |  V   |  V   |  F   |
      |  V   |  F   |  V   |
      |  F   |  V   |  V   |
      |  F   |  F   |  V   |

 Os símbolos “↓“ e “↑” são conhecidos como conectivos de Scheffer.

------

### Propriedades das proposições e fundamentos da dedução

##### Propriedades das principais proposições 

A seguir, serão apresentas as propriedades relacionadas às proposições. A demonstração destas será realizada por meio das tabelas-verdade