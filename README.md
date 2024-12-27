# Datos Exploratorios de Kaggle

## Descripción del Proyecto
Este proyecto explora los datos obtenidos del conjunto de datos ["Mexico Minerometallurgical Stats 2001-2023"](https://www.kaggle.com/datasets/valamcortes/mexico-minerometallurgical-stats-2001-2023) disponible en Kaggle. El objetivo principal es analizar y visualizar las Estadísticas de la Industria Minerometalúrgica (EIMM) en México.

### Descripción del Dataset
Las Estadísticas de la Industria Minerometalúrgica (EIMM) tienen como objetivo proporcionar indicadores confiables y oportunos sobre el volumen y valor de la producción minerometalúrgica. La caracterización de los datos se extiende a nivel nacional, por estado y a los municipios con actividad minera en México desde 2001 hasta 2023.

## Requisitos
- Python 3.8 o superior
- Librerías:
  - `pandas`
  - `numpy`
  - `matplotlib`

Para instalar las dependencias, utiliza el siguiente comando:
```bash
pip install pandas numpy matplotlib
```

## Código de Ejemplo
El siguiente fragmento de código ilustra la carga y manipulación de los datos:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Lectura de datos
entrenamiento = pd.read_csv('Minerometallurgical_production_by_main_products.csv')
prueba = pd.read_csv('Minerometallurgical_production_by_main_products.csv')

# Exploración de los datos
print(entrenamiento.head())
print(entrenamiento.columns)
print(entrenamiento.shape)
```

## Análisis Exploratorio
1. **Carga de Datos**: Los datos se cargan desde un archivo CSV local utilizando `pandas`.
2. **Exploración**: Se revisan las primeras filas, las columnas disponibles y la dimensión del conjunto de datos.
3. **Visualización** (en desarrollo): Se utilizará `matplotlib` para crear visualizaciones que ayuden a interpretar las tendencias y patrones del conjunto de datos.

## Uso de los Datos
Los datos utilizados en este proyecto fueron descargados de Kaggle y están sujetos a los términos y condiciones de la plataforma. Asegúrate de revisar la licencia del conjunto de datos antes de reutilizarlos.

## Notas Adicionales
- Si deseas contribuir o tienes sugerencias, por favor abre un *issue* o envía un *pull request*.
- Si encuentras algún problema con los datos o el código, no dudes en contactarnos.

## Referencias
- Kaggle Dataset: [Mexico Minerometallurgical Stats 2001-2023](https://www.kaggle.com/datasets/valamcortes/mexico-minerometallurgical-stats-2001-2023)

---

¡Gracias por tu interés en este proyecto! 

## Contacto
https://www.linkedin.com/in/arturo-garc%C3%ADa-9240a9216/
