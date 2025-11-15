## 2. DOCUMENTACIÓN COMPLETA EN GITHUB

### Integrantes:
* Ana Laura Flores Barcenas
* Carlos Perez Garcia
* Christian Jesus Pacheco Robles
* Keylie Gonzales Soberanis

---

### a) Representación Visual

* **¿Cómo decidieron representar cada concepto?**
    * Decidimos abordar la representación de conceptos técnicos de una manera **implícita y funcional** a través de una experiencia de usuario simplificada.
    * Utilizamos el mapa de Minecraft **"Find The Button Plus 2"** como entorno principal. La naturaleza del mapa (encontrar un botón oculto) es una metáfora clara de **Búsqueda Algorítmica** y **Control de Flujo Condicional (`IF/THEN`)**. La clave es que la **experiencia de juego en sí misma** actúa como la representación del concepto.
    * Cada nivel del mapa representa un **Módulo** o una **Función** que debe ejecutarse secuencialmente.

* **¿Qué criterios usaron para el diseño visual?**
    * El criterio principal fue la **Auto-Explicación Inmersiva**. Elegimos un mapa que, por su diseño y su nombre en inglés, indica inmediatamente la meta del juego ("Find The Button").
    * Se priorizó la **simplicidad y la navegabilidad** sobre la complejidad, usando niveles cortos para facilitar la comprensión de la **Modularidad**.
    * El diseño existente del mapa garantiza el cumplimiento del principio de **auto-explicación**.

* **¿Por qué eligieron determinados colores, formas, o disposiciones espaciales?**
    * La elección recayó en el mapa por su estructura preexistente que garantiza la **disposición espacial intuitiva** y lineal (progreso).
    * Los niveles son habitaciones cerradas, lo que define claramente un **Ámbito de Acción (Scope)** para cada desafío.
    * Los colores y formas ya presentes en el mapa se interpretan como **indicadores visuales** de dificultad o estado, evitando la necesidad de una guía explícita.

* **Justificación de sus decisiones de diseño**
    * Nuestra decisión fue utilizar un mapa popular y simple para cumplir con el requisito de que la experiencia fuera **autoexplicativa** y no necesitara instrucciones adicionales.
    * El título del mapa actúa como el único *input* de información, permitiendo al usuario saber inmediatamente **qué hacer**, simulando cómo un código bien diseñado debería ser intuitivo.

---

### b) Proceso de Desarrollo

* **¿Cómo construyeron el mundo?**
    * En lugar de la construcción tradicional, nuestro proceso se centró en la **selección, validación y empaquetado** de un mundo que cumpliera los criterios del proyecto.
    * El proceso incluyó la **Fase 1 (Selección)** del mapa "Find The Button Plus 2", la **Fase 2 (Validación)** de compatibilidad y funcionalidad sin *mods*, y la **Fase 3 (Empaquetado)** del archivo `.zip` para la distribución en GitHub.

* **¿Qué herramientas utilizaron?**
    * **Plataforma de Juego:** Minecraft Java Edition.
    * **Control de Versiones y Documentación:** **Git** y **GitHub** (para alojar el archivo de mapa y la documentación profesional).
    * **Herramientas de Compatibilidad:** Validaciones en diversas versiones de Minecraft (idealmente hasta la versión estable más reciente) para asegurar la accesibilidad.

* **¿Qué desafíos encontraron y cómo los resolvieron?**
    * **Desafío Principal:** Justificar la falta de "construcción" propia. **Resolución:** Enfocamos el valor del proyecto en la **Investigación, el Análisis de Viabilidad (Reto ASCII)**, y la **Documentación Técnica detallada**.
    * **Desafío Técnico:** Garantizar que el mapa fuera fácil de descargar y usar. **Resolución:** Proporcionamos el enlace directo del mapa original y una copia en el repositorio de GitHub con instrucciones claras de instalación.

* **Timeline del proyecto**
    * **Día 1:** Definición del enfoque (mapa preexistente, foco en documentación y reto ASCII).
    * **Día 2:** Selección y validación del mapa y análisis de su representación de conceptos.
    * **Días 3-5:** Investigación a fondo del Reto ASCII y desarrollo de la prueba de concepto base.
    * **Días 6-7:** Redacción final y detallada de toda la documentación (puntos a, b, c, d) y **commits descriptivos** en GitHub.

---

### c) Análisis del Reto Técnico Adicional

* **¿Es lógicamente posible?**
    * Sí es posible. El mundo virtual puede mandar información a la consola y esa información se puede transformar en dibujos hechos con caracteres ASCII. La lógica se basa en el **Mapeo de Datos**, donde la forma espacial se traduce a símbolos de texto. La idea es traducir las formas del mundo en símbolos que sí se puedan mostrar en texto. Por ejemplo un bloque puede ser un gato o un asterisco. No es algo automático pero sí se puede armar.

* **¿Es técnicamente viable?**
    * Sí es viable aunque depende del detalle que se quiera lograr. Se pueden hacer dibujos simples en ASCII sin problema. Lo complicado es hacerlo en tiempo real o con muchos detalles porque la consola solo trabaja con texto y tiene varios límites.

* **¿Qué herramientas o métodos podrían usarse?**
    * **Lenguajes de Procesamiento:** Lenguajes como **Python** o **Java** para manejar la información.
    * **Estructuras de Datos:** **Matrices** para guardar el dibujo antes de mostrarlo.
    * **Renderización:** `Prints` en la consola para formar figuras.
    * **Conexión:** APIs o librerías de Minecraft si se quiere conectar el mundo con código.
    * **Mapeo:** Un sistema donde cada bloque tenga un símbolo que lo represente.

* **¿Qué limitaciones existen?**
    * La consola no puede mostrar muchos detalles ni colores. El espacio para dibujar es pequeño. Los dibujos no van a quedar iguales al mundo virtual (distorsión de proporción). Si se actualiza seguido se vuelve lento. La profundidad es difícil de representar en ASCII.

* **Si lograron avances qué desarrollaron y cómo funciona:**
    * El equipo logró avanzar en una idea base para una **Prueba de Concepto (PoC)**. Se probó una forma simple para convertir una parte del mundo en un dibujo hecho con caracteres. Se imaginó la estructura como una matriz y en cada espacio se puso un símbolo que representara un bloque. Después se imprimió la matriz en la consola y salió un dibujo en ASCII. No es algo avanzado pero demuestra que se puede empezar así y que el sistema puede crecer más adelante. Es una prueba sencilla que ayuda a entender cómo funcionaría el proceso.
