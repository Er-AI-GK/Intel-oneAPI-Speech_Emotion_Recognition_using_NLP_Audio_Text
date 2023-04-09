![Untitled](https://user-images.githubusercontent.com/106463633/230747827-b3db1985-59c8-4792-9af7-f8eca83a496f.png)

# Intel oneAPI Speech Emotion Recognition using NLP Audio & Text

Human-Computer interactions are make it mandatory to get accuracy communications, like both human. If computer identify means we will get clever interaction  
We might be on the verge of too many screens. It seems like everyday, new versions of common objects are “re-invented” with built-in Wi-Fi and bright touchscreens. A promising antidote to our screen addiction are voice interfaces.


![Logo](https://image.khaleejtimes.com/?uuid=d09b8b16-f2ac-4e9c-be46-5d8109a86d73&function=cropresize&type=preview&source=false&q=75&crop_w=0.99999&crop_h=0.87209&x=0&y=0&width=1200&height=675)


# Problem Statement
Recently, deep learning algorithms have successfully addressed problems in various fields.

Emotion Recognition side it's not work properly because the previous model based on the **Facial Emotion Recognition** that model gives only the less accuracy output. 

# Solution ![image](https://cdn-icons-png.flaticon.com/128/1087/1087840.png) 
If we solve that problems it's only one way is availabe that is **Natural Language Processing** based Emotion Recognition using **Audio and Text** input signals.

The presence of various languages, accents, sentences, speaking styles, and speakers also adds another difficulty because these characteristics directly change most of the extracted features, including pitch and energy.

So, we introduced the NLP using **Audio and Text**.
## How I built it ![image](https://cdn-icons-png.flaticon.com/128/4946/4946348.png)

### 1. First I Import libraries in Intel oneAPI kernal

### 2. Preprocess the  dataset

### 3. Stemming using **NLTK Library**

### 4. Classify the sentences using **Count Vectorizer Tokenization**

### 5. Train the model using optimized TensorFlow in Intel oneDNN to get better results and faster computation.

### 6. Finally, I deploy my model using Streamlit framework

## Datasets ![](https://cdn-icons-png.flaticon.com/128/6802/6802146.png)
- IEMOCAP
- RAVDESS

## Technologies Used
- Jupyter Lab ( Intel oneAPI 2023 ) kernal
- TensorFlow
- Keras
- Streamlit
- NLTK
- Pickle

## Train & Accuracy 
https://user-images.githubusercontent.com/106463633/230749292-59d4f1cc-4aa8-4dfe-98af-2413da4d4a68.mp4

## Deployment ![image](https://user-images.githubusercontent.com/72274851/218502434-f6e66043-0db0-4f85-b7f4-f33b2d33df1f.png)

- Download and extract the project
- Download & Install requirement.

```
!pip install -r requirements.txt
  
```
- Run the web app using follow code
```
streamlit run app.py
  
```
https://user-images.githubusercontent.com/106463633/230747715-5a312479-ea23-443a-8a11-01ee70b7c294.mp4

## Role of oneAPI DNN
In this project we used large amount of dataset so normally it's take long time process.

I choosed OneAPI DNN it's have optimized library and Python OneAPI kernal. So, it's give acceleration my project and gives high accuracy output. 

![image](https://openbenchmarking.org/logos/pts_onednn.png)
## oneAPI Deep Neural Network Library (oneDNN)
oneAPI Deep Neural Network Library (oneDNN) is an open-source cross-platform
performance library of basic building blocks for deep learning applications.
oneDNN is part of [oneAPI](https://oneapi.io).
The library is optimized for Intel(R) Architecture Processors, Intel Graphics,
and Arm\* 64-bit Architecture (AArch64)-based processors. oneDNN has
experimental support for the following architectures: NVIDIA\* GPU,
AMD\* GPU, OpenPOWER\* Power ISA (PPC64), IBMz\* (s390x), and RISC-V.

oneDNN is intended for deep learning applications and framework
developers interested in improving application performance
on Intel CPUs and GPUs. Deep learning practitioners should use one of the
[applications enabled with oneDNN](#applications-enabled-with-onednn).

## Result & Output ![icon](https://cdn-icons-png.flaticon.com/128/5316/5316486.png)
https://user-images.githubusercontent.com/106463633/230747801-461227dd-2b4a-42d1-a1bc-5bf72014d939.mp4

## Intel DevMesh
https://devmesh.intel.com/projects/intel-oneapi-based-emotion-recognition-using-nlp-audio-text

## Get Start Your Intel oneAPI project 
==> https://devcloud.intel.com/oneapi/
==> www.oneapi.io/open-source/
