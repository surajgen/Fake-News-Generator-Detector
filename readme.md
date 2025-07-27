# Fake News Generator and Detector

This project implements two main functionalities using pretrained Transformer models:

- ✅ A **Fake News Generator** using **GPT-2**
- ✅ A **Fake News Detector** using **DistilBERT**
- ✅ A simple **Gradio User Interface** to interact with both modules

---

## 🧠 Models Used

- **GPT-2**: For generating news-like fake text based on a seed prompt.
- **DistilBERT** (fine-tuned): For binary classification of input text as "FAKE" or "REAL".

---

## 💻 Project Structure
##  Install dependencies
pip install -r requirements.txt

 ## Open and run notebooks
 fake news generator and detector(1).ipynb

fake news gradio.ipynb

## examples
## fake news generation
Input: "Government announces new scheme"
Output: "Government announces new scheme to provide benefits to farmers and encourage small-scale industries, said officials on Friday..."
## fake news detection
Input: "Breaking: Scientists discover humans can live without water for weeks."
Output: Prediction: FAKE

