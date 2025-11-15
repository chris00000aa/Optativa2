a) Representación Visual
La documentación del diseño visual se centra en justificar la elección de un mapa existente y cómo este cumple con los criterios de diseño exigidos, priorizando la auto-explicación y el aprendizaje implícito.

¿Cómo decidimos representar cada concepto?

Decidimos abordar la representación de conceptos técnicos de una manera implícita y funcional a través de una experiencia de usuario extremadamente simplificada.
Utilizamos el mapa de Minecraft "Find The Button Plus 2" como entorno principal. La naturaleza del mapa (encontrar un botón oculto para progresar) es una metáfora de los conceptos de Búsqueda Algorítmica y Control de Flujo Condicional (IF/THEN). El jugador debe iterar (buscar) y condicionar su progreso (IF el botón es encontrado, THEN avanza).
La clave es que la experiencia de juego en sí misma actúa como la representación del concepto, en lugar de una representación visual estática tradicional. Esto garantiza un aprendizaje activo e inmersivo.
¿Qué criterios usamos para el diseño visual?

El criterio principal fue la Auto-Explicación Inmersiva. Elegimos un mapa que, por su diseño y su nombre en inglés, indica inmediatamente al usuario la meta del juego ("Find The Button").
Se priorizó la simplicidad y la navegabilidad sobre la complejidad. El diseño del mapa (compuesto por niveles cortos y distintos) facilita la comprensión de la Modularidad y la Secuenciación de tareas, donde cada nivel es un "módulo" de código.
El diseño visual del mapa ya estaba establecido, lo que nos permitió enfocarnos en el cumplimiento del reto (investigación ASCII) y la calidad de la documentación (justificación de diseño).
¿Por qué elegimos determinados colores, formas o disposiciones espaciales?

La elección recayó en el mapa por su estructura preexistente que garantiza la disposición espacial intuitiva y la sensación de progreso lineal.
Los niveles son habitaciones cerradas, lo que define claramente un Ámbito de Acción (Scope) para cada desafío, limitando las variables y las búsquedas del jugador.
Los colores y formas ya presentes en el mapa (que suelen ser temáticos por nivel) se interpretan como indicadores visuales de estado (por ejemplo, un nivel oscuro o complejo representa un algoritmo más pesado), demandando la atención del usuario y evitando la necesidad de una guía externa.
Justificación de nuestras decisiones de diseño

Nuestra decisión más importante fue la de utilizar un mapa simple y popular para cumplir a cabalidad con el requisito de que la experiencia fuera autoexplicativa y no necesitara instrucciones adicionales.
El título del mapa en inglés actúa como el único input de información, y el usuario sabe inmediatamente qué hacer, sin depender de textos o menús complejos. Esto simula cómo un código bien diseñado debería ser intuitivo de usar y su funcionalidad, predecible.
b) Proceso de Desarrollo
Esta sección detalla cómo se gestionó el proyecto basándose en la estrategia de usar un recurso existente y enfocar el esfuerzo en la documentación y el análisis.

¿Cómo construimos el mundo?

En lugar de la construcción tradicional, nuestro proceso se centró en la selección, validación y empaquetado de un mundo que cumpliera los criterios del proyecto.
Fase 1 (Selección): Búsqueda de un mapa de "Encontrar el botón" que fuese sencillo y que transmitiera el concepto solo con su nombre (en este caso, "Find The Button Plus 2"). Se revisaron varios mapas antes de elegir uno que no requiriera mods o paquetes de recursos adicionales.
Fase 2 (Validación): Pruebas exhaustivas para confirmar que la experiencia de juego no requiriera mods complejos ni instrucciones externas y que fuera funcional en múltiples versiones de Minecraft.
Fase 3 (Empaquetado): Preparación del archivo .zip para la subida a GitHub y la generación del enlace de descarga, garantizando la accesibilidad y la compatibilidad con el formato de GitHub.
¿Qué herramientas utilizamos?

Plataforma de Juego: Minecraft Java Edition (requerido para la versión del mapa).
Herramientas de Compatibilidad: El mapa es compatible con la versión 1.12.2 o superior, pero se recomienda validar su funcionamiento en la versión 1.21.8 o la versión estable más reciente de Minecraft Java Edition para asegurar la compatibilidad.
Control de Versiones y Documentación: Git y GitHub (para alojar el archivo de mapa y toda la documentación profesional).
Archivo de Distribución: El mapa se proporciona como un archivo .zip listo para ser extraído en la carpeta de saves de Minecraft.
¿Qué desafíos encontramos y cómo los resolvimos?

Desafío Principal (Justificación del Valor): El desafío fue justificar la falta de "construcción" propia. Resolución: Se decidió enfocar el valor del proyecto en la Investigación, el Análisis de Viabilidad (Reto ASCII), y la Documentación Técnica detallada (explicando cómo la elección del mapa cumple los criterios).
Desafío Técnico (Distribución): Garantizar que el mapa fuera fácil de descargar y usar. Resolución: Proporcionamos el enlace directo del mapa original y una copia en el repositorio de GitHub para ofrecer dos puntos de acceso claros, además de instrucciones de instalación sencillas.
Timeline del proyecto

Día 1: Definición del enfoque (mapa preexistente, foco en documentación y reto ASCII).
Día 2: Selección y validación del mapa "Find The Button Plus 2" y análisis de cómo este representa los conceptos de forma implícita.
Días 3-5: Investigación a fondo del Reto ASCII (como se detalla en la sección 'c'), incluyendo el desarrollo de la prueba de concepto base.
Días 6-7: Redacción final y detallada de toda la documentación (puntos a, b, c, d) y commits descriptivos en GitHub, asegurando la calidad del entregable final.
d) Control de Versiones
Esta sección detalla cómo se mantuvo la organización del repositorio y el enfoque en la documentación profesional, incluyendo los detalles del README.md.

Commits claros y descriptivos

Cada commit realizado se acompañó de un mensaje claro que indica la naturaleza de los cambios.
Se siguió la convención Tipo(Alcance): Mensaje Descriptivo para mantener un historial limpio y legible.
Ejemplos de commits utilizados:
feat: Inclusión de la estructura inicial del documento MD
docs: Justificación de representación visual (Punto 2.a)
refactor: Optimización de la estructura de la documentación
chore: Actualización del archivo .zip del mapa de Minecraft
Historial que muestre la evolución del proyecto

El historial de commits refleja el enfoque del equipo en la documentación desde el inicio.
La progresión lógica muestra las etapas del proyecto: Setup inicial, Investigación ASCII, y Redacción de Justificaciones (a y b).
El historial demuestra un trabajo colaborativo y un proceso de documentación constante, no solo un vertido final de contenido.
