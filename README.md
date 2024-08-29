# Pensamiento critico

### citas textuales:
*la logica es una ciencia **formal** que estudia las estructuras del pensamiento*

*una ciencia debe contener un objeto de estudio, un metodo y una teoria*

*la filosofia no se considera una ciencia porque pretende estudiarlo todo*

*con las ciencias facticas podemos suponer esa relacion causal en un hecho no asi con las ciencias formales*

*el cambio es una caracteristica de la realidad*

*relaciones simetricas y asimetricas*


| imaginario                           | ideal |
| ------------------------------------ | ----- |
| implementa elementos de la  realidad |       |


*el pensamiento viene de la mano con el lenguaje*

*un lenguaje artificial surge para analizar un lenguaje natural*

# ciencias
| Formales                                                                                   | Facticas                                                    |
| ------------------------------------------------------------------------------------------ | ----------------------------------------------------------- |
| Tiene un objeto de estudio ideal                                                           | El objeto de estudio es real                                |
| El metodo es la deduccion, que siempre esta sujeto a una hipotesis determinada por axiomas | Utilizan el metodo empirico, no esta sujeto a una hipotesis |
| Logica, matematica, semantica, etc...                                                      | Fisica, quimica, psicologia, etc...                         |

### logica proposicional

*es un lenguaje artificial formado por:*
- letras esquematicas (variables)
- conectivas
- signos auxiliares () [] {}

# Estructuras logicas

## Conceptos
- terminos

## Proposiciones
las proposiciones deben cumplir 3 requisitos
- debe ser una oracion enunciativa (tener copula)
- debe ser una  afirmacion o una negacion
- debe poder clasificarse en un valor booleano (verdadero o falso)

se dividen en:
- Condicional (compleja)
- Disyuntiva (compleja)
- Categorica (simple)

## conectivas
- conjuncion (and) (•) ***p*** y ***q***

    | p   | q   | p • q |
    | --- | --- | ----- |
    | V   | V   | V     |
    | V   | F   | F     |
    | F   | V   | F     |
    | F   | F   | F     |

- disyuncion inclusiva (or) (∨) ***p*** y/o ***q***

    | p   | q   | p ∨ q |
    | --- | --- | ----- |
    | V   | V   | V     |
    | V   | F   | V     |
    | F   | V   | V     |
    | F   | F   | F     |
    Relacion: **Subcontraria**

- disyuncion excluyente (xor) (W): ***p*** o ***q***

    | p   | q   | p W q |
    | --- | --- | ----- |
    | V   | V   | F     |
    | V   | F   | V     |
    | F   | V   | V     |
    | F   | F   | F     |
    Relacion: **contraria**
    tambien se expresa como: 
    *(A • ~B) ∨ (~A • B)*
- negacion (not) (~) ***p*** es falso

    | p   | ~p  |
    | --- | --- |
    | V   | F   |
    | F   | V   |

- condicional (⊃) si ***p*** entonces ***q***

    ***antecedente*** ⊃ ***consecuente***
    | Condicion suficiente **(antecedente)** | Condicion necesaria **(consecuente)** |
    | -------------------------------------- | ------------------------------------- |
    | "si"                                   | "solo si"                             |
    | "es suficiente"                        | "es necesario"                        |
    | "alcanza"                              | "unicamente"                          |

    | p   | q   | p ⊃ q |
    | --- | --- | ----- |
    | V   | V   | V     |
    | V   | F   | F     |
    | F   | V   | V     |
    | F   | F   | V     |
    Relacion: **implicancia**

- bicondicional (xnor) (≡) ***p*** si y solo si ***q***
  | p   | q   | p ≡ q |
  | --- | --- | ----- |
  | F   | F   | V     |
  | F   | V   | F     |
  | V   | F   | F     |
  | V   | V   | V     |
    
  *(A V B) • (~A V ~B)*

*"una tautologia es una proposicon que siempre da verdadero y una contradiccion una que siempre da falso, una contingencia puede dar verdadero o falso"*

## relaciones entre formas proposicionales
- Contrariedad (nand): no son simultaneamente verdaderas
- Subcontrariedad (or): no son simultaneamente falsas
- Contradictorias (xor): si no son simultaneamente verdaderas ni falsas
- Equivalentes (xnor): dos formas proposicionales son equivalentes si y solo si en cada caso tienen el mismo valor
- Implicacion/deduccion (⊃): una forma proposicional implica a otra forma proposicional si y solo si no ocurre que siendo la primera verdadera, la segunda sea falsa (contraejemplo). Si una forma implica a otra, la segunda se deduce de la primera
- deduccion: *una implicacion en sentido contrario es una deduccion, si A implica B, entonces B se deduce de A*

# Leyes de demorgan
~(P • Q) <=> (~P) + (~Q)

~(P V Q) <=> (~P) • (~Q)

