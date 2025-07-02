<h2 id="partes-setup"><a href="#/docs/modules/partes/setup?id=partes-setup" style="text-decoration:none;">🔧 Mantenimientos de Partes de Trabajo</a></h2>

Este módulo central de la aplicación permite la gestión y visualización de diversas entidades esenciales para la operativa de los partes de trabajo. Aunque algunas secciones están en proceso de implementación para su edición, ya es posible visualizar los datos.

Dentro del módulo "**Partes de trabajo**", se pueden gestionar las siguientes secciones:

- **Clientes**
- **Tags**
- **Productos**
- **Ámbitos**
- **Almacenes**

![Listado de Partes de Trabajo](../../../_media/partes/setup/Image%20001.png 'Imagen 1: Menú mantenimientos')

---

<h3 id="tab-clientes"><a href="#/docs/modules/partes/setup?id=tab-clientes" style="text-decoration:none;">👥 Clientes</a></h3>

La sección de **Clientes** permite visualizar la información de los clientes registrados en el sistema.

> ℹ️ Actualmente, esta sección solo permite la visualización informativa de los clientes registrados en Sage200c, sin posibilidad de alta ni edición.

![Listado clientes](../../../_media/partes/setup/Image%20002.png 'Imagen 2: Listado clientes')

Al hacer clic en un cliente específico en la tabla, se abre una ventana con tres pestañas detalladas, explicadas a continuación:

- Información
- Contactos
- Notificaciones

#### Información

Esta pestaña muestra la información básica del cliente, como el Código de Cliente, la Razón Social y el Nombre. Esta información es de solo lectura.

![información básica cliente](../../../_media/partes/setup/Image%203.png 'Imagen 3: información básica cliente')

#### Contactos

En esta sección se listan los contactos asociados al cliente. Es importante destacar que esta pestaña es de **solo lectura**. Si no hay contactos informados para el cliente, se mostrará un aviso indicando esta situación.

![contactos cliente](../../../_media/partes/setup/Image%204.png 'Imagen 4: contactos cliente')

#### Notificaciones

> ⚠️ Por defecto, las notificaciones a clientes están desactivadas de forma global. Se está trabajando en una página donde configurar esta y otras opciones.
>
> Aunque aparezca la notificación activa en un cliente, esta no tiene efecto hasta que se solicite la activación global de las notificaciones y estas se activen manualmente.

La pestaña de **Notificaciones** permite activar o desactivar las notificaciones destinadas a los clientes. Actualmente, la única notificación disponible es la que se envía al crear un parte de trabajo. A diferencia de las otras pestañas, esta sección es editable y cuenta con un botón "**Aceptar**" para guardar los cambios.

![notificaciones cliente](../../../_media/partes/setup/Image%205.png 'Imagen 5: notificaciones cliente')

---

<h3 id="tab-tags"><a href="#/docs/modules/partes/setup?id=tab-tags" style="text-decoration:none;"> 🏷️ Tags</a></h3>

El apartado de **Tags** (etiquetas) permite gestionar todas las etiquetas utilizadas en la aplicación. Estas etiquetas son fundamentales para categorizar los partes de trabajo y facilitar futuros filtros y búsquedas.

![listado tags](../../../_media/partes/setup/Image%206.png 'Imagen 6: listado tags')

Una característica importante de las etiquetas es que pueden pertenecer a otra etiqueta (etiqueta padre), lo que permite una organización jerárquica. La visualización en la tabla ya refleja esta relación.

#### Crear un Nuevo Tag

Para crear un nuevo tag, se debe hacer clic en el botón flotante "**Crear Tag**" ubicado en la esquina inferior derecha.

Al pulsar este botón, se abrirá un formulario donde se deberá introducir:

- **Nombre de la etiqueta**: El nombre de la nueva etiqueta.
- **Vinculada a**: Si la etiqueta pertenece a otra etiqueta padre.

El color de la etiqueta se asigna aleatoriamente por defecto, pero se proporciona un selector de colores para modificarlo si se desea.

