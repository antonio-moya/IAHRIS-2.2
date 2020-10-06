# IAHRIS-2.2
Índices de Alteración Hidrológica en RÍoS (IAHRIS)<br/>
Indicators of Hydrologic Alteration in RIverS<br/>
Indicador de masas de agua muy alteradas: Manual de Referencia Metodológica Versión 2.2
## Autores:
### Metodología:
Carolina Martínez Santa-María <br/>
José Anastasio Fernández Yuste
### Software:
INCLAM, S.A.
### Manual de Referencia:
Carolina Martínez Santa-María <br/>
José Anastasio Fernández Yuste
## Edición:
Software financiado por la Dirección General del Agua del Ministerio de Medio Ambiente mediante convenio con el Centro de Estudios y Experimentación de Obras Públicas (CEDEX).
## Copyright ©  Universidad Politécnica de Madrid.
Software gratuito. <br/>
Cualquier operación comercial con este software está expresamente prohibida. <br/>
Los autores y editores no se responsabilizan de los errores y/o fallos del software. El usuario deberá verificar los resultados obtenidos con IAHRIS, y será de su exclusiva responsabilidad su uso y aplicación. <br/>

# Antecedentes
 El epígrafe 3.4.2 de la IPH (BOE de 22‐09‐08) indica: …  En los ríos identificados como masas de agua se analizará su grado de alteración hidrológica mediante el cálculo de índices de alteración hidrológica …  con estos índices se comparan las condiciones del régimen natural de referencia con las condiciones actuales …  los parámetros utilizados deben basarse en las características fundamentales de los regímenes hidrológicos, como magnitud, duración, frecuencia, estacionalidad y tasas de cambio...Se entenderá que una masa de agua está muy alterada hidrológicamente cuando presenta una desviación significativa en la magnitud de los parámetros que caracterizan las condiciones mensuales y anuales del régimen hidrológico... Se considerará que la desviación es significativa cuando la magnitud del parámetro anual o mensual se desvía significativamente de los valores del percentil del 10% al 90% de la serie en régimen natural.
 
 # Objetivo
 Dada la trascendencia que para los Planes de Cuenca tiene la designación de masas de agua muy alteradas (MMA), y la necesidad de que esa condición sea, en la medida de lo posible, establecida con arreglo a un criterio trasparente y objetivo, es necesario:
- Seleccionar un conjunto de índices parciales, entre el total de ellos que ofrece IAHRIS. Los índices seleccionados deben valorar la alteración del régimen en: 
  - a) sus valores habituales y extremos (avenidas y sequías)
  - b) considerando magnitud, duración, estacionalidad y variabilidad 
  - c) teniendo en cuenta escalas temporales tanto a nivel anual como mensual
- Estudiar nuevos criterios que, a partir de los resultados obtenidos con los índices seleccionados, permitan asignar la condición de masa muy alterada, y proponer aquel que mejor discrimine esa condición. Ese criterio debe establecer el umbral para la condición de masa muy alterada considerando:
  - Índices globales o no globales que reflejen la alteración de los aspectos del régimen de caudales con mayor significación en la integridad ambiental del ecosistema fluvial.
  - Métricas y/o criterios que eviten que valores positivos de aspectos no alterados compensen los negativos de aspectos trascendentes muy alterados. 
- Aplicar otros criterios para asignar la condición de masa muy alterada, en concreto el empleado por la Demarcación Hidrográfica del Júcar. Este criterio emplea como indicadores los percentiles 10% y 90% de la serie en régimen natural para aportaciones anuales y mensuales. 

# Descripción
**Indices de Alteración Hidrológica en RIoS es una aplicación informática que permite obtener:**
 
- Parámetros con los que caracterizar el régimen hidrológico, tanto natural como alterado, en un punto de un río. Estos parámetros valoran aspectos hidrológicos del régimen con marcada trascendencia ambiental (duración de las sequías, estacionalidad de las avenidas… ).
- Si el usuario facilita datos de los dos regímenes, natural y alterado, la aplicación, además, calcula unos índices que permiten valorar el grado de alteración del régimen hidrológico en aquellos aspectos de mayor significación ambiental.
- En las circunstancias anteriores, es decir disponiendo de datos en régimen natural y alterado, la aplicación asigna la condición de masa de agua muy alterada según dos criterios complementarios (criterio P10-90 y criterio IAH-MMA).
- Para un régimen natural dado, la aplicación permite obtener aplicando la Metodología RAC un conjunto de escenarios de regímenes ambientales especificados a nivel de aportación mensual para distintos tipos de año

