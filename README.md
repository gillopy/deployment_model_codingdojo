# deployment_model_codingdojo
Deployment a simple machine learning model


```python
model_training/
├── src/
│   ├── data/
│   │   ├── data_loader.py       # Carga de datos
│   │   ├── data_splitter.py     # División de datos
│   │   ├── data_processor.py    # Procesamiento de datos
│   ├── model/
│   │   ├── trainer.py           # Entrenamiento del modelo
│   │   ├── evaluator.py         # Evaluación del modelo
│   │   ├── saver.py             # Guardado del modelo
│   ├── main.py                  # Orquestación del entrenamiento
├── data/
│   ├── pima_diabetes.csv        # Dataset de los Pima Indian
├── models/
│   ├── trained_model.pkl        # Modelo entrenado (generado tras el entrenamiento)
├── requirements.txt             # Dependencias necesarias
```