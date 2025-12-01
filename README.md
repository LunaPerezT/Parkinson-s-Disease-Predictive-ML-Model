# Parkinson-s-Disease-Predictive-ML-Model

A Python-based machine learning project for predicting the likelihood or presence of Parkinson’s Disease using patient data with a 97% of accuracy.

The project integrates a trained ML model with an accessible web interface, making it ideal for demonstration, research exploration, and educational use. [**VISIT THE WEBPAGE HERE**](https://parkinsons-disease-ml-predictive-model-webpage.streamlit.app/") 

> ⚠️ **Disclaimer**: This repository is intended for research, educational or prototyping purposes only. It is **not** a diagnostic tool, and predictions should not be used as medical advice.

---

## 📚 Introduction   

<h5 style="text-align: center;color: black;"> <b>What Is Parkinson’s Disease?</b></h5>
                  
Parkinson’s disease (PD) is a **progressive neurodegenerative disorder** that primarily affects the brain regions responsible for movement control. It occurs when the neurons that produce **dopamine**, a key neurotransmitter involved in coordinating smooth and balanced muscle activity, begin to deteriorate over time.

The condition is typically characterized by a combination of **motor symptoms**, such as tremor, muscle rigidity, bradykinesia (slowness of movement), and postural instability. Many individuals also experience **non-motor symptoms**, including sleep disturbances, cognitive changes, mood alterations, and autonomic dysfunction.

Although the exact cause of Parkinson’s disease remains unknown, research suggests a multifactorial origin involving **genetic**, **environmental**, and **age-related** factors. While there is currently no cure, early detection and comprehensive clinical management can significantly improve quality of life and slow symptom progression.

<h5 style="text-align: center;color: black;"> <b>Why Early Detection Is Crucial in Parkinson’s Disease?</b></h5>    
                   
The **early detection of PD** is a growing priority within both clinical practice and research, as the condition often progresses silently before clear symptoms emerge. Despite advances in medical imaging and neurological assessment, **many individuals remain undiagnosed until the disease has already progressed**, limiting the effectiveness of available therapeutic interventions. Consequently, **timely diagnosis** can significantly **influence patient outcomes and long-term quality of life**. Developing a **predictive model** for Parkinson’s disease therefore represents a crucial step toward identifying individuals at risk long before traditional diagnostic criteria are met.

<h5 style="text-align: center;color: black;"> <b>Why develop a machine learning–based predictive model?</b></h5>  
                     
A reliable predictive system has the potential to support clinicians in recognizing subtle signs that might otherwise go unnoticed. Early identification could allow for **timelier monitoring, lifestyle adjustments, and targeted therapeutic strategies** that may slow **disease progression or improve quality of life**. Additionally, predictive modeling can help researchers **gain deeper insight into the complex interactions that contribute to the onset of neurodegenerative disorders**.
   
Beyond clinical impact, creating a predictive model encourages the integration of modern **data-driven approaches** into neurological healthcare. As medicine increasingly embraces digital tools, predictive modeling stands out as a promising path to **more personalized and proactive patient care**. In the context of Parkinson’s disease, such a model could become an **essential component of future screening programs**, ultimately **contributing to earlier intervention**, improved outcomes, and a more informed understanding of this challenging condition.

<h5 style="text-align: center;color: black;"> <b>What is the objetive of this project?</b></h5>    
                   
A set of demographic, lifestyle, clinical, cognitive, and symptom-related variables collected from a patient cohort, was used in this project. By integrating these diverse variables into a unified predictive framework, the project seeks to **evaluate multiple machine learning algorithms** and determine their capability to accurately identify patients at risk. The goal is not only to achieve strong **predictive performance** but also to explore **feature importance** and interpretability, enabling clinicians and researchers to better understand which factors contribute most meaningfully to diagnostic outcomes. Ultimately, this work aims to support the development of practical, **data-driven tools** that may assist in earlier and more reliable detection of Parkinson’s disease.
   
---

## 📁 Repository Structure   
    
Parkinson-s-Disease-Predictive-ML-Model/           
├── data/          
├── docs/          
├── img/   
├── models/     
├── notebooks/                     
├── `requirements.txt`       
└── `README.md`    
### 📁 Folders

#### [`/data`](./data)
Contains raw, processed, datasets or testing data used for model inference or demonstration inside the web interface.

#### [`/docs`](./docs)
Technical and business presentations of the project
   
#### [`/img`](./img)
Images displayed in the notebooks and (logos, UI elements, figures).
  
#### [`/models`](./models)
Stores trained machine-learning models in Pickle format(`.pkl`).   

#### [`/notebooks`](./notebooks)
Notebooks with the detailed development of the machine leaning models


### 📄 Files

#### [`requirements.txt`](./requirements.txt)
Python dependencies required to run the project.

Install with:
```bash
pip install -r requirements.txt
```
   
---
   
## 🚀 Getting Started

Follow these steps on your git bash to set up and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/LunaPerezT/Parkinsons-Disease-ML-Predictive-Model.git
cd Parkinsons-Disease-ML-Predictive-Model
```
   
### 2. (Optional) Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate       # Linux / macOS
venv\Scripts\activate          # Windows
```

### 3. Install Dependencies
    
```bash
pip install -r requirements.txt
```
    
### 4. Run the Jupyter Notebooks 

---
     
## 🙋🏻‍♀️ About the Author
    
I’m **Luna Pérez Troncoso**, a **Data Scientist** with a strong foundation in **Artificial Intelligence, data analytics, and computational modeling**, originally shaped through my background in **science and research**. Over time, I’ve transitioned my **analytical and experimental mindset** into the tech field, where I design **data-driven solutions** that **transform complex information into actionable insights**.
         
I have experience working across the **full data pipeline**, from data acquisition, cleaning, and exploration to building, validating, and deploying predictive models. My focus is on **leveraging machine learning and statistical methods to uncover patterns, optimize processes, and support strategic decisions**.
           
What defines my approach is a balance between **technical precision and creativity**. I’m passionate about **connecting raw data with real-world** impact, collaborating with **cross-functional teams**, and communicating insights in a way that drives innovation.    

   
<a href="https://www.linkedin.com/in/luna-p%C3%A9rez-troncoso-0ab21929b/">
 <img src="./img/linkedin.jpg" alt="linkedin" width="200"/>
</a>
   
Visit my [LinkedIn profile](https://www.linkedin.com/in/luna-p%C3%A9rez-troncoso-0ab21929b/)
