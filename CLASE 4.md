# Sistemas Rotacionales

Los sistemas rotacionales son aquellos donde los cuerpos giran alrededor de un eje fijo. Este tipo de sistemas aparece comúnmente en mecanismos como motores, poleas, engranajes y turbinas. La descripción de su comportamiento dinámico incluye conceptos como trabajo, energía, potencia y disipación.

---

## 1. Trabajo

>🔑 *Trabajo:* En sistemas rotacionales, el trabajo realizado por un torque (momento) sobre un cuerpo se define como el producto del torque por el desplazamiento angular.

$$\[
W = \int_{\theta_1}^{\theta_2} \tau\, d\theta
\]$$

Donde:
- $\( W \): Trabajo (J)$
- $\( \tau \): Torque (N·m)$
- $\( \theta \): Desplazamiento angular (rad)$

---

## 2. Energía Potencial

>🔑 *Energía Potencial:* Es la energía almacenada en un cuerpo debido a su posición o configuración. En sistemas rotacionales, depende de fuerzas restauradoras como la gravedad o resortes.

$$\[
U = m g h = m g r \sin(\theta)
\]$$

Si se considera un resorte rotacional:

$$\[
U = \frac{1}{2} k_\theta \theta^2
\]$$

---

## 3. Energía Cinética

>🔑 *Energía Cinética:* Es la energía asociada al movimiento rotacional de un cuerpo.

$$\[
K = \frac{1}{2} J \omega^2
\]$$

Donde:
- $\( J \): Momento de inercia (kg·m²)$
- $\( \omega \): Velocidad angular (rad/s)$

---

## 4. Potencia

>🔑 *Potencia:* Es la tasa de trabajo realizada por unidad de tiempo. En rotación, es el producto del torque por la velocidad angular.

$$\[
P = \tau \cdot \omega
\]$$

Donde:
- $\( P \): Potencia (W)$
- $\( \tau \): Torque (N·m)$
- $\( \omega \): Velocidad angular (rad/s)$

---

## 5. Energía potencial en un resorte

>🔑 *Resorte rotacional:* Elemento que almacena energía al girarse fuera de su posición de equilibrio.

$$\[
U = \frac{1}{2} k_\theta \theta^2
\]$$

Donde:
- $\( k_\theta \): Constante del resorte torsional (N·m/rad)$
- $\( \theta \): Ángulo de torsión (rad)$

---

## 6. Potencia en un resorte

Cuando un resorte rotacional aplica un torque $\( \tau = -k_\theta \theta \)$, y el sistema gira con velocidad $\( \omega \)$, la potencia instantánea es:

$$\[
P = \tau \cdot \omega = -k_\theta \theta \cdot \omega
\]$$

---

## 7. Potencia en una masa

Si una masa gira con velocidad angular $\( \omega \)$ bajo un torque $\( \tau \)$, entonces:

$$\[
P = \tau \cdot \omega = J \alpha \cdot \omega
\]$$

Donde:
- $\( \alpha \): aceleración angular (rad/s²)$
- $\( J \): momento de inercia$

---

## 8. Energía disipada

>🔑 *Energía disipada:* Energía transformada en calor u otras formas no recuperables, normalmente por fricción o amortiguadores.

$$\[
E_d = \int_{0}^{t} c \omega^2 dt
\]$$

Donde:
- $\( c \): coeficiente de amortiguamiento rotacional (N·m·s)$

---

## 9. Potencia disipada en un amortiguador

Para un amortiguador rotacional cuya fuerza disipa energía proporcional a la velocidad angular:

$$\[
P_d = c \omega^2
\]$$

---

## 10. Sistema Conservativo

>🔑 *Sistema conservativo:* Sistema en el que no hay pérdida de energía mecánica, es decir, la suma de la energía cinética y la potencial se mantiene constante:

$$\[
E = K + U = \text{constante}
\]$$

### Ejemplo:

Supongamos un disco rotando sin fricción y con un resorte torsional. Se aplica un desplazamiento angular y se suelta. La energía cinética y potencial se intercambian continuamente, pero su suma se conserva:

