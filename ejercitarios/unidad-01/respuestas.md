<h1>Respuestas — Ejercitario Unidad 01</h1>
<blockquote>
<p>Sistema de referencia: <strong>Sistema de gestión de gimnasio</strong> (socios, membresías, pagos, asistencia, clases e instructores).</p>
</blockquote>
<hr />
<h2>Tema 1 · Ingeniería de software: una visión previa</h2>
<p><strong>1. En tus propias palabras, define qué es la Ingeniería de Software.</strong></p>
<p><em>Respuesta:</em>
La Ingeniería de Software es la disciplina que aplica principios de ingeniería para construir, mantener, escalar y testear software de forma planificada y siguiendo procesos definidos. En el sistema de gestión de gimnasio, significa que no alcanza con que la aplicación "ande": tiene que registrar socios, cobrar membresías y controlar el acceso de forma confiable y segura, cumpliendo los requisitos del gimnasio dentro de un tiempo y un costo razonables.</p>
<p><strong>2. Explica con un ejemplo la diferencia entre "programar" y "hacer ingeniería de software".</strong></p>
<p><em>Respuesta:</em>
Programar es escribir código que resuelve un problema puntual. Por ejemplo, una función que calcula la fecha de vencimiento de la membresía de un socio a partir de su fecha de pago.</p>
<p>Hacer ingeniería de software implica todo lo que rodea a ese código: analizar los requisitos funcionales (alta de socios, cobros, control de asistencia) y no funcionales (seguridad de los datos, tiempos de respuesta en recepción), planificar una arquitectura adecuada, usar control de versiones, documentar, testear cada módulo, dividir el trabajo en el equipo y definir cómo se mantendrá y actualizará el sistema (por ejemplo, cuando el gimnasio cree nuevos planes o promociones).</p>
<p><strong>3. Menciona dos razones por las cuales la ingeniería de software es necesaria en el desarrollo de sistemas actuales.</strong></p>
<p><em>Respuesta:</em>
Los sistemas actuales son cada vez más grandes y complejos: un sistema de gimnasio integra socios, pagos, clases, reservas, accesos con QR o huella y reportes; sin un proceso ordenado es fácil que se vuelva inmantenible o falle.
El software de hoy se desarrolla en equipo y a largo plazo: necesita ser entendible, documentado y adaptable para que otros desarrolladores puedan modificarlo o escalarlo (por ejemplo, agregar una app móvil para socios) sin reescribir todo desde cero.</p>
<hr />
<h2>Tema 2 · El rol de la IS en el diseño de sistemas (+ impacto de la IA)</h2>
<p><strong>4. Enumera los elementos que conforman un sistema basado en computadora, además del software.</strong></p>
<p><em>Respuesta:</em>
Software: la aplicación de gestión del gimnasio.
Hardware: computadora de recepción, lector de QR o huella, torniquete, servidor.
Personas: recepcionistas, instructores, administrador y socios.
Base de datos: socios, membresías, pagos, asistencia y clases.
Documentación: manual de usuario, políticas del gimnasio, contratos de membresía.
Procedimientos: alta de socio, cobro de cuota, control de ingreso, cierre de caja.</p>
<p><strong>5. Describe brevemente la diferencia entre una visión sistémica y una visión aislada del software en el diseño de sistemas.</strong></p>
<p><em>Respuesta:</em>
Una visión aislada se enfoca solo en un módulo, por ejemplo el de pagos, sin considerar cómo se conecta con el resto, lo que genera problemas de integración (un socio paga pero el torniquete no lo deja pasar). Una visión sistémica entiende el software como parte de un conjunto mayor donde pagos, membresías, control de acceso, recepcionistas y base de datos se conectan, asegurando que el sistema completo funcione de manera coherente y sostenible.</p>
<p><strong>6. Elige una herramienta de inteligencia artificial aplicada al desarrollo de software (por ejemplo, un asistente de código o de testing) e indica:</strong>
Qué tarea del ingeniero de software apoya o transforma.
Un beneficio concreto que ofrece.
Un riesgo o desafío que introduce su uso.</p>
<p><em>Respuesta:</em>
<strong>Un buen ejemplo es GitHub Copilot, un asistente de código basado en inteligencia artificial:</strong>
<strong>Tarea que apoya o transforma:</strong> la programación. Sugiere fragmentos de código, completa funciones y genera pruebas unitarias; en el sistema del gimnasio puede ayudar a escribir, por ejemplo, la lógica de vencimiento de membresías o las pruebas del módulo de asistencia.
<strong>Beneficio concreto:</strong> aumenta la productividad al reducir el tiempo de escritura de código y permite enfocarse más en el diseño y la lógica del sistema.
<strong>Riesgo o desafío:</strong> puede generar dependencia excesiva y código que el ingeniero no comprende del todo, lo que afecta la calidad y mantenibilidad (por ejemplo, un cálculo de cobros con un error sutil que nadie detecta).</p>
<hr />
<h2>Tema 3 · Historia de la ingeniería de software</h2>
<p><strong>7. En tu opinión, ¿por qué la "crisis del software" de 1968 marcó un punto de inflexión para la disciplina?</strong></p>
<p><em>Respuesta:</em>
Porque evidenció que el desarrollo de programas ya no podía tratarse como un arte improvisado: la complejidad, los retrasos y los costos desbordados obligaron a formalizar la disciplina y dieron nacimiento a la ingeniería de software. Un sistema de gimnasio hecho "a lo que salga", sin análisis ni pruebas, sufriría lo mismo a pequeña escala: cobros mal calculados, datos perdidos y sobrecostos.</p>
<p><strong>Ejercicio de relación</strong> (completá con la letra que corresponda a cada número):</p>
<table>
<thead>
<tr>
<th>Evento / Período</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>
<tr>
<td>A. Programación artesanal (1950s–60s)</td>
<td>3</td>
</tr>
<tr>
<td>B. Crisis del software (1968)</td>
<td>1</td>
</tr>
<tr>
<td>C. Modelo en cascada (1970s–80s)</td>
<td>5</td>
</tr>
<tr>
<td>D. Métodos iterativos (1990s)</td>
<td>4</td>
</tr>
<tr>
<td>E. Metodologías ágiles (2001–hoy)</td>
<td>2</td>
</tr>
</tbody>
</table>
<ol>
<li>Se acuña el término "ingeniería de software" en una conferencia de la OTAN ante fallas y sobrecostos de proyectos.</li>
<li>Surge el Manifiesto Ágil; se popularizan Scrum, Kanban y XP.</li>
<li>El software se escribía de forma individual, sin procesos formales.</li>
<li>Ganan terreno la iteración, el prototipado y los modelos incrementales.</li>
<li>Se establecen los primeros procesos formales y estructurados de desarrollo.</li>
</ol>
<hr />
<h2>Tema 4 · El rol del ingeniero de software</h2>
<p><strong>8. Menciona tres competencias que debe tener un ingeniero de software, además del conocimiento técnico.</strong></p>
<p><em>Respuesta:</em>
Resolución de problemas (por ejemplo, resolver qué pasa si un socio paga dos veces la misma cuota).
Comunicación y trabajo en equipo (entender lo que necesita el dueño del gimnasio y coordinarse con otros desarrolladores).
Responsabilidad y ética profesional (cuidar los datos personales y de pago de los socios).</p>
<p><strong>9. Describe brevemente qué hace cada uno de los siguientes roles dentro de un equipo de desarrollo:</strong></p>
<table>
<thead>
<tr>
<th>Rol</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>
<tr>
<td>Analista</td>
<td>Levanta, interpreta y modela los requisitos del gimnasio: cómo se dan de alta los socios, qué planes existen, cómo se cobra y cómo se controla el acceso.</td>
</tr>
<tr>
<td>Arquitecto</td>
<td>Diseña la estructura general del sistema: módulos (socios, pagos, clases, accesos), base de datos, integración con lectores y pasarela de pagos.</td>
</tr>
<tr>
<td>Desarrollador</td>
<td>Diseña, programa y mantiene los módulos y funcionalidades del sistema (registro de socios, reservas de clases, reportes).</td>
</tr>
<tr>
<td>Tester / QA</td>
<td>Prueba y evalúa el sistema para verificar que cumple los requisitos: que los cobros se calculen bien, que el acceso se bloquee al vencer la membresía, etc.</td>
</tr>
</tbody>
</table>
<p><strong>10. Caso breve:</strong> Un ingeniero de software descubre, cerca de la fecha de entrega, una falla de seguridad que podría exponer datos de usuarios, pero corregirla retrasaría el proyecto una semana. ¿Qué debería hacer y por qué, considerando la ética profesional?</p>
<p><em>Respuesta:</em>
Debería priorizar la corrección de la falla, aunque implique retrasar la entrega, e informar al equipo y al cliente sobre el motivo. En un sistema de gimnasio la falla podría exponer datos personales y de pago de los socios, y la ética profesional exige proteger a los usuarios y garantizar la confiabilidad del sistema por encima del calendario.</p>
<hr />
<h2>Tema 5 · El ciclo del software.</h2>
<p><strong>11. Ordena y nombra las cinco fases genéricas del ciclo de vida del software vistas en clase.</strong></p>
<p><em>Respuesta:</em>
Análisis (relevar qué necesita el gimnasio).
Diseño (arquitectura, base de datos, pantallas).
Implementación (programar los módulos).
Pruebas (verificar cobros, accesos, reservas).
Mantenimiento (corregir, adaptar y actualizar).</p>
<p><strong>12. ¿Por qué se afirma que el mantenimiento suele ser la fase más costosa del ciclo de vida del software? Da un ejemplo hipotético.</strong></p>
<p><em>Respuesta:</em>
Porque representa la mayor parte del tiempo y los recursos invertidos después de la entrega inicial: los sistemas deben corregirse, adaptarse a nuevas necesidades y actualizarse frente a cambios tecnológicos. A diferencia del desarrollo inicial, que es un esfuerzo concentrado, el mantenimiento es continuo y prolongado, por lo que acumula costos durante años.</p>
<p>Ejemplo: se entrega el sistema de gestión del gimnasio y al cabo de un año:
Se detectan errores en el cálculo de recargos por mora que deben corregirse.
El gimnasio crea nuevos planes (pase familiar, clases sueltas) y el sistema debe adaptarse.
Surgen nuevas exigencias de facturación y de protección de datos que obligan a actualizar el sistema.</p>
<p>Aunque el desarrollo inicial tomó 6 meses, el mantenimiento durante los siguientes 5 años consume más horas de programación, pruebas y soporte, superando ampliamente el costo original.</p>
<hr />
<h2>Tema 6 · Relación con otras áreas de la ciencia de la computación</h2>
<p><strong>Completen el siguiente cuadro indicando cómo cada área apoya a la ingeniería de software.</strong></p>
<table>
<thead>
<tr>
<th>Área</th>
<th>¿Cómo apoya a la Ingeniería de Software?</th>
</tr>
</thead>
<tbody>
<tr>
<td>Estructuras de datos y algoritmos</td>
<td>Aportan las bases para que el sistema sea eficiente: por ejemplo, búsquedas rápidas de socios por nombre o documento y ordenamiento de pagos o asistencias, aplicados con metodologías que garanticen código robusto y mantenible.</td>
</tr>
<tr>
<td>Bases de datos</td>
<td>Permiten almacenar de forma eficiente, segura y escalable la información de socios, membresías, pagos y asistencia, y la ingeniería de software aporta el buen diseño y la arquitectura de ese almacenamiento.</td>
</tr>
<tr>
<td>Sistemas operativos</td>
<td>Proveen la base sobre la que corre el sistema (gestión de memoria, archivos, procesos y dispositivos); la ingeniería de software garantiza la integración del sistema con el hardware del gimnasio, como lectores de huella o QR e impresoras de tickets.</td>
</tr>
<tr>
<td>Redes</td>
<td>Permiten la comunicación entre la recepción, el servidor, la pasarela de pagos y la app móvil de los socios; la ingeniería de software aporta programabilidad y automatización para que los datos viajen de forma eficiente y segura.</td>
</tr>
</tbody>
</table>
<hr />
<h2>Tema 7 · Relación con otras disciplinas</h2>
<p><strong>13. Elige dos de las siguientes disciplinas — Administración, Psicología, Economía, Derecho, Comunicación — y explica con un ejemplo concreto cómo se relacionan con el trabajo diario de un ingeniero de software.</strong></p>
<p><em>Respuesta:</em>
<strong>Economía:</strong> un módulo de facturación y cobros que calcule bien las cuotas, recargos y descuentos del gimnasio no solo da eficiencia al área contable, sino que optimiza los tiempos de trabajo y permite procesar grandes volúmenes de información, además de ayudar al dueño a ver ingresos y morosidad para tomar decisiones.</p>
<p><strong>Comunicación:</strong> un módulo de notificaciones (avisos de vencimiento, recordatorios de clases, novedades del gimnasio) mantiene informados a los socios y facilita la coordinación entre recepción, instructores y administración.</p>
<p><strong>14. Reflexión final:</strong> de todo lo visto en clase (definición, historia, rol del ingeniero, ciclo del software, relación con otras áreas y disciplinas, e impacto de la IA), ¿qué idea te resultó más relevante y por qué?</p>
<p><em>Respuesta:</em>
La idea más relevante es que la ingeniería de software no se limita a programar, sino que abarca análisis, diseño, pruebas, mantenimiento y ética profesional. Para el sistema de gestión de gimnasio esto es crucial: el ingeniero debe garantizar que el sistema sea confiable, seguro y sostenible en el tiempo, porque de él dependen los cobros del negocio y los datos de los socios.</p>
