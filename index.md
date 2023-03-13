---
layout: default
---

# Titulo del artículo
> Trabajos revisados<!-- para desarrollar el primer artículo escrito durante mis estudios de doctorado-->.

---

### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/3.pdf">Omics applied to livestock genetics</a>

<p style="background-color: white; border: 1px solid yellow; color: black; border-radius: 15px 15px 15px 15px; font-size: 12px; padding: 20px; margin: 5px;" align="justify"><b>

Los estudios ómicos han permitido el desarrollo de importantes herramientas en el sector ganadero al revolucionar la traducción del genoma a la investigación fenómica.

<br>
<br>

A partir de los conjuntos de datos ómicos se han desarrollado herramientas para la producción animal y la sostenibilidad. Así mismo, los enfoques ómicos pueden aplicarse de forma integral (u holística) a la mejora de la cría animal, permitiendo también una mejor comprensión del trasfondo genético de la variabilidad fenotípica.

<br>
<br>

La transcriptómica y la genómica en bovinos y cerdos son los enfoques más utilizados (Figura <a href="https://leo4luffy.github.io/Art_p1/Articulos/Imagen/Fig1_Art3.png">aquí</a>).

<br>
<br>

La generación y el intercambio de conjuntos de datos multi-ómicos será fundamental para continuar avanzando en investigaciones en este campo. En este sentido, la integración de la fenómica con otras tecnologías ómicas ayudarán a aumentar las tasas de progresos genéticos en los programas de mejoramiento sostenibles.

<br>
<br>

<font color="gray" size="0.4"><u>NOTA</u>: En este artículo citan algunos estudios donde se integran distintos enfoques ómicos. Por ejemplo, un estudio donde se integró datos proteómicos y transcriptómicos a partir de un análisis factorial y red Bayesiana.</font>

</b></p>

---

### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/6.pdf">Machine and deep learning meet genome-scale metabolic modeling</a>

<p style="background-color: white; border: 1px solid yellow; color: black; border-radius: 15px 15px 15px 15px; font-size: 12px; padding: 20px; margin: 5px;" align="justify"><b>

Varios niveles del conocimiento han sido asociados con tecnologías ómicas emergentes. En años recientes, los más extendidos incluyen secuencias de ADN (<u>genómica</u>), secuencias de ARN (<u>transcriptómica</u>), metilación del ADN y modificaciones de histonas (<u>epigenómica</u>) y espectrometría de masas de proteínas o metabolitos (<u>proteómica</u> y <u>metabolómica</u>). Los datos ómicos brindan acceso directo y conveniente a la variabilidad genética y actividad celular.

<br>
<br>

Un problema fundamental en una biología basada en ómicas es la dificultad en extraer conocimientos de conjuntos de datos grandes y complejos. Esta tarea se puede abordar a través de algoritmos de machine (deep) learning, muchos de los cuales pueden ser adaptados a configuraciones específicas y tipos ómicos.

<br>
<br>

Un solo tipo de datos suele ofrecer una visión parcial de la complejidad biológica y puede limitar nuestra compresión de la misma, mientras que los <u>métodos de integración de datos</u> pueden facilitar el análisis combinado de múltiples conjuntos de datos ómicos (que pueden ser heterogéneos), y así representar más de cerca las relaciones genotipo-fenotipo.

<br>
<br>

Los métodos metadimensionales son los enfoques de integración de datos a gran escala más exitosos. Estos son:

<br>
<br>

1. <u>Integración basada en concatenación</u>. Varios tipos de datos se fusionan mediante la concatenación de matrices de datos. Luego, un algoritmo de aprendizaje puede aplicarse a esta matriz combinada. Este enfoque tiene como ventaja que facilita que a cualquier matriz combinada se le pueda aplicar métodos estadísticos con relativa facilidad. No obstante, combinar múltiples matrices puede ser desafiante debido a las diferencias de escala (que puede solucionarse a partir de la normalización) o el sesgo y la varianza inherente de cada tipo de dato (que aún con normalización puede afectar el análisis) (Figura <a href="https://leo4luffy.github.io/Art_p1/Articulos/Imagen/Fig1_Art6.png">aquí</a>).

<br>
<br>

2. <u>Integración basada en transformación</u>. Cada conjunto de datos se convierte a una forma intermedia. Luego la integración de los datos se realiza al nivel de los datos transformados, lo que da como resultado un gráfico integrador o matriz kernel, que puede usarse en la fase de aprendizaje. Este enfoque tiene la ventaja de preservar las propiedades originales de los datos y la capacidad de combinar prácticamente cualquier estructura de datos aplicando las transformaciones apropiadas. Su principal desventaja es la dificultad de detectar interacciones entre diferentes fuentes, la perdida de correlaciones ómicas cruzadas, y todo ello resulta en una difícil interpretación (Figura <a href="https://leo4luffy.github.io/Art_p1/Articulos/Imagen/Fig2_Art6.png">aquí</a>).

<br>
<br>

