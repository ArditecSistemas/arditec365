<h2 id="listado-partes"><a href="#/docs/modules/partes/partes?id=listado-partes" style="text-decoration:none;">▶️ Listado de Partes de Trabajo</a></h2>

En la pantalla principal del módulo de partes podemos visualizar un listado de todos los partes de trabajo. Por defecto, el sistema muestra aquellos que están en estado **Pendiente** y **Activo**.

![Listado de Partes de Trabajo](../../../_media/partes/Image%20001.png 'Imagen 1: Listado de Partes de Trabajo')

<h3 id="busqueda-filtros"><a href="#/docs/modules/partes/partes?id=busqueda-filtros" style="text-decoration:none;">Búsqueda y Filtros</a></h3>

Para localizar partes de trabajo específicos, existen dos opciones:

1.  **Búsqueda Rápida**: Escribir directamente en el campo "Buscar" para filtrar los resultados que se están mostrando en la tabla actual.
2.  **Filtro Avanzado**: Para búsquedas más complejas, se puede usar el filtro avanzado.

Para acceder al filtro avanzado, se puede hacer clic en el botón flotante verde y luego en "Filtrar partes", o bien directamente sobre la etiqueta azul "Hay filtros aplicados".

![Acceder a Filtros](../../../_media/partes/Image%20002.png 'Imagen 2: Acceder a Filtros')

Al abrirse, veremos un panel con múltiples opciones para acotar la búsqueda:

![Panel de Filtros Avanzados](../../../_media/partes/Image%20003.png 'Imagen 3: Panel de Filtros Avanzados')

- **Cliente**: Desplegable para seleccionar un cliente. (_Nota: Este filtro no está disponible para usuarios con rol "Técnico"_).
- **Estado**: Permite seleccionar uno o varios estados (Pendiente, Activo, Finalizado, Verificado, Cerrado).
- **Tags**: Filtra por las etiquetas asignadas a los partes.
- **Núm. Parte**: Busca un parte por su número identificador.
- **Responsable**: Filtra los partes asignados a un responsable concreto.
- **Técnico**: Filtra los partes asignados a un técnico concreto.
- **Fecha inicio / Fecha finalización**: Permite buscar partes dentro de un rango de fechas específico.

<h3 id="guardar-filtros"><a href="#/docs/modules/partes/partes?id=guardar-filtros" style="text-decoration:none;">Guardar y Restablecer Filtros por Defecto</a></h3>

Esta funcionalidad permite personalizar la vista por defecto del listado de partes.

- **Sobrescribir filtros**: Si se aplica una combinación de filtros de uso frecuente, se puede guardar como vista predeterminada. Para ello, se aplican los filtros deseados, se pulsa el menú de tres puntos (`⋮`) y se selecciona "Sobrescribir filtros" **antes** de darle a "Aceptar". A partir de ese momento, cada vez que se entre al listado de partes, se aplicará esta configuración.

- **Restablecer filtros**: Una vez que se han guardado filtros propios, aparecerá esta opción en el mismo menú. Se debe usar si se quiere volver a la configuración original de fábrica (estados Pendiente y Activo).

![Opciones de Filtro](../../../_media/partes/Image%20004.png 'Imagen 4: Opciones de Filtro')

---

<h2 id="crear-parte"><a href="#/docs/modules/partes/partes?id=crear-parte" style="text-decoration:none;">➕ Crear un Parte de Trabajo</a></h2>

Para crear un nuevo parte de trabajo, se debe hacer clic en el botón flotante verde y seleccionar la opción "Crear parte".

![Crear Parte](../../../_media/partes/Image%20005.png 'Imagen 5: Crear Parte')

Se abrirá un formulario solicitando la información esencial para dar de alta el parte:

![Formulario Nuevo Parte](../../../_media/partes/Image%20006.png 'Imagen 6: Formulario Nuevo Parte')

