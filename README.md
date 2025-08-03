# 🎯 Mini Portafolio: Sistemas de Recomendación con Python

Este repositorio contiene implementaciones prácticas de sistemas de recomendación utilizando Python. Se incluyen dos enfoques fundamentales: **filtrado colaborativo** usando `LightFM` y **filtrado basado en contenido** usando `scikit-learn`.

---

## 📦 Estructura del Proyecto

```
recommender_portfolio/
├── data/
│   └── ratings.csv                # Dataset simulado de usuarios, ítems y calificaciones
├── notebooks/
│   ├── 01_filtrado_colaborativo_lightfm.ipynb   # Recomendación basada en usuarios con LightFM
│   └── 02_filtrado_contenido.ipynb              # Recomendación basada en contenido con TF-IDF
├── src/                          # Carpeta para funciones reutilizables (vacía por ahora)
├── requirements.txt              # Lista de dependencias para instalar el entorno
└── README.md                     # Documentación general
```

---

## 🔧 Requisitos

- Python 3.8+
- pip

### Instalación de dependencias

```bash
pip install -r requirements.txt
```

---

## 📊 Notebooks

### 1. Filtrado Colaborativo (`LightFM`)
- Utiliza interacciones explícitas (calificaciones de 1 a 5).
- Aplica el modelo WARP de `lightfm` para generar recomendaciones personalizadas.
- Evalúa el rendimiento con `precision@k`.

### 2. Filtrado por Contenido
- Usa descripciones simuladas de ítems (categorías).
- Calcula similitud de coseno con TF-IDF para recomendar ítems similares a los ya consumidos.

---

## 💡 Dataset

- Simulado para propósito educativo.
- Contiene 10 usuarios, 4 ítems (`A`, `B`, `C`, `D`) y calificaciones de 1 a 5.
- Puede ser reemplazado fácilmente por cualquier dataset real (como MovieLens).

---

## 📈 Resultados Esperados

- Recomendaciones generadas por usuario o ítem.
- Métricas como precisión (`precision@k`) y similitud de coseno para evaluar calidad.
- Fácil de adaptar para nuevos datasets o enfoques híbridos.

---

## 📚 Referencias

- [`LightFM`](https://github.com/lyst/lightfm)
- [`scikit-learn`](https://scikit-learn.org/)
- [Curso de Recomendación - Coursera](https://www.coursera.org/learn/recommender-systems)

---

## 👨‍💻 Autor

**Francis Javier Vicente Romero**  
Data Engineer | Ciencia de Datos | Python & Cloud  
Maestría en Ciencia de Datos, UPC

---

## 📬 Contacto

¿Dudas o sugerencias? ¡Con gusto! Puedes escribirme o crear un issue en el repositorio.
