
<h1 align="center">Hello, I'm David!</h1>

<div align="center">
<a style="text-decoration: none;" href="https://linkedin.com/in/davidtobonmolina" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a style="text-decoration:none;" href="mailto:davidtobonm@gmail.com" target="_blank">
<img src=https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white alt=gmail style="margin-bottom: 5px;">
</a>
<a style="text-decoration:none;" href="mailto:d.tobonm2@uniandes.edu.co" target="_blank">
<img src=https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white alt=outlook style="margin-bottom: 5px;">
</a>
<p>📧 <b>davidtobonm@gmail.com</b></p>
<p>📧 <b>d.tobonm2@uniandes.edu.co</b> </p>
<!-- <a href="https://www.kaggle.com/davidtobonm " target="_blank">
<img src=https://img.shields.io/badge/kaggle-%2344BAE8.svg?&style=for-the-badge&logo=kaggle&logoColor=white alt=kaggle style="margin-bottom: 5px;" />
</a>  -->
</div> 

<!--<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXBwbmpnbXdwYjF3MDJtM3FjZGw4OGRtaDU5ZGk0djR5dm16a3h5bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Nx0rz3jtxtEre/giphy.webp" alt="hello there" align="right" height="" width="300" />  
-->
<div align="left">
<!-- <img src="https://rishavanand.github.io/static/images/greetings.gif" align="center" style="width: 100%" /> -->

