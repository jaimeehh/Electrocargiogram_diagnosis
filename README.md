# Electrocargiogram_diagnosis

## 📌 Descripción
Este repositorio contiene el notebook `Electrocargiogram_diagnosis.ipynb`, que aborda el análisis y procesamiento de datos para el reto de la versión 2023-2024.

## 📂 Estructura del repositorio
- `notebooks/` → Contiene el Jupyter Notebook principal.
- `src/` → Scripts en Python (funciones auxiliares, procesamiento de datos, etc.).
- `data/` → Datos crudos y procesados.
- `docs/` → Documentación y archivos relacionados.
- `requirements.txt` → Lista de dependencias necesarias.
- `.gitignore` → Archivos y carpetas que no deberían subirse a GitHub.

## 📚 Información académica
**Grado en Ingeniería Biomédica**  
**Universidad Rey Juan Carlos**

## 👥 Autores
- **Juan Luis Pareja Mora** 
- **Jaime Hernández Hernández** ([j.hernandezher.2020@gmail.com](mailto:j.hernandezher.2020@gmail.com))
- **Tomás Castillo Migueláñez** 

## 📜 Licencia
Esta obra está bajo una licencia de **Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional**.

## ℹ️ Sobre este Challenge
El problema que queremos abordar en este Challenge es la clasificación de registros cortos de una única derivación de ECG en tres categorías diferentes:

1. **Fibrilación Auricular**
2. **Ritmo Sinusal Normal**

Este desafío se basa en el **Physionet Challenge 2017** en la conferencia Computing in Cardiology. El reto original tenía como objetivo clasificar, a partir de un único registro corto de ECG, si el registro muestra un ritmo sinusal normal, fibrilación auricular (AF), un ritmo alternativo o si es demasiado ruidoso para ser clasificado.

El conjunto de datos consta de registros de ECG recogidos mediante el dispositivo **AliveCor**, generosamente donados para el Physionet Challenge por AliveCor. El conjunto de entrenamiento original contiene **8,528** registros de ECG de una sola derivación con duraciones de **9 segundos hasta poco más de 60 segundos**.

Los registros de ECG fueron muestreados a **300 Hz** y han sido filtrados con un **filtro paso banda** por el dispositivo AliveCor. Todos los datos están en formato **MATLAB V4 WFDB-compliant** (cada uno incluye un archivo `.mat` que contiene el ECG y un archivo `.hea` que contiene la información de la forma de onda).

## 🚀 Instalación y uso
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/jaimeehh/Electrocargiogram_diagnosis.git
   cd Electrocargiogram_diagnosis
   ```
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```
   o, si usas conda:
   ```bash
   conda env create -f environment.yml
   ```

3. Abrir el Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## ✨ Contribución
Si deseas contribuir, por favor abre un *pull request*.

---