- **Cliente (`*`)**: Se selecciona el cliente para el cual se realiza el trabajo.
- **Delegación (`*`)**: Una vez escogido el cliente, se selecciona la delegación o dirección donde se realizará la intervención.
- **Concepto (`*`)**: Se escribe un resumen o título breve (máx. 35 caracteres) que describa el trabajo.
- **Responsable (`*`)**: Se asigna uno o más usuarios que serán los responsables de supervisar y gestionar el parte.

Tras rellenar los campos y pulsar "ACEPTAR", el sistema redirige al listado principal. El nuevo parte aparecerá en la lista en unos instantes. Se puede hacer clic sobre él para acceder a su detalle.

---

<h2 id="detalle-parte"><a href="#/docs/modules/partes/partes?id=detalle-parte" style="text-decoration:none;">📖 Detalle del Parte de Trabajo</a></h2>

Al entrar en un parte, la pantalla se divide en dos grandes áreas: la **cabecera del parte** y las **acciones o imputaciones**.

![Detalle del Parte](../../../_media/partes/Image%20007.png 'Imagen 7: Detalle del Parte')

<h3 id="cabecera-parte"><a href="#/docs/modules/partes/partes?id=cabecera-parte" style="text-decoration:none;">Cabecera del Parte</a></h3>

La sección superior contiene toda la información de gestión del parte, organizada en 6 pestañas:

- **📝 DATOS PARTE**: Información general, fechas, descripción de tareas y estado.
- **👥 ASIGNACIONES**: Gestión de responsables, técnicos y etiquetas.
- **🔩 MATERIALES**: Registro de los artículos y productos utilizados.
- **💶 GASTOS**: Imputación de gastos como dietas, kilometraje u otros costes.
- **📷 MEDIA**: Sube y visualiza imágenes relacionadas con la intervención.
- **📧 COMUNICACIONES**: Envía el informe PDF del parte a los contactos del cliente.

<h3 id="seccion-acciones"><a href="#/docs/modules/partes/partes?id=seccion-acciones" style="text-decoration:none;">Acciones / Imputaciones</a></h3>

La sección inferior, siempre visible, es el núcleo de la intervención. Aquí, los técnicos podrán imputar al detalle las intervenciones realizadas.

<h3 id="menu-opciones"><a href="#/docs/modules/partes/partes?id=menu-opciones" style="text-decoration:none;">Menú de Opciones</a></h3>

En la esquina superior derecha, un menú de tres puntos (`⋮`) da acceso a dos acciones globales:

![Menú de Opciones del Parte](../../../_media/partes/Image%20008.png 'Imagen 8: Menú de Opciones del Parte')

- **Descargar PDF**: Genera y descarga un informe completo del parte de trabajo.
- **Eliminar parte**: Permite eliminar el parte. (_Nota: Esta acción solo está disponible para Administradores. El parte no se borra de forma permanente, sino que se envía a una papelera de reciclaje por un tiempo determinado_).

Para salir de la vista de detalle y volver al listado, se debe pulsar la **X** en la esquina superior izquierda.

---

<h3 id="tab-datos-parte"><a href="#/docs/modules/partes/partes?id=tab-datos-parte" style="text-decoration:none;">📝 Pestaña: Datos Parte</a></h3>

Esta pestaña contiene la información fundamental del parte. Es una de las dos únicas pestañas que tiene un botón de **GUARDAR**.

Cuando un parte se acaba de crear, su estado es "Pendiente" y es necesario completar cierta información antes de poder activarlo.

![Datos del Parte - Pendiente](../../../_media/partes/Image%20009.png 'Imagen 9: Datos del Parte - Pendiente')

Para poder guardar por primera vez, se deberá:

1.  Establecer una **Fecha** y **Hora** de inicio.
2.  Rellenar el campo **A realizar (`*`)** con la descripción detallada de las tareas.
3.  Cambiar el **Estado (`*`)** a "Activo".

Una vez hecho esto, el botón **GUARDAR** se habilitará.

**Descripción de los campos:**

