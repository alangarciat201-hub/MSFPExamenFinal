# MSFPExamenFinal
Sistema Circulatorio 
## Información de la estudiante

Alan Omar Garcia Toledo, 20210787, alan.garciat201@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1\. Desarrollar el modelo matemático del sistema circulatorio.
2. Obtener la función de transferencia del sistema.
3. Analizar la respuesta dinámica del sistema ante una señal de entrada.
4. Simular el comportamiento del sistema en lazo cerrado.
5. Diseñar un controlador PID para mejorar la respuesta del sistema.
6. Comparar el comportamiento entre el individuo sano (control) y el caso patológico.

## Descripción detallada del sistema

El sistema circulatorio, centrado en la dinámica cardiaca y vascular, puede representarse mediante una analogía eléctrica de tipo RLC. En este modelo, la resistencia vascular se asocia a elementos resistivos (R), la inercia de la masa sanguínea a inductores (L) y la elasticidad o capacitancia arterial a capacitores (C).Dentro de este enfoque, la señal de entrada corresponde a un impulso unitario generado por el nodo sinoauricular, el cual actúa como el marcapasos natural del corazón iniciando la excitación del sistema. Las diferencias entre un individuo sano y un paciente con alteraciones cardiovasculares se manifiestan en variaciones de los parámetros del circuito: una disminución en la resistencia de respuesta (R2) y un aumento significativo en la capacitancia (C). Estas alteraciones modifican la respuesta dinámica del sistema de segundo orden, provocando que el caso patológico exhiba una respuesta considerablemente más lenta y con una menor capacidad de recuperación de energía en comparación con el caso de control.El sistema exhibe un comportamiento dinámico donde la salida, identificada como el voltaje en el nodo principal (Vs(t)), representa la energía almacenada y liberada en el compartimento cardiaco. La incorporación de un controlador PID resulta fundamental para compensar estas deficiencias fisiológicas, ajustando la señal de excitación para que el flujo y la presión sanguínea del paciente alcancen los niveles de desempeño de un sistema cardiovascular saludable.

## Lista de archivos incluidos en el repositorio

1\. .Modelo de Simulink \[.slx]
2\. Imágenes de las graficas control y caso \[.pdf].
3. Evidencia del análisis matemático.



## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis, Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 2, Page 26.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.

\[4] T. Kind, T. J. Faes, J. W. Lankhaar, A. Vonk-Noordegraaf & M. Verhaegen, "Estimation of three- and four-element Windkessel parameters using subspace model identification", IEEE Transactions on Biomedical Engineering, vol. 57, no. 7, pp. 1531–1538, Jul 2010. https://doi.org/10.1109/TBME.2010.2041351
