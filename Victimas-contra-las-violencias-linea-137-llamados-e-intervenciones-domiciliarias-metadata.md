Víctimas contra las violencias línea 137 - llamados e intervenciones domiciliarias
----------------------------------------------------------------------------------

Este conjunto de datos contiene las llamadas atendidas por las profesionales del Programa las Víctimas contra las Violencias, de la Línea 137, sobre casos de Violencia Familiar y los acompañamientos en terreno de las víctimas de violencia familiar en CABA.

El Programa Las Víctimas Contra Las Violencias cuenta con un Centro de Llamadas que recibe el pedido de auxilio que realizan las víctimas de violencia familiar y sexual o personas de su entorno, las 24 horas los 365 días del año, tras el cual se da intervención a los equipos interdisciplinarios especializados en orientarlas, atenderlas y acompañarlas, en el ámbito de la CABA y en las provincias donde se replica el mismo.

Constituye una política pública efectiva para las víctimas de violencias y malos tratos propiciando el acceso a la justicia de las personas victimizadas.

http://datos.jus.gob.ar/dataset/victimas-contra-las-violencias-llamados-linea-137

Características
---------------

-   **Fecha de Primera** **Publicación:** 14/02/2018

-   **Tags o Etiquetas:** violencias, violencia familiar, violencia sexual, brigada móvil, línea 137, víctimas, género

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Acceso a la Justicia. Programa Las Víctimas Contra Las Violencias

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Acceso a la Justicia. Programa Las Víctimas Contra Las Violencias

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Acceso a la Justicia. Programa Las Víctimas Contra Las Violencias

-   **Grupo:** Acceso a Justicia, Género

-   **Frecuencia de Actualización:** Trimestralmente

Recursos disponibles
--------------------

### Llamados atendidos sobre violencia familiar – AAAA-MM

-   **Nombre del archivo:** llamados-atendidos-violencia-familiar-AAAA-MM.csv

-   **Descripción del contenido:** detalle de los llamados atendidos por los profesionales de la Línea 137 sobre casos de Violencia Familiar o Sexual. Cada fila en este archivo representa un llamado, ya que en el llamado se identifica una única víctima y un único agresor/a. AAAA-MM identifica al período de recepción de los llamados.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** se cuenta con datos de llamados entre enero de 2017 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **id\_caso (int):** código que permite identificar el caso

-   **llamante\_quien\_llama (string):** describe quién realiza el llamado. Puede indicar personas o instituciones

-   **llamante\_genero (string):** describe el género de la persona que realiza el llamado. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Ns/Nc: no sabe / no contesta

<!-- -->

-   **llamante\_vinculo\_ninios\_presentes\_hecho (string):** describe el vínculo que tiene la persona que realiza el llamado con niños/as presentes en el hecho

<!-- -->

-   **violencia\_tipo (string): describe el tipo de violencia que se denuncia. Puede tomar los valores:**

    -   Económica

    -   Económica y física

    -   Explotación comercial laboral

    -   Física

    -   No es un caso de Violencia Familiar

    -   Psicológica

    -   Sexual

    -   Sexual y económica

    -   Sin datos

    -   Otras

-   **victima\_edad (string):** describe la edad de la víctima principal del caso

<!-- -->

-   **victima\_rango\_etario (string):** describe el rango etario de la víctima. Puede tomar los valores:

    -   1 a 5 años

    -   6 a 11 años

    -   12 a 17 años

    -   18 a 29 años

    -   30 a 39 años

    -   40 a 49 años

    -   50 a 59 años

    -   más de 60 años

    -   Sin datos

-   **victima\_genero (string):** describe el género de la víctima. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Ns/Nc: no sabe / no contesta

-   **victima\_cantidad (int):** describe el número de víctimas involucradas en el caso

-   **agresor\_cantidad (int):** describe el número de agresores involucrados en el caso

-   **agresor\_genero (string):** describe el género del agresor. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Ns/Nc: no sabe / no contesta

<!-- -->

-   **agresor\_relacion\_victima (string):** describe el vínculo que existe entre el agresor y la víctima involucrada en el caso

<!-- -->

-   **llamado\_derivacion (string):**  acciones que se realizaron en el centro de llamados de la línea 137

-   **llamado\_fecha\_hora (date):** fecha y hora en la que se realiza el llamado

-   **llamado\_provincia (string):** provincia desde la que se realiza el llamado

-   **llamado_provincia_indec_id (string):** código de provincia desde la que se realiza el llamado, según la codificación de provincia implementada por INDEC

### Intervenciones domiciliarias - violencia familiar – AAAA-MM

-   **Nombre del archivo:** intervenciones-domiciliarias-violencia-familiar-AAAA-MM.csv

