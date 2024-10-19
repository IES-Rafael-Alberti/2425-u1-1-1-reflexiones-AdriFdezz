[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16536609&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** Practica 1.10 Preguntas sobre actividades
- **Módulo:** EDES
- **Unidad de Trabajo:** Unidad 1, Introduccion al desarrollo de software
- **Fecha de Creación:** 7/10/2024
- **Fecha de Entrega:** 20/10/2024
- **Alumno(s):** 
  - **Nombre y Apellidos:** Adrian Fernandez Garrido
  - **Correo electrónico:** afergar613@g.educaand.es
  - **Iniciales del Alumno/Grupo:** AFG

## Descripción de la Actividad

- Preguntas sobre practicas realizadas y el temario de la unidad 1 de Entornos en las preguntas veremos un poco de todo desde herramientas para el desarrollo de software, lenguajes de alto y bajo nivel, funcionamiento de la memoria y el procesador a la hora de ejecutar codigo, tipos de lenguaje que podemos encontrar, paradigmas entre otros temas.

- Algunas preguntas se respondian a partir de practicas realizadas en clase y otras se pueden responder a partir del temario explicado.

- Alguna pregunta se he tenido que realizar alguna busqueda en internet se vera reflejado en las referencias y fuentes.

## Conclusiones

- Estas preguntas me han servido para entender mejor diferentes temas en relacion al desarrollo de software.

- Tambien sirve como repaso para un futuro examen de esta unidad.

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

- [Temario Unidad 1 Revilofe](https://revilofe.github.io/section3/)

- [Apache Subversion](https://www.perforce.com/blog/vcs/what-svn)

- [Git vs Subversion](https://www.ionos.com/digitalguide/websites/web-development/svn-vs-git-comparing-version-control-systems/)

- [Chat GPT para aclaraciones y explicaciones](https://chatgpt.com/)

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.

# ACTIVIDADES

# 1. Relación software y hardware
## 1. Primera parte

**1.1.1. ¿Cómo se ejecuta el código en el procesador?**
   
   - Cuando se ejecuta un programa este se carga en la RAM y la CPU va recuperando 1 a 1 las intrucciones y las va ejecutando.
   - De forma mas exacta se ejecuta de la siguiente forma la unidad de control recibe la instruccion desde la RAM y esta la recibe la unidad aritmetologica esta realiza la operacion y la envia a los registros.

**1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?**
   
   - Se almacena temporalmente la informacion para que la CPU pueda acceder a las instrucciones de forma rapida.

**1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?**

   - En este caso el boton y el LED serian dispotivos de entrada y salida y estos necesitarian de un codigo el cual contenga unas instrucciones para el encendido y apagado del LED para que el procesador pueda seguirlas.

## 1.2. Segunda parte

**1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?**

- El procesador ejecutaria las intrucciones cargadas en la memoria de forma temporal y los perifericos serian los encargados de recibir y enviar datos que son procesados por el procesador.

**1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?**

- Los datos y intrucciones se cargan en la memoria y la unidad de control del procesador podra acceder a los datos pero hay que tener en cuenta que es volatil es decir cuando se apaga el equipo se borran.

**1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?**

- Las intrucciones del software es una parte muy importante ya que es la encargada de que todo funcione es decir que el procesador siga unas instrucciones en especifico para saber como mover datos entre la memoria y los perifericos tambien es necesario para que el hardware ejecute el programa de forma eficiente.

**1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?**

- Es una forma mucho mas facil de entender como es el funcionamiento de un ordenador real ya que nos muestra de una forma mucho mas facil como funciona un codigo sobre el procesador desde dentro con todas sus partes y como es el manejo de datos y instrucciones entre la memoria y los perifericos de entrada y salida.

# 2. Del código fuente al ejecutable

**2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?**

- El codigo fuente es aquel el cual el programador escribe en un lenguaje de programacion mientras que el codigo objeto se consigue despues de compilar un codigo fuente el cual contiene instrucciones en codigo maquina y no es completamente ejecutable y por ultimo el codigo ejecutable es la version final del programa el cual se puede ejecutar directamente ya que contiene las instrucciones en un formato que el procesador entiende.

**2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?**

- No pueden entenderlo porque los ordenadores solo pueden entender lenguaje maquina que son una serie de unos y ceros.

**2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?**

- Es un paso importante porque es el paso en el cual a partir de los archivos de codigo objeto se crea el archivo ejecutable mediante un enlazador ademas que el enlazador tiene bibliotecas para que el programa funcione de forma correcta.

**2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?**

- Pues que el codigo no funcionaria porque el ordenador seria incapaz de leer las instrucciones ya que solo lee codigo maquina es decir se necesita que el codigo fuente sea compilado en codigo objeto y este convertirse en codigo ejecutable para que el sistema operativo pueda ejecutarlo.

# 3. Generación de código intermedio

**3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?**

- Las principales diferencias es que el codigo intermedio no se puede ejecutar directamente se necesitaria una maquina virtual para que se vuelva ejecutable y es un codigo portable es decir se puede ejecutar en diferentes sistemas operativos solo con una maquina virtual mientras que el codigo ejecutable tradicional se puede ejecutar directamente y esta pensado para un sistema operativo en especifico.

**3.2. ¿Por qué es útil tener una máquina virtual?**

- Principalmente porque nos permite trabajar con un prograna independientemente de la plataforma en la que estamos trabajando y tambien nos aporta seguirdad ya que no se trabaja sobre el sistema principal y este no puede ser afectado.

**3.3. ¿Qué ventajas ofrece el código intermedio?**

- **Portabilidad:** El mismo programa puede correr en distintos sistemas operativos sin necesidad de recompilar el codigo solo se necesita una maquina virtual para cada plataforma.
- **Seguridad:** Las maquinas virtuales pueden agregar varias capas de seguridad extra para verificar y controlar el acceso al codigo intermedio al sistema operativo y al hardware.
- **Optimizacion en tiempo de ejecucion:** Algunas maquinas virtuales utilizan tecnicas como JIT (compilacion Just In Time) que convierte el codigo intermedio a maquina justo antes de que sea ejecutado para mejorar el rendimiento.

**3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?**

- Otros lenguajes que usa maquinas virtuales pueden ser:
   - Kotlin
   - Groovy
   - Clojure
   - JRuby (implementacion de Ruby)
   - Jython (implementacion de Python)

# 4. Lenguajes de programación

## 4.1. Primera parte
Compara el proceso de ejecución entre el lenguaje compilado y el interpretado.

**4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?**

- En un lenguaje compilado se necesita traducir el codigo fuente a maquina antes de poder ser ejecutado mediante un archivo ejecutable mientras que los lenguajes interpreatdps el codigo fuente se ejecuta linea por linea sin crear un archivo ejecutable.

**4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?**

- En un lenguaje compilado los errores se detectan a la hora de compilar si tiene un error no se compilara y por lo tanto no se generaria el archivo ejecutable mientras que en los lenguajes interpretados al ejecutarse linea a linea se econtrara el error cuando el interprete llegue a esa linea y se detenga.

## 4.2. Segunda parte
Compara un lenguaje de alto nivel con uno de bajo nivel.

**4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?**

- Los lenguajes de alto nivel son mas abstractos que los de bajo nivel porque se pueden entender con una mayor facilidad por el humano mientras que los de bajo nivel son lenguajes mas cercanos al lenguaje maquina y por tanto son mucho mas dificil de entender.

**4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?**

- **Ventajas:** Los de alto nivel mayor facilidad de uso/entendimiento y productividad mientras que los de bajo nivel puedes tener un mejor control del hardware como la memoria o los registros del procesador y una mejor eficiencia.

- **Desventajas:** Los de alto nivel menor control sobre el hardware y rendimiento mientras que los de bajo nivel son mas complejos y dificiles de entender.

## 4.3. Tercera parte
Compara un lenguaje orientado a objetos vs funcional.

**4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?**

- Java se basa en orientada a objetos por lo tanto se basan en objetos que representan entidades donde hay atributos (datos) y metodos (funciones) de esta forma se pueden encapsular datos y funcionalidades dentro de cada objeto.

**4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?**

- Trabajan en un paradigma completamente diferente en el caso de python las funciones son unidades fundamentales en lugar de dar instrucciones sobre cambiar estados las funciones toman entradas y producen salidas sin cambiar el estado del programa.

## 4.4. Reflexión final

**4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?**

- En mi opinion lenguajes de alto nivel como Python son bastante sencillos de aprender y usar mientras que los lenguajes de bajo nivel como ensamblador son muy dificiles de comprender y usar debido a que estan en un nivel mas cercano a al lenguaje maquina y se basan en unos y ceros.

**4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?**

- Cuando se quiere tener la maxima eficiencia compilado porque el codigo se traduce a instrucciones maquinas mientras que los interpretados son mejores cuando se busca flexibilidad y facilidad a la hora de probar el codigo porque no es necesario compilar puedes probar el codigo directamente.

**4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?**

- Es mejor usar lenguajes de alto nivel cuando necesitemos un desarrollo con rapidez, que el codigo se pueda entender con facilidad y sea facil su mantenimiento y los de bajo nivel cuando se necsita mucho control sobre el hardware o un alto rendimiento.

**4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?**

- El paradigma orientado a objetos es mas modular quiere decir que se pueden agrupar datos y metodos relacionandolos en objetos esto facilita la reutilizacion del codigo y facilita la forma de entender algunos programas complejos mientras que que el paradigma imperativo se centra mas en como el programa debe ejecutar las tareas y el funcional se basa en funciones puras que trabajan con entradas y salidas.

# 5. Herramientas de desarrollo
## 5.1. Primera parte
Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.

**5.1.1. ¿Qué hace cada una de las herramientas?**

- **Editores de texto:** Herramienta basica para escribir y modificar codigo fuente.

- **Compiladores:** Herramienta utilizada para traducir codigo fuente de lenguajes como C o C++ a codigo maquina.

- **Interpretes:** Herramienta que ejecuta codigo linea por linea sin necesidad de compilarlo previamente a codigo maquina.

- **Herramientas de documentacion:** Herramienta para mantener la claridad del codigo y facilitar su compresion.

- **Depuradores:** Herramientas que permiten examinar el estado de un codigo para detectar errores logicos y fallos.

- **Sistemas de gestion de versiones:** Herramienta que permite a los desarrolladores rastrear los cambios en su codigo y trabajar en diferentes ramas sin poner el peligro el trabajo de otras personas.

- **Frameworks:** Herramienta que proporcionan una estructura predefinida para desarrollar aplicaciones.

- **Herramientas para pruebas y calidad de codigo:** Herramienta que aseguran que el software funcione como se espera.

**5.1.2. ¿Qué tipo de tareas facilita?**

- **Editores de texto:** Escribir codigo de forma eficiente en diferentes lenguajes gracias a multiples caracteristicas como resltado de sintaxis y plugins entre otras opciones.

- **Compiladores:** Generacion de codigo ejecutable en diferentes lenguajes.

- **Interpretes:** Nos permiten ejecutar codigo de forma interactiva ademas de facilitar la depuracion y las pruebas.

- **Herramientas de documentacion:** Automatizan la generacion de documentacion y que la documentacion se mantenga actualizada con el codigo.

- **Depuradores:** Facilitan la identificacion de errores mas complejos y nos permiten explorar el estado del codigo en tiempo real.

- **Sistemas de gestion de versiones:**  Permiten trabajar en equipo de manera eficiente y segura tambien facilitan el seguimineto y revertido de cambios.

- **Frameworks:** Ahorro de tiempo en el desarrollo al reutilizar componentes.

- **Herramientas para pruebas y calidad de codigo:** Detectan errores y malas practicas de esta forma mejoran la mantenibilidad y legibilidad del codigo.

**5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?**

- - **Editores de texto:** Una forma facil y eficaz de escribir nuestro codigo.

- **Compiladores:** Generan nuestros archivos ejecutables.

- **Interpretes:** Ejecutan nuestro codigo linea a linea.

- **Herramientas de documentacion:** Una forma de comprender nuestro codigo.

- **Depuradores:** Nos ayudan a detectar errores.
 
- **Sistemas de gestion de versiones:** Nos ayudan a la hora de trabajar en equipo y una forma inteligente de revertir cambios. 

- **Frameworks:** Proporcionan una estructura predefinida para ahorrarnos tiempo.

- **Herramientas para pruebas y calidad de codigo:** Nos permite escribir un codigo sin malas practica y sin errores.

**5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**

- **Git:** Es una herramienta de control de versiones la cual es de mucha utilidad nos permite acceder a nuestro trabajo a traves de un repositorio siempre que tengamos una conexion a internet, tambien nos permite con facilidad trabajar en grupo de personas desarrollando sobre el mismo codigo.
- Al principio puede ser un poco confuso ya que hay que manejarse por terminal pero con el tiempo te das cuenta que son siempre los mismo comandos y por tanto se hace facil usarlo.

**5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**

- **Git:** Como mencione antes una de las mejores cosas que encontramos al usar git es la capacidad de trabajo en grupo de tal forma que podemos trabajar sin poner el riesgo el trabajo de otras personas y no da la posibilidad que en caso de error podamos revertir cambios.

**5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**

- **Git:** Personalmente no encontre ninguna limitacion pero realizando una busqueda en internet muchos usuarios de git se quejan del tamaño de los archivos que pueden subir que esta limitado a 50mb.

## 5.2. Segunda parte
Céntrate en una herramienta dentro de la misma categoría y compárala con otras:

**5.2.1. ¿Qué herramienta se considera más útil y por qué?**

- **Git vs Apache Subversion:** Git me parece mas util porque tiene una estructura descentralizada lo que nos permite trabajar desde local sin la necesidad de una conexion a un servidor ademas de que tiene un mejor manejo de ramas y fusiones.

**5.2.2. ¿Qué ventajas tiene una sobre la otra?**

- **Git vs Apache Subversion:** Git tiene una mayor flexibilidad en general, tienen mejor rendimiento a la hora de trabajar con ramas y trabajo distribuido mientras que Apache Subversion es mejor si se quiere trabajar de forma centralizada.

**5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?**

- **Git vs Apache Subversion:** Desde mi punto de vista lo mas intuitivo es Git pero puede ser en funcion de lo que busques a la hora de trabajar ya que Git puede ser mas intuitivos para las personas que esten acostumbradas a trabajar en un entorno mas descentralizado mientras que Subversion para las personas que esten mas acostumbrados a trabajar de forma mas centralizada y con un mayor control.

**5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?**

- **Compilador:** Un compilador se usa cuando es necesario generar un archivo ejecutable, se suelen usar cuando se necesitan generar programas con un alto rendimiento para que aprovechen los recursos del hardware al maximo.

- **Interprete:** Un interprete se usa cuando se necesita un desarrollo rapido, pruebas y scripts pequeños debido a que se ejecuta linea por linea sin necesidad de generar un archivo ejecutable.

**5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?**

- Django nos ofrece estructuras para validaciones, bases de datos, autenticacion entre otros... por lo tanto podria ser muy util en redes sociales o tiendas online por ejemplo ya que necesitan uso de base de datos y autenticacion, de esta forma usando Django nos facilitarian este tipo de estructuras y por tanto ahorrariamos tiempo.

## 5.3. Reflexión final
Con base en la experiencia de evaluación de las herramientas:

**5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?**

- Desde el punto de vista de un desarrollador de software una buena herramienta puede ayudar en mejorar la calidad del software en varios aspectos como mayor velocidad en el desarrollo, colaboracion en grupo y ayuda en prevencion y deteccion de errores lo que como resultado da un software de una calidad superior.

**5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?**

- En una herramienta buscaria caracteristicas como manejo eficiente de control de versiones, compatibilidad, flexibilidad, una buena documentacion, soporte tecnico de calidad, soporte para pruebas como caracteristicas principales.

**5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?**

- **(Git y Subversion)** En mi caso probe Git y para Subversion me informe bastante, Git tiene una gran flexibilidad y nos permite trabajar de manera distribuida que es una de las cosas que mas me gustan de Git que podemos tener el proyecto en local y trabajar sobre el sin la necesidad de conexion y subir los cambios mas tardes, en el pasado tmabien trabaje en equipo usando Git y fue una buena experiencia ya que es una herramienta bastante intuitiva a la hora de trabajar con varias ramas y usuarios. Subversion no me parece que sea una mala herramienta pero tiene sus limitaciones sobre todo porque trabaja de forma centralizada y es necesaria una conexion de tal forma me parece que  no es lo mejor cuando trabajas en grandes proyectos.

- En conclusion ambas son buenas herramientas de control de version cada una aporta unas ventajas y desventajas pero a la hora de elegirla para trabajar en un proyecto dependera de las necesidades del proyecto.