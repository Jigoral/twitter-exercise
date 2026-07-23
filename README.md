
## Preguntas de análisis

1. ¿La cantidad de respuestas (replies) difiere según el número de usuarios etiquetados (tagged_users)?
2. ¿La cantidad de posts del usuario (posts_count) está asociada con el número de likes que recibe un post?

## Conclusiones

1. Sí: la cantidad de respuestas difiere significativamente según cuántos usuarios se etiquetan (prueba de Kruskal-Wallis, p < 0.05).
2. Hay una asociación positiva pero débil entre posts_count y likes (Spearman rho ≈ 0.22, p < 0.05).

## Cómo ejecutarlo

1. Cloná o descargá el repositorio.
2. Asegurate de que `twitter-posts.csv` esté en la misma carpeta que el notebook.
3. Abrí `twitter-posts-tp-final.ipynb` con Jupyter Notebook, JupyterLab o VS Code.
4. Ejecutá las celdas en orden.

## Librerías utilizadas

pandas, numpy, scipy, matplotlib, seaborn
