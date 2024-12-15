# Entrega Final

Desarrollo de un modelo de reciclaje de plásticos provenientes de desechos de impresión 3D para fabricar placas funcionales: Proyecto "EcoPlaca 3D".

## Resumen

El proyecto "EcoPlaca 3D" aborda la problemática ambiental generada por los desechos plásticos provenientes de la impresión 3D, transformándolos en placas funcionales mediante el uso de tecnologías de fabricación digital y promoviendo la economía circular. En Uruguay, el crecimiento exponencial en el uso, la comercialización y la adopción de tecnologías de impresión 3D por parte de negocios locales, emprendedores y grandes empresas ha incrementado la generación de residuos plásticos, evidenciando la necesidad urgente de implementar soluciones sostenibles. Actualmente, no existen iniciativas en el país que ofrezcan una segunda vida a estos materiales, mucho menos orientadas a su conversión en placas funcionales.

Este trabajo presenta el diseño, desarrollo y fabricación de un sistema que permite reciclar los residuos plásticos generados por la impresión 3D, transformándolos en un material práctico, funcional y con valor estético. Se describen las metodologías aplicadas, los materiales y componentes utilizados, así como las preguntas clave abordadas a lo largo del proceso. El resultado es una solución innovadora, sostenible y accesible, dirigida a diseñadores, makers y emprendedores, con un modelo adaptado a las necesidades y herramientas locales, pero con potencial de replicabilidad a nivel global.

## Introducción

El reciclaje de plásticos derivados de la impresión 3D representa un desafío significativo debido a la acumulación de residuos y la falta de un sistema eficaz para su reutilización. Este proyecto surge como respuesta a esta problemática, con el objetivo de crear un sistema replicable a nivel nacional que transforme los desechos plásticos generados por la impresión 3D en un material funcional, reutilizable en nuevos procesos productivos. Se busca, además, reducir el impacto ambiental de estos residuos y fomentar prácticas de economía circular en la comunidad de diseñadores y emprendedores, con un modelo que puede ser replicado en otros contextos del mundo.

## Objetivos

Se destacan los siguientes puntos generales y específicos:

### Objetivos Generales

Desarrollar un modelo local de reciclaje de desechos plásticos generados por la impresión 3D para transformarlos en placas funcionales reutilizables.

### Objetivos Específicos

● Crear un proceso eficiente para clasificar, triturar, fundir y moldear desechos plásticos en un material laminar reutilizable.</br>

● Desarrollar un sistema basado en Arduino para el monitoreo y estandarización de las condiciones de fabricación (temperatura y humedad) de las placas recicladas.</br>

● Generar una guía y difundir la solución entre diseñadores, makers y emprendedores, promoviendo prácticas sostenibles y modelos de economía circular.</br>

● Proponer alternativas de uso para el material laminar reciclado en diversos procesos de diseño y fabricación.</br>

## Marco teórico

El marco teórico se fundamenta en los principios de economía circular y sostenibilidad en la fabricación digital. En particular, se exploran los métodos de reciclaje de plásticos y su integración con tecnologías de fabricación aditiva (impresión 3D) y fabricación sustractiva (corte láser). El uso de sistemas de monitoreo digital, como Arduino, permite optimizar el proceso y garantizar la calidad del material reciclado. Además, se abordan iniciativas globales como Precious Plastics, un proyecto de código abierto que promueve el reciclaje descentralizado de plásticos a través de la fabricación digital.

## Antecedentes

A lo largo del tiempo, la problemática de los desechos plásticos ha impulsado diversas iniciativas enfocadas en su reciclaje y reutilización, especialmente en combinación con tecnologías de fabricación digital. Estas iniciativas han servido de inspiración para el desarrollo de soluciones que promuevan la economía circular y reduzcan el impacto ambiental.

### Antecedentes mundiales

En el ámbito global, el proyecto Precious Plastics se destaca como una de las iniciativas más relevantes. Creado por Dave Hakkens, este movimiento ofrece herramientas y conocimientos para que comunidades de todo el mundo puedan reciclar plásticos a pequeña escala. Su enfoque abarca procesos de clasificación, trituración, fundición y moldeado, con diseños modulares que permiten la personalización y escalabilidad de los sistemas. 

