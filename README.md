# DSC3
Pipeline de entrenamiento en PyTorch y clasificador base

# Pre-entrega 1: Pipeline de entrenamiento y clasificador base

## Descripción del Proyecto
Implementación de un pipeline de entrenamiento y validación en PyTorch utilizando un clasificador base (MLP) sobre el dataset de personalidades MBTI.

## Fuente del dataset
https://www.kaggle.com/datasets/datasnaek/mbti-type?resource=download

## Entorno y Tecnologías
- **PyTorch Version**: 2.11.0+cpu
- **Dispositivo**: Detección dinámica (`cuda` / `mps` / `cpu`)

## Hiperparámetros
- **Optimizador**: Adam
- **Learning Rate**: 0.001
- **Épocas**: 10
- **Batch Size**: 32
- **Función de Pérdida**: CrossEntropyLoss

## Resultados y Conclusiones
- Evolución de la pérdida (Loss): para cada corrida la pérdida fue disminuyendo de 0,56 a 0,52.
- Accuracy alcanzada en el conjunto de validación: 77%
