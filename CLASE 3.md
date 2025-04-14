# Sistema Masa-Resorte-Amortiguador

El sistema masa-resorte-amortiguador es uno de los modelos fundamentales en dinámica de sistemas físicos. Representa un cuerpo con masa conectado a un resorte y a un amortiguador, y sirve para estudiar fenómenos como vibraciones, oscilaciones, disipación de energía y respuesta ante fuerzas externas.

Es ampliamente utilizado en ingeniería mecánica, automotriz, robótica y control de sistemas.

---

## 1. Definición

>🔑 *Sistema masa-resorte-amortiguador:* Modelo mecánico compuesto por una masa conectada a un resorte (que aporta elasticidad) y a un amortiguador (que disipa energía). Describe el movimiento del sistema cuando se le aplica una fuerza externa o se encuentra en oscilación libre.

---

## 2. Ecuación del sistema

Se parte de la Segunda Ley de Newton:  
**Suma de fuerzas = masa × aceleración**

$$\[
m\ddot{x}(t) + c\dot{x}(t) + kx(t) = F(t)
\]$$

Donde:
- \( m \): masa del cuerpo (kg)
- \( c \): coeficiente de amortiguamiento (N·s/m)
- \( k \): constante del resorte (N/m)
- \( x(t) \): desplazamiento en el tiempo (m)
- \( F(t) \): fuerza externa aplicada (N)

---

## 3. Tipos de respuesta del sistema

- **Respuesta libre:** cuando \( F(t) = 0 \), el sistema se mueve debido a condiciones iniciales.
- **Respuesta forzada:** cuando se aplica una fuerza \( F(t) \neq 0 \).
- **Subamortiguado:** oscila con amplitud decreciente.
- **Críticamente amortiguado:** vuelve al equilibrio en el menor tiempo sin oscilar.
- **Sobreamortiguado:** vuelve al equilibrio sin oscilar, más lentamente.



## Ejemplo


 |<-- K2 -->|       u(t)
   ┌───────┐   ↑
   │   m   │   │
   └───────┘   │
   |<----->|   ↓
   Pared   K1   Superficie



## Fenómenos físicos que modelan el sistema

- $fr = K₂ * x→ Ley de Hooke$
- $Ff = K₁ * Vm** → Fricción viscosa$
- $F = m * a** → Ley de Newton$



## Diagrama de bloques


u ──► [ Sistema ] ──► y
     entrada       salida




## Diagrama de cuerpo libre


←── fr ──[ m ]── ff ──→
          ↑
         u(t)


## Desarrollo de la ecuación

Partimos de la Segunda Ley de Newton:


$u - fr - ff = m * a$


Sustituyendo fr y ff:

$fr = K₂ * y(t)$
$ff = K₁ * dy(t)/dt$


Entonces:


$u(t) - K₂ * y(t) - K₁ * dy(t)/dt = m * a$


Y como:


$a = d²y(t)/dt²$


Finalmente obtenemos la ecuación del sistema:


$u(t) - K₂ * y(t) - K₁ * dy(t)/dt = m * d²y(t)/dt²$

$\[
u(t) = K_2 \cdot y(t) + K_1 \cdot \frac{dy(t)}{dt} + m \cdot \frac{d^2 y(t)}{dt^2}
\]$



## 4. Diagrama del sistema

![Diagrama MRA](https://github.com/JhonyCasas/Sistemas-Din-micos-/blob/main/Imagenes%20Apuntes/2025-04-07%20155735.png)  
*Figura 1: Sistema masa-resorte-amortiguador con notación estándar*

