📚 Educación Superior y Desarrollo Económico
Análisis de la relación entre matriculación, PBI per cápita y tasa de natalidad (1990–2021)

📖 Descripción

El dataset construido presenta información sobre la matriculación en educación superior, el PBI per cápita y la tasa de natalidad de distintos países entre los años 1990 y 2021, junto con el continente correspondiente.

El objetivo principal es explorar la relación entre el desarrollo económico y el acceso a la educación superior, considerando además la evolución demográfica de cada país.

📊 Fuentes de Datos

Paises por Continente:

Kaggle – Countries by Continent

https://www.kaggle.com/datasets/hserdaraltan/countries-by-continent?resource=download

Indicadores Económicos y Educativos:

World Bank API

https://datahelpdesk.worldbank.org/knowledgebase/topics/125589-developer-information

Datos de UNESCO:

UNESCO Reader (PyPI)

https://pypi.org/project/unesco-reader/

🧾 Diccionario de Datos

Columna	Descripción

Continente - Nombre del continente en el cual se encuentra el país.

Pais - Nombre del país.

Año -	Año de los datos del PBI y matriculación.

PIB_per_capita_USD - PBI per cápita en dólares del país.

Porcentaje_Matriculas - Tasa bruta de matriculación en educación terciaria o universitaria (% de la población en edad correspondiente).

Año_Natalidad - Año correspondiente a 19 años antes del dato de matriculación.

Tasa_Natalidad - Cantidad de nacimientos vivos por cada 1.000 habitantes.

🎯 Objetivo

Entrenar un modelo para predecir la matriculación futura en educación superior a partir de la tasa de natalidad y las proyecciones del PBI per cápita.
Esto permitirá anticipar la demanda educativa y planificar políticas de acceso o infraestructura de manera eficiente.

💼 Contexto Comercial

El acceso a la educación superior impulsa el desarrollo económico y social de los países.
Analizar los factores que influyen en la matriculación permite diseñar políticas públicas más efectivas y mejorar la equidad educativa.

👥 Audiencia

Dirigencias y organismos vinculados a la educación superior.

Áreas de planificación en gobiernos nacionales y regionales.

Organizaciones no gubernamentales interesadas en educación y desarrollo.

🧠 Problema Comercial y Contexto

En las últimas décadas, la tasa de natalidad ha disminuido globalmente, mientras que las economías muestran fluctuaciones e inestabilidad.
Ambos factores podrían afectar el porcentaje de matriculación a la educación superior.

💡 Hipótesis

La disminución de la natalidad reduce la cantidad de estudiantes potenciales, pero no necesariamente el porcentaje de matriculación, ya que este depende del grupo etario.

El PBI per cápita influye directamente en la tasa de matriculación: una mayor estabilidad económica permite que más jóvenes continúen su educación en lugar de ingresar al mercado laboral.

⚙️ Metodología

Recolección de datos desde las APIs del World Bank y UNESCO, y dataset de países por continente (Kaggle).

Limpieza y unificación de los datos, armonizando nombres de países y años.

Análisis exploratorio (EDA) con visualizaciones interactivas (Plotly).

Creación de variables derivadas, como “Año_Natalidad”.

Evaluación de correlaciones entre PBI, natalidad y matriculación.

Desarrollo de modelo predictivo para estimar futuras tasas de matriculación.

📈 Resultados Esperados

Determinar qué variable (PBI o natalidad) tiene mayor impacto en la matriculación.

Visualizar tendencias y diferencias entre continentes.

Generar proyecciones de matriculación por país o región.

Proveer información útil para la planificación educativa y económica.

🧩 Tecnologías Utilizadas

Python (pandas, numpy, matplotlib, plotly, scikit-learn)

Google Colab

GitHub

APIs: World Bank, UNESCO

📬 Autora

Catalina Siches
Proyecto del curso de Data Science – Coder House