-   **Descripción del contenido:** detalle de las intervenciones domiciliarias realizadas por los profesionales del Programa Victimas Contra Las Violencias sobre casos de Violencia Familiar.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** intervenciones domiciliarias desde enero de 2018 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **id\_registro\_caso (int):** código con el que se registró el caso

-   **intervencion\_fecha\_hora (date):** fecha y hora en la que se realiza la intervención en el lugar de los hechos

<!-- -->

-   **victima\_embarazo (string):** describe si la víctima involucrada en el caso está embarazada: Toma los valores SI/NO

-   **victima\_edad (int):** describe la edad de la víctima involucrada en el caso

<!-- -->

-   **victima\_genero (string):** describe el género de la víctima involucrada en el caso. Puede tomar los valores:

    -   Masculino

    -   Femenino

    -   Trans

    -   Ns/Nc: no sabe / no contesta

<!-- -->

-   **victima\_nacionalidad (string):** describe la nacionalidad de la víctima involucrada en el caso

<!-- -->

-   **victima\_discapacidad (string):** describe si la víctima involucrada en el caso posee algún tipo de discapacidad. Puede tomar los valores:

    -   Sí

    -   No

    -   Ns/Nc: no sabe / no contesta

    <!-- -->

    -   Ns/Nc: no sabe / no contesta

-   **violencia\_tipo (string):** describe el tipo de violencia que se denuncia. Puede tomar los valores:

    -   Económica

    -   Económica y física

    -   Explotación comercial laboral

    -   Física

    -   No es un caso de Violencia Familiar

    -   Psicológica

    -   Sexual

    -   Sexual y económica

    -   Sin datos

    -   Otras

-   **agresor\_relacion\_victima (string):** describe el vínculo que existe entre el agresor y la víctima involucrada en el caso

Notas:
------

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

Las modalidades de implementación del Programa las Víctimas contra las Violencias se nutren de la experiencia de las profesionales en la escena de la violencia, acompañando a las víctimas, colaborando en su autovalimiento y en la restitución de los derechos vulnerados.

La Línea 137 es atendida por un equipo profesional especializado, integrado por psicólogas/os y trabajadoras/es Sociales, que se ocupa de escuchar, contener, orientar y, en los casos en los que se está desarrollando un episodio de violencia (familiar o sexual) al momento del llamado, decidir el desplazamiento de un equipo móvil al lugar donde se encuentra la víctima. Desde su creación, en octubre de 2006, a Diciembre de 2017, la Línea 137 recibió en CABA 129.980 llamados con pedidos de ayuda u orientación, acompañando a 29.962 víctimas de violencia familiar y a 11.688 víctimas de violencia sexual.

Desde el Programa no se reciben denuncias sino que se trata de una instancia previa, en la que se interviene ya sea en el sitio donde están teniendo lugar las violencias o mediante la atención telefónica por parte de profesionales especializados en las temáticas abordadas. Si la víctima lo desea, entre otras acciones que se realizan en las intervenciones “en terreno”, se la acompaña a realizar la denuncia a los lugares pertinentes (según la denuncia sea civil, penal o ambas).

**Seguimiento del caso:** el Equipo de Seguimiento refuerza el trabajo realizado por las/los profesionales en las intervenciones, así como aquellos llamados realizados a la línea 137 que no han generado desplazamientos de los equipos móviles. Colabora en el proceso de sostenimiento de las denuncias realizadas, complementa la labor de acompañamiento legal, y procura optimizar el acceso a los recursos interinstitucionales para las víctimas de violencia familiar, en los niveles de contención, asistencia, prevención y promoción de la problemática de la violencia.

**Acompañamientos jurídicos:** consiste en el asesoramiento y abordaje legal, derechos que le asisten a la víctima, medidas de protección aplicables respecto del hecho de violencia acontecido. Se efectúan en todas las instancias que sean requeridos, según lo previsto en la normativa vigente, [Ley N°24.417 de Protección contra la Violencia Familiar](http://servicios.infoleg.gob.ar/infolegInternet/anexos/90000-94999/93554/norma.htm) y [Ley N° 26.485 de Protección Integral para Prevenir, Sancionar y Erradicar la Violencia contra las Mujeres](http://servicios.infoleg.gob.ar/infolegInternet/anexos/150000-154999/152155/norma.htm), [Convención Interamericana para Prevenir, Sancionar y Erradicar la Violencia Contra la Mujer](http://servicios.infoleg.gob.ar/infolegInternet/anexos/35000-39999/36208/norma.htm) y demás normativa vigente.

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 187 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2018-187-APN-MJ.pdf), del 9 de Marzo de 2018.
