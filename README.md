# ADC

1) Colocar el punto medio del potenciómetro en PA0 y los otros dos en 3V3 y GND
2) Ajustar el potenciónmetro aproximadamente en la mitad de la posición
3) Clonar el repositorio y abrir el proyecto STM32CubeIDE
4) Enchufar la placa NUCLEO-F103RB
5) Analizar la configuración del ADC configurado, sin modificarla

## Test 1
6) Volver al código y configurar el primer test, verificando la etiqueta TEST_NUMBER, es decir que diga #define TEST_NUMBER 1
7) Compilar y debuggear. En la consola deben listarse 100 muestras.
8) Ingresar a https://www.wedodatascience.com/graphs/histogram y hacer click en Histogram
9) Copiar las 100 muestras desde la consola y pegarlas en la sección del sitio web 'Or input your data as csv' y apretar 'Submit CSV' para obtener un histograma de las muestras
10) Hacer Click en Statistics y tomar nota de la media y el desvío estándar (mean y std)


## Test 2
11) Volver al código y configurar el segundo test, verificando la etiqueta TEST_NUMBER, es decir que diga #define TEST_NUMBER 2
12) Compilar y debuggear. En la consola deben listarse 100 muestras.
13) Ingresar nuevamente a https://www.wedodatascience.com/graphs/histogram y hacer click en Histogram
14) Copiar las 100 muestras desde la consola y pegarlas en la sección del sitio web 'Or input your data as csv' y apretar 'Submit CSV' para obtener un histograma de las muestras
15) Hacer Click en Statistics y tomar nota de la media y el desvío estándar (mean y std)
16) Comparar resultados
