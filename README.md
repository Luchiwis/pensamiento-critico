# Pensamiento critico

### citas textuales:
*la logica es una ciencia **formal** que estudia las estructuras del pensamiento*

*una ciencia debe contener un objeto de estudio, un metodo y una teoria*

*la filosofia no se considera una ciencia porque pretende estudiarlo todo*

*con las ciencias facticas podemos suponer esa relacion causal en un hecho no asi con las ciencias formales*

*el cambio es una caracteristica de la realidad*

*relaciones simetricas y asimetricas*

*casos de sustitucion*

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

- disyuncion excluyente (xor) (W): ***p*** o ***q***

    | p   | q   | p W q |
    | --- | --- | ----- |
    | V   | V   | F     |
    | V   | F   | V     |
    | F   | V   | V     |
    | F   | F   | F     |
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

- bicondicional (xnor) (≡) ***p*** si y solo si ***q***
  | p   | q   | p ≡ q |
  | --- | --- | ----- |
  | F   | F   | V     |
  | F   | V   | F     |
  | V   | F   | F     |
  | V   | V   | V     |
    
  *(A V B) • (~A V ~B)*

- incompatible (/)
  | p   | q   | p / q |
  | --- | --- | ----- |
  | F   | F   | v     |
  | F   | V   | v     |
  | V   | F   | v     |
  | V   | V   | F     |

*"una tautologia es una proposicon que siempre da verdadero y una contradiccion una que siempre da falso, una contingencia puede dar verdadero o falso"*

## relaciones entre formas proposicionales
- Contrariedad (nand): no son simultaneamente verdaderas
- Subcontrariedad (or): no son simultaneamente falsas
- Contradictorias (xor): si no son simultaneamente verdaderas ni falsas
- Equivalentes (xnor): dos formas proposicionales son equivalentes si y solo si en cada caso tienen el mismo valor
- Implicacion (⊃): una forma proposicional implica a otra forma proposicional si y solo si no ocurre que siendo la primera verdadera, la segunda sea falsa (contraejemplo). Si una forma implica a otra, la segunda se deduce de la primera
- deduccion: *una implicacion en sentido contrario es una deduccion, si A implica B, entonces B se deduce de A*

## algebra de boole
- conmutativa
- distriburiva
- asociativa
- identidad
- anulacion
- idempotencia
- absorcion
- complementacion
- involucion
- de morgan

## Leyes de demorgan
### negacion de la conjuncion
~(P • Q) <=> (~P) V (~Q)

~(P V Q) <=> (~P) • (~Q)


P V Q <=> ~(~P • ~Q)
P • Q <=> ~(~P V ~Q)




## Razonamientos
- deductivos (son validos)
  - formales
  - logicos
- inductivos
- falaces (son invalidas)
  - formales
  - materiales

## expresiones derivativas
- indicadores: pues, puesto que, ya que, dado que, porque
- conclusion: por lo tanto, asi que, luego, por consiguiente, en consecuencia, por ende, de modo que, de manera que

## Tipos de logica
- formal
- cuantificacional
- informal (razonamientos inductivos y falacias materiales)


*un razonamiento es valido si su forma es valida y una forma valida es aquella en la cual las premisas implican a la conclusion*

## Prueba de invalidez (asignacion de valores)
1. reemplazar las  variables del consecuente para forzar un valor falso
2. si da falso reemplazar las variables con los mismos valores en las premisas y forzar un valor verdadero
3. Si la expresion da V ⊃ F entonces el razonamiento es invalido
   
una proposicion es invalida cuando las premisas no implican a la conclusion


## Metavariables
*variables que contienen expresiones*
por ejemplo
A = P w Q

## Reglas logicas
- modus ponens:
  - P⊃Q,P ∴ Q
- doble negacion
  - !!Q = Q
- silogismo hipotetico
  - (P ⊃ Q ⊃ R) ∴ (P ⊃ R)
- silogismo disyuntivo
  - 
- simplificacion
- adicion