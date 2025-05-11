# Memsy - AI-Powered Text-to-Meme Generator

Memsy is an AI-powered meme generation tool that lets users input a text prompt and receive meme suggestions complete with witty captions. It supports various machine learning models to ensure high-quality, humorous output.

---

## 🚀 Features

- **Text-to-Meme Generation**: Enter a text prompt, and Memsy will suggest relevant meme templates.
- **Template Selection**: Choose from a list of meme templates that best match your input.
- **Witty Captions**: Uses GPT-3 to generate humorous and creative captions for your selected meme template.
- **Interactive Interface**: Built using Streamlit for a clean and user-friendly interface.
- **Baseline Comparisons**: Evaluate different models (CLIP, SBERT, Roberta) for template matching and caption generation.

---

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/memsy.git
   cd memsy
---
##💻 Usage
1.Open the Streamlit app in your browser.

2.Enter a text prompt in the input box.

3.Select a meme template from the suggestions.

4.Click "Generate Meme" to create your meme.

5.Save or share your meme!
---
📁 Project Structure
bash
Copy
Edit
memsy/
├── notebooks/
│   ├── Baselines.ipynb                  # Baseline evaluations for template matching
│   ├── sentencebert-finetuning.ipynb   # Fine-tuning Sentence-BERT
│   ├── transformer_training.ipynb      # Training Roberta for meme classification
├── utils/
│   ├── sbert_meme_classifier.py        # SBERT-based classifier
│   ├── roberta_meme_classifier.py      # Roberta-based classifier
│   ├── draw_utils.py                   # Utilities for drawing captions on images
├── data/                               # Dataset and pre-trained models
├── streamlit_demo.py                   # Main Streamlit app
├── requirements.txt                    # Python dependencies
---
🧠 Tech Stack
Frontend
Streamlit: Provides an interactive and user-friendly interface for the application.

Backend
Python: Core programming language for the project.

PyTorch: Used for training and fine-tuning machine learning models.

Hugging Face Transformers: For pre-trained models like Roberta and Sentence-BERT.

OpenAI GPT-3: For generating witty captions.
---

