# Matematicas-IA-Descenso-Gradiente
Implementación de seis ejercicios de descenso del gradiente en Python utilizando Jupyter Notebook.

## Nota teórica: Clasificación de puntos críticos

Para determinar si un punto crítico corresponde a un mínimo, máximo o punto silla, se utiliza el criterio de la segunda derivada mediante la matriz Hessiana.

En funciones de dos variables, se calcula el determinante:

$$
D=f_{x_1x_1}f_{x_2x_2}-(f_{x_1x_2})^2
$$

**Criterios de clasificación:**

- **D > 0 y fₓ₁ₓ₁ > 0:** Mínimo local.
- **D > 0 y fₓ₁ₓ₁ < 0:** Máximo local.
- **D < 0:** Punto silla.
- **D = 0:** El criterio no es concluyente.

Este procedimiento permite clasificar los puntos críticos de una función. Para determinar si un mínimo es global, se requiere analizar propiedades adicionales de la función.

En funciones de tres o más variables, se analiza la matriz Hessiana mediante criterios de definitud, como los valores propios o los menores principales.
