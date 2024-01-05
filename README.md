# CAD_Glaucoma_GUI 🚀

## Español

### Objetivo de la GUI 🎯
Esta GUI está diseñada específicamente para facilitar el análisis y procesamiento de imágenes médicas de fondo de ojo, con un enfoque particular en la detección y clasificación de defectos en la capa de fibras nerviosas de la retina, lo cual es crucial para el diagnóstico y seguimiento del glaucoma.

### Funcionalidades ✨
- **Clasificación de Imágenes:** La pestaña 'Classifier' permite visualizar imágenes en RGB o escala de grises y aplicar corrección gamma para resaltar contrastes, ayudando en la decisión de aceptar o rechazar imágenes basadas en la presencia de lesiones.
- **Etiquetado de Imágenes:** La pestaña 'Labeling' facilita la carga de imágenes para su anotación, visualización de etiquetas existentes, y la estandarización de imágenes para la consistencia del dataset.
- **Preparación para Entrenamiento de Modelo:** La pestaña 'Pre-training Model - Yolo v7' contiene herramientas para la conversión de formatos de etiquetas, selección de espacios de color, estandarización de imágenes, y división del dataset en conjuntos de entrenamiento, prueba y validación.

### Estado Actual 🔄
La GUI se encuentra en una fase funcional con capacidades completas para la clasificación y etiquetado de imágenes. La implementación para el entrenamiento de modelos, incluyendo la selección de hiperparámetros y la iniciación del entrenamiento dentro de la GUI, está planificada para futuras actualizaciones.

### Dataset 📊
Los conjuntos de imágenes utilizados para este proyecto están alojados en Roboflow. Para acceder y explorar los datasets, por favor visita https://universe.roboflow.com/rnfld/. 
Aquí encontrarás los datasets organizados y listos para su uso. Siéntete libre de descargarlos y utilizarlos de acuerdo con los términos y condiciones especificados dentro de la plataforma.

### Último Entrenamiento y Modelo Disponible 🧑‍🎓
La última sesión de entrenamiento se realizó como parte del proyecto de tesis titulado "Enhancing Glaucoma Detection: AI-driven Localization of Retinal Nerve Fiber Layer Defects". El modelo, entrenado con YOLOv8, demostró resultados prometedores:

- **Sensibilidad:** 0.91
- **Precisión:** 0.869
- **Puntuación F1:** 0.889

Si estás interesado en acceder o usar este modelo, por favor contáctame directamente. Los detalles de contacto se pueden encontrar en la sección de Contacto de este repositorio. El uso del modelo está sujeto a ciertos términos y condiciones, que se proporcionarán a solicitud.

### Citación📚
Si utilizas los datasets etiquetados, la GUI de Glaucoma, el modelo YOLOv8 o cualquier parte de la tesis en tu investigación o proyectos, por favor cítalo de la siguiente manera: "XXXX". 

Se agradece mucho el reconocimiento adecuado de estos recursos en tu trabajo y contribuye a la investigación y desarrollo continuos en este campo.


## English

### Purpose of the GUI 🎯
This GUI is specifically designed to facilitate the analysis and processing of medical fundus images, with a particular focus on the detection and classification of defects in the retinal nerve fiber layer, which is crucial for the diagnosis and monitoring of glaucoma.

### Functionalities ✨
- **Image Classification:** The 'Classifier' tab allows the visualization of images in RGB or grayscale and the application of gamma correction to highlight contrasts, aiding in the decision to accept or reject images based on the presence of lesions.
- **Image Labeling:** The 'Labeling' tab facilitates the loading of images for annotation, visualization of existing labels, and standardization of images for dataset consistency.
- **Model Training Preparation:** The 'Pre-training Model - Yolo v7' tab contains tools for label format conversion, color space selection, image standardization, and dataset division into training, test, and validation sets.

### Current State 🔄
The GUI is in a functional phase with complete capabilities for image classification and labeling. The implementation for model training, including hyperparameter selection and training initiation within the GUI, is planned for future updates.


### Dataset 📊
The image datasets utilized for this project are hosted on Roboflow. To access and explore the datasets, please visit https://universe.roboflow.com/rnfld/. 

Here you will find the datasets organized and ready for use. Feel free to download and utilize them in accordance with the terms and conditions specified within the platform.

### Latest Training and Model Available 🧑‍🎓
The most recent training session was part of the thesis project titled "Enhancing Glaucoma Detection: AI-driven Localization of Retinal Nerve Fiber Layer Defects". The model, trained using YOLOv8, showed promising results:

- **Recall:** 0.91
- **Precision:** 0.869
- **F1-Score:** 0.889

If you are interested in accessing or using this model, please contact me directly. Contact details can be found in the Contact section of this repository. The use of the model is subject to certain terms and conditions, which will be provided upon request.

### Citation📚 📚 
If you use the labeled datasets, the Glaucoma GUI, the trained YOLOv8 model, or any part of the thesis in your research or projects, please cite it as follows: "XXXX". 

Proper acknowledgment of these resources in your work will be highly appreciated and contributes to the ongoing research and development in this field.
