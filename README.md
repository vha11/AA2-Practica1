# Hola, bienvenid@ al repositorio de la Práctica No.1 de Aprendizaje Automático II

Esta práctica está dividida en dos partes:

---

## Parte 1

* Diseñar y entrenar una red de convolución que prediga la rotación de la flecha en el pavimento.
* Cargar una VGG-16 y usar *Transfer Learning* para el mismo propósito.
* Comparar los resultados obtenidos.

La implementación correspondiente se encuentra en la carpeta:

```
Parte1_CNN
```

### Configuración del entorno virtual (obligatorio)

Dentro de la carpeta `Parte1_CNN` se debe crear un entorno virtual antes de ejecutar el proyecto.

1️. Crear el entorno virtual:

```
python -m venv venv
```

2️. Activarlo según el sistema operativo:

* **Windows:**

```
venv\Scripts\activate
```

* **MacOS / Linux:**

```
source venv/bin/activate
```

3️. Instalar las dependencias:

```
pip install -r requirements.txt
```

⚠️ El entorno virtual (`venv/`) no debe subirse al repositorio.
Cada persona debe crearlo en su propia computadora.

---

## Parte 2

* Diseñar y entrenar una arquitectura *Transformer* para predecir los valores futuros de una sinusoidal.
* Aplicarla a la predicción de valores de las acciones de una empresa usando `yfinance`.

La implementación correspondiente se encuentra en la carpeta:

```
Parte2_Transformers
```

---

Se recomienda trabajar cada parte dentro de su propia carpeta y respetar la estructura del proyecto.
