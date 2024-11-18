---
hide:
    - toc
---

# Pruebas con el material

Visité el taller de Andrés Parravicini en Montevideo, un espacio completamente equipado con una amplia variedad de herramientas manuales y eléctricas especializadas en carpintería. Además, cuenta con equipos de fabricación digital de última generación, como una fresadora CNC y una cortadora láser, que permiten realizar proyectos con un alto nivel de precisión y detalle.

![](../images/PFI02/IMG-20241116-WA0009.jpg)
![](../images/PFI02/IMG-20241116-WA0010.jpg)
![](../images/PFI02/IMG-20241116-WA0011.jpg)

Al visitar el taller, me propuse los siguientes objetivos:

Realizar pruebas de corte: Centrarme en evaluar y ajustar los parámetros de velocidad y potencia de la cortadora láser para obtener cortes precisos y eficientes.

Investigar encastres: Analizar y experimentar con diferentes pruebas de ensamblaje, enfocándome en los índices de expansión y las tolerancias necesarias para lograr un ajuste perfecto.

<p style="font-size: 20px; color: red;">Corte láser:</p>

Iniciamos las pruebas utilizando los parámetros:
![](../images/PFI02/IMG-20241116-WA0006.jpg)

PROC SPD (Velocidad de corte): 1200<br>
TRVL SPD (Velocidad de desplazamiento entre cortes): 1200<br>
Cut PWR (Potencia de corte): 50%<br>
Turn PWR (Potencia de encendido): 50%<br>

![](../images/PFI02/IMG-20241116-WA0003.jpg)
![](../images/PFI02/IMG-20241116-WA0004.jpg)

Los parámetros iniciales resultaron en un corte con excesiva potencia y una velocidad demasiado baja, lo que generó quemaduras y sobrecalentamiento en el material, comprometiendo la calidad del trabajo. Para solucionar esto, ajusté los valores y realicé nuevas pruebas con los siguientes parámetros:

PROC SPD: 700<br>
TRVL SPD: 1200<br>
Cut PWR: 30<br>
Turn PWR: 30<br>

Conclusiones:<br>
Utilicé una potencia demasiado baja en relación con la velocidad de corte, lo que resultó en cortes que no lograron atravesar completamente el material. Esto evidenció la necesidad de equilibrar ambos parámetros para obtener un resultado óptimo.

PROC SPD: 700<br>
TRVL SPD: 1200<br>
Cut PWR: 40<br>
Turn PWR: 40<br>

Conclusiones:<br>
Logré ajustar la potencia y la velocidad a valores cercanos a los ideales. Sin embargo, el material aún presentaba dificultades para desprenderse completamente tras el corte, indicando que eran necesarios ajustes adicionales para perfeccionar el proceso.

PROC SPD: 600<br>
TRVL SPD: 1200<br>
Cut PWR: 40<br>
Turn PWR: 40<br>

Conclusiones: <br>
Logré encontrar una combinación adecuada de potencia y velocidad. Con estos parámetros, el corte se desprendió fácilmente de la placa, y las deformaciones en el contorno fueron mínimas, alcanzando un resultado preciso y limpio.

![](../images/PFI02/IMG-20241116-WA0002.jpg)
![](../images/PFI02/IMG-20241116-WA0008.jpg)
![](../images/PFI02/IMG-20241116-WA0001.jpg)

<p style="font-size: 20px; color: mediumseagreen;">Encastres y tolerancias:</p>

Diseñé una pieza hembra con recuadros de 10 mm x 1,5 mm, donde el espesor se incrementa progresivamente en intervalos de 0,05 mm. Este diseño tuvo como objetivo identificar la tolerancia de encastre óptima para una plancha de 1,5 mm de espesor, facilitando un ajuste preciso y funcional.

![](../images/PFI02/1.PNG)

