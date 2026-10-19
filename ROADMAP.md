[Inicio](README.md) · [Propósitos y visión](PROPOSITOS.md) · [Versiones](VERSIONS.md) · [Descargar](DOWNLOAD.md)

# Roadmap público

**Actualizado: 19 de octubre de 2026. Punto de partida: 0.5.0 Alpha 1 · código 110.**

Este mapa explica hacia dónde va AtherKeyring. Las etapas se ordenan por prioridad y por las
comprobaciones necesarias para avanzar; no tienen fechas de lanzamiento comprometidas.
El [árbol de versiones](VERSIONS.md) recoge las entregas reales y los
[propósitos del proyecto](PROPOSITOS.md) explican la visión a largo plazo.

## Disponible ahora · Android Alpha

- Integración del libro con Índice, Notas, Colección, Tienda y Ajustes.
- Mini Office y archivo local de notas e imágenes, con accesos a cámara y captura.
- Opciones existentes organizadas en la nueva interfaz: 29 controles y 33 páginas iniciales.
- Personalización y equipamiento de llaveros A/B, con créditos de prueba en la Tienda.
- Complementos futuros señalados como «Próximamente».

Ather ha probado y elegido esta integración como checkpoint. Sigue siendo una **alpha
experimental**: la aceptación de este avance no cierra todas las pruebas de dispositivos,
gestos, permisos o persistencia. [Descargar](DOWNLOAD.md) · [Cambios](CHANGELOG.md) ·
[Problemas conocidos](KNOWN_ISSUES.md).

## Misiones de AtherKeyring

Cada casilla representa una misión completa. Tener código o un diseño listo no basta para
marcarla: se registrarán la versión, las pruebas y la aceptación que demuestren su cierre.

