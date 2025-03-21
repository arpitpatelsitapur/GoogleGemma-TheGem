# 🚀 GoogleGemma-TheGem

A repository showcasing **Google Gemma models** for practical use cases, including **OCR tasks** and **specialized responses**. This project demonstrates the power of **Gemma 3** with **local inference** using Ollama and **Gemma 2** using Hugging Face API.

## 🛠️ Applications Included

### 1️⃣ Gemma3 OCR (Local Inference with Ollama)
🔹 Performs **OCR (Optical Character Recognition)** using the **Gemma 3 model** on a local server with **Ollama**.  
🔹 Extracts text from images and displays the results through a **Streamlit UI**.

✅ **Tech Stack:**
- Ollama (for local inference)
- Streamlit (for UI)
- Transformers (for model handling)

📦 **Installation & Usage:**
```bash
# Install Ollama
brew install ollama

# Pull the Gemma 3 model
ollama pull gemma:3b

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run gemma3_ocr.py
```

### 2️⃣ Gemma2 Specialized Responses (Hugging Face API)
🔹 Uses **Gemma 2** via Hugging Face API to generate **specialized responses**.  
🔹 Handles **custom NLP tasks** with accurate and contextual answers.

✅ **Tech Stack:**
- Hugging Face API (for inference)
- Transformers (for model handling)
- Streamlit (for UI)

📦 **Installation & Usage:**
```bash
# Install dependencies
pip install -r requirements.txt

# Set your Hugging Face token
export HUGGINGFACE_TOKEN=your_token_here

# Run the app
streamlit run gemma2_specialized.py
```

## 📂 Repository Structure
```
/GoogleGemma-TheGem
 ├── gemma3_ocr.py                # OCR app with Gemma 3 (Ollama)
 ├── google_gemma.ipynb           # Specialized responses with Gemma 2 (Hugging Face)
 ├── requirements.txt             # Dependencies
 ├── README.md                    # Documentation
 ├── assets                  
    ├──  gemma3.png                   
```

## ⚙️ Requirements
- Python 3.10+
- Ollama (for local inference with Gemma 3)
- Hugging Face API token (for Gemma 2 responses)
- Streamlit and Transformers libraries

## 🚀 Contributing
Feel free to use and modify it.

## 📫 Contact
👤 mail- pa7238867@gmail.com  
