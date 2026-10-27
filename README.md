# Proyecto Big Data · Criptomonedas

**Un proyecto de exploración de precios de criptomonedas y conversaciones en redes sociales.**

Este repositorio conserva materiales de análisis sobre **Bitcoin, Ethereum y Dogecoin**: series de precios, archivos de tweets, notebooks, prototipos de extracción con Python y visualizaciones de Tableau. Es un trabajo histórico (2022), útil para estudiar el enfoque y los datos disponibles, no un servicio de analítica en producción.

## Qué podés explorar

| Componente | Dónde está | Contenido |
| :-- | :-- | :-- |
| Datos | [`Criptomonedas/backend/`](Criptomonedas/backend/) | CSV de velas BTC/ETH/DOGE y registros vinculados a variación de precios y tweets. |
| Exploración | [`crypto_tweets.ipynb`](Criptomonedas/backend/crypto_tweets.ipynb) | Notebook Jupyter de experimentación. |
| API experimental | [`app.py`](Criptomonedas/backend/app.py) | Prototipo Flask con MongoDB, fuentes de tweets y CoinGecko. |
| Visualización | [`Criptomonedas/Tableau/`](Criptomonedas/Tableau/) | Libros de trabajo de Tableau (`.twb` y `.twbx`). |

## Cómo empezar

1. Para una revisión **sin dependencias externas**, empezá por los CSV, notebooks y archivos de Tableau.
2. Para estudiar el backend, mirá [el código Python](Criptomonedas/backend/app.py) y [las dependencias fijadas](Criptomonedas/backend/requirements.txt).
3. Si querés ejecutar el prototipo, prepará **un entorno aislado** con versiones compatibles de Python y configurá por tu cuenta MongoDB y las credenciales de APIs necesarias.

> [!CAUTION]
> El backend usa bibliotecas y endpoints históricos de Twitter y otros servicios; no se verificó que puedan funcionar hoy. No ejecutes ni publiques credenciales de conexión. La presencia de código de extracción no equivale a un pipeline actualizado o reproducible de punta a punta.

## Tecnologías y alcance

Python, Flask, pandas, Jupyter, MongoDB, bibliotecas de Twitter, CoinGecko y Tableau. Las series y resultados reflejan el período de recolección del proyecto; **no son precios de mercado actuales ni recomendaciones financieras**.

## Licencia

No se encontró un archivo de licencia en el repositorio. Su reutilización queda sujeta a los derechos correspondientes.
