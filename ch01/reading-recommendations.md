# Recomendaciones para sacar el máximo provecho de un libro técnico

A continuación, comparto algunas notas que he publicado anteriormente cuando los lectores me preguntan cómo aprovechar al máximo mi(s) libro(s) sobre la construcción de *Large Language Models* desde cero.

Sigo un enfoque similar cuando leo libros técnicos. No pretende ser una receta universal, pero puede servir como un buen punto de partida.

Para este libro en particular, sugiero fuertemente leerlo en orden, ya que cada capítulo depende del anterior. Y para cada capítulo, recomiendo los siguientes pasos.

### 1) Primera lectura (*offline*)

Recomiendo leer el capítulo de principio a fin sin programar nada todavía. El objetivo de esta primera pasada es entender el panorama general primero.

Idealmente, recomiendo leer el capítulo lejos de la computadora. Una copia física funciona bien, pero un dispositivo digital sin distracciones (sin navegador, redes sociales ni correo electrónico) también sirve.

En lo personal, leo tanto en papel como en una tableta de tinta electrónica (*e-ink*). Aunque uso tabletas *e-ink* desde 2018 y siempre trato de leer más en ellas, sigo notando que las copias físicas me ayudan a concentrarme mejor. Por eso también a veces imprimo *papers* de investigación que son complejos o que realmente quiero entender a detalle.

Mi recomendación es que esta primera lectura sea una sesión corta y enfocada de 20 minutos, con mínimas distracciones y sin darle demasiadas vueltas ni quedarse atascado en los detalles.

Resaltar o anotar partes confusas o interesantes está perfecto, pero no me pondría a buscar conceptos en esta etapa. Solo sugiero leer, pero sin ejecutar código todavía. Esta primera pasada está pensada para asimilar la idea global.

### 2) Segunda lectura (con código)

En la segunda lectura, recomiendo transcribir y ejecutar el código del capítulo. Copiar el código es tentador porque volver a teclear es mucho trabajo, pero cuando leo otros libros técnicos, por lo general me ayuda a pensar un poco más en el código (en lugar de solo echarle un vistazo superficial).

Si obtengo resultados diferentes a los del libro, revisaría el repositorio de GitHub del libro y probaría el código desde ahí. Si sigo obteniendo resultados distintos, intentaría ver si se debe a diferentes versiones de paquetes, *random seeds* (semillas aleatorias), uso de CPU/CUDA, etc. Si después de eso sigo sin resolverlo, no sería mala idea preguntarle al autor (a través del foro del libro, en los *issues* o *discussions* públicos del repositorio en GitHub y, como último recurso, por correo electrónico).

### 3) Ejercicios

Después de la segunda lectura, de haber transcrito y ejecutado el código, suele ser un buen momento para intentar los ejercicios. Es excelente para consolidar la comprensión o jugar con un problema de manera semiestructurada. Si el ejercicio es demasiado complejo, está bien mirar la solución. Sin embargo, sigo recomendando hacer un buen intento primero.

### 4) Revisa tus notas y explora más a fondo

Ahora, después de leer el capítulo, correr el código y resolver los ejercicios, recomiendo volver a los resaltados y anotaciones de las dos lecturas anteriores y ver si todavía hay algo que no quede claro.

Este también es un buen momento para buscar referencias adicionales o hacer una búsqueda rápida para aclarar cualquier cosa que aún parezca no estar resuelta. Pero incluso si todo tiene sentido, leer más sobre un tema de tu interés no es mala idea.

En esta etapa, también tiene sentido anotar o transferir conocimientos útiles, *code snippets*, etc., a tu aplicación de notas favorita.

### 5) Aplica las ideas en un proyecto

Los pasos anteriores consistían en absorber conocimiento. Ahora, intenta ver si puedes usar ciertos aspectos de un capítulo en tu propio proyecto. O tal vez construir un pequeño proyecto usando el código del libro como punto de partida. Para inspirarte, revisa el material extra, que básicamente son miniproyectos que hice para satisfacer mi propia curiosidad.

Por ejemplo, después de leer sobre los mecanismos de *multi-head attention* e implementar el LLM, puede que te preguntes qué tan bien funciona un modelo con *grouped-query attention*, o qué tanta diferencia hace realmente usar `RMSNorm` en lugar de `LayerNorm`. Y así sucesivamente.

También podría haber aspectos más pequeños que resulten útiles en tus propios proyectos. Por ejemplo, a veces es un detalle diminuto el que termina siendo útil, como probar si llamar explícitamente a `torch.mps.manual_seed(seed)` cambia algo en comparación con usar solo `torch.manual_seed(seed)`.

A fin de cuentas, de alguna forma quiero usar ese conocimiento. Esto podría implicar usar el concepto principal del capítulo, pero a veces también pequeños detalles que aprendí en el camino, ej., incluso cosas triviales como si realmente hace una diferencia en mi proyecto llamar explícitamente a `torch.mps.manual_seed(seed)` en lugar de solo `torch.manual_seed(seed)`.

### Pensamientos adicionales

Por supuesto, nada de lo anterior está escrito en piedra. Si el tema en general me es muy familiar o fácil, y principalmente estoy leyendo el libro para obtener algo de información de capítulos posteriores, ojear rápidamente el capítulo está bien (para no perder el tiempo).

Además, para los capítulos que no tienen nada de código (por ejemplo, el capítulo introductorio 1), tiene por supuesto sentido saltarse los pasos relacionados con programar.

En fin, espero que esto sea de utilidad. ¡Y feliz lectura y aprendizaje!