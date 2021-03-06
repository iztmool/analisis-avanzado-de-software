<p align = "center">
    <img alt="Logo" src="https://www.tijuana.tecnm.mx/wp-content/themes/tecnm/images/logo_TECT.png">
</p>

# Ingeniería en Informática

## ADF-1702IF8A ANÁLISIS AVANZADO DE SOFTWARE

---

# Equipo Softonic

### :pencil:Maestro
* Nombre: **Leonardo Enriquez Alvarez **


  
---

### :necktie: Datos del Alumno

* Nombre: **Jonathan Ismael Navarro Rodriguez **
* Licenciatura: Ingeniería Informatica
  

---


# Inicio del proyecto

## :trophy: C1.2 Reto en clase

Elaboracion del acta constitutiva del proyecto

### :blue_book: Instrucciones

- De acuerdo con la información presentada por el asesor referente al tema, y basado en el caso de estudio, realizar el acta constitutiva del proyecto basado en el ejemplo [documento acta constitución del proyecto](../pdf/C1.2_Ejemplo_ActaConstitución_delProyecto.pdf) indicada por el asesor
- Toda actividad o reto se deberá realizar utilizando el estilo **MarkDown con extension .md** y el entorno de desarrollo VSCode, debiendo ser elaborado como un documento **single page**, es decir si el documento cuanta con imágenes, enlaces o cualquier documento externo debe ser accedido desde etiquetas y enlaces.
- Es requisito que el archivo .md contenga una etiqueta del enlace al repositorio de su documento en Github, por ejemplo **Enlace a mi GitHub**
- Al concluir el reto el reto se deberá subir a github el archivo .md creado.
- Desde el archivo **.md** se debe exportar un archivo **.pdf** con la nomenclatura **C1.2_NombreAlumno_Equipo.pdf**, el cual deberá subirse a classroom dentro de su apartado correspondiente, para que sirva como evidencia de su entrega; siendo esta plataforma **oficial** aquí se recibirá la calificación de su actividad por individual.
- Considerando que el archivo .pdf, fue obtenido desde archivo .md, ambos deben ser idénticos y mostrar el mismo contenido.
- Su repositorio ademas de que debe contar con un archivo **readme**.md dentro de su directorio raíz, con la información como datos del estudiante, equipo de trabajo, materia, carrera, datos del asesor, e incluso logotipo o imágenes, debe tener un apartado de contenidos o indice, los cuales realmente son ligas o **enlaces a sus documentos .md**, _evite utilizar texto_ para indicar enlaces internos o externo.
- Se propone una estructura tal como esta indicada abajo, sin embargo puede utilizarse cualquier otra que le apoye para organizar su repositorio.

``` 
| readme.md
| | blog
| | | C0.1_x.md
| | | C0.2_x.md
| | | C0.3_x.md
| | img
| | docs
| | | A0.1_x.md
| | | A0.2_x.md
```
___

## :pencil2: Desarrollo

## Acta de constitución del proyecto

> | ***Datos generales***                  |                         |
> |------------------------------------    |-------------------------|
> | **Empresa**                            | Lambda Technologies     |
> | **Nombre del proyecto**                | IOTonic                 |
> | **Tipo de proyeto**                    | Escritorio              |
> | **Patrocinador**                       | Carlos Jose Postigo     |
> | **Dueño del producto**                 | Luis Eduardo Fierro     |
> | **Gerente del proyecto**               | Jonathan Ismael Navarro |
> | **Scrum Master**                       | José Luis Cuevas        |
____
### Propósito del documento  
> Este documento define la descripción general, los objetivos y los participantes del proyecto. Se
  relaciona principalmente con la autorización del inicio del proyecto. Asimismo este documento brinda una descripción de la situación actual, los requisitos de alto nivel,
  criterios de éxito, riegos y oportunidades.

### Propósito - Justificación     
> La empresa **Open Warehouse Company** que ofrece servicios de almacenamiento busca diferenciarse del mercado al ofrecer a sus clientes mayores niveles de seguridad y control por medio de un sistema para monitorear las condiciones ambientales en el área de almacenamiento.

### Breve descripción del proyecto     
> Un plataforma de monitoreo y control en tiempo real que enviara notificaciones o alertas cada vez que suceda una falla o evento relevante sobre las siguientes condiciones ambientales:
>  * Humedad y temperatura
>  * Iluminación

### Alcance preliminar del proyecto    
> Monitorear y enviar alertas sobre las condiciones de humedad, temperatura y la iluminación de cada sector de almacenamiento que lo requiera. Sin embargo, se utilizara una arquitectura que permita la implementación de nuevos sensores.

### Resultados esperados del proyecto - Beneficios   
> Un sistema estable, seguro y escalable que cumpla los requerimientos del cliente.

> **Beneficios:**
>   * Se tendra un sistema de adquisición de datos escalable
>   * Remuneración económica por el desarrollo del software
>   * Desarrollo de componentes reutilizables de IoT
>   * Ampliación de la oferta de nuestra empresa
>   * Nuevo cliente

