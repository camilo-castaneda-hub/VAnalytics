## Notas básicas de los modismos implementados.

### Gráfica de barras:
La gráfica muestra la distribución de películas por calificación de IMDb, ideal para comprender la distribución de las calificaciones de IMDb. Puede responder a preguntas como:

- ¿Cuál es la calificación de IMDb más común?

### Gráfica de líneas:
La gráfica muestra la evolución de la recaudación bruta en Estados Unidos de las películas a lo largo del tiempo. Esta gráfica está dividida en dos partes:

- La parte superior muestra la evolución de la recaudación bruta en Estados Unidos de las películas a lo largo del tiempo, con un intervalo de tiempo variable. El intervalo de tiempo se puede seleccionar utilizando el parámetro brush.
- La parte inferior muestra la recaudación bruta en Estados Unidos media por año.

Esto se logra gracias al atributo "params" y sus características.
Se podría concluir que la recaudación bruta en Estados Unidos de las películas ha ido aumentando a lo largo del tiempo. El aumento ha sido especialmente pronunciado en los últimos años. Y la regla en la gráfica muestra la recaudación bruta en Estados Unidos media por año. La regla se traza utilizando el canal de acumulación para contar la recaudación bruta de las películas en cada año.

### Diagrama de dispersión:
La gráfica muestra la relación entre la recaudación bruta en Estados Unidos y la recaudación bruta mundial de películas.
Como filtro dinámico se usa el parámetro opacity, que controla la opacidad de los puntos de datos. El valor predeterminado es 50, lo que significa que los puntos de datos son semitransparentes.

### Gráfico de anillos:
La gráfica muestra la distribución de películas por género principal, cada anillo representa un género principal. El tamaño de cada anillo es proporcional al número de películas en ese género. Puede responder a preguntas como:

- ¿Cuál es el género principal más común de las películas?

*nota: los valores nulos se deberían descartar por ruido en los datos, sin embargo, es una cantidad importante, he ahí el dilema :/*