![crear tag](../../../_media/partes/setup/Image%207.png 'Imagen 7: crear tag')

#### Editar o Eliminar un Tag

Una vez creada una etiqueta, al pasar el ratón por encima de ella en la tabla, aparecerá un botón de edición a la derecha. Debido a la visualización especial de las etiquetas, no se puede hacer clic directamente sobre el elemento para editarlo como en otras páginas.

Al hacer clic en el botón de edición, se abrirá un formulario similar al de creación de etiqueta, donde se podrá modificar cualquiera de sus datos (nombre, vinculación y color). Además, se podrá eliminar la etiqueta pulsando en el menú de tres puntos (`⋮`).

![editar tag](../../../_media/partes/setup/Image%208.png 'Imagen 8: editar tag')

![editar tag2](../../../_media/partes/setup/Image%208,5.png 'Imagen 8.5: editar tag2')

---

<h3 id="tab-productos"><a href="#/docs/modules/partes/setup?id=tab-productos" style="text-decoration:none;"> 🛒 Productos</a></h3>
En el apartado de **Productos**, es posible visualizar una tabla con los artículos que han sido dados de alta en el sistema.

> Actualmente, esta sección solo permite la visualización informativa de los artículos registrados en Sage200c, sin posibilidad de edición.

![listado de productos](../../../_media/partes/setup/Image%209.png 'Imagen 9: listado de productos')

---

<h3 id="tab-ambitos"><a href="#/docs/modules/partes/setup?id=tab-ambitos" style="text-decoration:none;"> 📋 Ámbitos</a></h3>
La sección de **Ámbitos** permite gestionar las categorías que se utilizarán para clasificar las acciones vinculadas a los partes de trabajo. Estas categorías son esenciales para una organización eficiente de las acciones imputadas.

![listado de ambitos](../../../_media/partes/setup/Image%2010.png 'Imagen 10: listado de ambitos')

#### Agregar un Nuevo Ámbito

Para añadir un nuevo ámbito, se debe hacer clic en el botón flotante "**Insertar ámbito**" ubicado en la esquina inferior derecha de la pantalla.

Al pulsar el botón, se abrirá un formulario sencillo donde solo se deberá introducir el **Nombre del Ámbito**.

![crear ambito](../../../_media/partes/setup/Image%2011.png 'Imagen 11: crear ambito')

#### Editar o Eliminar un Ámbito

Para editar un ámbito existente, se debe hacer clic sobre su nombre en la tabla. Se abrirá la misma pantalla de edición con el campo "**Ámbito**" precargado con el nombre actual. Desde esta ventana, también se tendrá la opción de **Eliminar** el ámbito si se desea.

![editar ambito](../../../_media/partes/setup/Image%2012.png 'Imagen 12: editar ambito')

---

<h3 id="tab-almacenes"><a href="#/docs/modules/partes/setup?id=tab-almacenes" style="text-decoration:none;"> :department_store: Almacenes</a></h3>

En el apartado de **Almacenes**, se muestran todos los almacenes registrados en el sistema. Actualmente, esta sección es de **solo visualización**, lo que significa que no es posible crear nuevos almacenes desde aquí.

![listado almacenes](../../../_media/partes/setup/Image%2013.png 'Imagen 13: listado almacenes')

#### Editar Usuarios con Acceso a Almacenes

Aunque no se pueden crear almacenes, sí es posible editar los usuarios que tienen acceso a cada uno de ellos. Al hacer clic en un almacén en la tabla, se abrirá una ventana que permite modificar la lista de usuarios asociados.

Es importante tener en cuenta que los usuarios con perfil de administrador tienen acceso a todos los almacenes por defecto y, por lo tanto, no aparecerán en la selección de usuarios para almacenes específicos. El resto de los usuarios sí estarán disponibles para ser asignados. Los usuarios técnicos o responsables solo podrán incluir materiales de los almacenes a los que tengan acceso.

![usuarios almacenes](../../../_media/partes/setup/Image%2014.png 'Imagen 14: usuarios almacenes')