- **Concepto (`*`)**: Título principal del parte (heredado de la creación).
- **Delegación (`*`)**: Dirección de la intervención.
- **Fecha (`*`)** y **Hora (`*`)**: Momento de inicio planificado para el trabajo.
- **Fecha finalización**: Fecha estimada de finalización del parte.
- **Horas estimadas**: Total de horas previstas para el parte. Sirve para calcular una barra de progreso comparando lo estimado con las horas imputadas por los técnicos, muy útil para proyectos largos.
- **A realizar (`*`)**: Descripción detallada de las tareas a ejecutar.
- **Observaciones**: Anotaciones relevantes que serán visibles en el informe PDF para el cliente.
- **Observaciones internas**: Notas para el equipo interno, no visibles para el cliente.
- **Número de pedido**: Campo informativo para asociar un número de pedido del cliente.
- **Estado (`*`)**: El estado actual del flujo de trabajo del parte (Pendiente, Activo, Finalizado, etc.).

<h3 id="tab-asignaciones"><a href="#/docs/modules/partes/partes?id=tab-asignaciones" style="text-decoration:none;">👥 Pestaña: Asignaciones</a></h3>

Al igual que "Datos Parte", esta pestaña dispone de su propio botón de **GUARDAR** para aplicar los cambios realizados.

![Pestaña de Asignaciones](../../../_media/partes/Image%20010.png 'Imagen 10: Pestaña de Asignaciones')

Aquí se pueden gestionar:

- **Responsables (`*`)**: Modificar o añadir los usuarios que gestionan el parte.
- **Técnicos**: Asignar los técnicos que realizarán las intervenciones.
- **Tags**: Añadir o quitar etiquetas para categorizar y facilitar la búsqueda del parte de trabajo (p. ej., "Urgente", "Mantenimiento Preventivo", "Revisión Anual").

<h3 id="tab-materiales"><a href="#/docs/modules/partes/partes?id=tab-materiales" style="text-decoration:none;">🔩 Pestaña: Materiales</a></h3>

Desde esta sección se gestionan todos los artículos y productos consumidos durante la intervención. Si la lista es muy extensa, se puede utilizar la barra de "Buscar" para filtrar por cualquiera de los campos visibles.

![Listado de Materiales](../../../_media/partes/Image%20011.png 'Imagen 11: Listado de Materiales')

Para añadir un nuevo artículo, se debe pulsar el botón **"Insertar material"**. Se abrirá un formulario para introducir los detalles.

![Insertar Material](../../../_media/partes/Image%20012.png 'Imagen 12: Insertar Material')

**Campos del formulario:**

- **Almacén (`*`)**: Indica el almacén de origen del material. Es necesario seleccionar uno, incluso si no se lleva un control de stock activo.
- **Cód. producto (`*`)**: Código identificador del producto. Al seleccionarlo, se rellenará la descripción.
- **Producto**: Descripción del producto. Se puede editar, útil en el caso de usar artículos genéricos.
- **Facturable (`*`)**: Define si el coste de este material se repercutirá en la factura del cliente.
- **Unidades (`*`)**: Cantidad del producto utilizado.
- **Precio/u (`*`)**: Coste por cada unidad del producto.
- **Descuento**: Porcentaje de descuento a aplicar sobre el precio del producto.
- **Observaciones**: Cualquier nota o apunte adicional sobre el material.

Para **editar** un material, simplemente se debe hacer clic sobre su fila en el listado. Se abrirá un formulario idéntico al de inserción, pero con una diferencia clave: no se podrá modificar ni el `Almacén` ni el `Cód. producto`.

Si se necesita cambiar el producto, se deberá eliminar la línea actual desde el menú (`⋮`) y crear una nueva.

![Editar/Eliminar Material](../../../_media/partes/Image%20013.png 'Imagen 13: Editar/Eliminar Material')

> 💡 **Consejo:** Se recomienda tener un material genérico (ej: "MATERIALES VARIOS") para poder imputar artículos no catalogados, modificando el campo de descripción para detallar el concepto.

<h3 id="tab-gastos"><a href="#/docs/modules/partes/partes?id=tab-gastos" style="text-decoration:none;">💶 Pestaña: Gastos</a></h3>

