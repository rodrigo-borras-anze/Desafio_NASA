# Simulador de Despegue - Misión NASA 1962 🚀

Este proyecto es una aplicación web interactiva desarrollada como desafío práctico para la asignatura de **Métodos Numéricos**. Está inspirado en los cálculos de trayectoria realizados por las matemáticas de la NASA en 1962 (como se muestra en la película *Talentos Ocultos*).

## 📝 Descripción del Proyecto

La aplicación simula el despegue vertical de un cohete experimental durante los primeros 20 segundos de vuelo. Para ello, resuelve una ecuación diferencial ordinaria de primer orden utilizando diferentes métodos numéricos y los compara con la solución analítica exacta.

### Características Principales:
*   **Ingreso de parámetros personalizados:** Masa, empuje, gravedad, coeficiente de resistencia, tamaño de paso ($h$) y tiempo total de simulación.
*   **Múltiples Métodos Numéricos:** Implementación iterativa de:
    *   Método de Euler (1er orden)
    *   Método de Heun (2do orden)
    *   Método de Runge-Kutta (4to orden - RK4)
*   **Solución Analítica:** Cálculo del valor exacto para contrastar la precisión.
*   **Visualización de Datos:** Gráficas interactivas generadas con Chart.js y tablas comparativas de error absoluto.

## 🧮 Modelo Matemático

El ascenso del cohete se modela a partir de la Segunda Ley de Newton ($\Sigma F = ma$), considerando el empuje del motor, el peso y la resistencia aerodinámica. La ecuación diferencial resultante para la velocidad es:

$$ \frac{dv}{dt} = \frac{T}{m} - g - \frac{k}{m}v $$

Donde:
*   $m$ = Masa del cohete (kg)
*   $T$ = Empuje (N)
*   $g$ = Gravedad ($m/s^2$)
*   $k$ = Coeficiente de resistencia ($kg/s$)
*   $v$ = Velocidad ($m/s$)

## 🛠️ Tecnologías Utilizadas

*   **HTML5 & CSS3:** Estructura y diseño de la interfaz de usuario.
*   **JavaScript (Vanilla):** Lógica matemática y métodos iterativos.
*   **Chart.js:** Librería para la renderización de las gráficas comparativas.

## 🚀 Cómo ejecutar el proyecto

1.  Clona este repositorio o descarga los archivos.
2.  Abre el archivo `index.html` directamente en cualquier navegador web (Chrome, Firefox, Edge, etc.).
3.  *Opcional:* Puedes ver la versión en vivo alojada en GitHub Pages haciendo clic en el enlace del panel lateral derecho (sección "Environments").

## 👨‍💻 Autor

*   **Rodrigo Borras Anze** - *Desarrollo de simulación numérica*