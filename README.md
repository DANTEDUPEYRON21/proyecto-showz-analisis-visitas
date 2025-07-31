📊 Proyecto 9 – Análisis de Marketing para Showz
Este proyecto forma parte del programa de Data Analytics en TripleTen. El objetivo es ayudar a optimizar los gastos de marketing de Showz, una empresa dedicada a la venta de entradas para eventos, mediante el análisis del comportamiento de los usuarios y la rentabilidad de las campañas publicitarias.

📌 Objetivos del proyecto
Analizar cómo los clientes usan el servicio.

Determinar cuándo los usuarios comienzan a comprar.

Calcular cuánto dinero aporta cada cliente a la compañía.

Identificar en qué momento los ingresos cubren el costo de adquisición de clientes (ROI).

📂 Dataset utilizado
Se proporcionaron tres archivos con información del periodo enero 2017 – diciembre 2018:

visits_log_us.csv

uid: identificador único del usuario.

device: tipo de dispositivo.

start_ts, end_ts: inicio y fin de la sesión (AAAA-MM-DD).

source_id: fuente publicitaria.

orders_log_us.csv

uid: identificador único del comprador.

buy_ts: fecha y hora del pedido.

revenue: ingresos generados por el pedido.

costs_us.csv

source_id: identificador de la fuente publicitaria.

dt: fecha del gasto.

costs: monto gastado en la fuente publicitaria ese día.

🛠️ Tecnologías y librerías utilizadas
Python 3

Pandas – para manipulación de datos.

NumPy – para cálculos numéricos.

Matplotlib y Seaborn – para visualizaciones.

📑 Flujo de trabajo
Carga y limpieza de datos

Estandarización de nombres de columnas.

Conversión de formatos de fecha.

Revisión de valores nulos y duplicados.

Análisis exploratorio (EDA)

Tendencias de visitas y pedidos.

Comportamiento de usuarios nuevos y recurrentes.

Distribución de ingresos por fuente publicitaria.

Cálculo de métricas clave

ARPU (Average Revenue Per User).

CAC (Customer Acquisition Cost).

ROI (Return on Investment) por canal publicitario.

Visualización de resultados

Gráficos de tendencia de usuarios y conversiones.

Comparativa entre gastos y retornos por canal.

👤 Autor
Dante Dupeyron Puig
🔗 LinkedIn


💻 GitHub
