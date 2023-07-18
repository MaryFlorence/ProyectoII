# Proyecto II: Data Analytics

Este proyecto tiene como objetivo analizar el mercado argentino de las telecomunicaciones y explorar las oportunidades de crecimiento en el contexto de la transformación digital. Se busca comprender las principales problemáticas de negocio que enfrentan y proponer algunos espacios de oportunidad para evolucionar a Trust Advisor en tecnología, generar valor agregado para retención de clientes y elevar el ticket promedio.

## Contenido de este repositorio
El repositorio incluye los siguientes elementos:

Notebooks de ETL y EDA: Estos Notebooks contienen las transformaciones de los datasets en un formato adecuado, y  la exploracion analítica para comprender los datos, realizar visualizaciones, identificar patrones y tendencias, y obtener información valiosa para la toma de decisiones.

Conjuntos de datos: Se incluyen los conjuntos de datos relevantes utilizados en los Notebooks, que abarcan aspectos como los ingresos por internet, la telefonía móvil, la penetración de internet por provincia, entre otros. Estos conjuntos de datos permiten llevar a cabo análisis detallados y obtener información sobre el mercado argentino de las telecomunicaciones.

Dashboard de Power BI:  Se encuentan dos capturas: el principal y el anexo. Esto permite una exploración más profunda de los datos y una presentación visual de los hallazgos obtenidos durante el análisis.

## Herramientas utilizadas:

- Python
- Librerias: pandas, numpy, matplotlib, seaborn
- PowerBI

## Analisis del mercado de Telecomunicaciones en Argentina

![Captura Dashboard principal](ProyectoII/Dashboard_principal.PNG)

[colocar dashboard]
 *El analisis contiene datos históricos, desde el 2014 al 2022, y se centra especificamente en el 2022 como último año y que se tomará como actual.

En Argentina, hay tres operadoras principales, que se reparten casi equitativamente el mercado. Claro representa el 39%, Personal el 34%, y Movistar el 27% del mercado de las telecomunicaciones. Claro es de origen mexicano, Movistar de España y Personal es Argentina (perteneciente al grupo Telecom).
En el dashboard podemos obsevar un mapa con los accesos a internet por cada 100 hogares, en todo el territorio nacional argentino. Contrastando con la distribución territorial de la población según el último censo nacional [link](https://censo.gob.ar/index.php/datos_provisionales/), podemos observar una relación directa siendo los principales puntos con mayor acceso: Buenos Aires, Ciudad de Buenos Aires, Córdoba, Santa Fe, Mendoza. También podemos observar que Argentina tiene una conectividad a internet del 87%, cuando la media en el mundo es del 63%.
Luego podemos observar los ingresos por Internet y Telefonia movil, principales servicios que constituyen el 65% de la facturacion total de estas empresas. Los gráficos lineales muestran una tendencia ascendente de ambos servicios.

Entrando en mayor detalle, en el gráfico de 'Altas/Bajas Portabilidad por empresa' podemos analizar el comportamiento de los clientes entre las tres operadoras, a lo largo de los últimos años. Movistar es la que mayor cantidad de bajas reporta en este período. Según estudios de consultora, como IDC, y estados financieros presentados por las operadoras, el ticket promedio por usuario es de 5usd, y la tasa de baja promedio del 5% (en algunos casos hay empresas con 7%). Sabemos que el costo de adquisicion por nuevo cliente siempre es más elevado que mantenerlo cautivo, por lo cual esto definitivamente es una variable de perdida importante para las empresas. En un contexto de competencia oligopólica, los servicios prestados se terminan commoditizando y por ende la rotación es alta. Por otro lado, haciendo benchmark con otras operadoras a nivel mundial, el ticket promedio por usuario es considerablemente más alto llegando incluso a 30usd o más.

Es por ello que dada la problemática actual, es relevante medir progresivamente (mensualmente) con los siguientes 3 KPIs:
ARPU: Average Revenue per user. El mismo se mide con facturación total dividido cantidad de clientes. Es importante medir mensualmente la evolución de ese ticket sea que venga por estrategias de upselling, o new revenue steams.
Churn: Tasa de baja. El mismo se mide diviendo la cantidad de bajas de clientes del mes actual y el baseline del mes anterior.
Digital Mix: Porcentaje de la facturación de servicios digitales dividido el total de facturación.

![Captura Dashboard_propuesta](ProyectoII/Dashboard_anexo.PNG)

Para poder cambiar esta tendencia de ARPU bajo, churn alto, propongo la exploración de algunos espacios de oportunidad y crecimiento. Haciendo leverage de las fortalezas que tienen las empresas de telecomunicaciones como integrador de servicios, el know how en networking, y la gran cobertura de clientes a nivel nacional, pueden desarrollar un rol fundamental en el ecosistema de IoT. Me pareció clave para abordar este analisis, contemplar las verticales/sectores con mayor participación en el PBI, para entender cuales son las industrias con mayor potencial. En este caso: industria manufacturera, comercio, transporte, inmobiliaria, y el sector del agro. También ubicar ese potencial geograficamente: Buenos Aires, Ciudad de Buenos Aires, Santa Fe, Córdoba, Mendoza. Según un estudio realizado por GSMA, en América Latina presenta más de 900 millones de conexiones IoT en 2022. Por otro lado, se presenta una tabla comparativa entre las tres empresas en materia de latencia y velocidad de descarga. Para ambas categorias, Personal es la que mejor se presenta, seguido por Claro y luego Movistar. Además, el negocio de IoT tiene varios componentes que no solo tienen que ver con la integración y la conectividad, sino que también hay una gran oportunidad para monetizar la data que van a generar esos dispositivos, donde se van a almacenar, procesar, y consumir. Este es el espacio y el momento para que las operadoras adopten un rol protagónico, liderando la transformacion digital en mas de 600mil empresas y con un impacto económico favorable a escala nacional.

En conclusión, la industria de las telecomunicaciones en Argentina se enfrenta a desafíos importantes, como el churn, el bajo ARPU y la commoditización de los servicios. Sin embargo, la transformación digital ofrece oportunidades interesantes para que las empresas de telecomunicaciones se reinventen y se conviertan en asesores confiables y agentes de cambio en la economía digital. Al adoptar un enfoque consultivo, invertir en tecnologías emergentes y ofrecer soluciones diferenciadas, las operadoras pueden generar crecimiento, agregar valor a sus clientes y contribuir al desarrollo económico del país.

##Fuentes adicionales consultadas:

- Banco Mundial
- IDC
- GSMA
- Indec
- CEPAL
