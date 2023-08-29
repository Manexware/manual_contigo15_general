![Logo Contigo](/assets/img/contigo_logo.png)
# Manual General Sistema Contigo

## Índice de Contenido
- [Manual General Sistema Contigo](#manual-general-sistema-contigo)
  - [Índice de Contenido](#índice-de-contenido)
  - [1. Prerrequisitos](#1-prerrequisitos)
    - [1.1 Información Básica](#11-información-básica)
    - [1.2 Información de Correo](#12-información-de-correo)
    - [1.3 Archivos de Importación](#13-archivos-de-importación)
  - [2. Configuración Inicial](#2-configuración-inicial)
    - [2.1 Creación de Usuarios](#21-creación-de-usuarios)
  - [3. Primeros Pasos](#3-primeros-pasos)
  - [4. Contabilidad](#4-contabilidad)
  - [5. Algunos de Nuestros Clientes](#5-algunos-de-nuestros-clientes)
  - [6. Contactanos](#6-contactanos)

## 1. Prerrequisitos

### 1.1 Información Básica
- Información de la compañía: RUC del SRI (PDF)
- Firma electrónica formato archivo .p12 y contraseña
- Habilitar emisión de documentos electrónicos en el portal de SRI
- Nombre para el subdominio ejemplo miempresa.manexware.com
- Lista de Usuarios – Nombres completos y correo electrónico 
- Logo de la compañía en formato png

### 1.2 Información de Correo
- Servidor SMTP - ejemplo: smtp.dominio.com
- Puerto SMTP - ejemplo: 465
- Usuario
- Contraseña

### 1.3 Archivos de Importación
- Excel de Contactos
- Excel de Productos

## 2. Configuración Inicial

### 2.1 Creación de Usuarios
__Datos del usuario__: Esta tarea solo puede ser realizada por el administrador, debe dirigirse al módulo de __Ajustes__, seleccionar en el menú la opción __Usuarios y Compañías__ y seguido la opción __Usuarios__.
Para crear un usuario, se debe llenar los campos Nombre, Dirección de email y foto (opcional) con un tamaño máximo de 1024x1024px.
![submenu ajustes](/assets/img/datosusuario.png)
__Activación del usuario__: En la esquina superior del mismo formulario nos encontraremos con un recuadro que indica si el usuario creado ha confirmado su inicio de sesión, caso contrario, se mostrará “nunca se conecta”.
<p align="center">
  <img src="/assets/img/nuncaseconecta.png">
</p>

Esta barra de estado nos indicará si el usuario no se ha conectado desde su creación, pero en el caso de que se haya conectado, la barra cambiará de “Nunca se conecta” a “Confirmado”.
<p align="center">
  <img src="/assets/img/confirmadouser.png">
</p>

__Permisos de acceso__: Parte fundamental del sistema, que se encarga de la administración de los privilegios del usuario; dependiendo de los permisos concedidos, el usuario realizará o no actividades en el sistema.

![submenu ajustes](/assets/img/permisosaccess.png)

__Tiendas__: El sistema permite gestionar las sucursales en que el usuario se encuentra actualmente, para más información de las sucursales revisar la opción __Agencia__.

![submenu ajustes](/assets/img/agencies.png)
__Preferencias__: Nos permite seleccionar para cada usuario el idioma, la zona horaria, el medio de entrega de notificaciones, la plantilla de firma y la firma digital(opcional).
![submenu ajustes](/assets/img/preferencias.png)
__Seguridad de la cuenta__: Nos permite seleccionar la autenticación de dos pasos para proteger la cuenta.
![submenu ajustes](/assets/img/security.png)
__Acciones__: Nos permite archivar, suprimir, duplicar y cambiar la contraseña de dicho usuario, desactivar la autenticación de dos pasos y también nos permite ayudar al usuario a recuperar su contraseña enviando instrucciones para el restablecimiento de la misma.
<p align="center">
  <img src="/assets/img/acciones.png">
</p>

En caso de cambiar la contraseña se abrirá una ventana emergente, donde se deberá digitar la nueva contraseña y seguidamente guardar los nuevos datos.
![submenu ajustes](/assets/img/changepassword.png)

En la parte superior, antes de las opciones de crear o editar usuario tenemos una barra que permite “Enviar un correo de invitación”:
<p align="center">
  <img src="/assets/img/correoinvitacion.png">
</p>

Al usuario se le enviará por correo una invitación para que ingrese al sistema, si todo sale bien y la invitación se envía con éxito mostrará un mensaje confirmando dicha acción.

__Nota Importante__: Antes de enviar el correo de invitación, primero se debe configurar el correo saliente del sistema; para más información revisar Configuración de __Correo Saliente__.

### 2.2 Plan Contable
Debe dirigirse al módulo de __Contabilidad__, seleccionar el menú de __Configuración__, buscar el apartado de __Contabilidad__ y seleccionar la opción __Plan de Cuentas__.

El plan contable en Ecuador es un conjunto de normas y directrices que regulan la forma en que las entidades deben registrar y presentar sus transacciones financieras y contables. Basado en estándares internacionales adaptados a las regulaciones locales, el plan define cuentas contables, códigos numéricos, reglas de registro y formatos de estados financieros. Su objetivo es estandarizar la información contable para facilitar la comparabilidad y comprensión de los estados financieros por parte de diversos usuarios. Este plan puede actualizarse para reflejar cambios en las normativas y necesidades locales, y es esencial para mantener la precisión e integridad de la información financiera.

Estas cuentas deben estar ordenadas y codificadas de forma sistemática para facilitar la contabilidad.  Además, permite que todas las cuentas y registros sean presentados y visualizados con la finalidad de verificarlos.  De esa forma, se elaboran con facilidad los estados financieros.
![submenu ajustes](/assets/img/planctauno.png)
El sistema Contigo tiene los datos básicos del plan contable, pero es necesario verificar cuáles son las cuentas contables que utilizará la empresa; en el caso de que se necesite añadir más cuentas contables, se debe seguir la secuencia correspondiente del código.

En el caso de querer visualizar más información respecto a una cuenta en específico, deberá dar clic al botón “Configurar”, de esta manera se abrirá una vista formulario en el cual podrá visualizar tanto el código, el nombre de la cuenta, el tipo de la misma, pero habrá campos adicionales como:
![submenu ajustes](/assets/img/planctados.png)
![submenu ajustes](/assets/img/planctatres.png)

__Tipo__: Aquí se define el tipo de cuenta, ya sean capitales, activos, pasivos; cabe recalcar que las cuentas por cobrar y pagar deberán definirse de manera correcta y darle el respectivo permiso de conciliación.

__Impuestos determinados__: En esta opción se mostrará diferentes porcentajes de impuesto a usar si son compras o ventas.

__Etiquetas__: Ayuda a definir qué tipo de actividad es, ya sea de operaciones, financiera o actividades extraordinarias.

__Diarios permitidos__: Se definen los diarios contables que pueden ser usados dentro de ese plan contable. Si se llena esta opción sólo podrán usar dichas cuentas siempre y cuando el asiento contable posea dicho diario.

__Obsoleto__: De igual manera no es posible eliminar una cuenta una vez que se haya registrado una transacción en ella. Puede hacerla inutilizable deberá marcar el check de __“Obsoleto”__.

__Grupo__: Se define automáticamente, en este apartado se define a qué grupo de cuenta pertenece (grupo previamente creado).

__Centralizado__:  En el caso de que se desee que se muestren los detalles de la cuenta en el libro mayor, deberá marcar esta opción.

El sistema Contigo permite de igual manera visualizar las cuentas según su nivel, el nivel lo define de manera automática siempre y cuando se digite el código de la cuenta contable.
<p align="center">
  <img src="/assets/img/nivelescta.png">
</p>
Por ejemplo, en la imagen de arriba solo se están visualizando las cuentas nivel 1.

### 2.3 Grupos de cuentas
Debe dirigirse al módulo de __Contabilidad__, seleccionar el menú de __Configuración__, buscar el apartado de __Contabilidad__ y seleccionar la opción __Grupos de Cuentas__.

Los grupos de cuentas sirven para listar múltiples cuentas como subcuentas de una cuenta más grande y, por lo tanto, consolidar reportes como la balanza de comprobación. De forma predeterminada, los grupos se gestionan según el código del grupo.

Para la creación de un grupo de cuentas, se deberá definir el nombre de la misma y el prefijo de esta; dependiendo de los dígitos seleccionados al momento de guardar el registro el sistema enlazará todas las cuentas contables que posean dicho prefijo.

![submenu ajustes](/assets/img/grupoctas.png)

### 2.4 Impuestos
Esta tarea solo puede ser realizada por el administrador, debe dirigirse al módulo de __Contabilidad__, seleccionar el menú de __Configuración__, buscar el apartado de __Contabilidad__ y seleccionar la opción __Impuestos__.

Los impuestos son tributos que cada persona, familia o empresa debe pagar al Estado para costear las necesidades colectivas, contribuyendo así con una parte de sus ingresos.

Al momento de crear un nuevo impuesto es necesario agregar el nombre del impuesto, si se desea se puede añadir un nombre corto y seleccionar el ámbito de este (ventas, compras, ninguno y ajustes).

![submenu ajustes](/assets/img/impuestosuno.png)
__Definición__: Esta pestaña nos ayuda a determinar el cálculo del impuesto, su importe, la cuenta de impuestos y la cuenta de impuestos para las notas de crédito.
![submenu ajustes](/assets/img/impuestosdos.png)
__Opciones avanzadas__: Esta opción nos permite añadir la etiqueta de factura, el grupo de impuestos, si se debe incluir en el precio, si tiene base imponible y añadir más etiquetas para reconocimiento de este.
![submenu ajustes](/assets/img/impuestostres.png)
__Código de impuestos__: Nos permite ingresar el código base y el código de impuestos para las ventas y compras; de la misma manera el reembolso de ventas y compras con la diferencia del código de devoluciones.     

![submenu ajustes](/assets/img/impuestosfour.png)


### 2.5 Información de la compañía 
Esta tarea solo puede ser realizada por el administrador, debe dirigirse al módulo de __Administración__, seleccionar la opción __Compañías__.
Por defecto hay un registro con el nombre de My Company (Rio Tinto Group), es necesario ingresar a dicho registro para poder configurar con los respectivos datos de la empresa.

Proceden a llenar cada uno de los campos con su respectiva información según la empresa, especialmente los campos obligatorios empezando por el nombre de la compañía.

![submenu ajustes](/assets/img/companyuno.png)

__Información General__: Se debe registrar todos los datos de la compañía y si la compañía posee factura electrónica, llenar en el sistema sus respectivos campos para su posterior utilización.

![submenu ajustes](/assets/img/companydos.png)

![submenu ajustes](/assets/img/companytres.png)

![submenu ajustes](/assets/img/companyfour.png)

__Contabilidad__: Nos permite indicar al sistema las retenciones, sustentos tributarios, las cuentas contables y la cuenta de transferencia entre bancos que la empresa utiliza para toda su actividad contable.
![submenu ajustes](/assets/img/contuno.png)

![submenu ajustes](/assets/img/contdos.png)

![submenu ajustes](/assets/img/contres.png)

![submenu ajustes](/assets/img/contfour.png)

![submenu ajustes](/assets/img/contfive.png)

![submenu ajustes](/assets/img/contseis.png)

![submenu ajustes](/assets/img/contsiete.png)

![submenu ajustes](/assets/img/contocho.png)

## 3. Primeros Pasos

## 4. Contabilidad

## 5. Algunos de Nuestros Clientes

## 6. Contactanos
