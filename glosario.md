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

Una sola persona (Registro) puede poseer un historial extenso de múltiples ingresos a lo largo del tiempo.

**Entidades relacionadas:** Ingresos por el Día, PAT, Listado de Ingreso, Zona Reservada.

### Ingreso por el Día 
Modalidad de ingreso para visitas que no poseen el Pase de Acceso Transitorio (PAT) con una duración máxima de 24 horas.

El registro del ingreso comienza cuando el ingresante otorga su documento de identificación, recibiendo a cambio una tarjeta temporal; y finaliza cuando la persona se retira del establecimiento, momento en el cual se le retorna su documento de identificación y se registra en el sistema la hora de salida.

**Entidades relacionadas:** PAT, Oficina de Zona Reservada, Oficina de Zona Restringida.

### PAT Pase de Acceso Transitorio. 
Documento físico confeccionado por la Oficina de Pases, utilizado para autorizar el acceso recurrente a la BNPB. 

Se lo solicita en el Puesto 1°; en caso de que la persona no posea uno, se lo registrará en el sistema previo a otorgarle el documento.

Se le pueden atribuir diferentes diseños de impresión, para los cuales se ingresan datos necesarios para la autorización del pase de la persona. Los datos que se encuentran en cada diseño están relacionados con la identificacion de la persona titular y los motivos por los cuáles frecuenta el ingreso al establecimiento.

Posee una fecha de vencimiento definida por la persona autorizante, además del detalle de la zona en donde la persona estará desarrollando sus actividades.

**Entidades relacionadas:** Solicitante, Autorizante, Titular, Diseño PAT.

### Diseño PAT 
Plantilla visual del Pase de Acceso Transitorio confeccionada por la Oficina de Pases.

La misma tiene al alcance herramientas de edición para el canvas del proyecto como previsualización del diseño a imprimir, selección de variables; que ayudarán a documentar el ingreso de la persona de una manera organizada. 

**Entidades relacionadas:** Canvas, Variables, Solicitante.

### Solicitante 
Persona que requiere o tramita la solicitud de un PAT para un tercero (el titular).  

No es quien recibe ni hace uso del pase físico, sino el responsable de iniciar el requerimiento de acceso.

**Entidades relacionadas:** PAT, Titular del PAT, Autorizante.

### Autorizante 
Persona que tiene la autoridad y responsabilidad de aprobar el otorgamiento de un PAT a un titular.  

Es una figura distinta a la del solicitante y su validación es indispensable para que el pase pueda ser confeccionado y posteriormente impreso.  

**Entidades relacionadas:** PAT, Solicitante, Titular del PAT.

### Titular del PAT 
Persona física que recibe, porta y hace uso del Pase de Acceso Transitorio.  

Para poder ser titular de un PAT, la persona debe contar obligatoriamente con un Registro activo en el sistema.  

**Entidades relacionadas:** PAT, Registro.

### Zona Restringida 
Área de acceso controlado dentro de la base naval.  

A veces es llamada Zona Común, y sus accesos e ingresos son operados y manejados principalmente por el Puesto 1° y la Oficina de Zona Restringida (Operadores PEN).  

**Entidades relacionadas:** Ingreso, PEN.

### Zona Reservada 
Área de la base naval con un nivel de restricción y seguridad mayor que la Zona Restringida.

El control de ingreso a esta zona es administrado por la Oficina de Zona Reservada, la cual es operada exclusivamente por operadores militares.  

**Entidades relacionadas:** Ingreso, PAT.

### BNPB 
Siglas correspondientes a la Base Naval Puerto Belgrano.

**Entidades relacionadas:** Cargo Contrainteligencia, Zona Reservada, Zona Restringida.

### PEN 
Siglas correspondientes al Personal Establecimientos Navales.  

Está conformado principalmente por personal policial u operadores civiles que cumplen tareas de control y vigilancia en los accesos de la BNPB, en particular en la Zona Restringida.  

**Entidades relacionadas:** Zona Restringida.

### Vinculación 
Relación formal y documentada que mantiene una persona con la BNPB (puede ser empleado, proveedor, familiar, empresa, etc.).  

El seguimiento y administración de estas relaciones es llevado a cabo por la Oficina de Vinculaciones. 

**Entidades relacionadas:** Registro, PEN, Civil, Personal de Vinculaciones.

### Novedad
Observación, alerta o aviso de seguridad asociado directamente a un Registro.  

Puede indicar restricciones de acceso o llamados de atención que el sistema debe advertir mediante alertas visuales cuando un operador consulta el registro.  

**Entidades relacionadas:** Registro.

### Listado de Ingreso 
Modalidad del sistema diseñada para facilitar el registro en bloque de un grupo de personas que ingresan juntas al establecimiento por un motivo en común (por ejemplo, operarios de una empresa contratista).  

El sistema permite el ingreso masivo mediante planillas con formato estandarizado para agilizar el proceso.  

**Entidades relacionadas:** Ingreso, Registro.

### Usuario 
Persona física u operador que utiliza el sistema de gestión.  

Para acceder, debe autenticarse utilizando un identificador único (idealmente DNI) y una contraseña encriptada . El usuario puede crear registros, registrar ingresos o generar pases, siempre limitado por los permisos de su rol.  

**Entidades relacionadas:** Organización, Registro.

### Organizacion 
Define a qué oficina, departamento o área específica de trabajo (por ejemplo: Oficina de Pases, Oficina de Zona Restringida, Oficina de Vinculaciones) pertenece un Usuario .  

Esta pertenencia determina los roles, atributos y el conjunto de permisos específicos que habilitan o deniegan funcionalidades particulares dentro del sistema, garantizando la seguridad bajo el esquema ABAC (Control de Acceso Basado en Atributos) .  

**Entidades relacionadas:** Usuario, Vinculación.
