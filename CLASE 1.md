# Ecuaciones Diferenciales y Transformada de Laplace

## 1. Metodología de solución

### 1.1 Pasos generales

1. Aplicar la **Transformada de Laplace** a toda la ecuación diferencial.
2. Despejar la función incógnita en el dominio `s`.
3. Aplicar la **Transformada Inversa de Laplace** para obtener la solución en el dominio del tiempo.

## 2. Definiciones

>🔑 *Transformada de Laplace:* Método integral que transforma una función del tiempo \( f(t) \) en una función del dominio complejo \( F(s) \), facilitando la solución de ecuaciones diferenciales.

>🔑 *Transformada inversa de Laplace:* Operación que permite recuperar la función original en el dominio del tiempo a partir de su expresión transformada en el dominio `s`.

## 3. Ejemplos

### 💡Ejemplo 1:

$$\[
\ddot{x} + 3\dot{x} + 2x = 0,\quad \dot{x}(0) = a,\quad x(0) = b
\]$$

Aplicando la transformada de Laplace:

\[
s^2X(s) - sa - b + 3[sX(s) - a] + 2X(s) = 0
\]

\[
(s^2 + 3s + 2)X(s) = sa + b + 3a
\]

\[
X(s) = \frac{a(s+1) + b}{(s+1)(s+2)}
\]

Transformada inversa:

\[
x(t) = ae^{-2t} + (a + b)e^{-t},\quad t \geq 0
\]

---

### 💡Ejemplo 2:

\[
\ddot{x} + 2\dot{x} + 5x = 3,\quad x(0) = 0,\quad \dot{x}(0) = 0
\]

Transformada de Laplace:

\[
s^2X(s) + 2sX(s) + 5X(s) = \frac{3}{s}
\Rightarrow X(s) = \frac{3}{s(s^2 + 2s + 5)}
\]

Fracciones parciales:

\[
X(s) = \frac{A}{s} + \frac{Bs + C}{s^2 + 2s + 5}
\]

Donde:

- \( A = \frac{3}{5} \)
- \( B = -\frac{3}{5} \)
- \( C = -\frac{6}{5} \)

Reescribimos:

\[
X(s) = \frac{3}{5s} - \frac{3s + 6}{5((s+1)^2 + 4)}
\]

Transformada inversa:

\[
x(t) = \frac{3}{5} - \frac{3}{5}e^{-t}\cos(2t) - \frac{3}{10}e^{-t}\sin(2t)
\]

## 9. Ejercicios

📚 **Ejercicio 1:**

Resuelve:
$$\[
\ddot{y} + 4y = \cos(2t),\quad y(0) = 0,\quad \dot{y}(0) = 0$$
\]

✅ **Solución:**

Transformada de Laplace:

\[
s^2Y(s) + 4Y(s) = \frac{s}{s^2 + 4}
\Rightarrow Y(s) = \frac{s}{(s^2 + 4)^2}
\]

Transformada inversa (tabla de transformadas):

\[
y(t) = \frac{1}{4}t\sin(2t)
\]

📚 **Ejercicio 2:**

Resuelve:
$$\[
\dot{y} + y = e^{-2t},\quad y(0) = 1
\]$$

✅ **Solución:**

\[
sY(s) - y(0) + Y(s) = \frac{1}{s + 2}
\Rightarrow (s + 1)Y(s) = \frac{1}{s + 2} + 1
\Rightarrow Y(s) = \frac{1}{(s + 1)(s + 2)} + \frac{1}{s + 1}
\]

Transformada inversa:

\[
y(t) = e^{-t} + \left(e^{-t} - e^{-2t}\right)
= 2e^{-t} - e^{-2t}
\]

## 10. Conclusiones

La transformada de Laplace permite resolver ecuaciones diferenciales de manera sistemática, convirtiéndolas en expresiones algebraicas manejables. El dominio `s` facilita el trabajo con condiciones iniciales y simplifica la obtención de soluciones analíticas.

## 11. Referencias

- Tabla de transformadas de Laplace: Kreyszig, *Matemáticas Avanzadas para Ingeniería*.
- Apuntes de clase – profesor [nombre].
