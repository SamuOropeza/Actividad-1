# Actividad 1: Paint Game - Extensión de Funcionalidades

Este repositorio contiene la evolución del software "Paint", enfocado en la implementación de geometrías complejas y gestión de estados de color.

## Registro de Cambios (Version Control)

### Push 1: Gestión de Color y Geometría Circular
* **Modificación de Teclado:** Se integró el mapeo de la tecla 'O' para el color naranja mediante `onkey(lambda: color('orange'), 'O')`.
* **Cálculo de Radio:** Se implementó la función `circle(start, end)` utilizando el teorema de Pitágoras para determinar la magnitud del radio basada en la distancia euclidiana entre los puntos de clic inicial y final.

### Push 2: Lógica Poligonal (Rectángulo y Triángulo)
* **Geometría de Rectángulo:** Rediseño del ciclo de renderizado en `rectangle(start, end)` para permitir la distinción entre base y altura mediante vectores de desplazamiento independientes.
* **Geometría de Triángulo:** Implementación de un ciclo de iteración triple con una rotación de 120° para asegurar el cierre de un triángulo equilátero dinámico.
