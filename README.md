# MLTutorial

# Del script de forest fires:
# ¿Se desea resolver el problema utilizando aprendizaje supervisado o no supervisado? ¿Es un problema de clasificación o de regresión?
# Se desea resolver el problema utilizando aprendizaje supervisado ya que además de los atributos se tiene la etiqueta área quemada del bosque.
# Es un problema de regresión pues se está trabajando con valores continuos.
# ¿Qué interpretación le puede dar a los resultados obtenidos?
# El porcentaje de error de los datos de prueba fue bajo, quiere decir que el modelo tiene una alta precisión

# Del script de recursos humanos (rrhh):
# ¿Cuál es la clase para la que el modelo más se equivoca? ¿Por qué?

# ¿Cuál cree que es el propósito del parámetro max_depth usado al momento de instanciar el modelo de árbol de decisión?
# El max_depth define el número máximo de niveles del árbol de decisión o el número de veces que se va a bifurcar.
# Para este caso particular, ¿por qué cree que es difícil obtener un buen clasificador?
# Hay pocos datos para entrenar y probar el modelo, también pocos atributos

# Identificación de géneros musicales: Tenga en cuenta que hay dos scripts: music.ipynb y music-multiclass.ipynb. En el primero se intenta crear un modelo clasificador # # solo para dos clases (caso binario) y en el segundo se entrena uno para todas las clases (géneros musicales) del dataset.
# Para el caso binario (jazz and blues vs. soul and reggae) ¿Es posible obtener mejores métricas entrenando un modelo basado en Random Forest?
# Escoja otro par de géneros, entrene un conjunto de modelos y documente los resultados del mejor que se haya obtenido.
# Para el caso multi-clase, ¿cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
# Para el caso multi-clase, el modelo basado en red neuronal parece estar mayoritariamente sesgado hacia un género particular ¿Cuál género cree que es?

# Segmentación de cajas de compensación familiar (subsidio):
# ¿Qué cajas de compensación parecen ser mayoritariamente diferentes a las demás?
# ¿A partir de qué características utilizadas para el entrenamiento del modelo se podría explicar la razón por la que las cajas anteriores fueron agrupadas en clusters # # tan pequeños?
# ¿Se pueden obtener resultados más homogéneos utilizando cantidades diferentes de clusters para el entrenamiento? Entienda homogeneidad como clusters con cantidades # # # similares de instancias de datos.
