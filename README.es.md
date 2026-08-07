# Sprint del sistema de producción de cortos con IA

[English](README.md)

## Una sala de guionistas reutilizable para crear videos cortos con IA de manera coherente

Convierta las reglas de su marca, los personajes recurrentes, las localizaciones y las ideas de contenido en un sistema de producción estructurado; después, reciba los próximos **3–4 episodios como 12–20 paquetes de planos listos para renderizar**.

**Un sprint de alcance fijo · $1,250 · cinco días hábiles**

[Comience con el formulario de admisión de GitHub apto para información no privada →](../../issues/new?template=pilot.yml)

> Este es un servicio de sistema de producción y desarrollo creativo. **No** promete que un modelo de video vaya a renderizar correctamente todos los planos y **no** incluye la publicación en plataformas sociales.

---

## El problema

El trabajo de video con IA suele comenzar como un conjunto desordenado de prompts. Las descripciones cambian entre planos, los personajes pierden coherencia, las instrucciones de estilo se extravían y las revisiones no se pueden reproducir.

Este sprint sustituye ese conjunto por un pequeño sistema operativo de contenidos independiente del modelo:

- un conjunto de reglas de marca y visuales;
- descripciones canónicas («bloqueos») para las entidades recurrentes;
- un formato de serie repetible;
- briefs estructurados de episodios y planos;
- herencia coherente de prompts desde la marca hasta el plano;
- entregas legibles por máquina y hojas para revisión humana.

Usted conserva una fuente de referencia editable en lugar de empezar de cero con cada corto.

## Examine el método de trabajo antes de hacer una consulta

Un canal ficticio público y desarrollado demuestra la estructura de archivos subyacente y los bloqueos de continuidad:

