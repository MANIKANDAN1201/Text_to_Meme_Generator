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

## Use Cases

- **Social Media Content Creation**: Quickly generate memes for social media posts.
- **Marketing Campaigns**: Create engaging and humorous content for marketing purposes.
- **Entertainment**: Have fun generating memes for personal use or sharing with friends.
- **Meme Research**: Explore how machine learning models can be used for creative tasks like meme generation.

## Tech Stack

### Frontend
- **Streamlit**: Provides an interactive and user-friendly interface for the application.

### Backend
- **Python**: Core programming language for the project.
- **PyTorch**: Used for training and fine-tuning machine learning models.
- **Hugging Face Transformers**: For pre-trained models like Roberta and Sentence-BERT.
- **OpenAI GPT-3**: For generating witty captions.

## Machine Learning Models

- **Sentence-BERT**: Fine-tuned for text-to-template matching.
- **Roberta**: Trained for meme classification.
- **CLIP**: Used for text-to-image matching.
- **GPT-3**: Generates captions for memes.

## Data

- **Meme Dataset**: A cleaned dataset of 900k memes, including captions, labels, and image paths.

## How It Works

1. **Input Prompt**: The user enters a text prompt in the Streamlit interface.
2. **Template Matching**:
   - The system uses a classifier (e.g., SBERT, Roberta, or CLIP) to suggest relevant meme templates.
   - The user selects a template from the suggestions.
3. **Caption Generation**:
   - GPT-3 generates a witty caption based on the input prompt and selected template.
4. **Final Meme**:
   - The caption is overlaid on the template, and the final meme is displayed to the user.