Esta pantalla es muy similar a la de Materiales, pero está diseñada para registrar gastos asociados a la intervención que no son artículos de un almacén, como dietas, kilometraje, peajes o compras puntuales.

![Listado de Gastos](../../../_media/partes/Image%20014.png 'Imagen 14: Listado de Gastos')

Para registrar un nuevo gasto, se debe pulsar en **"Insertar Gasto"**.

![Insertar Gasto](../../../_media/partes/Image%20015.png 'Imagen 15: Insertar Gasto')

**Campos del formulario:**

- **Cód. producto (`*`)**: Selecciona el tipo de gasto (ej: "DIETAS", "KILOMETRAJE").
- **Producto**: Descripción del producto. Se puede editar, útil en el caso de usar gastos genéricos.
- **Comprado por (`*`)**: Indica qué técnico o usuario ha realizado el gasto.
- **Unidades (`*`)**: La cantidad del gasto (ej: 150 para km, 1 para una comida).
- **Coste (`*`)**: El valor monetario del gasto.
- **Facturable (`*`)**: Define si el gasto se debe facturar al cliente.
- **Liquidable**: Indica si el importe del gasto debe ser reembolsado al empleado.
- **Observaciones**: Espacio para añadir detalles adicionales sobre el gasto.

La **edición de un gasto** sigue la misma lógica que los materiales. Al hacer clic en una línea, se abre el formulario de edición. No se puede modificar el `Cód. producto`, pero sí el resto de campos. Para cambiar el tipo de gasto, es necesario eliminar la línea existente y crear una nueva.

![Editar/Eliminar Gasto](../../../_media/partes/Image%20016.png 'Imagen 16: Editar/Eliminar Gasto')

<h3 id="tab-media"><a href="#/docs/modules/partes/partes?id=tab-media" style="text-decoration:none;">📷 Pestaña: Media</a></h3>

En esta sección se pueden adjuntar y gestionar archivos multimedia relacionados con el parte de trabajo. Es ideal para documentar visualmente el estado de un equipo antes y después de una reparación, o para adjuntar pruebas gráficas de la intervención.

![Listado de Media](../../../_media/partes/Image%20017.png 'Imagen 17: Listado de Media')

Para subir un archivo, se debe hacer clic en **"Insertar Media"**. Se abrirá una ventana que permitirá seleccionar una o varias imágenes del dispositivo. Los formatos admitidos son `.png`, `.jpg` y `.jpeg`.

![Insertar Media](../../../_media/partes/Image%20018.png 'Imagen 18: Insertar Media')

> ⚠️ **Nota sobre el almacenamiento:** El espacio disponible para almacenar imágenes puede estar sujeto a los límites del plan de suscripción. Próximamente se implementarán herramientas para ayudar a gestionar el espacio de almacenamiento de forma eficaz.

Una vez subida, la imagen aparecerá en el listado. Si se hace clic sobre ella, se podrá ver en un tamaño mayor y se tendrá la opción de eliminarla a través del menú (`⋮`).

![Visualizar/Eliminar Media](../../../_media/partes/Image%20019.png 'Imagen 19: Visualizar/Eliminar Media')

---

<h2 id="acciones"><a href="#/docs/modules/partes/partes?id=acciones" style="text-decoration:none;">⚡ Acciones </a></h2>

> **Nota sobre la estructura del manual**
>
> Antes de continuar con la última pestaña de la cabecera (_Comunicaciones_), se procederá a explicar la sección inferior de **Acciones**. Se considera fundamental comprender primero cómo se registran las intervenciones, ya que estas constituyen el contenido principal del informe que se genera y envía desde la pestaña de Comunicaciones, la cual se detallará a continuación.

La sección de Acciones es el corazón del parte de trabajo. Aquí, los técnicos registran detalladamente cada una de las intervenciones, horas y tareas realizadas. Estos registros son cruciales, ya que conforman el cuerpo del informe que se enviará al cliente.

![Listado de Acciones](../../../_media/partes/Image%20020.png 'Imagen 20: Listado de Acciones')