- [fuente del canal, el canon, la serie y el episodio](https://github.com/ruizmr/minimax-h3-runpod/tree/main/room/10-Channels/Night%20Shift%20Supply)
- [implementación del compilador/linter](https://github.com/ruizmr/minimax-h3-runpod/blob/main/room/tools/roomctl.py)
- [episodio desarrollado de cuatro planos](https://github.com/ruizmr/minimax-h3-runpod/blob/main/room/10-Channels/Night%20Shift%20Supply/Episodes/ep-001-a-single-egg.md)

Esto demuestra el método de planificación/compilación, no la existencia de renderizados finales del modelo ni el rendimiento de una campaña. No se hace ninguna afirmación de ese tipo.

## Qué recibe

Para **una marca / un canal**, el sprint incluye:

1. **Una sesión inicial de 90 minutos** sobre la audiencia, la voz, el lenguaje visual, las restricciones y los objetivos de contenido.
2. **Una sala de guionistas personalizada** apta para un flujo de trabajo de Markdown al estilo de Obsidian.
3. **Un sistema para un canal** con reglas visuales, voz, restricciones negativas, cadencia y campos de identidad social.
4. **Un canon compacto:** hasta 2 personajes recurrentes, 2 localizaciones y 3 objetos de utilería, cada uno con descripciones canónicas reutilizables.
5. **Un formato de serie repetible** con una estructura de episodio definida.
6. **3–4 episodios compilados, con un total de 12–20 planos.**
7. **Paquetes de producción para cada plano** que contienen:
   - prompts en lenguaje natural y etiquetados;
   - intención del prompt negativo;
   - bloques de acción, cámara, diálogo, audio y continuidad cuando corresponda;
   - identificadores de plano estables y notas de continuidad del último fotograma;
   - un manifiesto JSON legible por máquina; y
   - una hoja de contacto/revisión legible por personas.
8. **Una adaptación al dialecto de un modelo** que adecúa el paquete a un generador que usted ya utilice, cuando el formato de entrada documentado de este lo permita.
9. **Una ronda consolidada de revisiones.**
10. **Una sesión de entrega de 60 minutos** que muestra cómo editar, ejecutar el linter, compilar y ampliar el sistema.

Los entregables se proporcionan como archivos Markdown, JSON y de texto sin formato en una carpeta de proyecto portátil. El flujo de trabajo subyacente es independiente del modelo; el comportamiento específico de cada generador sigue fuera de nuestro control.

## Qué no se incluye

Para que la oferta sea transparente y mantenga un precio fijo, el sprint excluye expresamente:

- renderizados de video, coherencia de apariencia, sincronización labial, calidad de audio o aceptación por parte del modelo garantizados;
- uso de GPU, créditos de generación, almacenamiento u otras tarifas de terceros;
- un costo por video o un porcentaje de ahorro garantizados;
- configuración de cuentas sociales, aprobación de OAuth, programación o publicación;
- alcance, interacción, conversiones, ingresos o aprobación de plataformas garantizados;
- software web personalizado, SaaS alojado, acceso multiusuario o soporte continuo;
- conceptos o revisiones ilimitados;
- autorización legal de nombres, música, apariencias, marcas comerciales, afirmaciones o recursos proporcionados por el cliente.

Si posteriormente se solicita asistencia con el renderizado o la publicación, se requiere un **alcance escrito por separado**. La compra de este sprint no autoriza ningún trabajo de generación de pago ni ninguna acción de publicación externa.

## Proceso y calendario

### 1. Incidencia de admisión

Abra el formulario piloto de admisión en GitHub. **No** incluya contraseñas, claves de API, claves de monederos, datos privados de clientes, detalles de campañas aún no publicadas ni otros secretos. Los materiales sensibles solo se pueden gestionar mediante un canal seguro acordado por separado.

### 2. Alcance escrito

Revisamos la información de admisión y enviamos un alcance escrito que especifica:

- la marca/el canal;
- el canon y la serie incluidos;
- el intervalo de episodios y planos;
- el generador de destino para la única adaptación de dialecto;
- los materiales proporcionados;
- las fechas de entrega y aceptación; y
- cualquier excepción aprobada.

**No se solicita ningún pago antes de que ambas partes aprueben ese alcance escrito.** El envío de una incidencia es una consulta, no un pedido.

### 3. Reserva

Tras la aprobación del alcance escrito, el sprint se reserva con un **depósito del 20 % ($250)** pagado en **USDC en Base**. La solicitud de pago indicará el importe exacto, la red Base, el contrato del token y la dirección del destinatario. No envíe fondos a una dirección publicada por un tercero no verificado ni en otra red.

### 4. Desarrollo y revisión

El plazo de entrega de cinco días hábiles comienza una vez que el depósito se confirma y se reciben todos los materiales de origen acordados. El trabajo continúa con la configuración del sistema, la compilación, las comprobaciones internas y la entrega para su revisión.

### 5. Aceptación y saldo

La aceptación se basa en el alcance escrito, no en el rendimiento subjetivo del renderizado. El paquete se acepta cuando contiene los elementos acordados:

- archivos del canal y del canon;
- formato de la serie;
- 3–4 episodios y 12–20 planos;
- archivos de prompts compilados, manifiesto(s) y hoja(s) de revisión;
- una adaptación al dialecto de un modelo; y
- materiales/sesión de entrega.

Puede comunicar los defectos respecto al alcance en una única lista consolidada durante el periodo de aceptación indicado en el alcance escrito. Corregimos los defectos válidos respecto al alcance y completamos la ronda de revisiones incluida. El **80 % restante ($1,000)** se debe pagar en **USDC en Base** tras la aceptación. Cualquier comisión de transacción/red corre a cargo del remitente, salvo que el alcance escrito indique lo contrario.

Las condiciones de cancelación, reembolso, impuestos y tipo de cambio se indicarán en el alcance escrito antes del pago. Nunca envíe un depósito sin ese documento.

## Uso autorizado de agentes de IA

Este servicio utiliza deliberadamente asistencia de IA. Al aprobar el alcance escrito, usted autoriza a los agentes de IA a colaborar con las tareas necesarias para producir los entregables enumerados, entre ellas:

- organizar y analizar los materiales no secretos que usted proporcione;
- redactar documentos de marca, canon, serie, episodio y plano;
- ejecutar localmente el linter, la compilación, el formateo y comprobaciones deterministas de control de calidad;
- identificar incoherencias y preparar revisiones; y
- preparar la documentación de entrega.

El criterio humano sigue formando parte de la definición del alcance, la dirección creativa, la aceptación y cualquier decisión que autorice efectos externos.

Salvo aprobación por escrito y por separado, los agentes **no están autorizados** a:

- acceder a secretos, claves privadas, frases mnemotécnicas, contraseñas o cuentas no relacionadas;
- enviar trabajos de pago a GPU/modelos;
- publicar, programar, comentar, enviar mensajes o modificar cuentas sociales;
- comprar recursos, generar cargos de terceros o transferir fondos;
- entrenar con materiales confidenciales del cliente o reutilizarlos fuera del encargo; ni
- presentar material generado como legalmente autorizado.

Indíquenos durante la admisión si determinados materiales no pueden procesarse con asistencia de IA. Antes de aceptar el pago, confirmaremos si el sprint puede realizarse con esa restricción.

## Para quién es este servicio

Este servicio resulta especialmente adecuado para una agencia boutique de redes sociales, un profesional independiente de video con IA, un estudio de creadores o una marca dirigida por su fundador que:

- ya experimenta con un generador de video con IA;
- desea formatos recurrentes en lugar de prompts aislados;
- necesita una mayor continuidad visual y narrativa; y
- cuenta con alguien que pueda revisar el trabajo creativo y utilizar el generador elegido.

No resulta adecuado si el éxito exige renderizados finales garantizados, publicación autónoma, un resultado de rendimiento específico o una aplicación multiusuario lista para producción.

## Precio fijo

| Concepto | Importe |
|---|---:|
| Sprint del sistema de producción de cortos con IA | **$1,250** |
| Depósito de reserva tras el alcance escrito (20 %) | **$250 USDC en Base** |
| Saldo tras la aceptación (80 %) | **$1,000 USDC en Base** |

Este precio no incluye créditos de renderizado ocultos, ya que el renderizado no está incluido. Cualquier complemento futuro requiere un nuevo alcance escrito.

## Inicie el piloto

[Abra la incidencia de admisión en GitHub](../../issues/new?template=pilot.yml). Comparta suficiente contexto apto para divulgarse públicamente a fin de evaluar la idoneidad, pero **no publique secretos ni información sensible sobre campañas**.

Responderemos con preguntas o con un alcance escrito. No deberá nada hasta que se acuerde dicho alcance.

---

### Resumen en lenguaje sencillo

Usted compra un sistema personalizado y reutilizable de planificación y prompts, junto con 3–4 episodios cortos compilados; no compra videos finales garantizados, publicación, crecimiento de audiencia ni alojamiento de software. Los agentes de IA prestan asistencia conforme a los límites anteriores. El precio es de $1,250: $250 para la reserva y $1,000 tras la aceptación, ambos en USDC en Base y únicamente después de establecer un alcance escrito.
