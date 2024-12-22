# Emotion Recognition in Artworks: Leveraging CNNs for Visual Emotion Analysis and Chatbot Development
The project develops a comprehensive system that combines emotion recognition in artworks with interactive AI-driven conversations. Using Convolutional Neural Networks (CNNs), we classify the emotions evoked by images into distinct categories. This model is then integrated with a fine-tuned Llama 2-Chat language model to create an intelligent chatbot. The chatbot is designed to analyze images emotionally and engage with users through meaningful evokes emotional interactions, connecting the gap between visual art analysis and conversational AI.

Authors: Keer Lu(kl3658), Purui Niu(pn2433)
---
## Features
* Emotion Classification: Classifies images into positive, negative, or mixed emotions using a CNN-based architecture.
* Chatbot Integration: Fine-tuned Llama 2-Chat model provides conversational responses based on image emotion analysis.
* Advanced Techniques:
Transfer learning and data augmentation for CNNs.
Low-Rank Adaptation (LoRA) and quantization for efficient fine-tuning of Llama 2-Chat.
* Visualization Tools: Includes training/validation accuracy and loss plots, confusion matrices, and workflow diagrams.




## Installation

 ```bash
git clone https://github.com/KeerheitBO/202412-6-Emotion-Recognition-in-Artworks.git
cd emotion-recognition-in-artworks
```

 Install dependencies:
 ```bash
   pip install -r requirements.txt
```



## Organization of Directory

```
 FinalProject-eecs6893-202412-6/
├── CNN/
│   ├── Binary_Model.ipynb
│   ├── Final_Project_DataProcessing_11.ipynb
│   ├── Multi-Classes_Models.ipynb
│   ├── Tri_Classes_Models.ipynb
├── LLM/
│   ├── Fine_tune.ipynb
├── emotion_chatbot/
│   ├── emotion_chatbot_gradio.ipynb
│   ├── emotion_model.keras 
├── README.md
└── requirements.txt
```
