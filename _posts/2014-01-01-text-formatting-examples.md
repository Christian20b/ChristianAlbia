---
layout: post
title: "Modelo de procesos de software"
author: "ChristianAlbia"
categories: journal
tags: [documentation,sample]
image: cards.jpg
---

## Modelo de procesos de Software

<h2>El modelo de cascada</h2>
  <p>Modelo de Plan-impulsado. Fases separadas y distintas de especificación y desarrollo.</p>
<h2>El desarrollo incremental</h2>  
   <p>Especificación, desarrollo y validación se intercalan. Puede ser el plan impulsado o ágil.</p>
   <p></p>
   <p>Ingeniería de software orientado a reutilización</p>
   <p>-El sistema se ensambla a partir de componentes existentes. Puede ser el plan impulsado o ágil. </p>
   <p>En la práctica, la mayoría de los grandes sistemas se desarrollan mediante un proceso que incorpora elementos de todos estos modelos.</p> 

## Modelo Cascada

   <p>Las fases están identificadas por separado:</p>
   <p>•  El análisis  y definición de requerimientos</p>
   <p>•  Diseño del sistema y software.</p>
   <p>•  Pruebas de implementación de unidades</p>
   <p>•  Integración y pruebas del sistema </p>
   <p>•  Operación y mantenimiento </p>
   <p>El principal inconveniente del modelo de la cascada es la dificultad de acomodar el cambio después de que está en marcha el proceso. En principio, una fase tiene que ser completada antes de pasar a la siguiente fase.</p>
<h2>Problemas del Modelo de Cascada:</h2>
   <p>•  Inflexible división del proyecto en fases distintas hace que sea difícil responder a las necesidades cambiantes de los clientes. </p>
   <p>•  Por lo tanto, este modelo sólo es apropiado cuando los requisitos son bien entendidos y los cambios serán bastante limitados durante el proceso de diseño.</p>
   <p>•  Pocos sistemas tienen requisitos estables.</p>
   <p>•  El modelo de cascada se utiliza sobre todo para los grandes proyectos de ingeniería de sistemas en que un sistema se desarrolla en varios lugares</p>



## Desarrollo Incremental

<h2>Beneficios</h2>
   <p>•  El costo de atender las necesidades cambiantes de los clientes se reduce. </p>
   <p>--La cantidad de análisis y la documentación que tiene que ser hecho de nuevo es mucho menor que la que se requiere con el modelo de cascada. </p>
    <p>•  Es más fácil obtener retroalimentación de los clientes en el trabajo de desarrollo que se ha hecho.</p>
    <p>--Los clientes pueden hacer comentarios sobre las manifestaciones del software y ver cuánto se ha implementado. </p>
    <p>•  Más rápida entrega y despliegue de software de utilidad para el cliente es posible. </p>
    <p>--Los clientes pueden usar y obtener valor a partir del software anterior que es posible con un proceso de cascada.</p>
<h2>Problemas:</h2>
    <p>•  El proceso no es visible.</p>
    <p>--Los gerentes necesitan entregas regulares para medir el progreso. Si se desarrollan rápidamente los sistemas, no es rentable para producir documentos que reflejen todas las versiones del sistema.</p>
    <p>•  Estructura del sistema tiende a degradarse a medida que se añaden nuevos incrementos. </p>
    <p>--A menos tiempo y dinero que se gasta en la refactorización para mejorar el software, cambio regular tiende a corromper su estructura. La incorporación de nuevos cambios de software se vuelve cada vez más difícil y costoso. </p>



## Espiral

<h3>Definición:</h3>
   <p>•  Es un modelo de ciclo de vida desarrollado por Barry Boehm en 1988. </p>
   <p>•  Las actividades de este modelo son una espiral, cada bucle es una actividad. </p>
   <p>•  Las actividades no están fijadas a prioridad, sino que las siguientes se eligen en función del análisis de riesgo, comenzando por el bucle interior.</p>
   <p>•  En este modelo, el esfuerzo de desarrollo es iterativo. Tan pronto como uno completa un esfuerzo de desarrollo, otro comienza. Además, en cada desarrollo ejecutado, puedes seguir estos cuatros pasos.</p>
   <p>1.  Determinar qué quieres lograr. </p>
   <p>2.  Determinar las rutas alternativas que puedes tomar para lograr estas metas. Por cada una, analizar los riesgos y resultados finales, y seleccionar la mejor. </p>
   <p>3.  Seguir la alternativa seleccionada en el paso 2.</p>
   <p>4.  Establecer qué tienes terminado. </p>