### Requisitos de alto nivel del proyecto
> | **Requisito**                      | **Criterio de éxito**   |
> |------------------------------------|-------------------------|
> | Reducir los costos relativos al personal operativo, así como eliminar documentos en papel                            | Automatizar tareas, procedimientos y formularios     |        
> | Ofrecer la seguridad que es un indicador clave e importante, a través del manejo de usuarios                         | Agregar un control de usuarios     |    
> | Almacenar el historial de todos los eventos, especialmente en aquellos que el sistema indicará fuera de control                          | Crear y almacenar un log de eventos   |   
> | Ofrecer alertar al personal e incluso al cliente cuando una condición de ambientación se salga de control, al momento que el evento ocurra.                  | Notificar al personal y al cliente por medio de un correo o un mensaje en cuanto ocurra un evento  |  
> | Asegurar que el sistema esté siempre disponible cuando se requiera.                 | Distribuir el sistema para garantizar el funcionamiento si un nodo falla  |
> | Garantizar que los registros no se pierdan o se dañen.                | Crear respaldos periódicamente para evitar perder información en caso de un imprevisto  |
> | Permitir ser accedido en cualquier lugar que el usuario se encuentre, tanto dentro como fuera del área de trabajo.                | Crear un sistema online con un servidor siempre en ejecución  |
> | Permitir la compatibilidad, para usarse desde cualquier tipo de dispositivo.               | Adaptar el sistema para que sea multiplataforma  |
> | Reportar los indicadores claves del sistema como son históricos, alertas, y gráficos.               | Mostrar la información clave por medio de un dashboard  |
> | Soportar múltiples sensores tales como son temperatura, humedad, luminosidad, presencia, contaminación.               | Desarrollar una arquitectura estable y escalable  |

### Hitos
> * Desarrollar un API para la comunicación entre el cliente y el servidor
> * Diseñar una interfaz de usuario para visualizar los datos.
> * Implementar sensores para recibir datos del ambiente.
> * Diseñar e implementar una base de datos en la nube
> * Recibir y enviar las alertas de los sensores

### Riesgos
> * Nueva tecnología en la empresa
> * Poco conocimimiento de la arquitectura
> * Tiempo de desarrollo limitado a 6 meses

### Costo preliminar - Presupuesto
> * **Programadores/diseñadores:** 3 programadores ($3,500 x 1 mes) x 6 meses = $108,000 MN
> * **Cloud Firestore:** (261.90 USD) = $5,665 MN
> * **INDAUTOR:** $271 MN
> * **Beneficio** 15% = $113,936 MN x 0.15 = $17,090.4 MN
> * **Costo real** $131,026.4 MN

### Interesados en el proyecto
> | ***Interesado***  |***Cargo***|***Rol***|***Teléfono***|***Email***|
> |-----------------  |-----------|---------|--------------|-----------|
> |Carlos Jose Postigo|Patrocinador|Patrocinador|(664)5784658|cpostigo@openwarehouse.com|
> |Luis Eduardo Fierro|Product Owner|Programador/analista|(664)4970108|luis.fierro16@tectijuana.edu.mx|
> |Jonathan Ismael Navarro|Gerente de proyecto|Programador|(664)5635008|jonathan.navarro@tectijuana.edu.mx|
> |José Luis Cuevas|Scrum Master|Programador/diseñador|(664)5109193|jose.cuevas@tectijuana.edu.mx|


### Supuestos
> * Se desarrollo el sistema a tiempo
> * Las fallas del sistema se corrigieron
> * No hubo complicaciones al comunicar los sensores con el API
> * La intefaz de usuario es funcional y agradable
> * Se envían alertas de manera exitosa

### Restricciones
> * **Costo:** No se cuenta con el suficiente presupuesto. 
>     * Se encuentran opciones más baratas solo para prototipo.
> * **Tiempo:** Se tienen ~ 4 meses para realizar el proyecto. 
>     * Se ajusta las tecnologías a unas conocidas por los desarrolladores.
> * **Alcance:** No se pueden implementar todos los sensores en el tiempo estimado. 
>     * Se limita la utilización de sensores solo a ***iluminación*** o ***humedad y temperatura***

### Autorización del proyecto
> | ***Nombre***  |***Cargo***|***Firma***|***Fecha***
> |-----------------  |-----------|---------|--------------|
> |Carlos Jose Postigo|Patrocinador|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/Firma_de_Juan_Jos%C3%A9_Pradera.svg/800px-Firma_de_Juan_Jos%C3%A9_Pradera.svg.png" width="150" height="100">|02 de Octubre del 2020|
___

### :bomb: Rubrica

| Criterios     | Descripción                                                                                  | Puntaje |
| ------------- | -------------------------------------------------------------------------------------------- | ------- |
| Instrucciones | Se cumple con cada uno de los puntos indicados dentro del apartado Instrucciones?            | 20 |
| Desarrollo    | Se respondió a cada uno de los puntos solicitados dentro del desarrollo de la actividad?     | 80      |



## <img  style="vertical-align: middle; margin-bottom: 5px;" src="https://www.iconfinder.com/data/icons/octicons/1024/mark-github-512.png" width="30" height="30"/> GitHub

<a href="https://github.com/iztmool/analisis-avanzado-de-software" target="_blank">GitHub</a>
