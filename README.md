```markdown
# 🔤 Next Word Prediction using LSTM RNN

A deep learning project focused on generating the next word in a sequence using a Long Short-Term Memory (LSTM) Recurrent Neural Network. Built and trained using Python and TensorFlow/Keras, the model learns linguistic patterns from a text corpus and predicts contextually appropriate words.

## 📘 Abstract

This project utilizes LSTM RNNs to perform next-word prediction based on a sequence of input words. Using a dataset sourced from Kaggle’s Fake News Detection corpus, we trained a model that can generate coherent and contextually relevant text. The architecture includes an embedding layer, two LSTM layers with 150 units each, and a softmax-activated dense layer for word prediction.

---

## 🧠 Methodology

- **Data Preprocessing:**
  - Lowercasing, punctuation removal, tokenization
  - Word embeddings for model input
- **Model Architecture:**
  - Embedding Layer → 2 LSTM Layers (150 units) → Dense Layer with Softmax
- **Training:**
  - 100 epochs
  - Adam optimizer
  - Categorical cross-entropy loss
- **Evaluation Metrics:**
  - Accuracy
  - Perplexity

---

## 🛠️ Tools and Frameworks

- **Language:** Python
- **Libraries:**
  - TensorFlow/Keras
  - NumPy
  - Matplotlib
- **Hardware:** Trained using CPU/GPU depending on system configuration

---

## 📊 Results

- Achieved training accuracy of ~99%
- Perplexity scores indicated strong language modeling capabilities
- Model generated fluent, syntactically valid word predictions
- Visualized loss and accuracy across training epochs

---

## ⚠️ Limitations

- No validation split was used
- Performance on rare or ambiguous words was weaker
- Training time is high on large datasets

---

## 🔮 Future Scope

- Integrate **Attention Mechanism** to improve contextual relevance
- Use **Transformer architectures** for scalability
- Expand dataset for more generalizable results
- Real-time application in predictive keyboards or chatbots

---

## 📁 Files Included

- `Rnn_textgen.ipynb`: Jupyter notebook with full code and training workflow
- `Report.pdf`: Complete project report and analysis

---

## 📜 License

This project is for academic and research purposes only. Commercial use requires permission from the author.

---

## 🙋 Author

**Jeevan EG**  
School of Computer Science and Engineering  
RV University  
```
