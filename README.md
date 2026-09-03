# 🧬 Clasificando secuencias biológicas con Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00?logo=googlecolab)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-purple)
![PyLadies](https://img.shields.io/badge/PyLadies-Cuernavaca-e91e63)
![Code License: MIT](https://img.shields.io/badge/Code%20License-MIT-yellow.svg)
![Content License: CC BY 4.0](https://img.shields.io/badge/Content%20License-CC%20BY%204.0-lightgrey.svg)

Material del taller práctico **“Clasificando secuencias biológicas con Deep Learning”**, organizado por **PyLadies Cuernavaca** e impartido en el **Instituto de Biotecnología de la Universidad Nacional Autónoma de México (IBt-UNAM)**.

📅 **Fecha:** 12 de septiembre de 2025  
🕓 **Horario:** 16:00 – 18:00 h  
📍 **Lugar:** Instituto de Biotecnología, UNAM — Cuernavaca, Morelos  
👩‍💻 **Instructora:** Alida Zárate  

---

## 🧬 Sobre el taller

Este taller introduce de manera práctica algunos conceptos fundamentales de **Deep Learning aplicado al análisis de secuencias biológicas**.

A lo largo del taller se explora un problema de clasificación de **proteínas virales**, utilizando secuencias correspondientes a diferentes grupos virales y transformándolas en representaciones que puedan ser utilizadas por modelos de aprendizaje profundo.

El objetivo es mostrar, de manera accesible, cómo podemos pasar de una **secuencia de aminoácidos** a un problema de **clasificación mediante Deep Learning**.

---

## 📚 Temas

Durante el taller se abordan conceptos como:

- Secuencias de proteínas virales
- Formato FASTA
- Obtención de secuencias desde NCBI Virus
- Aminoácidos y codificación de proteínas
- Preparación de secuencias para modelos de Deep Learning
- Inteligencia Artificial y Deep Learning
- Redes Neuronales Convolucionales (CNN)
- Función de activación ReLU
- Max Pooling
- Redes residuales (ResNet)
- Softmax
- Épocas, iteraciones y tamaño de batch
- Clasificación de secuencias biológicas

---

## 🦠 Problema de clasificación

Durante el taller se trabaja con proteínas virales pertenecientes a tres clases:

| Clase | Grupo |
|:---:|---|
| 0 | SARS-CoV-2 |
| 1 | Orthoherpesviridae |
| 2 | Bacteriófagos |

Las secuencias utilizadas para ejemplificar el flujo de trabajo fueron obtenidas de **NCBI Virus**.

---

## 📂 Contenido del repositorio

```text
.
├── Pyladies_DeepLearning/Data/
│   ├── Secuencias_prueba/
│   ├──- Astroviridae.fasta
│   ├──- Bacteriofagos.fasta
│   ├──- Orthoherpesviridae.fasta
│   ├──- Orthomyxoviridae.fasta
│   └──- Sars-CoV-2.fasta
│
├── Curso_Pyladies_Clasificando_Proteinas_Deep_Learning.ipynb
├── DeepLearning_Para_Secuencias_Biologicas.pptx.pdf
├── README.md
└── LICENSE