Diseñé dos fichas con encastres tipo macho de 10 mm x 2 mm, donde el ancho del encastre disminuye en intervalos de 0,5 mm. El objetivo de estas pruebas fue determinar la tolerancia de encastre ideal para las piezas hembra mencionadas anteriormente, asegurando un ajuste adecuado entre ambas.

![](../images/PFI02/2.PNG)


Después de varias iteraciones, descubrí que la mejor tolerancia para un ajuste preciso era de 0,5 mm, tanto en las piezas hembra como en las macho.

Con este parámetro establecido, procedí a realizar pruebas de encastres tipo machimbre, con el objetivo de diseñar y ensamblar una pequeña caja, evaluando tanto la funcionalidad como la estabilidad estructural del material.

![](../images/PFI02/3.PNG)
![](../images/PFI02/IMG-20241116-WA0027.jpg)

Al realizar múltiples encastres consecutivos, en lugar de uno único, surgieron nuevas dificultades que afectaron las tolerancias establecidas. Identifiqué que la retracción del plástico, producto de las propiedades del material, generó desfasajes en las distancias entre los encastres. Además, las deformaciones inherentes al material, al no estar sometido a un proceso de fabricación industrial más controlado, contribuyeron a estos problemas. 

Como resultado, los encastres se fracturaron durante el intento de ensamblaje, evidenciando la necesidad de ajustar aún más los parámetros de diseño y fabricación.

![](../images/PFI02/IMG-20241116-WA0024.jpg)
![](../images/PFI02/IMG-20241116-WA0026.jpg)

A raíz de esto, incrementé la tolerancia a 0,6 mm, lo que resultó en una mejora significativa en los encastres. Esta pequeña modificación permitió un ajuste más preciso, reduciendo las deformaciones y evitando la fractura de los encastres durante el ensamblaje. El resultado fue más estable y funcional, lo que indica que la tolerancia de 0,6 mm es la más adecuada para este tipo de pruebas.

![](../images/PFI02/IMG-20241116-WA0020.jpg)
![](../images/PFI02/IMG-20241116-WA0021.jpg)

Aunque el encastre mejoró con la tolerancia de 0,6 mm, este no es perfecto. Si bien un lado calza correctamente, el otro no lo hace debido a que, en el punto donde se cortó la pared macho, la placa presentaba variaciones en el espesor. Estas irregularidades en el material impidieron que el encastre fuera funcional, incluso con tolerancias relativamente permisivas. 

Esto resalta la importancia de un control más preciso del espesor del material durante el proceso de corte y fabricación.

<p style="font-size: 20px; color: orange;">Conclusiones:</p>

Estoy conforme con los resultados obtenidos, pero reconozco que aún queda mucho por trabajar. Es crucial seguir experimentando con el proceso de fabricación de la placa, buscando lograr una superficie y espesor más homogéneo si deseo realizar piezas con encastres de alta precisión.

De lo contrario, me veo en la necesidad de cuestionar qué tipo de productos quiero desarrollar con este material. Podría considerar aprovechar los colores y acabados más artísticos a su favor, explorando diseños que no sean tan "cuadrados" ni tan estrictamente funcionales, sino que busquen resaltar la estética y creatividad del material. Esto abriría nuevas posibilidades y podría dar lugar a productos con un enfoque más libre y distintivo.

Sin embargo, no quisiera restringir las posibilidades de diseño de productos debido a problemas de calidad del material generado. La flexibilidad en el diseño es fundamental para explorar nuevas ideas y formas innovadoras, por lo que, aunque la calidad del material es un factor crítico, mi objetivo es seguir perfeccionando el proceso para garantizar que no sea una limitación.

<p style="font-size: 20px"; class="rainbow">¡Muchas gracias por su atención!</p>

<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embed YouTube Video</title>

<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Texto Arcoíris</title>
    <style>
        .rainbow {
            background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
            color: transparent;
            background-clip: text;
        }
    </style>    

<html lang="en">