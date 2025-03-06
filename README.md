# AI Comic Strip Generator  

## Overview  
AI Comic Strip Generator is an AI-powered application that creates comic strips using **Stable Diffusion (for images)** and **GPT-4 (for dialogues)**. The project allows users to generate and edit comic panels based on textual prompts, combining **image generation and AI-driven storytelling**.  

## 🚀 Features  
- **Text-to-Image Generation**: Uses **Stable Diffusion** to generate high-quality comic panels.  
- **AI Dialogues**: Integrates **GPT-4** for dynamic and engaging comic dialogues.  
- **User-Friendly UI**: Built with **Streamlit**, making it easy to interact with the model.  
- **Custom Image Editing**: Modify existing images using Stability AI's APIs.  
- **Fast Deployment**: Can be hosted using **FastAPI**.  

## Tech Stack  
### **Libraries & Tools**  
- **Generative AI**: Stable Diffusion, GPT-4, Hugging Face Transformers  
- **NLP & ML**: LangChain, spaCy, NLTK, TensorFlow/PyTorch  
- **Frameworks**: Streamlit (UI), FastAPI (Deployment)  
- **Cloud APIs**: OpenAI API, Stability AI API  

## Setup Instructions  

### 1. **Clone the Repository**  
```bash
git clone https://github.com/Shrashti04/AI-Comic-Strip-Creator.git
cd AI-Comic-Strip-Creator
```
### 2. **Environment Variables**: 
Add your API keys to .env file:
```bash
OPENAI_API_KEY= YOUR OPEN API KEY
STABILITY_KEY= YOUR STABILITY API KEY
TOGETHER_API_KEY= YOUR TOGETHER API KEY
 ``` 
### 3. **Install Dependencies**: 
This project uses Python and pip for package management. Install the required packages with the following command:
```bash
pip install -r requirements.txt
```

### 4. **Running the Application**
To run the application, execute the `app.py` file using Streamlit:
```bash
streamlit run app.py
```
