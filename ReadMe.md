# <font color='darkslategrey'>Sistema de Salud Colombiano</font>

## <font color='teal'>Motivación</font>

Aportar al entendimiento de las desigualdades en el sistema de salud colombiano, respondiendo a las siguientes líneas de trabajo:

- Comparación entre cobertura de aseguramiento y distribución de las IPS a nivel municipal

- Acceso a nivel municipal a IPS de acuerdo con el nivel de complejidad

- Asistencia de las personas a las IPS cuando tienen una enfermedad que no requiere hospitalización 

- Percepción de las personas sobre la calidad del servicio de la IPS

## <font color='teal'>Fuentes de información</font> 

Para llevar a cabo este análsis se utilizaron bases de datos del Ministerio de Salud proporcionadas a través de la página web y Datos Abiertos sobre las IPS habilitadas a nivel municipal, lo que incluye su nivel de complejidad, y cobertura de aseguramiento (régimen subsidiado/contributivo). 

Adicionalmente, para obtener información sobre las personas a nivel municipal se procesó el censo de 2018 en el cual se utilizaron las siguientes preguntas: 

- ¿Algun problema de salud en los últimos 30 días, sin hospitalización?
- Tratamiento principal del problema de salud
- Atención del problema de salud en la IPS
- Calidad de la prestación del servicio de salud en la IPS

## <font color='teal'>Procesamiento</font>

- **Python:** Se realizó el procesamiento de las bases de datos, para la información de Datos Abiertos se utilizó la API Socrata Open Data API (SODA)
- **Tableu:** Se analizó las respuestas de las personas en la encuesta del censo sobre el servicio de la IPS
- **Qgis:** Se analizó la distribución de las IPS a nivel municipal comparado con la cobertura de aseguramiento, nivel de complejidad y naturaleza jurídica. 

## <font color='teal'>Resultados</font>


### 1. Comparación entre cobertura de aseguramiento y distribución de las IPS a nivel municipal

![Insumo1.png](attachment:Insumo1.png)

![Insumo2.png](attachment:Insumo2.png)

- De los 1.122 municipios de Colombia, 926 cuentan con el servicio de una IPS. Sin embargo, 12 municipios no cuentan con aseguramiento, es decir, ninguno de la población está afiliado al sistema de salud; estos municipios tampoco cuentan con IPS y pertenecen a los departamentos de Guainía, Amazonas, Vaupés y Chocó

- Hay mayor presencia de IPS de naturaleza jurídica pública con presencia en 854 municipios mientras que las privadas y mixtas tienen presencia en 443 y 17, respectivamente. A pesar de esto, en el país existen 9.904 IPS privadas, 1.003 públicas y 18 mixtas. Lo cual muestra que las privadas tienen una alta concentración en algunos municipios, mientras que la públicas y mixtas intentan cubrir gran parte del territorio

###  2. Acceso a nivel municipal a IPS de acuerdo con el nivel de complejidad

El nivel de complejidad determina el nivel de los servicios proporcionados por las IPS:
- **Nivel 1:** Son aquellos que tienen servicios de médico general y/o personal auxiliar y/o paramédico y/o de otros profesionales de la salud no especializados. 
- **Nivel 2:** Cuenta con servicio de médico general y/o profesional paramédico con interconsulta, remisión y/o asesoría de personal o recursos especializados.
- **Nivel 3:** : Servicios de médico especialista con la participación del médico general y/o profesional paramédico. 

![Insumo3.png](attachment:Insumo3.png)

En Colombia el nivel de complejidad es sólo calculado para las IPS públicas, de las cuales 859 de nivel 1, 115 de nivel 2 y 28 de nivel 3. Estas tienen presencia en 798, 106 y 19 municipios, respectivamente. Esto lo que muestra es un escenario complejo para acceder a servicios de salud con especialistas o con nivel de atención más complejo frente a diferentes enfermedades teniendi en cuenta que las IPS públicas tienen mayor presencia en todo el territorio. 

###  3. Asistencia de las personas a las IPS cuando tienen una enfermedad que no requiere hospitalización 



![Tratamiento.png](attachment:Tratamiento.png)

De las personas que manifestaron tener un problema de salud que no requería hospitalización en los últimos 30 días, la mayoría asistió a una IPS o médico particular. Sin embargo, el uso de remedios caseros o la automedicación son elementos que levantan alarmas y que habría que observar con mayor detalle, porque podrían generar complicaciones dependiendo del tipo de enfermedad.

###  4. Calidad del servicio IPS


![Calidad.png](attachment:Calidad.png)

De las personas que asistieron a su IPS consideran que el servicio es muy bueno o bueno. Sin embargo, sería interesante conocer las razones por las cuales algunos continúan considerando que el servicio es malo para poder mejorar el sistema de salud


```python

```
