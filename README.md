# PI2
PI2 Henry 
# Proyecto de Análisis de Acceso a Internet y Velocidad de Conexión

## Introducción

El internet ha revolucionado la manera en que interactuamos con el mundo. Como una red global de computadoras interconectadas, permite el intercambio de información en tiempo real, convirtiéndose en una herramienta esencial para la comunicación, la educación, el entretenimiento y el comercio.

Uno de los mayores retos globales que enfrenta el internet es la inclusión digital. A pesar de sus beneficios, aún existen millones de personas sin acceso a esta red, lo que crea una brecha digital significativa. Esta desigualdad puede afectar negativamente las oportunidades educativas y laborales, además de limitar el acceso a información vital.

Económicamente, el internet genera cantidades astronómicas de dinero. En 2020, se estimó que el sector de las tecnologías de la información y la comunicación (TIC), al cual pertenece el internet, generó más de 4.9 trillones de dólares a nivel mundial. Esta cifra subraya la importancia del internet como motor económico, impulsando la innovación, la productividad y el crecimiento en diversas industrias.

El internet apoya a la humanidad de innumerables maneras. Facilita la educación a través de cursos en línea y recursos educativos abiertos, permite el trabajo remoto y la colaboración global, y ofrece plataformas para la expresión y el activismo social. También es crucial en la atención médica, proporcionando telemedicina y acceso a información sanitaria.

Sin embargo, el despliegue y mantenimiento de la infraestructura de internet involucra costos considerables. Desde la instalación de cables de fibra óptica hasta el mantenimiento de servidores y el desarrollo de tecnologías de ciberseguridad, los costos son significativos. Además, la expansión del internet a áreas rurales y remotas requiere inversiones sustanciales.

Analizar la situación del acceso a internet y su velocidad de conexión es vital para identificar áreas de mejora y asegurar que todos puedan beneficiarse de esta herramienta poderosa. Este proyecto tiene como objetivo explorar estas dinámicas en Argentina, proporcionando una visión detallada a través de indicadores clave de rendimiento (KPIs) que ayudan a monitorear el desempeño y establecer objetivos claros para el futuro.

## Metodología

### Análisis Exploratorio de Datos (EDA)
Para comenzar, se realizó un Análisis Exploratorio de Datos (EDA) utilizando Python. Este proceso incluyó la limpieza y organización de los datos, permitiendo identificar patrones, anomalías y relaciones significativas entre las variables.

### Creación del Dashboard en Power BI
Con los datos organizados, se utilizó Power BI para crear un dashboard interactivo. Este dashboard facilita la visualización de los datos y proporciona una plataforma para el análisis dinámico, permitiendo a los usuarios interactuar con los datos y obtener insights relevantes.

### Definición de KPIs
Se definieron cinco indicadores clave de rendimiento (KPIs) para medir y monitorear diferentes aspectos del acceso y la calidad del servicio de internet:

### KPI 1: Velocidad Promedio de Conexión (Mbps)
- **Descripción**: Promedio de la velocidad de conexión en Mbps.
- **Fórmula**: Promedio de `Velocidad (Mbps)` para todas las entradas.
- **Importancia**: Mide la calidad del servicio de internet. Una mayor velocidad indica una mejor experiencia de usuario.
- **Análisis**: Se observa que las provincias con mayores velocidades promedio tienden a tener una mejor infraestructura y servicios de internet más desarrollados. Esto es un indicador de progreso y modernización en esas áreas.

### KPI 2: Accesos Totales por Tecnología
- **Descripción**: Número total de accesos por cada tipo de tecnología (ADSL, Cablemodem, Fibra óptica, etc.).
- **Fórmula**: Suma de `Accesos` para cada tipo de tecnología.
- **Importancia**: Identifica cuáles tecnologías son más utilizadas y pueden necesitar mayor inversión o mejoras.
- **Análisis**: La fibra óptica muestra una tendencia creciente en comparación con tecnologías más antiguas como ADSL, lo que indica una transición hacia conexiones más rápidas y estables.

