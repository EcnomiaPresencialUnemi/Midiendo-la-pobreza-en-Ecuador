# Midiendo-la-pobreza-en-Ecuador
Medición de la pobreza por ingresos en Ecuador con Python

Este repositorio contiene el material del taller:

📊 **"Midiendo la pobreza por ingresos en Ecuador con Python"**  
📍 Universidad Estatal de Milagro (UNEMI)  
📅 Junio 2025 | 💻 Google Colab

---

## 🧾 Contenido

- Notebook en Python para análisis de pobreza con ENEMDU
- Cálculo de incidencia (FGT0) por provincia usando `pandas`
- Carga y uso de microdatos en formato `.sav`
- Exportación y visualización de resultados en Colab

---

## 📂 Datos

El archivo `BDDenemdu_personas_2024_anual.sav` está disponible en la carpeta `/DATA` y puede ser usado directamente en Google Colab.

### 🔗 Cómo cargar en Python

```python
import pyreadstat
df, meta = pyreadstat.read_sav("data.sav")
```

## ▶️ Cómo abrir el notebook en Google Colab

### 📘 Abrir el notebook en Google Colab

[![Abrir en Colab](https://github.com/EcnomiaPresencialUnemi/Midiendo-la-pobreza-en-Ecuador/blob/main/Pobreza_Ecuador.ipynb)


---

## 🧑‍🏫 Licencia

Este material está disponible bajo la [Licencia MIT](LICENSE), lo puedes usar, modificar y compartir con libertad, siempre dando crédito al autor.

---

¡Gracias por participar en el taller!

