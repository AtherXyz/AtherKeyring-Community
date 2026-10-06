[Inicio](README.md) · [Propósitos y visión](PROPOSITOS.md) · [Versiones](VERSIONS.md) · [Descargar](DOWNLOAD.md)

# Roadmap público

**Actualizado: 6 de octubre de 2026. Punto de partida: 0.5.0 Alpha 1 · código 110.**

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

## Próximas prioridades

| Orden | Objetivo | Qué permitirá darlo por completado |
| --- | --- | --- |
| **1. Corregir errores de la integración** | Recoger fallos de navegación, menús, notas y equipamiento; reproducirlos y corregirlos manteniendo las funciones que ya conviven. | Casos reproducibles comprobados después de cada corrección, con pruebas de uso en dispositivo. |
| **2. Consolidar notas y archivo** | Revisar guardado interrumpido, reapertura, papelera, recuperación, exportación y conservación de datos al actualizar. | Comprobaciones de interrupción y recuperación sin pérdidas ni duplicados conocidos; actualización ensayada con datos de prueba. |
| **3. Afinar interacción y compatibilidad** | Validar gestos con texto/foto, teclado y cancelaciones; cámara, captura, permisos, orientación, accesibilidad y rendimiento. | Pruebas documentadas por dispositivo y aplicación, con límites de compatibilidad visibles. |
| **4. Preparar una beta funcional** | Reunir evidencia de estabilidad, instrucciones de prueba y soporte; resolver los bloqueantes del núcleo. | Sin bloqueantes conocidos de datos o controles; validación física suficiente y aprobación de una candidata concreta. |
| **5. Preparar distribución y versión estable** | Resolver la estrategia de firma y actualización, requisitos de publicación, privacidad y soporte. | Candidata reproducible, pruebas completas aplicables y decisión de publicación. Una beta no equivale a una versión estable ni a estar en una tienda. |

La prioridad inmediata es **corregir errores sobre el checkpoint actual**. Esta tabla no anuncia
que todas las fases estén en ejecución ni asigna números a versiones aún no construidas.
La posible duplicación al interrumpir un guardado sigue siendo una comprobación pendiente,
recogida en [problemas conocidos](KNOWN_ISSUES.md).

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
| **Gamer** | Una mini oficina especializada para la experiencia de juego. | Expansión posterior al núcleo estable; fuera del alcance de la beta funcional actual. |
| **Audiovisual** | Herramientas creativas relacionadas con imágenes y edición. | Exploración; funciones concretas aún por definir. |
| **Modelo comercial** | Definir cómo sostener el proyecto y distribuir complementos. | Sin precios ni calendario anunciados. Los créditos actuales son de prueba; no hay compras reales en esta alpha. |

Las ampliaciones no bloquean la beta funcional ni convierten las ideas originales en promesas
de entrega. Su alcance se revisará con el avance del núcleo y las decisiones de producto.

## Cómo influye la comunidad

Los [informes de errores](https://github.com/AtherXyz/AtherKeyring-Community/issues/new?template=bug_report.yml)
y las pruebas de [compatibilidad](COMPATIBILITY.md) ayudan a priorizar correcciones.
Las [ideas y preguntas](https://github.com/AtherXyz/AtherKeyring-Community/discussions) se evalúan
antes de incorporarse al plan; una sugerencia no se convierte automáticamente en una función comprometida.

[Cómo participar](CONTRIBUTING.md) · [Guía para Alpha testers](ALPHA_TESTING.md) · [Mapa del proyecto](PROJECT_MAP.md).
