# PI2
PI2 Henry 
# Análisis de Acceso a Internet y Velocidad de Conexión

## Introducción

Este proyecto tiene como objetivo analizar el acceso a internet y la velocidad de conexión en diferentes provincias y localidades. Se utilizan diversos conjuntos de datos para obtener información sobre los accesos a internet por tecnología, penetración de internet en hogares y población, y velocidades promedio de conexión. A través de este análisis, se identifican tendencias, se evalúan mejoras y se establecen indicadores clave de rendimiento (KPIs) para monitorear el desempeño y alcanzar objetivos específicos.

## KPIs

### KPI 1: Velocidad Promedio de Conexión (Mbps)
- **Descripción**: Promedio de la velocidad de conexión en Mbps.
- **Fórmula**: 
  ```DAX
  Promedio_Velocidad = AVERAGE('TuTabla'[Velocidad (Mbps)])

  
Importancia: Este KPI es crucial para medir la calidad del servicio de internet. Una mayor velocidad indica una mejor experiencia de usuario.

Análisis: Se observa que las provincias con mayores velocidades promedio tienden a tener una mejor infraestructura y servicios de internet más desarrollados. Esto es un indicador de progreso y modernización en esas áreas.


KPI 2: Accesos Totales por Tecnología
Descripción: Número total de accesos por cada tipo de tecnología (ADSL, Cablemodem, Fibra óptica, etc.).

Fórmula:

DAX
Accesos_Totales = SUM('TuTabla'[Accesos])
Importancia: Ayuda a identificar cuáles tecnologías son más utilizadas y pueden necesitar mayor inversión o mejoras.

Análisis: La fibra óptica muestra una tendencia creciente en comparación con tecnologías más antiguas como ADSL, lo que indica una transición hacia conexiones más rápidas y estables.

KPI 3: Tasa de Penetración de Internet por Provincia
Descripción: Porcentaje de accesos a internet por cada 100 habitantes.

Fórmula:

DAX
Tasa_Penetracion = SUM('TuTabla'[Accesos por cada 100 hab])
Importancia: Este KPI muestra cómo se distribuye el acceso a internet entre diferentes provincias, lo cual es importante para identificar brechas digitales.

Análisis: Provincias urbanas como Buenos Aires y Capital Federal tienen una mayor penetración, lo que resalta la necesidad de enfocarse en mejorar el acceso en áreas rurales y menos desarrolladas.

KPI 4: Ingresos Totales por Periodo
Descripción: Total de ingresos generados en miles de pesos por periodo.

Fórmula:

DAX
Ingresos_Totales = SUM('TuTabla'[Ingresos (miles de pesos)])
Importancia: Este KPI es fundamental para evaluar el desempeño financiero de la empresa y planificar estrategias de crecimiento.

Análisis: Los ingresos han mostrado un aumento constante, reflejando el crecimiento en la adopción de servicios de internet y la expansión de la base de usuarios.