$$\[
\frac{1}{2}J\omega^2 + \frac{1}{2}k_\theta \theta^2 = \text{constante}
\]$$

---

##  Ejemplo completo

### 💡Ejemplo 1:

Un disco con $\( J = 0.2\ \text{kg·m}^2 \)$ está sujeto a un resorte torsional con $\( k_\theta = 5\ \text{N·m/rad} \)$. Inicialmente se encuentra en reposo, desplazado angularmente $\( \theta_0 = 0.1\ \text{rad} \)$. Determina la energía total del sistema y su frecuencia de oscilación.

 **Solución:**

**Energía total:**

$$\[
E = \frac{1}{2}k_\theta \theta^2 = \frac{1}{2}(5)(0.1)^2 = 0.025\ \text{J}
\]$$

**Frecuencia de oscilación:**

$$\[
\omega_n = \sqrt{\frac{k_\theta}{J}} = \sqrt{\frac{5}{0.2}} = \sqrt{25} = 5\ \text{rad/s}
\]$$


##  11.Caso Vertical

El **caso vertical** es un tipo de movimiento rectilíneo uniformemente acelerado (MRUA) en el que un objeto se lanza hacia arriba o hacia abajo bajo la influencia de la **gravedad**, sin resistencia del aire.

- **Aceleración**: En este caso, la aceleración es constante y dirigida hacia abajo, con un valor aproximado de `g = 9.8 m/s²`.
- **Velocidad**: Al subir, la velocidad disminuye hasta llegar a 0 en el punto más alto. Al bajar, la velocidad aumenta.

**Ejemplo:**
> Si lanzamos una pelota verticalmente hacia arriba con una velocidad inicial de 20 m/s, ¿cuánto tiempo tarda en alcanzar el punto más alto?

**Solución:**
$$\[
v = v_0 - g \cdot t \Rightarrow 0 = 20 - 9.8t \Rightarrow t = \frac{20}{9.8} \approx 2.04 \, \text{segundos}
\]$$


##  12.Energía Cinética

La **energía cinética (EC)** es la energía que posee un objeto debido a su movimiento. Se define como:

$$\[
EC = \frac{1}{2}mv^2
\]$$

Donde:
- $\( m \) es la masa del objeto (en kg)$
- $\( v \) es la velocidad del objeto (en m/s)$

**Características:**
- Es siempre **positiva** o **cero**.
- Depende del **cuadrado** de la velocidad, por lo que pequeñas variaciones en la velocidad tienen un gran efecto en la EC.

**Ejemplo:**
> Un coche de 1000 kg se mueve a 20 m/s. ¿Cuál es su energía cinética?

$$\[
EC = \frac{1}{2} \cdot 1000 \cdot 20^2 = 200,000 \, \text{J}
\]$$

---

## 13.Movimiento Rotacional y Translacional

Algunos objetos pueden moverse de forma **rotacional** y **translacional** al mismo tiempo.  
- **Translación**: todo el cuerpo se mueve en una dirección.
- **Rotación**: el cuerpo gira sobre un eje.

**Ejemplo:**
> Una rueda de bicicleta que avanza por una calle.  
La rueda rota sobre su eje (movimiento rotacional) **y** al mismo tiempo se desplaza hacia adelante (movimiento translacional).

**Relación entre velocidad lineal y angular:**

$$\[
v = \omega \cdot r
\]$$

Donde:
- $\( v \) es la velocidad lineal$
- $\( \omega \) es la velocidad angular$
- $\( r \) es el radio de la rueda$

---

**Conclusión:**  
Estos conceptos están interrelacionados y son fundamentales para entender la dinámica de los cuerpos en movimiento, tanto en situaciones cotidianas como en problemas más complejos de física.



## 12. Conclusión

Los sistemas rotacionales permiten analizar fenómenos mecánicos asociados al giro de cuerpos rígidos. Comprender el trabajo, la energía y la potencia involucrada en estos sistemas es esencial para el diseño de mecanismos eficientes. La conservación de energía es un principio clave para distinguir sistemas disipativos y conservativos.


