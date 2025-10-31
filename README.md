# AudioClassifier 🎵

Hi there! 👋  
This is **AudioClassifier**, a machine learning project I built to classify short audio samples into different categories like **dog, cat, cow**, and more.  

I actually created **two versions**:  
1. A simple **binary classifier** that distinguishes between dog and cat sounds.  
2. A **multiclass classifier** that can tell apart dog, cat, and cow audio samples.  

---

## 🧠 How it works

The core of the project is a **custom CNN** that works on **Mel-spectrograms** of audio samples.  
It learns the patterns in audio frequencies to predict which animal sound it is.  

---

## 📊 Dataset

- The dataset is quite small, about **50–90 samples per class**.  
- I used **Kaggle datasets** as a source.  
- Two versions of the dataset: one for binary classification, one for multiclass.

---

## 📈 Performance

- **Binary classifier (dog vs cat):** ~95% accuracy ✅  
- **Multiclass classifier (dog, cat, cow):** ~87% accuracy ✅  

These results were achieved with the custom CNN trained on the spectrograms.

---

## 🚀 Running the project

I built everything to run easily in **Google Colab**:

1. Clone the repo and open the notebook in Colab.  
2. Install the dependencies:
```bash
!pip install -r requirements.txt
