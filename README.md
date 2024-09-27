<h1 align="center"> Pensamiento critico </h1>

<p align="center"> Hecho por: Lucio el mejor :)</p>

## citas textuales y conceptos de la primera clase:
*la logica es una ciencia **formal** que estudia las estructuras del pensamiento*

*una ciencia debe contener un objeto de estudio, un metodo y una teoria*

*la filosofia no se considera una ciencia porque pretende estudiarlo todo*

*con las ciencias facticas podemos suponer esa relacion causal en un hecho no asi con las ciencias formales*

*el cambio es una caracteristica de la realidad*


## ciencias
| Formales | Facticas |
| --- | --- |
| Tiene un objeto de estudio ideal                                                           | El objeto de estudio es real                                |
| El metodo es la deduccion, que siempre esta sujeto a una hipotesis determinada por axiomas | Utilizan el metodo empirico, no esta sujeto a una hipotesis |
| Logica, matematica, semantica, etc...                                                      | Fisica, quimica, psicologia, etc...                         |


| imaginario                           | ideal |
| ------------------------------------ | ----- |
| implementa elementos de la  realidad |       |


*el pensamiento viene de la mano con el lenguaje*

*un lenguaje artificial surge para analizar un lenguaje natural*

___

## Conceptos

*relaciones simetricas y asimetricas*

*casos de sustitucion*




## logica proposicional

*es un lenguaje artificial formado por:*
- letras esquematicas (variables)
- conectivas
- signos auxiliares () [] {}

## Proposiciones
las proposiciones deben cumplir 3 requisitos
- debe ser una oracion enunciativa (tener copula)
- debe ser una  afirmacion o una negacion
- debe poder clasificarse en un valor booleano (verdadero o falso)

se dividen en:
- Condicional (compleja)
- Disyuntiva (compleja)
- Categorica (simple)

# conectivas
Con sus respectivas tablas de verdad y simbolos

- ### conjuncion (and) (•) ***p*** y ***q***

    | p   | q   | p • q |
    | --- | --- | ----- |
    | V   | V   | V     |
    | V   | F   | F     |
    | F   | V   | F     |
    | F   | F   | F     |

- ### disyuncion inclusiva (or) (∨) ***p*** y/o ***q***

    | p   | q   | p ∨ q |
    | --- | --- | ----- |
    | V   | V   | V     |
    | V   | F   | V     |
    | F   | V   | V     |
    | F   | F   | F     |

- ### disyuncion excluyente (xor) (W): ***p*** o ***q***

    | p   | q   | p W q |
    | --- | --- | ----- |
    | V   | V   | F     |
    | V   | F   | V     |
    | F   | V   | V     |
    | F   | F   | F     |

    tambien se expresa como: `(A • ~B) ∨ (~A • B)`
- ### negacion (not) (~) ***p*** es falso

    | p   | ~p  |
    | --- | --- |
    | V   | F   |
    | F   | V   |

- ### condicional (⊃) si ***p*** entonces ***q***

    | p   | q   | p ⊃ q |
    | --- | --- | ----- |
    | V   | V   | V     |
    | V   | F   | F     |
    | F   | V   | V     |
    | F   | F   | V     |

    
  #### p = condicion suficiente **(antecedente)**
  - "si"
  - "es suficiente"
  - "alcanza"
  #### q = Condicion necesaria **(consecuente)**
  -	"solo si"
  - "es necesario"
  - "unicamente"


- ### bicondicional (xnor) (≡) ***p*** si y solo si ***q***
  | p   | q   | p ≡ q |
  | --- | --- | ----- |
  | F   | F   | V     |
  | F   | V   | F     |
  | V   | F   | F     |
  | V   | V   | V     |
    
  tambien se expresa como: `(A V B) • (~A V ~B)`

- ### incompatible (/)
  | p   | q   | p / q |
  | --- | --- | ----- |
  | F   | F   | V     |
  | F   | V   | V     |
  | V   | F   | V     |
  | V   | V   | F     |

*"una tautologia es una proposicon que siempre da verdadero y una contradiccion una que siempre da falso, una contingencia puede dar verdadero o falso"*

