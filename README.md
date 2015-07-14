# diabetesmx

Resultado de consulta a la base de datos SAEH de la Secretaría de Salud. 

Tabla dinámica_Hoja1_2: 

Se listan el número de casos por año en cada municipio (según la contatenación "clave de estado"&"clave de municipio"=ID_ENT_MUN

Tabla: DIABETES-SAEH_2000-2013XAÑO.ods

CAUSABAS: Código CIE-10 de la Causa Básica
Nombre_Causa: Nombre de la Causa
AFECPRIN: Código CIE-10 de la Reselección de la Afección principal 
CLUES: Clave Única de Establecimientos en Salud
Nombre_Unidad: Nombre del Establecimiento
Domicilio_Unidad: Domicilio del Establecimiento
CP_Unidad: Código Postal del Establecimiento
Municipio: Nombre del Municipio del Establemiento (En algunso casos viene una clave en lugar del nombre del Municipio)
IDMPO: Clave del Municipio del Establecimiento
Estado: Nombre del estado del Establecimiento
IDEDO: Clave del Municipio del Establemiento
Sexo: Sexo del paciente
ID_Sexo: Clave del sexo del paciente
EDAD: Edad del paciente
INGRESO: Fecha de ingreso al Establecimiento
EGRESO: Fecha de egreso del Establecimiento
ID_ENT_MUN: Concantenacion de "IDEDO" y "IDMPO"
AÑO-EGRESO: Año del Egreso (Se agregó para facilitar la generación de tabla dinámica)

Tabla: QUERY-CAUSA-DIABETES.xlsx

Contiene la descripción de la CAUSA


Notas:

1.- Hay 32 datos del año 2011 que no cuentan con la clave de Municipio ni Estado, por lo que los desché de la tabla.

2.- En las bases de datos de cada año se presentan registros del año anterior. Por ejemplo, en la BD de 2000 hay 33 casos de egresos de 1999. Esta es la razón por la cuál se incluyen en la tabla esos registros.




