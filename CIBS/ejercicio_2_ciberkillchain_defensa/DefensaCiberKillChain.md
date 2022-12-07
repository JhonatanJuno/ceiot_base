# Ejercicio CiberKillChain - Defensa

Hacer una copia de este documento para utilizar com plantilla para el ejercicio

## Alumno

Jhonatan Alexander Juño Garcia  i0611

## Enunciado

Desarrollar la defensa en función del ataque planteado en orden inverso.

Para cada etapa elegir una sola defensa, la más importante, considerar recursos limitados.

## Resolución

### Actions on Objectives

- Uso de Backup Locales para respaldo de informacion en Local en una Plataforma aparte.
- Validar los valores medidos en la plataforma, contraste con los datos historicos para encontrar inconsistencias.

### Command and Control

- Implementar un registro de acceso de usuarios, para validar que usuarios entran a la plataforma. 
- Mejorar la seguiridad para el acceso de los equipos, sello de seguridad en nodo podria dar inicio de manipulacion.

### Installation
- Implementar politicas para siempre recibir notificaciones del sistema aunque no haya alarmas, de esa manera se identifican interrupciones en el sistema.

### Exploitation

- No usar firmaware por defecto. Implementar un Custom firmaware, de preferencia por SWDIO para la programacion y desabilitar los comandos AT.
- Activar la autenticacion en dos pasos para impedir acceso desconocidos.

### Delivery
- Implementar politicas para la publicacion de informacion sensible de la empresa en redes socioales, concientizar a tabajadores, sobre todo a los administradores que tienen acceso al sistema.
- Conocer los formatos de reporte de Correoy SMS para nos ser engañado por una notificacion falsa. 


### Weaponization

- Proteger el acceso al Firmware, con proteccion de lectura en flash.
- Podemos delegar la administracion del Network Server a un tercero, dejar solo accesos de Usuario y el acceso de adminstrador a un tercero fuera de la empresa.

### Reconnaissance

- Mejorar la seguridad de la instalacion, camaras de seguridad o un cerco perimetrico protegido, impedira el acceso a los equipos por personal no autorizado.

- Mejorar las politicas de publicacion de inforacion en Red, Tener lista de remitentes Seguros para los SMS y Correros de la PLataforma. Atencion ante intentos de ataque por Ingenieria social.


  