![](../images/PFI03/PRECIOUSPLASTICS.jpg)
[Web Precious Plastics](https://www.preciousplastic.com/)

Además, otras iniciativas han explorado la reutilización de plásticos en fabricación digital, como el reciclaje de filamento para impresión 3D. Ejemplos como el Filabot y proyectos relacionados con impresión 3D circular han demostrado cómo los plásticos pueden transformarse en nuevos insumos para esta tecnología.

![](../images/PFI03/FILABOT.jpg)
[Web Filabot](https://www.filabot.com/)

### Antecedentes locales

En Uruguay, el crecimiento en el uso y comercialización de impresoras 3D ha incrementado significativamente la generación de desechos plásticos, especialmente en comunidades de diseñadores, makers y emprendedores. No obstante, hasta la fecha no se han desarrollado sistemas de gestión locales que aprovechen estos desechos de manera totalmente sistemática.

Sin embargo, se destacan algunas iniciativas que abordan la temática desde puntos ideológicos similares:

La Fábrica Makerspace es un emprendimiento que forma parte de la comunidad global de Precious Plastics y generaron el primer taller de experimentación y reciclaje de plástico en Uruguay, se dedican a tomar materiales plásticos deshechados (principalmente ABS) y utilizarlos como materia prima para generar nuevos productos.

![](../images/PFI03/LAFABRICA.PNG)
[Web La Fábrica Makersapce](https://lafabrica.uy/)

Kenistech es un emprendimiento que fabrica y comercializa filamento para impresion 3D reciclado hecho 100% a partir de plásticos de tablets, computadoras en desuso del Plan Ceibal, componentes plásticos de máquinas y periféricos (principalmente ABS).

![](../images/PFI03/KENISTECH.jpeg)
[Web Kenistech](https://fkenistech.wixsite.com/kenistech)

Si bien existen esfuerzos relacionados con el reciclaje de plásticos, estos no están adaptados para atender específicamente los residuos derivados de la impresión 3D. Por lo tanto, el país carece de un modelo que promueva la transformación de estos materiales en productos reutilizables, lo que presenta una oportunidad única para desarrollar soluciones innovadoras y sostenibles dentro del contexto nacional.

## Descripción del proyecto

El proyecto "EcoPlaca 3D" tiene como objetivo ofrecer un modelo de reciclaje adaptado a las herramientas y necesidades locales con el fin de brindar una solución innovadora y accesible a la problemática de los desechos plásticos generados por la impresión 3D. Estas placas pueden ser utilizadas en diversos proyectos de diseño y fabricación, cerrando el ciclo de vida del plástico de una manera eficiente y sostenible. El proceso se basa en la clasificación, triturado, fundición, moldeo y secado de los plásticos reciclados. 

## Materiales y componentes

● Materiales: Residuos plásticos de impresión 3D (PLA y PLA + principalmente)</br>

● Herramientas: Trituradora de plásticos y máquina de sublimación.

● Componentes Electrónicos: Sensores de temperatura y humedad, Placa Arduino UNO, y controladores electrónicos</br>

## Modelo de funcionamiento

El proceso esencialmente consta de cinco pasos: selección de plásticos, monitoreo de condiciones, triturar los plásticos, fundición y moldeo, y, finalmente, desmoldar y enfriar.

### Selección de plásticos

El primer paso es seleccionar cuidadosamente los desechos de impresión 3D con dimensiones y densidad adecuadas para la trituradora, asegurando su funcionamiento óptimo. Los fragmentos deben medir, como máximo, 2 a 3 centímetros cúbicos, lo que permite procesarlos eficientemente sin sobrecargar la máquina. Se utilizarán principalmente desechos de PLA y PLA+, ya que estos materiales no solo son los más utilizados en impresión 3D, sino que también presentan una temperatura de fusión baja, facilitando su fundición y posterior transformación en placas funcionales. Además, el PLA está diseñado para enfriarse rápidamente, lo que lo hace ideal para procesos como el corte láser, donde mantiene su estabilidad. En contraste, materiales como el ABS reciclado tienden a fundirse nuevamente durante el corte láser debido a sus propiedades térmicas, limitando su aplicación en este tipo de procesos.

El PLA (ácido poliláctico) es un termoplástico biodegradable derivado de recursos renovables, conocido por su facilidad de uso en impresión 3D y su baja temperatura de fusión, alrededor de 173 °C. Esta característica permite que el PLA se funda y solidifique rápidamente, facilitando su procesamiento en técnicas como el corte láser. Por otro lado, el ABS (acrilonitrilo butadieno estireno) tiene una temperatura de fusión más alta y una mayor resistencia al calor, lo que puede provocar que, durante el corte láser, el material se reblandezca o funda nuevamente, afectando la precisión y calidad del corte. Por lo tanto, el uso de PLA para la fabricación de placas destinadas al corte láser es más adecuado debido a su comportamiento térmico favorable en estos procesos.

### Monitoreo de condiciones

Se emplea un sistema basado en Arduino y sensores específicos para medir y controlar las condiciones de temperatura y humedad del material reciclado antes de su fundición. Este enfoque permite establecer parámetros precisos que garantizan la consistencia y calidad del proceso, aportando fiabilidad técnica y trazabilidad. Al monitorear y ajustar estas variables en tiempo real, se asegura que la metodología de fabricación de las placas sea replicable bajo circunstancias definidas, optimizando así la uniformidad del producto final y facilitando su integración en procesos estandarizados.

### Sistema de Triturado

A continuación, los plásticos seleccionados se introducen en la tolva de la máquina trituradora, basada en los diseños desarrollados por Precious Plastic, que proporciona planos y guías detalladas para su construcción. Esta trituradora está equipada con un motorreductor que acciona un eje con múltiples cuchillas metálicas diseñadas para triturar eficazmente los plásticos. Dependiendo del tamaño y densidad de los desechos, puede ser necesario repetir el proceso de trituración para obtener un picadillo más fino y homogéneo.

Este proceso de refinamiento es esencial para garantizar que el material esté en condiciones óptimas para las etapas posteriores de fundición y moldeado, asegurando la calidad y consistencia del producto final. El uso del diseño de Precious Plastic no solo garantiza un rendimiento comprobado, sino que también promueve la filosofía de código abierto y sostenibilidad en el reciclaje de plásticos.

### Máquina de Fundición y Moldeo

Se coloca una lámina de teflón reforzada con fibra de vidrio en la base de la máquina de sublimación, seguida de la colocación de un marco metálico centrado sobre ella. El interior del marco se rellena con el picadillo triturado previamente procesado. Luego, se coloca una segunda lámina de teflón con fibra de vidrio sobre el material, y todo el conjunto se prensa utilizando la estructura superior de la máquina. Tras el tiempo requerido para la sublimación, se abre la máquina y se voltea el marco para repetir el prensado, asegurando un acabado uniforme en ambos lados del material.

El tiempo de sublimación varía según factores como la cantidad de material, las dimensiones del marco y la temperatura empleada. En este proceso, se utiliza un marco de 340x220x15 mm, trabajando a una temperatura de 170 °C, con un tiempo estimado de prensado de entre 5 y 7 minutos por cada lado. Este método asegura que el material se funda de manera uniforme, adopte la forma deseada y garantice un producto final con alta resistencia y calidad.

Aunque la máquina de sublimación no es una herramienta especializada para el reciclaje de plásticos, su disponibilidad, adaptabilidad y bajo costo la convierten en una opción viable para proyectos locales que buscan implementar soluciones sostenibles en el manejo de desechos plásticos de impresión 3D.

### Desmoldeo y enfriado

Se retira el conjunto completo de la máquina de sublimación y se coloca en un lugar adecuado para que el material se enfríe a temperatura ambiente. Una vez que el plástico ha alcanzado una temperatura segura, se utiliza una trincheta para repasar cuidadosamente los bordes del marco, lo que facilita la extracción de la plancha sin comprometer su integridad. Este procedimiento es crucial para prevenir daños en el producto final y garantizar que conserve la forma y calidad deseadas, manteniendo así la uniformidad y funcionalidad de la placa reciclada.

## Procesos utilizados

● Fabricación Aditiva (Impresión 3D): Para la creación de componentes del dispositivo, como estructuras y soportes.</br>

● Fabricación Sustractiva (Corte Láser y CNC): Para la creación de piezas metálicas y el corte de las placas recicladas.</br>

● Termoformado y Moldeo: Los plásticos reciclados son fundidos y moldeados en una máquina sublimadora, produciendo placas que se estabilizan por enfriamiento.</br>

## Propuesta de valor

EcoPlaca 3D ofrece una solución innovadora y sostenible para transformar los desechos plásticos generados por la impresión 3D en placas funcionales reutilizables. Este proyecto promueve la economía circular mediante el reciclaje de plásticos, reduciendo el impacto ambiental y proporcionando un material útil para diseñadores, makers y emprendedores.

Los valores clave de la propuesta incluyen:

● Reciclaje funcional: Placas reutilizables de alta calidad a partir de desechos plásticos.

● Diseño único: Acabado "tie-dye" que resalta el reciclaje.

● Sostenibilidad: Contribución activa a la economía circular.

● Accesibilidad: Solución práctica y económica, fácil de replicar.

● Innovación responsable: Integración de tecnologías como el corte láser y termoformado.

En conjunto, EcoPlaca 3D proporciona una respuesta práctica al desperdicio plástico y abre nuevas oportunidades en el diseño y fabricación sostenible.

## Resultados y discusión

En el transcurso del proyecto, algunas problemáticas fueron correctamente abordadas, así como otras no. Estas son algunas de ellas:

### Preguntas Respondidas:

● ¿Es posible reciclar desechos plásticos de impresión 3D para producir materiales reutilizables de manera efectiva?</br>

● ¿Qué condiciones deben ser monitoreadas para garantizar la calidad del material reciclado?</br>

### Lo que Funcionó:

● El proceso de reciclaje generó placas funcionales de alta calidad.</br>

● El sistema de monitoreo basado en Arduino permitió optimizar las condiciones de producción.</br>

### Lo que No Funcionó:

● La variabilidad en la calidad de los desechos plásticos afectó la consistencia del material reciclado.</br>

● El sistema de fundición necesitó ajustes para mejorar la uniformidad del grosor de las placas.</br>

## Conclusiones

El proyecto "EcoPlaca 3D" demostró que es posible reciclar desechos plásticos de impresión 3D y transformarlos en un material funcional y reutilizable. El sistema es accesible, económico y aplicable a una variedad de usuarios, desde diseñadores hasta emprendedores. Sin embargo, se identificaron áreas de mejora en el control de la calidad del material reciclado y en la optimización de los procesos de fabricación.

## Glosario

● Economía Circular: Modelo de producción y consumo que promueve la reutilización, el reciclaje y la reducción de residuos.</br>

● Fabricación Aditiva: Proceso de creación de objetos mediante la adición de capas sucesivas de material.</br>

● Termoformado: Proceso de modelado de plásticos a través del calor para darles forma.</br>

● Precious Plastics: Iniciativa global de código abierto que promueve el reciclaje de plásticos a pequeña escala.</br>

## Bibliografía

● Kreiger, M. (2019). Precious Plastics: Recycling Plastics with Open-Source Technology. [PDF]. Precious Plastics. Recuperado de: https://preciousplastics.com

● Bocken, N. M. P., de Pauw, I., Bakker, C., & Van der Grinten, B. (2016). Product design and business model strategies for a circular economy. Journal of Industrial Ecology, 20(3), 383–397. https://doi.org/10.1111/jiec.12259

● Moreno, M., Chiaroni, D., & del Río, P. (2016). Towards a Circular Economy: A SWOT Analysis of the Circular Economy at the Micro-Enterprise Level. Journal of Cleaner Production, 135, 983–994. https://doi.org/10.1016/j.jclepro.2016.07.033

● Tuck, C., & Hague, R. (2014). The Role of Additive Manufacturing in the Circular Economy. Additive Manufacturing & 3D Printing, 1(1), 16–23. https://doi.org/10.1080/25734988.2014.1091807

● ISO 14021:2016. Environmental labels and declarations — Self-declared environmental claims (Type II environmental labeling). International Organization for Standardization.

● Schmidt-Bleek, F. (1994). Wieviel Umwelt braucht der Mensch? MIPS – das Maß für ökologisches Wirtschaften. Birkhäuser Verlag.

● Thompson, R. C., Moore, C. J., Vom Saal, F. S., & Swan, S. H. (2009). Plastics, the environment and human health: current consensus and future trends. Philosophical Transactions of the Royal Society B: Biological Sciences, 364(1526), 2153–2166. https://doi.org/10.1098/rstb.2009.0053

● Kunz, N., & Morell, A. (2018). Recycling Plastics: Challenges and Opportunities for Sustainable Manufacturing. Journal of Cleaner Production, 172, 2446–2457. https://doi.org/10.1016/j.jclepro.2017.10.179

● Bakker, C., & Jiang, Y. (2014). Designing the Circular Economy: From Waste to Resources. Technological Innovation for Sustainability, 1(2), 111–123. https://doi.org/10.1016/j.techsoc.2014.01.002

● Meadows, D. H., Randers, J., & Meadows, D. L. (2004). Limits to Growth: The 30-Year Update. Chelsea Green Publishing.

<p style="font-size: 20px"; class="rainbow">¡Muchas gracias por su atención!</p>

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