**¿Para qué sirve IAHRIS?**
- Poner a disposición de la comunidad científica y de los gestores de recursos hídricos un instrumento que permite cumplir lo exigido por la DMA para la caracterización del estado hidrológico de las masas de agua.
- Cuantificar objetivamente la alteración que inducen los aprovechamientos de los recursos hídricos sobre el régimen natural de caudales.
- Interpretar las consecuencias de la alteración del régimen de caudales en la integridad del ecosistema fluvial.
- Trabajar como banco de pruebas:
Valorar la alteración que sobre el régimen natural de caudales producirían distintos escenarios de usos y gestión de los recursos hídricos.
 En el caso de masas de agua fuertemente modificadas, puede utilizarse para caracterizar el óptimo potencial hidrológico como el regimen que resultaría de considerer las alteraciones derivadas de
contemplar de manera estricta los condicionantes que obligan a la consideración de masa de agua fuertemente modificada.
- Identificar los aspectos del régimen actual que en mayor medida condicionan la rehabilitación o recuperación del tramo estudiado.
- Fijar criterios objetivos para establecer prioridades en la restauración de ecosistemas fluviales.
- Definir escenarios de regímenes ambientales tomando como referencia el régimen natural
- Conocer la condición de masa de agua muy alterada con criterios objetivos

 **Instalación de IAHRIS.**
La aplicación se ha desarrollado utilizando Microsoft Visual Studio 2005, estando escrita en lenguaje Visual Basic, por lo que, para su correcto funcionamiento, es necesario tener instalado Microsoft.NET Framework 2.0 o superior.
Todos los resultados obtenidos se vuelcan a hojas Excel, por lo que también resulta necesario tener instalado el programa comercial Microsoft Excel 2003 o superior.<br/>
Por último, todos los datos de entrada utilizados por la aplicación se almacenan en una base de datos en formato Microsoft Access 2000, que es manejada totalmente por aquella sin necesidad de tener instalada una licencia de uso. Sin embargo, si el usuario quiere poder visualizar o exportar los datos en ella almacenados, sí resulta necesario disponer de la correspondiente licencia.<br/>
Ahora lo que sigue es ejecutar el instalador de IAHRIS, el cual guiara al usuario durante la instalación. El instalable se encarga de colocar en el directorio escogido por el usuario (por defecto, C:\Archivos de programa\IAHRIS) todos los ficheros requeridos por la aplicación, así como de incorporar el icono correspondiente al programa ejecutable en el escritorio.<br/>
Los archivos colocados en el directorio de la aplicación, no deben manipularse para garantizar un correcto funcionamiento de la aplicación.
 
**Datos que se emplean**
La aplicación utiliza series temporales de datos correspondientes a caudales diarios, expresados en m3/s, y/o a aportaciones mensuales, expresadas en hm3. En ambos casos, cada registro –caudal o aportación- debe llevar asociada la correspondiente fecha, día, mes y año en el caso de caudal diario, y mes y año para la aportación mensual.<br/>
Para cada punto del río sólo se podrá disponer de hasta dos series en régimen natural, una con caudales diarios y otra con aportaciones mensuales.<br/>
En régimen alterado, el usuario podrá aportar tantas como disponga. Por ejemplo, si se trata de una presa que lleva años en explotación puede considerarse una única serie correspondiente al régimen alterado, o varias, si a lo largo de ese período los criterios de gestión han cambiado, de manera que cada una de las series de caudales correspondiente a cada uno de esos períodos se trataría como serie independiente, todas con el carácter de régimen alterado y asociadas al mismo
punto del río. Otro caso para el que se dispondría de varias series en régimen alterado para el mismo punto del río sería aquel en el que se analicen distintas estrategias de gestión de una infraestructura hidráulica: para cada hipótesis, y con la misma o distinta ventana temporal, se generaría la correspondiente serie simulada, y cada una de esas series constituiría un régimen alterado distinto vinculado al mismo punto del río.<br/>
Esta posibilidad de que el usuario pueda disponer en un punto de un río de más de una serie asociada en régimen alterado, hace que la aplicación prevea un tratamiento específico para estas series.<br/>
 
**Aplicación y Base de Datos Asociada**
Para entender adecuadamente la estructura, la gestión de datos y el funcionamiento de la aplicación, es necesario tener presente que su núcleo central lo constituye la base de datos.<br/>
Hay tres conceptos fundamentales en torno a los que la aplicación organiza y gestiona la información, los cálculos y los resultados:
- PROYECTO: entidad o unidad de trabajo que engloba un conjunto de puntos, así como sus alteraciones y series asociadas.
- PUNTO: Se entiende por punto la sección o tramo de río para el que se dispone de datos de caudales diarios y/o aportaciones mensuales.
Todos los puntos a almacenar en la base de datos requieren un CÓDIGO identificativo y una DESCRIPCIÓN, pudiendo introducirse tantos puntos como se quiera, siempre que su CÓDIGO identificativo sea diferente de cualquier otro código utilizado para otro punto aunque pertenezca a un proyecto diferente.
- SERIE: Serie de caudales medios diarios o aportaciones mensuales asociada a un determinado PUNTO. Todas las SERIES utilizadas por la aplicación requieren tener asignado:
  - ...Tipo de periodicidad: MENSUAL o DIARIO
  - ...Tipo de régimen: NATURAL o ALTERADO
  - ... Código de PUNTO asociado
  - ...Código de ALTERACIÓN asociada (sólo para las series correspondientes a un régimen alterado)