3. <u>Integración basada en modelos</u>. Genera modelos de machine learning de cada conjunto de datos y, posteriormente, los combina para producir un modelo final basado en datos. Este enfoque puede tener una flexibilidad mayor comparado con la integración basada en transformación, sin embargo, al igual que esta última, puede pasar por alto la interacción entre diferentes tipos de datos, además de que es sensible a sobre ajustes, por lo que se recomienda su uso cuando los conjuntos de datos son extremadamente hereogéneos (Figura <a href="https://leo4luffy.github.io/Art_p1/Articulos/Imagen/Fig3_Art6.png">aquí</a>).

<br>
<br>

<font color="gray" size="0.4"><u>NOTA</u>: .</font>

</b></p>

---

### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/7.pdf">Rise of deep learning for genomic, proteomic, and metabolomic data integration in precision medicine</a>

<p style="background-color: white; border: 1px solid yellow; color: black; border-radius: 15px 15px 15px 15px; font-size: 12px; padding: 20px; margin: 5px;" align="justify"><b>

El crecimiento continuo de las investigaciones ómicas ha requerido mejoras en instrumentación, algoritmos bioinformáticos, métodos de ciencia de datos y acceso a recursos computacionales. El deep learning es un subdominio del machine learning que ha emergido como un enfoque poderoso, y que puede codificar y modelar muchas formas de datos complejos, tanto en entornos supervisados como no supervisados.

<br>
<br>

En particular, la medicina de precisión (<font color="gray" size="0.4">que podría ser el caso también de la ganadería de precisión</font>) presenta una oportunidad única para que los datos ómicos se integren con muchos otros tipos, incluidos los sensores de internet de las cosas, que si se realizan, podrían mejorar en gran medida la calidad de la atención médica.

<br>
<br>

La flexibilidad de las arquitecturas del deep learning permite la capacidad de generar inferencias significativas, en caso de que se tengan suficientes datos de entrenamiento. <u>Esta flexibilidad podría ser aplicado al análisis ómico y a su integración</u>.

<br>
<br>

La integración de datos multiómicos se requiere para modelar de forma robusta sistemas biológicos complejos. Además, una sola medida ómica podría no revelar mecanismos dinámicos o dependientes del tiempo. Este tipo de desafíos requiere de combinaciones bien pensadas de medidas ómicas para caracterizar lo suficiente las firmas bioquímicas que reflejan el fenotipo en el momento mismo en que la muestra es tomada.

<br>
<br>

La integración ómica es un enfoque que vincula conjuntos de datos a través de dominios bioquímicos ortogonales, magnificando con esto señales biologicamente relevantes (Figura <a href="https://leo4luffy.github.io/Art_p1/Articulos/Imagen/Fig1_Art7.png">aquí</a>).

<br>
<br>

Los modelos deep learning pasan la señal de entrada a través de una serie de capas computacionales, lo que crea una dependencia direccional de la codificación de la señal entre las capas anteriores y posteriores, lo que refleja el acto de identificar biomarcadores dentro una red de interacción de gen, proteína y metabolito enlazada. Estos modelos contienen un mínimo de tres capas: entrada, oculta y salida. Esto podría imitar la representación de las relaciones entre la transcripción de genes, la expresión de proteínas y las concentraciones de metabolitos, pero también puede extenderse a otras capas ómicas (Figura <a href="https://leo4luffy.github.io/Art_p1/Articulos/Imagen/Fig2_Art7.png">aquí</a>).

</b></p>

---

### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/5.pdf">Genomic evaluation methods to include intermediate correlated features such as high-throughput or omics phenotypes</a>

<p style="background-color: white; border: 1px solid yellow; color: black; border-radius: 15px 15px 15px 15px; font-size: 12px; padding: 20px; margin: 5px;" align="justify"><b>

Hoy en día existe una plétora de nuevas mediciones, parte de ellas cercanas a la biología animal (por ejemplo la transcripción de genes, el metagenoma, las imágenes, entre otros), hecho que a favorecido el desarrollo de nuevos enfoques para su análisis (machine learning en particular) y con ello, la posibilidad de predecir, en principio, casi cualquier cosa.

<br>
<br>

Si bien, a partir de estos nuevos enfoques es posible la predicción de rasgos, ¿cómo esto se puede convertir en algo útil para la selección? Esto debido a que un fenotipo per se no puede usarse directamente para seleccionar animales. Por lo tanto, además de poder predecir fenotipos a partir de ómicas, también se necesita de una teoría para utilizar las ómicas en la mejora genética.<!-- Además de ayudar a nuestra comprensión, una teoría, aunque no sea perfecta, prepara el escenario para planes a priori para usar ómicas en esquemas de selección a partir de unos pocos parámetros básicos.-->

$$
y_{i} =
$$

</b></p>

---

### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/4.pdf">Deep learning meets metabolomics: a methodological perspective</a>

---

<!--
### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/2.pdf">Do molecular markers inform about pleiotropy?</a>

<BR>

## ¿De qué trata?

---

### :scroll: <a href="https://leo4luffy.github.io/Art_p1/Articulos/1.pdf">Pleiotropy or linkage? Their relative contributions to the genetic correlation of quantitative traits and detection by multitrait GWA studies</a>

<BR>

## ¿De qué trata?
-->