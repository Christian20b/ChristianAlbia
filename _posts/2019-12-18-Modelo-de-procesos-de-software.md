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
<h2>Ventajas:</h2>
   <p>•  El modelo en espiral puede adaptarse y aplicarse a lo largo de la vida del software de computadora. </p>
   <p>•  Como el software evoluciona a medida que progresa el proceso, el desarrollador y el cliente comprenden y reaccionan mejor ante riesgos en cada uno de los nivele evolutivos. </p>
   <p>•  El modelo en espiral permite a quien lo desarrolla aplicar el enfoque de construcción de prototipos en cualquier etapa de evolución del producto.   </p>
   <p>•  El modelo en espiral demanda una consideración directa de los riesgos técnicos en todas las etapas del proyecto y si se aplica adecuadamente debe reducir los riesgos antes de que se conviertan en problemas. </p>
   <p>•  En la utilización de grandes sistemas a doblado la productividad.   </p>




## Desarrollo Rápido de Aplicaciones (DRA)

<h2>Definición:</h2>
   <p>•  Es un modelo de proceso del ciclo de vida clásico que enfatiza un ciclo de vida de desarrollo extremadamente corto.   </p>
    <p>•  El modelo DRA es una adaptación a alta velocidad del ciclo de vida clásico en el que se logra el desarrollo rápido utilizando un enfoque de construcción basado en componentes. Si se comprenden bien los requisitos y se limita el ámbito del proyecto, el proceso DRA permite al equipo de desarrollo crear un sistema completamente funcional dentro de períodos cortos de tiempo. </p>
    <p>•  Cuando se utiliza principalmente para aplicaciones de sistemas de información, el enfoque DRA comprende las siguientes fases:</p>
    <p>--Modelado de gestión: El flujo de información entre las funciones de gestión se modela de forma que responda a las siguientes preguntas: ¿Qué información conduce el proceso de gestión? ¿Qué información se genera? ¿Quién la genera? ¿A dónde va la información? ¿Quién la procesa?</p>
    <p>--Modelado de datos: El flujo de información definido como parte de la fase de modelado de gestión refina como un conjunto de objetos de datos necesarios para apoyar la empresa. Se definen las características de cada uno de los objetos y relaciones entre estos objetos.</p>
    <p>--Modelado de procesos: Los objetos de datos definidos en la fase de modelado de datos quedan transformados para lograr el flujo de información necesario para implementar una función de gestión. Las descripciones se crean para añadir, modificar, suprimir, o recuperar un objeto de datos.</p>
    <p>--Generación de aplicaciones: El DRA asume la utilización de técnicas de cuarta generación. En lugar de crear software con lenguajes de programación de tercera generación, el proceso DRA trabaja para volver a utilizar componentes de programas ya existentes (cuando es posible) o a crear componentes reutilizables (cuando sea necesario). En todos los casos se utilizan herramientas automáticas para facilitar la construcción del software.</p>
    <p>--Prueba y entrega: Como el proceso DRA enfatiza la reutilización, ya se han comprobado muchos de los componentes de los programas. Esto reduce tiempo de pruebas. Sin embargo, se deben probar todos los componentes nuevos y se deben ejercitar todas las interfaces a fondo.</p>
    <p>--Prueba y entrega: Como el proceso DRA enfatiza la reutilización, ya se han comprobado muchos de los componentes de los programas. Esto reduce tiempo de pruebas. Sin embargo, se deben probar todos los componentes nuevos y se deben ejercitar todas las interfaces a fondo.</p>
<h2>Limitaciones:</h2>
    <p>Las limitaciones de tiempo impuestas en un proyecto DRA demandan ámbito en escalas. </p>
    <p>•  Si una aplicación de gestión puede modularse de forma que permita completarse cada una de las funciones principales en menos de tres meses, es el candidato del DRA. </p>
    <p>•  Cada una de las funciones puede ser afrontada por un equipo DRA diferente y ser integradas en un solo conjunto.</p>
