### *Glosario* ###

**Introducción**

Este documento planea ser una fuente de definiciones de los términos utilizados en los restantes archivos de documentacion y del dominio naval, a fin de orientar al usuario lector en la introducción al Sistema de Control de Ingresos desarrollado para BASE NAVAL PUERTO BELGRANO CARGO CONTRA-INTELIGENCIA.

El esquema de las definiciones consiste en una enumeración de los términos, y sus entradas correspondientes con el siguiente formato:

* Definición del término
* Aclaraciones importantes en caso de ser necesario
* Entidades relacionadas con el concepto

**Terminología**

### Registro 
Entidad central del sistema. Representa los datos personales de una persona que tiene o puede tener acceso a la BNPB (nombre, documento, nacionalidad, domicilio, foto, observaciones, etc.).

Un Registro no implica que la persona haya ingresado ni que tenga un pase vigente. Es simplemente la ficha de la persona en el sistema.

**Entidades relacionadas:** Ingresos, PATs, Vinculaciones.

### Ingreso 
Forma de registrar el momento en el que una persona ingresa y sale del establecimiento. Brinda información detallada sobre la hora de ambos sucesos, que luego puede ser recolectada para generar un informe sobre la persona especificada o sobre otro criterio de agrupación de entidades.

Una persona puede tener muchos ingresos --> detallar 

**Entidades relacionadas:** Ingresos por el Día, PAT, Listado de Ingreso, Zona Reservada.

### Ingreso por el Día 
Modalidad de ingreso para visitas que no poseen el Pase de Acceso Transitorio (PAT) con una duración máxima de 24 horas.

El registro del ingreso comienza cuando el ingresante otorga su documento de identificación, recibiendo a cambio una tarjeta temporal; y finaliza cuando la persona desea retirarse del establecimiento, momento en el cual se le retorna su documento de identificación y se registra en el sistema la hora de salida.

**Entidades relacionadas:** PAT, Oficina de Zona Reservada, Oficina de Zona Restringida.

### PAT Pase de Acceso Transitorio. 
Documento físico utilizado para autorizar el acceso recurrente a la BNPB, solicitado en el Puesto 1°; en caso de que la persona no posea uno, se lo registrará en el sistema previo a otorgarle el documento.

Se le pueden atribuir diferentes diseños de impresión, para los cuales se ingresan diferentes datos relevantes a la autorización del pase de la persona. Los datos que se encuentran en cada diseño están relacionados con la identificacion de la persona titular y los motivos por los cuáles frecuenta el ingreso al establecimiento.

Posee una fecha de vencimiento definida por el solicitante, además del detalle de la zona en donde la persona estará desarrollando sus actividades.

**Entidades relacionadas:** Solicitante, Autorizante, Titular, Diseño PAT.

### Diseño PAT 
Plantilla visual del Pase de Acceso Transitorio confeccionada a medida por el solicitante.

El solicitante tiene al alcance herramientas de edición para el canvas del proyecto como previsualización del diseño a imprimir, selección de variables; que lo ayudarán a documentar el ingreso de la persona de una manera organizada. 

**Entidades relacionadas:** Canvas, Variables, Solicitante.

### Solicitante 
Persona que solicita un PAT para otra (el titular). No es quien lo recibe.

### Autorizante 
Persona que aprueba el otorgamiento del PAT. Distinto del solicitante.

### Titular del PAT 
La persona que recibe y usa el PAT. Tiene un Registro en el sistema.

### Zona Restringida 
a veces llamada Zona Comun, es una Zona de acceso controlado manejada por el Puesto 1° / Oficina PEN.

### Zona Reservada 
Zona de mayor restricción, manejada por operadores militares.

### BNPB 
Base Naval Puerto Belgrano.

### PEN 
Personal Establecimientos Navales. Conformado principalmente por policias dentro de la BNPB.

### Vinculación 
Relación formal de una persona con la BNPB (empleado, proveedor, familiar, etc.). La gestiona la Oficina de Vinculaciones.

### Novedad
Observación o alerta asociada a un Registro. Puede indicar restricciones de acceso.

### Listado de Ingreso 
Modalidad para registrar grupos de personas que ingresan juntas (ej: operarios de una empresa).

### Usuario 
Usuario del sistema, crea registros/ingresos/pases etc. pertenece a una organizacion.

### Organizacion 
Determina a que organizacion u oficina pertenece el usuario. Por ende los permisos y funciones a las cuales puede acceder.