<h2>Principios Básicos:</h2>
   <p>•  Decidir qué problema se quiere resolver antes de viajar a resolverlo. </p>
   <p>•  Examinar tus múltiples alternativas de acción y elegir una de las más convenientes. </p>
   <p>•  Evaluar qué tienes hecho y qué tienes que haber aprendido después de hacer algo. </p>
   <p>•  No ser tan ingenuo para pensar que el sistema que estás construyendo será "EL" sistema que el cliente necesita, y </p>
   <p>•  Conocer (comprender) los niveles de riesgo, que tendrás que tolerar.  </p>
   <p>El Modelo Espiral mejora el Modelo de Cascada enfatizando la naturaleza iterativa del proceso de diseño. Eso introduce un ciclo de prototipo iterativo. En cada iteración, las nuevas expresiones que son obtenidas transformando otras dadas son examinadas para ver si representan progresos hacia el objetivo.  </p>
<h2>Actividades principales:</h2>
   <p>PRIMER PASO. Identificación de:</p>
   <p>•  Los objetivos de la parte del producto que está siendo elaborada (rendimientos, funcionalidad, adaptación al cambio, etc.). </p>
   <p>•  Las alternativas principales de la implementación de esta porción del producto (usar el diseño A, usar el diseño B, reutilizar el módulo X de la aplicación Z, comprar a un proveedor externo, etc.). </p>
   <p>•  Las restricciones impuestas para cada alternativa (costes, planificaciones, interfaces, etc.). </p>
   <p>SEGUNDO PASO</p>
   <p>•  Evaluar las diferentes alternativas que se plantean teniendo en cuenta los objetivos a conseguir y las restricciones impuestas. Frecuentemente, este paso identifica las áreas de incertidumbre del proyecto con sus correspondientes riesgos.</p>
   <p>•  Si existen riesgos, lo siguiente es la formulación de una estrategia efectiva en coste (utilizando prototipos, simulación, bancos de prueba, cuestionario para los usuarios, modelización analítica o combinaciones de éstas y otras técnicas de resolución de riesgos) para resolver dichos riesgos.</p>
   <p>TERCER PASO. Consiste en desarrollar, verificar y validar (probar):</p>
   <p>•  Tareas de la actividad propia y de prueba.</p>
   <p>•  Análisis de alternativas e identificación resolución de riesgos. </p>
   <p>•  Dependiendo del resultado de la evaluación de los riesgos, se elige un modelo para el desarrollo, el que puede ser cualquiera de los otros existentes, como formal, evolutivo, cascada, etc. </p>
   <p>CUARTO PASO. Revisar todo lo hecho, evaluándolo, y con ello decidir si se continúa con las fases siguientes y planificar la próxima actividad. </p>
<h2>Características:</h2>
   <p>•  En cada giro se construye un nuevo modelo del sistema completo. </p>
   <p>•  Este modelo puede combinarse con otros modelos de proceso de desarrollo (cascada, evolutivo). </p>
   <p>•  Mejor modelo para el desarrollo de grandes sistemas. </p>
   <p>•  El análisis de riesgo requiere la participación de personal  altamente calificado.  </p>
<h2>Ventajas:</2h>
   <p>•  El modelo en espiral puede adaptarse y aplicarse a lo largo de la vida del software de computadora. </p>
   <p>•  Como el software evoluciona a medida que progresa el proceso, el desarrollador y el cliente comprenden y reaccionan mejor ante riesgos en cada uno de los nivele evolutivos. </p>
   <p>•  El modelo en espiral permite a quien lo desarrolla aplicar el enfoque de construcción de prototipos en cualquier etapa de evolución del producto.   </p>
   <p>•  El modelo en espiral demanda una consideración directa de los riesgos técnicos en todas las etapas del proyecto y si se aplica adecuadamente debe reducir los riesgos antes de que se conviertan en problemas. </p>
   <p>•  En la utilización de grandes sistemas a doblado la productividad.   </p>



## Links


## Blockquotes



## Code and Syntax Highlighting



## Images





## Unordered and Numbered Lists




## MathJax Example


## Tables


## Embedding


## Inline HTML elements



## Horizontal Rule



## Useful Resources


