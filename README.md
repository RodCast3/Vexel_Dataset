# Vexel_Dataset

Repositorio de imágenes biométricas filtradas y clasificadas para el entrenamiento de modelos de reconocimiento facial, desarrollado como parte del proyecto de tesis:  
**Sistema de control de acceso hospitalario basado en reconocimiento biométrico utilizando redes neuronales.**

## 📄 Descripción

Este conjunto de datos fue construido con 2,000 imágenes originarias del dataset MeGlass, clasificadas por identidad y filtradas mediante técnicas de preprocesamiento (detección de rostro, redimensionamiento y realce de bordes). 
El objetivo del dataset es proporcionar material visual para el entrenamiento de modelos como FaceNet, bajo escenarios realistas y variados.

Las imágenes se organizan por carpetas etiquetadas con identificadores anónimos, lo que facilita su uso en tareas de clasificación, comparación de embeddings y pruebas de reconocimiento.

## 🔗 Enlace al dataset original:
https://github.com/cleardusk/MeGlass

## 🧠 Tecnologías aplicadas en la construcción
- OpenCV (detección y recorte de rostros)
- MTCCN para recorte de rostros
- Filtro Sobel para realce de bordes
- Clasificación manual y validación visual