El máximo número de series asociadas a un determinado punto es de 2*(1+Nº alteraciones asociadas), ya que cada punto puede llevar asociadas dos series diferentes (de aportaciones mensuales y de caudales medios diarios) para cada tipo de régimen.
- ALTERACIÓN: en un punto pueden considerarse varias series correspondientes a distintos regímenes alterados. Para facilitar la gestión de esta información, la aplicación exige que cualquier serie de regimen alterado vaya siempre asociada a un PUNTO y sea declarada en la base de datos con CÓDIGO identificativo de la alteración y una DESCRIPCIÓN, pudiendo introducirse, para un determinado PUNTO, tantos regímenes alterados como se quiera, siempre que el CÓDIGO identificativo sea diferente de cualquier otro utilizado para una alteración, con independencia del punto al que esta última se encuentre asociada y del proyecto al que pertenezca.

**La estructura de los Ficheros de Datos**
La aplicación sólo lee ficheros tipo csv (comma separated values). Se trata de un tipo de fichero de texto sencillo, en el que las columnas se separan utilizando un determinado carácter (que, en el caso que nos ocupa, es el punto y coma), y las filas por saltos de línea.< br/>
Dichos ficheros pueden confeccionarse con distintos editores, pero se atienen a una estructura fácilmente manejada por Microsoft Excel, por lo que éste resulta ser un buen editor para su manejo, ya que permite organizar toda la información estructurada en columnas, y guardarlo como fichero tipo csv.< br/>
Los ficheros de importación válidos deben incorporar una primera línea conteniendo la información necesaria para establecer a qué tipo de datos corresponden, cuál es la periodicidad de los mismos y a qué punto de cálculo y alteración, esta última, sólo en caso de corresponder a una serie de datos alteradoscorresponden. El resto de líneas –ninguna de ellas en blanco- contienen cada una el periodo (mes y año) o fecha (día, mes y año) al que corresponden, así como el valor correspondiente a la serie en cuestión para dicho periodo o fecha.< br/>

La PRIMERA LÍNEA de un archivo válido debe contener, por este orden:
- El tipo de periodicidad al que corresponde la serie: Solo se admiten, en mayúsculas, los tipos MENSUAL o DIARIO
- ; (punto y coma) que, como se ha indicado anteriormente, es el único carácter separador admitido.
- El tipo de régimen al que corresponde la serie: Solo se admiten, en mayúsculas, los tipos NATURAL o ALTERADO
- ; (punto y coma)
- El CÓDIGO correspondiente al PUNTO de cálculo asociado a la serie (que debe  estar declarado previamente en la base de datos para que la serie pueda ser incorporada con éxito)
 
Únicamente para las series correspondientes a un régimen alterado, se require la siguiente información adicional:
-  ; (punto y coma)
- El CÓDIGO correspondiente a la ALTERACIÓN asociada a la serie
El RESTO DE LÍNEAS, conteniendo la información temporal de la serie, tienen diferente estructura, según cuál sea su periodicidad:

SERIE DE VALORES DIARIOS:
- Fecha asociada al valor, con formato dd/MM/aaaa (por ejemplo, 03/07/2007). No se admite suprimir el cero para los días o meses inferiores a 10, ni otro separador diferente de la barra /. Tampoco se admite ordenar los valores de día, mes y año de diferente forma
- ; (punto y coma)

Caudal medio diario, expresado en m3/s (el separador decimal empleado –punto o coma-, debe coincidir con el utilizado en la configuración regional o de idioma a través del panel de control del equipo de trabajo)

SERIE DE VALORES MENSUALES:
Año correspondiente al valor mensual asociado, con formato aaaa (por ejemplo, 2007)
- ; (punto y coma)
    Mes correspondiente al valor asociado, con formato m (un solo dígito para los nueve primeros meses: 1 para enero, 2 para febrero,… 10 para octubre, etc)
- ; (punto y coma)
    Aportación mensual, expresada en hm3 (el separador decimal empleado –punto o coma-, debe coincidir con el utilizado en la configuración regional o de idioma a través del panel de control del equipo de trabajo)

OBSERVACIONES IMPORTANTES:
La información temporal contenida en un fichero de importación no tiene porqué estar ordenada en función de la fecha, ya que aquélla se ordena posteriormente en la base de datos. Sin embargo, no se admiten fechas inexistentes ni tampoco fechas repetidas (dos o más líneas con fecha o periodo coincidente).
Los ficheros no pueden contener líneas en blanco, y cada línea debe contener toda la información requerida.
La aplicación está preparada para rechazar cualquier fichero que no se ajuste estrictamente a los requisitos de formato expuestos.

