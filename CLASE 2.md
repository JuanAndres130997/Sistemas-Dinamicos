# Sistemas Mecánicos

Los sistemas mecánicos son modelos físicos que permiten representar el movimiento de cuerpos sometidos a fuerzas. Están formados por componentes como masas, resortes, amortiguadores y fricción, y su comportamiento se describe mediante ecuaciones diferenciales obtenidas a partir de la Segunda Ley de Newton.

## 2. Definiciones

>🔑 *Ley de Hooke:* principio físico que establece que la fuerza ejercida por un resorte es proporcional a su elongación, es decir, \( F = -kx \), donde \( k \) es la constante del resorte y \( x \) el desplazamiento respecto a la posición de equilibrio.

>🔑 *Fricción viscosa:* tipo de fricción que se opone al movimiento y es proporcional a la velocidad. Se modela como $\( F = -b \dot{x} \)$, donde \( b \) es el coeficiente de amortiguamiento y \( \dot{x} \) la velocidad.

>🔑 *Segunda Ley de Newton:* ley fundamental de la dinámica que indica que la fuerza neta aplicada a un cuerpo es igual al producto de su masa por su aceleración: \( F = ma \).

##  Resortes

>🔑 *Resorte:* Es un elemento elástico que genera una fuerza proporcional al desplazamiento desde su posición de equilibrio. Su comportamiento se describe mediante la ley de Hooke.

### Ecuación:

$\[
F = kx = k(x_1 - x_2)
\]$


Donde:
- $\( F_s \)$: Fuerza del resorte (N)
- $\( k \)$: Constante del resorte o rigidez (N/m)
- $\( x \)$: Desplazamiento desde la posición de equilibrio (m)


[Resorte](images/resorte.png)

## Amortiguador

>🔑 *Amortiguador:* Es un elemento mecánico que disipa energía al oponerse al movimiento. Su fuerza es proporcional a la velocidad del cuerpo en movimiento y se opone a ella.

### Ecuación:

$\[
F = bx = b(x_1 - x_2)
\]$


Donde:
- $\( F_d \): Fuerza del amortiguador (N)$
-$ \( c \): Coeficiente de amortiguamiento (N·s/m)$
- $\( \dot{x} \): Velocidad del cuerpo (m/s)$

![Amortiguador](images/amortiguador.png)

 ## Fricción en seco y por rodamiento

>🔑 *Fricción:* Es la fuerza que se opone al movimiento relativo entre dos superficies en contacto. Puede clasificarse en **fricción en seco (Coulomb)** y **fricción por rodamiento**.

---

### Fricción en seco (Coulomb)

Se produce cuando un cuerpo se desliza sobre una superficie sin lubricación. La magnitud de la fuerza es constante y depende del sentido del movimiento.

#### Ecuación:

$\[
F_f = -\mu N \cdot \text{sgn}(\dot{x})
\]$

Donde:
-$\( F_f \): Fuerza de fricción en seco (N)$
- $\( \mu \): Coeficiente de fricción (adimensional)$
- $\( N \): Fuerza normal (N)$
- $\( \text{sgn}(\dot{x}) \): Signo de la velocidad (indica dirección de la fricción)$

---

### Fricción por rodamiento

Se da cuando un cuerpo rueda sobre una superficie. Esta fricción se puede modelar como proporcional a la velocidad para simplificar análisis.

#### Ecuación:

$\[
F_r = -b \dot{x}
\]$

Donde:
- $\( F_r \): Fuerza de fricción por rodamiento (N)$
- $\( b \): Coeficiente de fricción por rodamiento (N·s/m)$
- $\( \dot{x} \): Velocidad (m/s)$


![Fricción](images/friccion.png)
