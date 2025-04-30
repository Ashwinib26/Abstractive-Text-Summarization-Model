# **Abstractive Text Summarizer using T5 and Gradio**

---

## **🧠 Overview:**  
### This project is an **Abstractive Text Summarizer** that uses the **T5 Transformer model** (`t5-base`) to generate human-like summaries from long text inputs. It allows users to **set a custom word limit** using a simple interactive UI.

---

## **🛠️ Key Features:**
### - Uses **pretrained T5 model** from Hugging Face Transformers.
### - Allows **customizable summary length** via word-to-token mapping.
### - Fully interactive via **Gradio web interface**.

---

## **🔄 Flow of Summary Generation:**
### 1. User inputs text and selects desired summary length (in words).
### 2. Word limit is converted into token limit (approx. `1 word ≈ 1.3 tokens`).
### 3. Input is prepended with `"summarize:"` (as required by T5).
### 4. The model generates a summary using beam search decoding.
### 5. Output is decoded and displayed in a textbox.

---

## **🖥️ What Gradio Does:**
### - Provides a **frontend interface** with:
  - A **textbox** to enter the input text.
  - A **slider** to select summary word limit.
### - Connects UI inputs directly to the Python function.
### - Handles **user interaction, UI rendering**, and live hosting.

---
## ❓ Tired of writing endless frontend code just to demo your ML model? 🎯Gradio lets you build beautiful, interactive ML demos with just Python. In this project, it handles user input and display—no HTML or JS needed. Fast, simple, and perfect for sharing your model with the world! 🚀

---

