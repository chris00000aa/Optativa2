

**Integrantes del Equipo:**
* Ana Laura Flores Barcenas
* Carlos Perez Garcia
* Christian Jesus Pacheco Robles
* Keylie Gonzales Soberanis

---

## DESCRIPCIÓN Y ENFOQUE DEL PROYECTO

Hemos seleccionado el mundo virtual de **Minecraft** para implementar una experiencia interactiva que representa los conceptos técnicos mediante una metáfora de juego universalmente reconocida: la búsqueda.

**Conceptos Centrales Representados:**
* **Control de Flujo Condicional (IF/THEN):** Representado por la necesidad de encontrar el botón para activar la salida y avanzar (la condición debe ser TRUE).
* **Búsqueda Algorítmica/Iteración (LOOP):** La búsqueda repetitiva del botón dentro de un nivel hasta que la condición se cumple.
* **Modularidad y Secuenciación:** Cada nivel del mapa es un módulo de código que debe ejecutarse en orden para completar el programa (el mapa).

### Criterio Fundamental: Mundo Autoexplicativo

El proyecto se basa en el mapa **"Find The Button Plus 2"** precisamente porque su título y mecánica son inherentemente autoexplicativos. Cualquier persona que ingrese entiende inmediatamente la tarea: buscar el botón para progresar. Este enfoque garantiza una **navegación intuitiva** y una comprensión implícita de los conceptos sin necesidad de texto, guía o instructor.

### MUNDO VIRTUAL FUNCIONAL:

La experiencia interactiva se basa en el mapa de Minecraft **"Find The Button Plus 2"**.

| Requisito | Cumplimiento y Acceso |
| :--- | :--- |
| **Una forma clara de acceder al mundo** | El mapa está disponible para descarga directa en el repositorio de GitHub. |
| **Instrucciones de Conexión** | Plataforma: **Minecraft Java Edition** (Versión 1.12.2 o superior). <br> Instalación: Simplemente extraer el archivo `.zip` en la carpeta `saves` de Minecraft. |
| **Los conceptos técnicos representados de manera explícita y obvia** | Los conceptos están representados de forma **implícita y funcional**. La mecánica de *Encontrar el Botón* es la metáfora explícita de la **Condición** y la **Iteración**. |
| **Navegación intuitiva sin necesidad de guía** | El diseño del mapa es lineal y el objetivo (el botón) es universalmente conocido, haciendo la navegación intuitiva. |
| **Experiencia autoexplicativa** | El nombre del mapa y la mecánica del juego eliminan la necesidad de cualquier explicación externa. |

[Descargar «Find The Button Plus 2» (Mapa de Minecraft)] (https://es.mapcraft.me/adventure-maps/find-the-button-plus-2)

---

## RETO TÉCNICO ADICIONAL (Investigación ASCII)

Una vez establecido el entorno de conceptos, el equipo enfrentó el desafío ambicioso de crear un sistema que permita dibujar en la consola (CMD) usando arte ASCII, tomando datos del mundo virtual.

Este componente fue abordado prioritariamente desde la **investigación, documentación, y análisis de viabilidad técnica**, ya que el tiempo fue invertido en demostrar la posibilidad del concepto a través de un prototipo teórico y un avance simple de prueba de concepto.

* **¿Es lógicamente posible?**
    * Sí es posible. El mundo virtual puede mandar información a la consola y esa información se puede transformar en dibujos hechos con caracteres ASCII. La lógica se basa en el **Mapeo de Datos**, donde la forma espacial se traduce a símbolos de texto. La idea es traducir las formas del mundo en símbolos que sí se puedan mostrar en texto. Por ejemplo un bloque puede ser un gato o un asterisco. No es algo automático pero sí se puede armar.
---
* **¿Es técnicamente viable?**
    * Sí es viable aunque depende del detalle que se quiera lograr. Se pueden hacer dibujos simples en ASCII sin problema. Lo complicado es hacerlo en tiempo real o con muchos detalles porque la consola solo trabaja con texto y tiene varios límites.
---
* **¿Qué herramientas o métodos podrían usarse?**
    * **Lenguajes de Procesamiento:** Lenguajes como **Python** o **Java** para manejar la información.
    * **Estructuras de Datos:** **Matrices** para guardar el dibujo antes de mostrarlo.
    * **Renderización:** `Prints` en la consola para formar figuras.
    * **Conexión:** APIs o librerías de Minecraft si se quiere conectar el mundo con código.
    * **Mapeo:** Un sistema donde cada bloque tenga un símbolo que lo represente.
---
* **¿Qué limitaciones existen?**
    * La consola no puede mostrar muchos detalles ni colores. El espacio para dibujar es pequeño. Los dibujos no van a quedar iguales al mundo virtual (distorsión de proporción). Si se actualiza seguido se vuelve lento. La profundidad es difícil de representar en ASCII.
---
* **Si lograron avances qué desarrollaron y cómo funciona:**
    * El equipo logró avanzar en una idea base para una **Prueba de Concepto (PoC)**. Se probó una forma simple para convertir una parte del mundo en un dibujo hecho con caracteres. Se imaginó la estructura como una matriz y en cada espacio se puso un símbolo que representara un bloque. Después se imprimió la matriz en la consola y salió un dibujo en ASCII. No es algo avanzado pero demuestra que se puede empezar así y que el sistema puede crecer más adelante. Es una prueba sencilla que ayuda a entender cómo funcionaría el proceso.
