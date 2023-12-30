**1,2,6,7,10,13**
> Done (nelson): 1, 2, 6, 7, 

### Preparación de Datos y Entorno de Trabajo
1. *Adaptar y Preparar el Conjunto de Datos*:
   - Organizar las imágenes en carpetas.
   - Balancear los conjuntos de datos para garantizar una distribución uniforme de las clases.

2. *División del Conjunto de Datos*:
   - Dividir los datos en 70% para entrenamiento, 20% para validación y 10% para pruebas.

3. *Transformaciones de Datos y Data Augmentation*:
   - Definir transformaciones adecuadas para las imágenes (normalización, escalado).
   - Aplicar técnicas de data augmentation (rotación, etc.).

4. *Configuración de DataLoaders*:
   - Configurar DataLoader para cada uno de los conjuntos de datos para manejar lotes de imágenes durante el entrenamiento y la validación.

### Construcción y Entrenamiento de Modelos
5. *Definición de Modelos de Redes Neuronales*:
   - Construir un modelo de red neuronal básico sin preentrenamiento.
   - Para un proyecto posterior, adaptar un modelo de red neuronal con preentrenamiento.

6. *Bucle de Entrenamiento*:
   - Implementar el proceso de entrenamiento y validación, incluyendo cálculos de pérdida y precisión (accuracy).

7. *Funciones de Métricas y Pérdida*:
   - Utilizar CrossEntropyLoss como función de pérdida.
   - Calcular métricas de rendimiento: precisión, recall y F1-score.

8. *Implementación de Early Stopping*:
   - Integrar early stopping para evitar el sobreentrenamiento durante las iteraciones de entrenamiento.

### Evaluación y Ajuste
9. *Evaluación del Modelo*:
   - Evaluar el modelo con los conjuntos de validación y pruebas.
   - Utilizar la matriz de confusión para analizar el rendimiento del modelo.

10. *Ajuste de Hiperparámetros*:
   - Experimentar con distintas configuraciones de hiperparámetros para mejorar los resultados del modelo.

11. *Guardado y Carga de Modelos*:
   - Implementar funcionalidades para guardar el modelo entrenado y cargarlo para uso futuro o inferencia.

### Documentación y Repetibilidad
12. *Documentación del Proceso*:
   - Documentar el proceso de entrenamiento, parámetros usados y los resultados obtenidos.

13. *Revisión de Arquitecturas de Red (Opcional)*:
   - Para un segundo proyecto, considerar la revisión y comparación de diferentes arquitecturas de red neuronal para seleccionar la que mejor se ajuste al problema.

Con estas tareas organizadas de forma clara, se minimiza la repetición y se proporciona un flujo de trabajo secuencial que es fácil de seguir y mantiene una carga de trabajo equilibrada. Esto debería proporcionar una base sólida para construir un catalogador de imágenes utilizando PyTorch.