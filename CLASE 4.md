# Sistemas Rotacionales

Los sistemas rotacionales son aquellos donde los cuerpos giran alrededor de un eje fijo. Este tipo de sistemas aparece comúnmente en mecanismos como motores, poleas, engranajes y turbinas. La descripción de su comportamiento dinámico incluye conceptos como trabajo, energía, potencia y disipación.

---

## 1. Trabajo

>🔑 *Trabajo:* En sistemas rotacionales, el trabajo realizado por un torque (momento) sobre un cuerpo se define como el producto del torque por el desplazamiento angular.

$\[
W = \int_{\theta_1}^{\theta_2} \tau\, d\theta
\]$

Donde:
- $\( W \): Trabajo (J)$
- $\( \tau \): Torque (N·m)$
- $\( \theta \): Desplazamiento angular (rad)$

---

## 2. Energía Potencial

>🔑 *Energía Potencial:* Es la energía almacenada en un cuerpo debido a su posición o configuración. En sistemas rotacionales, depende de fuerzas restauradoras como la gravedad o resortes.

$\[
U = m g h = m g r \sin(\theta)
\]$

Si se considera un resorte rotacional:

$\[
U = \frac{1}{2} k_\theta \theta^2
\]$

---

## 3. Energía Cinética

>🔑 *Energía Cinética:* Es la energía asociada al movimiento rotacional de un cuerpo.

$\[
K = \frac{1}{2} J \omega^2
\]$

Donde:
- $\( J \): Momento de inercia (kg·m²)$
- $\( \omega \): Velocidad angular (rad/s)$

---

## 4. Potencia

>🔑 *Potencia:* Es la tasa de trabajo realizada por unidad de tiempo. En rotación, es el producto del torque por la velocidad angular.

$\[
P = \tau \cdot \omega
\]$

Donde:
- $\( P \): Potencia (W)$
- $\( \tau \): Torque (N·m)$
- $\( \omega \): Velocidad angular (rad/s)$

---

## 5. Energía potencial en un resorte

>🔑 *Resorte rotacional:* Elemento que almacena energía al girarse fuera de su posición de equilibrio.

$\[
U = \frac{1}{2} k_\theta \theta^2
\]$

Donde:
- $\( k_\theta \): Constante del resorte torsional (N·m/rad)$
- $\( \theta \): Ángulo de torsión (rad)$

---

## 6. Potencia en un resorte

Cuando un resorte rotacional aplica un torque \( \tau = -k_\theta \theta \), y el sistema gira con velocidad \( \omega \), la potencia instantánea es:

$\[
P = \tau \cdot \omega = -k_\theta \theta \cdot \omega
\]$

---

## 7. Potencia en una masa

Si una masa gira con velocidad angular \( \omega \) bajo un torque \( \tau \), entonces:

$\[
P = \tau \cdot \omega = J \alpha \cdot \omega
\]$

Donde:
- $\( \alpha \): aceleración angular (rad/s²)$
- $\( J \): momento de inercia$

---

## 8. Energía disipada

>🔑 *Energía disipada:* Energía transformada en calor u otras formas no recuperables, normalmente por fricción o amortiguadores.

$\[
E_d = \int_{0}^{t} c \omega^2 dt
\]$

Donde:
- $\( c \): coeficiente de amortiguamiento rotacional (N·m·s)$

---

## 9. Potencia disipada en un amortiguador

Para un amortiguador rotacional cuya fuerza disipa energía proporcional a la velocidad angular:

$\[
P_d = c \omega^2
\]$

---

## 10. Sistema Conservativo

>🔑 *Sistema conservativo:* Sistema en el que no hay pérdida de energía mecánica, es decir, la suma de la energía cinética y la potencial se mantiene constante:

$\[
E = K + U = \text{constante}
\]$

### Ejemplo:

Supongamos un disco rotando sin fricción y con un resorte torsional. Se aplica un desplazamiento angular y se suelta. La energía cinética y potencial se intercambian continuamente, pero su suma se conserva:

$\[
\frac{1}{2}J\omega^2 + \frac{1}{2}k_\theta \theta^2 = \text{constante}
\]$

---

## 11. Ejemplo completo

### 💡Ejemplo 1:

Un disco con \( J = 0.2\ \text{kg·m}^2 \) está sujeto a un resorte torsional con \( k_\theta = 5\ \text{N·m/rad} \). Inicialmente se encuentra en reposo, desplazado angularmente \( \theta_0 = 0.1\ \text{rad} \). Determina la energía total del sistema y su frecuencia de oscilación.

✅ **Solución:**

**Energía total:**

$\[
E = \frac{1}{2}k_\theta \theta^2 = \frac{1}{2}(5)(0.1)^2 = 0.025\ \text{J}
\]$

**Frecuencia de oscilación:**

$\[
\omega_n = \sqrt{\frac{k_\theta}{J}} = \sqrt{\frac{5}{0.2}} = \sqrt{25} = 5\ \text{rad/s}
\]$

---

## 12. Conclusión

Los sistemas rotacionales permiten analizar fenómenos mecánicos asociados al giro de cuerpos rígidos. Comprender el trabajo, la energía y la potencia involucrada en estos sistemas es esencial para el diseño de mecanismos eficientes. La conservación de energía es un principio clave para distinguir sistemas disipativos y conservativos.

---

## 13. Referencias

- Apuntes de clase – profesor [nombre]
- Figuras desarrolladas por el estudiante
- Meriam & Kraige – *Dinámica*
- Kreyszig – *Matemáticas Avanzadas para Ingeniería*