# relaciones entre formas proposicionales
**Si no sos lucio ignorá las relacioens que hice con las compuertas logicas :p**
- ### Contrariedad *(nand)*:
  - dos formas proposicionales son contrarias cuando **no son simultaneamente verdaderas.**
  - relación **simetrica**

- ### Subcontrariedad *(or)*:
    - dos formas proposicionales son subcontrarias cuando **no son simultaneamente falsas.**
  - relación **simetrica**

- ### Contradictorias *(xor)*:
  - dos formas proposicionales son contradictorias cuando **no son simultaneamente verdaderas ni falsas** (son distintas en todos los casos)
  - relación **simetrica**
  
- ### Equivalentes *(xnor)*:
  - dos formas proposicionales son equivalentes si y solo si **en cada caso tienen el mismo valor** (son iguales en todos los casos)
  - relación **simetrica**
- ### Implicacion (⊃):
  - una forma proposicional implica a otra si y solo si no ocurre que siendo la primera verdadera, la segunda sea falsa (contraejemplo). Si una forma implica a otra, la segunda se deduce de la primera
  - relación **asimetrica**
- ### deduccion:
  - *una implicacion en sentido contrario es una deduccion, si A implica B, entonces B se deduce de A*
  -  relación **asimetrica**

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
*es tratar de demostrar V ∴ F reemplazando las variables, si el razonamiento supera la prueba de invalidez significa que es valido, duh..*
1. reemplazar las  variables del consecuente para forzar un valor falso. Si lo logras ya sabes que el razonamiento no es una tautología!
2. si da falso reemplazar las variables en las premisas con los mismos valores que usaste en el consecuente *(no te hagas el vivo)* y trata de forzar un resultado verdadero
3. Si la expresion da V ∴ F entonces el razonamiento es invalido.

*una proposicion es invalida cuando las premisas no implican a la conclusion*

___
**barra separadora de segundo parcial**

# Álgebra de Boole

## Ley Conmutativa
- **Suma (OR):**  
  `A ∨ B = B ∨ A`
- **Producto (AND):**  
  `A • B = B • A`

## Ley Distributiva
- **Suma sobre producto (OR sobre AND):**  
  `A ∨ (B • C) = (A ∨ B) • (A ∨ C)`
- **Producto sobre suma (AND sobre OR):**  
  `A • (B ∨ C) = (A • B) ∨ (A • C)`

## Ley Asociativa
- **Suma (OR):**  
  `(A ∨ B) ∨ C = A ∨ (B ∨ C)`
- **Producto (AND):**  
  `(A • B) • C = A • (B • C)`

## Ley de Identidad
- **Suma (OR):**  
  `A ∨ 0 = A`
- **Producto (AND):**  
  `A • 1 = A`

## Ley de Anulación
- **Suma (OR):**  
  `A ∨ 1 = 1`
- **Producto (AND):**  
  `A • 0 = 0`

## Ley de Idempotencia
- **Suma (OR):**  
  `A ∨ A = A`
- **Producto (AND):**  
  `A • A = A`

## Ley de Absorción
- **Primera ley:**  
  `A ∨ (A • B) = A`
- **Segunda ley:**  
  `A • (A ∨ B) = A`

## Ley de Complementación
- **Suma (OR):**  
  `A ∨ ~A = 1`
- **Producto (AND):**  
  `A • ~A = 0`

## Ley de Involución
- `~~A = A`

## Leyes de De Morgan
- **Primera ley:**  
  `~(A ∨ B) = ~A • ~B`
- **Segunda ley:**  
  `~(A • B) = ~A ∨ ~B`



## Metavariables
*variables que contienen expresiones*
por ejemplo
`A = P w Q`

## Reglas Lógicas
- **Modus Ponens**:
  - `P ⊃ Q, P ∴ Q`
- **Doble Negación**:
  - `!!Q = Q`
- **Silogismo Hipotético**:
  - `(P ⊃ Q) ⊃ R ∴ (P ⊃ R)`
- **Silogismo Disyuntivo**:
  - `P ∨ Q, ¬P ∴ Q`
- **Simplificación**:
  - `P • Q ∴ P`
- **Adición**:
  - `P ∴ P ∨ Q`