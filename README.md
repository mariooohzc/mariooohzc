<img width="1834" alt="mario readme github" src="https://github.com/user-attachments/assets/b3cf5a97-6407-49a6-b647-3ee595ef1555">

Welcome to my page! I'm a current undergraduate at NUS majoring in Data Science and Analytics, with a minor in Computer Science. I am an AI and tech enthusiast with a passion for learning and experimenting with new technologies.

<br/>

## My Personal Projects:
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=mariooohzc&repo=rizzume)](https://github.com/mariooohzc/rizzume)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=mariooohzc&repo=Gender-prediction-DataCamp-Project)](https://github.com/mariooohzc/Gender-prediction-DataCamp-Project)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=mariooohzc&repo=ImageSegmentationDeepLearning)](https://github.com/mariooohzc/ImageSegmentationDeepLearning)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=mariooohzc&repo=ConvolutionNeuralNetworkImageClassificationProject)](https://github.com/mariooohzc/ConvolutionNeuralNetworkImageClassificationProject)


### [Resume Web Application (rizzume)](https://github.com/mariooohzc/rizzume)
- **Description**: Developed AI-driven resume feedback and job search features using FastAPI and BeautifulSoup for web scraping
- Implemented CI/CD (Continuous Integration Continuous Development), unit testing, integration testing, system testing and regression testing using Pytest, Docker and GitHub Actions
- Deployed on HuggingFace VPS
- **Technologies**: Python, FastAPI, BeautifulSoup, Poetry, Docker, GitHub Actions, HTML, JavaScript, CSS, BootStrap, Pytest
- Website link: [https://mariooohzc-rizzume.hf.space/](https://mariooohzc-rizzume.hf.space/)

---
### [Convolutional Neural Network Image Classification Project](https://github.com/mariooohzc/IT1244_Project)

- **Convolutional Neural Network (CNN) Image Classification Project**  
  Collaborating with my friends on a university project focused on CNN-based image classification. In this project:
  - Conducted extensive research by reading and analyzing papers on pre-trained models, such as **MobileNetV2** and **ResNet50**, to understand their architectures and potential applications.
  - Performed **data augmentation** and utilized **TensorFlow** and **Keras** for model training.
  - Planned to continue developing and expanding the project beyond the submission deadline to explore further improvements.

---
### [Data Visualization Project with R (StackOverflow Data)](https://mariooohzc.github.io/DSA2101_project/)
 
  Working on a data visualization project using the **Tidy Tuesday StackOverflow dataset**.\
  This project aims to uncover insights from StackOverflow user data:
  - Doing data cleaning such as joining multiple tables, mutating columns to get desired values, etc.
  - Leveraging **ggplot2** and **plotly** for rich, interactive visualizations.
    
  Link to project: [Click here](https://mariooohzc.github.io/DSA2101_project/)\
  Link to repo: [Click here](https://github.com/mariooohzc/DSA2101_project)

---

### [ImageSegmentationDeepLearning](https://github.com/mariooohzc/ImageSegmentationDeepLearning)
- **Description**: An image segmentation project using U-Net architecture with PyTorch
- **Technologies**: Python, PyTorch, U-NET

---
  
### [Gender Prediction](https://github.com/mariooohzc/Gender-prediction-DataCamp-Project)
- **Description**: Created a Python program using the New York Times best-selling books dataset for gender analysis, implementing phonetic matching with the Fuzzy library (NYSIIS encoding) to identify similar-sounding names and visualizing gender distribution trends using Matplotlib.



## 🔭 Current Work in Progress
### 🚧 Private Repositories
### Image Caption Generator Web Application (Machine Learning Project)

I’m currently working on a Machine Learning Project (Image Caption Generator Web App) using FastAPI and PyTorch

You can test the model for inference by going to the : [huggingface link](https://mariooohzc-imagecaptiongenerator.hf.space/)

- **Dataset & Preprocessing**
  - Used the [Flickr8k Dataset](http://cs.stanford.edu/people/karpathy/deepimagesent/) of images and captions.
  - Cleaned and tokenized captions; built a custom `Vocabulary` class.
  - Resized images to 224×224 and normalized with ImageNet mean/std.

- **Model Architecture**
  - **Encoder:** Pretrained VGG16 (final layers removed) + a small FC layer to reduce dimensionality.
  - **Decoder:** LSTM taking the encoder’s features as its initial state. Uses an Embedding layer and outputs vocab scores.

- **Training**
  - Trained with CrossEntropyLoss (ignoring `<PAD>`), using Adam optimizer.
  - Freezed VGG16 convolution layers to speed up and stabilize training.
  - Logged average epoch loss and saved checkpoints.

- **Inference**
  - Extracted features once, then performed step-by-step decoding:
    - Fed each predicted word back into the LSTM until `<EOS>` or max length.
   
- **Evaluation** - BLEU Scoring
  - Used **NLTK's BLEU scoring** to measure the similarity between generated and actual captions.
  - BLEU score evaluates **n-gram overlap** (1-gram, 2-gram, 3-gram, and 4-gram).

- **Deployment**
  - Converted the PyTorch model to ONNX.
  - Deployed on [Hugging Face Spaces](https://huggingface.co/spaces](https://mariooohzc-imagecaptiongenerator.hf.space/) using a Gradio app for live caption generation.


![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) 
![Hugging Face](https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)

---

<br/>

## Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)	
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) 
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) 
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Poetry](https://img.shields.io/badge/Poetry-%233B82F6.svg?style=for-the-badge&logo=poetry&logoColor=0B3D8D)
![Hugging Face](https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)

<br/>

## Let's Connect:
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mario-hanzel-13641621a/) [![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:mario.hanzel@u.nus.edu)
