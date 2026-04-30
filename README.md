## Cómo ejecutar este Notebook

Este repositorio contiene un análisis y desarrollo de una Red Neuronal Multicapa (MLP) para la clasificación del dataset Fashion-MNIST. A continuación, se detallan los pasos para configurar el entorno y ejecutar el notebook.

### Prerrequisitos

Asegúrate de tener instalado Python 3.8+ y `pip`.

### 1. Instalación de Dependencias

Este proyecto utiliza las siguientes librerías de Python. Puedes instalarlas ejecutando el siguiente comando:

```bash
pip install tensorflow numpy matplotlib scikit-learn pandas
```

### 2. Ejecución del Notebook

#### Opción A: Google Colab (Recomendado)

La forma más sencilla de ejecutar este notebook es abrirlo directamente en Google Colab. Colab proporciona un entorno preconfigurado con las librerías necesarias y acceso a GPUs, lo cual es ideal para el entrenamiento de modelos de Deep Learning.

1.  Haz clic en el siguiente enlace: [Abrir en Google Colab](https://colab.research.google.com/github/tu_usuario/tu_repositorio/blob/main/tu_notebook.ipynb) (Asegúrate de reemplazar `tu_usuario`, `tu_repositorio` y `tu_notebook.ipynb` con los valores correctos de tu repositorio de GitHub).
2.  Una vez abierto en Colab, ve a `Entorno de ejecución > Ejecutar todas` para ejecutar todas las celdas del notebook.

#### Opción B: Ejecución Local

Si prefieres ejecutar el notebook en tu máquina local, sigue estos pasos:

1.  **Clona el repositorio**:
    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    cd tu_repositorio
    ```
2.  **Instala las dependencias** (si no lo has hecho ya):
    ```bash
    pip install -r requirements.txt
    ```
    (Nota: Es buena práctica generar un `requirements.txt` con `pip freeze > requirements.txt` después de instalar las librerías mencionadas anteriormente).
3.  **Inicia Jupyter Notebook o Jupyter Lab**:
    ```bash
    jupyter notebook
    # o
    jupyter lab
    ```
4.  En la interfaz de Jupyter, navega hasta el archivo del notebook (`tu_notebook.ipynb`) y ábrelo.
5.  Puedes ejecutar las celdas individualmente o ir a `Cell > Run All` para ejecutar todo el notebook.