<h2>Problemas:</h2>
    <p>•  Para proyectos grandes aunque por escalas, el DRA requiere recursos humanos suficientes como para crear el número correcto de equipos DRA.</p>
    <p>•  DRA requiere clientes y desarrolladores comprometidos en las rápidas actividades necesarias para completar un sistema en un marco de tiempo abreviado. Si no hay compromiso, por ninguna de las partes constituyentes, los proyectos DRA fracasarán.</p>
    <p>•  No todos los tipos de aplicaciones son apropiados para DRA. </p>
    <p>•  Si un sistema no puede modularizarse adecuadamente, la construcción de los componentes necesarios para DRA será problemático. </p>
    <p>•  Si está en juego el alto rendimiento, y se va a conseguir el rendimiento convirtiendo interfaces en componentes de sistemas, el modelo DRA puede que no funcione. </p>
    <p>•  DRA no es adecuado cuando los riesgos técnicos son altos. Esto ocurre cuando una nueva aplicación hace uso de tecnologías nuevas, o cuando el nuevo software requiere un alto grado de interoperatividad con programas de computadoras ya existentes. </p>
    <p>•  DRA enfatiza el desarrollo de componentes de programas reutilizables. </p>


## Orientados a la Reutilización
  
<h2>Definición:</h2>
   <p>•  Esta aproximación se basa en la existencia de un número significativo de elementos reutilizables. El proceso de desarrollo, se centra en la integración de estos elementos en un sistema, en lugar de desarrollarlo desde cero.</p>
   <p>•  Incorpora muchas características del modelo en espiral. Es evolutivo por naturaleza. </p>
   <p>•  El proceso tiende a estructurarse en dos subprocesos distintos y separados: </p>
   <p>--El desarrollo para reutilización: construcción de elementos reutilizables dentro de un dominio concreto.</p>
   <p>El desarrollo con reutilización: construcción de aplicaciones utilizando elementos reutilizables.</p>
   <p>•  Etapas del proceso </p>
   <p>--Análisis de los componentes; </p>
   <p>--Requisitos de modificación; </p>
   <p>--Configuración del sistema con la reutilización; </p>
   <p>--Desarrollo e integración. </p>
   <p>•  La reutilización es ahora el enfoque estándar para la construcción de muchos tipos de sistemas de negocio.</p>
<h3>Orientados a Objetos</h3>

   <h2>Definición:</h2>
   <p>•  El modelo orientado a objetos utiliza el paradigma de la orientación a objetos para el desarrollo de software.</p>
   <p>•  Este enfoque realiza la construcción de modelos de un sistema por medio de la identificación y la especificación de un conjunto de objetos relacionados, que colaboran entre si de acuerdo a los requerimientos establecidos para el sistema de objetos.</p>
   <p>•  La definición del modelado orientado a objetos puede claramente dividir el enfoque en tres dimensiones: </p>
   <p>--La dimensión estructural. </p>
   <p>--La dimensión dinámica. </p>
   <p>--La dimisión funcional. </p>
   <p>•  Este tipo de modelado implica la realización de las siguientes actividades: </p>
   <p>1.  Identificar las clases, modelos y objetos. (objetos y atributos).</p>
   <p>2.  Asociar estáticamente los objetos. (relaciones dependientes del dominio del problema). </p>
   <p>3.  Especificación del comportamiento de los objetos. (Definir como se comportaran los objetos). </p>
   <p>4.  Definir la jerarquía de herencia de las clases. (Definir la jerarquía de clases, para que el sistema quede lo más abstracto posible).</p>
<h2>Características:</h2>
   <p>•  EL modelado Orientado a Objetos está basado en el paradigma orientado a objetos. </p>
   <p>•  Trata el almacenamiento de objetos (persistencia de los objetos). </p>
   <p>•  Define un lenguaje para le definición y manipulación de objetos. </p>
   <p>•  Incluye mecanismos para optimizar el acceso (Indexación y Clustering), el control de la concurrencia, seguridad y gestión de usuarios, facilidad de consulta y recuperación ante fallos. </p>
   <p>•  Debido a que es un esquema orientado a objetos incluye: Encapsulamiento, herencia, polimorfismo, etc.</p>