### KPI 3: Tasa de Penetración de Internet por Provincia
- **Descripción**: Porcentaje de accesos a internet por cada 100 habitantes.
- **Fórmula**: Suma de `Accesos por cada 100 hab` por provincia.
- **Importancia**: Muestra cómo se distribuye el acceso a internet entre diferentes provincias, lo cual es crucial para identificar brechas digitales.
- **Análisis**: Provincias urbanas como Buenos Aires y Capital Federal tienen una mayor penetración, lo que resalta la necesidad de enfocarse en mejorar el acceso en áreas rurales y menos desarrolladas.

### KPI 4: Ingresos Totales por Periodo
- **Descripción**: Total de ingresos generados en miles de pesos por periodo.
- **Fórmula**: Suma de `Ingresos (miles de pesos)` por periodo.
- **Importancia**: Evalúa el desempeño financiero de la empresa y planifica estrategias de crecimiento.
- **Análisis**: Los ingresos han mostrado un aumento constante, reflejando el crecimiento en la adopción de servicios de internet y la expansión de la base de usuarios.

### KPI 5: Distribución de Accesos por Rango de Velocidad
- **Descripción**: Porcentaje de accesos en diferentes rangos de velocidad.
- **Fórmula**: `(Suma de accesos en cada rango / Total de accesos) * 100`
- **Importancia**: Entiende la distribución de usuarios según la velocidad de su conexión para ajustar ofertas y planes de servicios.
- **Análisis**: La mayoría de los accesos se encuentran en rangos de velocidad superiores, indicando una demanda creciente por conexiones más rápidas y fiables.

## Conclusiones

El análisis realizado revela importantes hallazgos sobre el estado del acceso a internet y la calidad de la conexión en Argentina. La velocidad promedio de conexión es un reflejo claro de la calidad del servicio de internet ofrecido; se encontró que las provincias con mayores velocidades promedio disponen de una infraestructura más desarrollada y servicios tecnológicos avanzados. Esto indica que mejorar la infraestructura en áreas con velocidades inferiores podría elevar significativamente la calidad del servicio.

Por otro lado, la adopción de tecnologías de conexión muestra una preferencia creciente por la fibra óptica y el Cablemodem, mientras que tecnologías más antiguas como el ADSL están quedando en segundo plano. Esta transición hacia tecnologías más rápidas y fiables es una señal positiva del avance tecnológico y de la disposición de los usuarios a adoptar mejores servicios.

Sin embargo, se identificaron brechas digitales significativas entre las provincias. Buenos Aires y Capital Federal presentan una tasa de penetración de internet mucho mayor en comparación con regiones más rurales. Esta disparidad destaca la necesidad urgente de invertir en infraestructura en áreas menos desarrolladas para asegurar que todas las provincias puedan disfrutar de los beneficios del acceso a internet.

El análisis financiero reveló un incremento constante en los ingresos generados por los servicios de internet, lo que refleja la creciente adopción de estos servicios y la expansión de la base de usuarios. Este crecimiento financiero es fundamental para sustentar las inversiones necesarias en infraestructura y tecnología.

Finalmente, se observó que la mayoría de los accesos a internet se encuentran en rangos de velocidad superiores, lo cual indica una demanda creciente por conexiones más rápidas y estables. Este comportamiento de los usuarios sugiere la necesidad de ajustar las ofertas y planes de servicios para satisfacer mejor las expectativas y necesidades de los consumidores.

En conclusión, Argentina está progresando significativamente en términos de acceso y calidad del servicio de internet. No obstante, es esencial continuar invirtiendo en infraestructura, especialmente en las áreas rurales y menos desarrolladas, para reducir las brechas digitales y asegurar que todos los ciudadanos puedan beneficiarse del acceso a internet. Monitorear estos indicadores clave de rendimiento de manera constante permitirá adaptar estrategias efectivas y garantizar un desarrollo continuo y equitativo en el ámbito de las telecomunicaciones.

## Agradecimientos

Gracias por revisar este proyecto. Agradezco cualquier sugerencia o mejora que puedan proporcionar. Espero que este análisis sea útil para comprender mejor el estado actual de las telecomunicaciones y el acceso a internet en Argentina.

---

**Autor**: Santiago Quiceno Novoa

**Fecha**: 17/12/2024

---

¡Gracias por revisar el proyecto! No dudes en contribuir con sugerencias o mejoras.