Como en otras listas, se dispone de un campo de búsqueda para localizar rápidamente cualquier acción por los datos visibles.

Para registrar una nueva intervención, se debe hacer clic en **"Insertar Acción"**.

![Formulario Nueva Acción](../../../_media/partes/Image%20021.png 'Imagen 21: Formulario Nueva Acción')

**Campos del formulario (todos obligatorios):**

- **Técnico asignado (`*`)**: El técnico que ha realizado la tarea.
- **Facturable (`*`)**: Indica si las horas de esta acción deben ser facturadas al cliente.
- **Ámbito (`*`)**: Clasifica el área o el tipo de contrato al que pertenece la acción (p.ej. Mantenimiento general, Proyecto, etc.).
- **Tipo acción (`*`)**: Especifica el tipo de horas (p.ej. Horas Normales, Horas Extra).
- **Fecha (`*`)**: El día en que se realizó el trabajo.
- **Inicio (`*`)** y **Fin (`*`)**: Hora de comienzo y finalización de la tarea. La duración se calculará automáticamente.
- **Comentarios (`*`)**: Descripción detallada del trabajo realizado. Se recomienda ser muy específico en este campo, ya que esta información será clave para el cliente.

Para **editar** una acción, se debe hacer clic sobre su fila. Se abrirá el mismo formulario con los datos cargados. Dentro de este, un menú (`⋮`) dará dos opciones adicionales:

![Opciones de Acción](../../../_media/partes/Image%20022.png 'Imagen 22: Opciones de Acción')

- **Eliminar acción**: Borra la imputación de forma permanente.
- **Duplicar acción**: Crea una nueva acción con los mismos datos que la actual. Es muy útil para agilizar la entrada de trabajos similares. Al duplicar, aparecerá un aviso en la parte superior del formulario para indicar que se está creando una copia.

![Duplicar Acción](../../../_media/partes/Image%20023.png 'Imagen 23: Duplicar Acción')

---

<h2 id="tab-comunicaciones"><a href="#/docs/modules/partes/partes?id=tab-comunicaciones" style="text-decoration:none;">📧 Pestaña: Comunicaciones</a></h2>

> **Nota sobre la estructura del manual**
>
> Recomendamos visitar la sección de **Acciones** antes de visitar la pestaña de **Comunicaciones**. Se considera fundamental comprender primero cómo se registran las intervenciones, ya que estas constituyen el contenido principal del informe que se genera y envía desde la pestaña de Comunicaciones, la cual se detallará a continuación.

En esta última pestaña se podrá enviar el informe del parte de trabajo al cliente y consultar un registro histórico de todas las comunicaciones enviadas.

![Pestaña Comunicaciones](../../../_media/partes/Image%20024.png 'Imagen 24: Pestaña Comunicaciones')

<h3 id="gestion-destinatarios"><a href="#/docs/modules/partes/partes?id=gestion-destinatarios" style="text-decoration:none;">Gestión de Destinatarios</a></h3>

El sistema permite una gestión flexible de los destinatarios:

- **Contactos del cliente**: Por defecto, el desplegable "Contactos" se cargará con los emails de contacto que estén registrados en la ficha del cliente. Si el cliente no tiene contactos informados, se verá un aviso.
- **Con copia a**: Se pueden añadir manualmente cualquier otra dirección de correo. Simplemente se escribe el email y se pulsa la tecla "Enter" para añadirlo a la lista.
- **Selección de destinatarios**: Se tiene control total sobre quién recibe el informe en cada envío. Se puede desmarcar un contacto principal de la lista o eliminar un correo añadido en copia si se decide no enviárselo en ese momento.

![Gestión de Destinatarios](../../../_media/partes/Image%20025.png 'Imagen 25: Gestión de Destinatarios')

> 💡 **Consejo:** Si se detecta que el contacto por defecto de un cliente es incorrecto en el momento de realizar el envío, se recomienda eliminarlo de la lista para ese envío, añadir el email correcto en "Con copia a", enviar el parte, y posteriormente acceder a la ficha del cliente para actualizar sus datos de contacto.