- [x] **M00 — Conservar el checkpoint 0.5.0/110.** Integración probada y aceptada por Ather dentro de ese alcance, con [entrega publicada para Alpha testers](https://github.com/AtherXyz/AtherKeyring-Community/releases/tag/v0.5.0-alpha1-tester). Esta aceptación no acredita toda la futura beta.
- [ ] **M01 — Asegurar las notas.** Comprobar guardados interrumpidos, reintentos, reapertura, papelera y restauración; corregir pérdidas o duplicados reproducidos y verificar la recuperación.
- [ ] **M02 — Corregir gestos y escritura.** Validar Guardar/Papelera/Cancelar, descarte exterior y teclado con notas de texto, foto o ambos.
- [ ] **M03 — Consolidar cámara y fotografías.** Verificar permisos, interrupciones, pila de imágenes, cuatro posiciones, recolocación y recuperación.
- [ ] **M04 — Completar la revisión del libro.** Corregir navegación, menús, equipamiento A/B, persistencia y legibilidad; incorporar los diseños de objetos que se vayan aprobando.
- [ ] **M05 — Validar convivencia y rendimiento.** Probar orientación, teclado, llaveros, controles de otras apps, consumo y accesibilidad en dispositivos reales.
- [ ] **M06 — Cerrar la beta funcional.** Verificar actualización conservando datos, compilación, firma y pruebas físicas; cerrar los bloqueantes conocidos de datos o controles y aceptar una candidata concreta.
- [ ] **M07 — Definir un catálogo comercial acotado.** Elegir beneficios nuevos vendibles, precios y condiciones. Las funciones básicas existentes conservarán su acceso; completar los 16 objetos de Tienda no será requisito de esta beta.
- [ ] **M08 — Verificar compras y nuevos hápticos.** Probar adquisición, restauración, cancelación y reembolso, junto con los nuevos efectos del llavero. Preparar la conexión Gamer y mantener el artículo pendiente hasta que todos sus beneficios estén disponibles.
- [ ] **M09 — Preparar la beta comercial.** Cerrar las pruebas de compra, firma y distribución, privacidad, soporte y documentación. Comenzar con facturación de prueba antes de habilitar cobros reales.

La primera entrega de correcciones se centrará en **M01: notas y recuperación**. La posible
duplicación al interrumpir un guardado sigue pendiente de comprobación en
[problemas conocidos](KNOWN_ISSUES.md). Los bloqueantes de cada etapa impedirán avanzar a
la siguiente. Los números de versión se asignarán al preparar las entregas; estas misiones
no anuncian nuevas compilaciones, fechas ni precios.

## Consola Gamer · segunda app independiente

La dirección aprobada es una **segunda aplicación con su propio motor para juegos de GBA**.
Su desarrollo y seguimiento serán independientes de AtherKeyring. La beta comercial de
AtherKeyring podrá avanzar antes que la consola.

- [ ] **G01 — Probar una consola básica.** Evaluar un motor GBA reutilizable y su licencia; demostrar carga de juegos, controles, audio y conservación de partidas.
- [ ] **G02 — Preparar una candidata independiente.** Validar instalación, estabilidad, rendimiento y respuesta háptica de sus controles en dispositivos reales.
- [ ] **G03 — Conectar Instancia Gamer.** Reconocer el derecho adquirido entre ambas apps, permitir su restauración y comprobar los estados comprado/no comprado e instalada/no instalada. El acceso llevará a descargar la consola o abrirla, según corresponda.
- [ ] **G04 — Probar el taller de modificaciones.** Elegir un juego y un cambio concreto, obtener un resultado comprobable y reversible y probarlo en el emulador.
- [ ] **G05 — Investigar la creación con IA.** Ampliar las capacidades demostradas por el taller. Crear juegos desde cero y modificar cualquier juego son objetivos de investigación, sin disponibilidad ni compatibilidad universal prometidas.

El futuro artículo **Instancia Gamer** combinará nuevos hápticos y acceso a la consola.
Los hápticos se desarrollarán por etapas: primero en el llavero y después en los controles
de la segunda app. **El artículo completo se pondrá a la venta cuando sus beneficios y la
validación de la compra entre apps estén listos.** Un enlace de descarga por sí solo no
acredita una compra. La consola y su taller todavía no están disponibles.

## Comprobaciones por versión

Cada entrega identificará las misiones y los errores que pretende cerrar, con este seguimiento:

- [ ] Alcance y resultado esperado definidos.
- [ ] Correcciones implementadas.
- [ ] Pruebas técnicas aplicables superadas.
- [ ] Regresiones comprobadas.
- [ ] Prueba en teléfono y resultado registrados cuando corresponda.
- [ ] Aceptación del alcance registrada; checkpoint, cambios y pendientes actualizados.

Esta es la plantilla para futuras entregas, no el resultado de una nueva prueba. Cada check
necesita evidencia vinculada a la versión; si un caso falla, la misión seguirá pendiente en
la siguiente revisión. El [árbol de versiones](VERSIONS.md) y los [cambios](CHANGELOG.md)
recogerán las entregas reales. Una beta comercial no equivale a una versión estable.

## En desarrollo · iOS

Existe trabajo de código para una versión nativa, pero **no hay IPA ni TestFlight disponibles**.
La compilación y validación con las herramientas de Apple siguen pendientes. Los siguientes
hitos previstos incluyen notas e imágenes en una Mini Office dentro de la aplicación,
persistencia y pruebas de interacción en dispositivo.

iOS seguirá hitos propios. La experiencia debe adaptarse a la plataforma; no se promete
reproducir el llavero flotante de Android sobre otras aplicaciones ni publicar cada alpha en ambas.

## Ampliaciones futuras · sin fecha comprometida

| Línea | Intención | Estado y dependencias |
| --- | --- | --- |
| **Momentos** | Voz, etiquetas, búsqueda y asistencia opcional para títulos o relatos. | Dirección de producto pendiente de diseño e implementación; requiere conservar originales y definir permisos, privacidad y costes antes de ofrecer servicios externos. |
| **Organización del archivo** | Ampliar la organización de entradas y explorar varios cuadernos. | Planificación futura; primero se consolida la fiabilidad del archivo actual. |
| **Colección y complementos** | Ampliar objetos y opciones del libro manteniendo el equipamiento y las notas existentes. | Incorporación por etapas, según diseño aprobado y pruebas. «Próximamente» no significa que un objeto ya funcione. |
| **Gamer** | Consola GBA independiente, conectada desde el artículo Instancia Gamer, y posterior taller de modificaciones y creación. | Misiones G01–G05; desarrollo separado. Su disponibilidad no bloquea la beta principal y condiciona la venta del artículo completo. |
| **Audiovisual** | Herramientas creativas relacionadas con imágenes y edición. | Exploración; funciones concretas aún por definir. |
| **Modelo comercial** | Catálogo acotado de beneficios nuevos, compras restaurables y preparación de beta comercial. | Misiones M07–M09; sin precios ni calendario anunciados. Los créditos actuales son de prueba; no hay compras reales en esta alpha. |

Las ampliaciones no bloquean la beta funcional ni convierten las ideas originales en promesas
de entrega. Su alcance se revisará con el avance del núcleo y las decisiones de producto.

## Cómo influye la comunidad

Los [informes de errores](https://github.com/AtherXyz/AtherKeyring-Community/issues/new?template=bug_report.yml)
y las pruebas de [compatibilidad](COMPATIBILITY.md) ayudan a priorizar correcciones.
Las [ideas y preguntas](https://github.com/AtherXyz/AtherKeyring-Community/discussions) se evalúan
antes de incorporarse al plan; una sugerencia no se convierte automáticamente en una función comprometida.

[Cómo participar](CONTRIBUTING.md) · [Guía para Alpha testers](ALPHA_TESTING.md) · [Mapa del proyecto](PROJECT_MAP.md).