<!-- - 🔭 I’m currently working on **[Multiple Sclerosis Spinal Cord Lesions Detection](https://github.com/sergiocanar/Ms-Multi-Spine)** -->
- 🏛️ Currently studying **Biomedical and Software Engineering @ [Universidad de los Andes](https://www.uniandes.edu.co/)**
- 🌱 Constantly learning about **Artificial Intelligence, Computer Vision and Health Tech**. 
- ⚡ Fun fact: Star Wars prosthetics are what inspired me to learn about biomedical tech and programming.
</div>

<br/> 

## 🛠️ Languages and Tools 

<div align="center">
<table><tr><td valign="top" width="50%" align="center">

<p align="center">
  <h3> Tools I frequently use </h3>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,pytorch,sklearn" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,react,fastapi" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=gcp,postgres,mongodb" />
  </a>
</p>
  

</td><td valign="top" width="50%" align="center">

<p align="center">  
<h3> Other tools I have worked with </h3>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,ts,java,kotlin" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,spring,django,nestjs" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ros,latex,html,css" />
  </a>
</p>

</td></tr></table>  
</div>


<br/> 

## 🌠 Projects
<div align="left">

* [Training-free Acceleration of Image Generation Models](#image-generation)
* [Text Classification of Opinions on SDGs](#sdg-classification)
* [DocAId - Automatic documentation of medical appointments](#docaid)
* [OrientApp - for visually impaired users in the Transmilenio](#orientapp)
* [Lesion Segmentation in MRIs](#ms-spine)

<a id="image-generation"></a>
### Training-free Acceleration with Dense-Caption Control in Text-to-Image Generation with Conditional Diffusion Models

**Tools:** PyTorch, Hugging Face.

Training-free pipeline for Text-to-Image diffusion models that integrates [Dense Diffusion](https://github.com/naver-ai/DenseDiffusion) for spatial control and [Adaptive Guidance](https://bcv-uniandes.github.io/adaptiveguidance-wp/) for inference acceleration. The method employs attention modulation to guide text features toward designated spatial regions, enabling layout control for dense captions without model retraining. The incorporation of Adaptive Guidance transitions from Classifier-Free Guidance to conditional-only steps to reduce the number of function evaluations during the diffusion process.

* [Poster](https://drive.google.com/file/d/1xx9_Tkgj9UYHGJNrVcZWpagpvCj1ZYg-/view?usp=sharing)
* [Presentation](https://drive.google.com/file/d/1flt6JcY9lSqyWoXzu4B-lXm0-S2kZEq0/view?usp=sharing)

---

<a id="sdg-classification"></a>
### Text Classification of Opinions on Sustainable Development Goals

**Tools:** scikit-learn, nltk, Vite, FastAPI, Docker. 

End-to-end MLOps solution for social impact text analysis. The project consists of a a full-stack NLP web application that classifies text opinions according to UN Sustainable Development Goals (SDGs), specifically targeting SDG 1 (No Poverty), SDG 3 (Health and Well-being), and SDG 4 (Quality Education). The system exposes a FastAPI REST backend and a Vite-powered frontend, both containerized with Docker.

The ML pipeline supports live inference as well as on-demand model retraining through the web interface, and was developed following the CRISP-ML(Q) methodology.

Solución MLOps end-to-end para el análisis de texto con impacto social. El proyecto consiste en una aplicación web full-stack de NLP que clasifica opiniones de texto según los Objetivos de Desarrollo Sostenible (ODS) de la ONU, específicamente el ODS 1 (Fin de la Pobreza), el ODS 3 (Salud y Bienestar) y el ODS 4 (Educación de Calidad). El sistema expone un backend REST con FastAPI y un frontend desarrollado con Vite, ambos contenerizados con Docker.

El pipeline de Machine Learning soporta inferencia en tiempo real, así como reentrenamiento del modelo bajo demanda a través de la interfaz web, y fue desarrollado siguiendo la metodología CRISP-ML(Q).

* <a href="https://github.com/BILabsAndProjects/Proyecto1" target="_blank">Repository</a>

---

### DocAId

**Tools:** React, FastAPI, OpenAI, Whisper, MongoDB.

Automatic transcription and documentation, using Speech-to-Text models and NLP, of medical appointments for structured patient and medical records management. Helps healthcare providers save time and improve accuracy during patient care.

Transcripción y documentación automática de citas médicas para el registro y manejo estructurado de pacientes y sus historias clínicas. Para ayudar a los proveedores de salud a ahorrar tiempo y mejorar la precisión de los registros durante la atención al paciente.

* <a href="https://github.com/DavidTobonIBIO/docaid-frontend" target="_blank">Frontend</a>
* <a href="https://github.com/DavidTobonIBIO/docaid-backend" target="_blank">Backend</a>

---

### OrientApp

**Tools:** React Native, FastAPI, Whisper, Google Cloud.

Mobility application for visually impaired users in the TransMilenio transit system. Integrates audio-based assisted navigation functions and accessibility features to enhance autonomous mobility for blind and low-vision passengers. 

Aplicación de movilidad en el sistema de TransMilenio para personas con discapacidad visual. Integra funciones de navegaión asistida basada en audio y características de accesibilidad para mejorar la movilidad autónoma de los pasajeros ciegos y de baja visión.

* *Private repositoy.* Read the design paper [here](https://docs.google.com/document/d/1OYVWeQkz6W3IeGBgsOqhXkaOp2-UGgBGOfZ1uhSQuY8/edit?usp=sharing).

---

<a id="ms-spine"></a>
### Multiple Sclerosis Spinal Cord Lesion Segmentation from MultiSequence MRIs

**Tools:** PyTorch, Weigths & Biases, MONAI.

Custom model architecture based on SwinUNETR for lesion detection within a missing modalities context in automated MRI analysis.

Arquitectura de modelo personalizada basada en SwinUNETR para la detección de lesiones en un contexto de modalidades faltantes en el análisis automatizado de resonancias magnéticas.

* [Poster](https://drive.google.com/file/d/1y1d1yvAkIC596Vg53apYaG2JJ91x_vcn/view?usp=sharing)

* [Presentation](https://drive.google.com/file/d/1l2tJ0TOoQkUAisL7b_bn41-gE4qqFQro/view?usp=sharing)

</div>

<!-- <div align="center">
<img src="https://komarev.com/ghpvc/?username=DavidTobonIBIO&&style=flat-square" align="center" />
</div>   -->

<br />