<h3 id="proceso-envio-firma"><a href="#/docs/modules/partes/partes?id=proceso-envio-firma" style="text-decoration:none;">Proceso de Envío y Firma</a></h3>

Una vez configurados los destinatarios y decidido si se quiere **"Incluir media como elemento adjunto al correo"**, existen dos opciones:

1.  **Enviar directamente**:
    Pulsar el botón **"ENVIAR"**. El sistema pedirá una última confirmación, mostrando la lista final de destinatarios antes de proceder con el envío.

    ![Confirmación de Envío](../../../_media/partes/Image%20027.png 'Imagen 27: Confirmación de Envío')

2.  **Firmar y Enviar**:
    Este proceso permite que el cliente firme digitalmente el parte como prueba de conformidad antes de recibirlo.

    > ⚠️ **Nota:** El proceso de firma digital está en constante mejora y es posible que su funcionamiento actual varíe en futuras actualizaciones para incorporar nuevas funcionalidades.

    - **Paso 1: Iniciar Firma.** Pulsar el botón **"FIRMAR"**.

      ![Iniciar Firma](../../../_media/partes/Image%20028.png 'Imagen 28: Iniciar Firma')

    - **Paso 2: Previsualizar Informe.** Se abrirá una previsualización del informe en PDF. Para garantizar que el cliente ha revisado el contenido, el botón **"SIGUIENTE"** permanecerá desactivado hasta que se haya hecho scroll hasta el final del documento.

      ![Previsualización PDF - Botón desactivado](../../../_media/partes/Image%20029.png 'Imagen 29: Previsualización PDF - Botón desactivado')

    - **Paso 3: Habilitar Siguiente.** Una vez revisado todo el informe, el botón **"SIGUIENTE"** se activará, permitiendo continuar hacia el paso final de la firma.

      ![Previsualización PDF - Botón activado](../../../_media/partes/Image%20030.png 'Imagen 30: Previsualización PDF - Botón activado')

    - **Paso 4: Captura de Firma y Datos.** Al pulsar "SIGUIENTE", se mostrará la pantalla final para la recogida de la firma. Aquí, el representante del cliente deberá introducir su nombre y, opcionalmente, su DNI/NIE. Luego, podrá firmar directamente en el recuadro digital.

      ![Captura de Firma](../../../_media/partes/Image%20031.png 'Imagen 31: Captura de Firma')

    - **Opciones de Firma:** Desde el menú (`⋮`) en esta pantalla, el cliente tiene dos opciones:

      - **Restablecer**: Borra el dibujo de la firma para poder volver a realizarla.
      - **No conforme**: Si el cliente no está de acuerdo con el parte, puede seleccionar esta opción. Al hacerlo, se estampará un sello de "NO CONFORME" en el lugar de la firma, dejando constancia de su disconformidad.

      ![Opciones de Firma y No Conforme](../../../_media/partes/Image%20032.png 'Imagen 32 y 33: Opciones de Firma y No Conforme')

    - **Paso 5: Finalizar y Enviar.** Una vez introducidos los datos y realizada la firma (o marcada la no conformidad), al pulsar **"FIRMAR Y ENVIAR"** se mostrará la ventana de confirmación final con los destinatarios antes de que el parte se envíe definitivamente.

<h3 id="geolocalizacion-firma"><a href="#/docs/modules/partes/partes?id=geolocalizacion-firma" style="text-decoration:none;">Geolocalización para evidencias de firma</a></h3>

La primera vez que se utilice la función de firma en un nuevo dispositivo o navegador, la aplicación solicitará permiso para acceder a la ubicación.

![Solicitud de Ubicación](../../../_media/partes/Image%20033.png 'Imagen 33: Solicitud de Ubicación')

> ⚠️ **Nota:** La recogida de la ubicación se realiza para añadir una capa extra de evidencia al proceso de firma. Esta funcionalidad se encuentra en desarrollo activo y puede estar sujeta a cambios en el futuro.
