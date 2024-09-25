# 🌍 Translation and Summarization with Language Detection 🌐

This project fetches articles from the web, detects their language, translates them into English, and provides a concise summary. It leverages **Gradio** for the user interface, **Huggingface's transformers** for translation and summarization, **Newspaper3k** for article extraction, and **Langdetect** for language detection.

## ✨ Features

- 🌐 **Language Detection**: Automatically detects the language of the fetched article.
- 🔄 **Translation**: Translates articles in Arabic, Chinese, and Japanese into English.
- 📝 **Summarization**: Provides a concise summary of the translated article.
- 🖥️ **User-friendly Interface**: A simple, interactive Gradio interface for inputting article URLs and receiving translations and summaries.

## 🛠️ Technologies Used

- 🎨 **Gradio**: For creating the user interface.
- 🤗 **Huggingface Transformers**: Pre-trained models for translation and summarization.
- 📰 **Newspaper3k**: For fetching and parsing articles from URLs.
- 🈸 **Langdetect**: To detect the language of the article.
- 🖥️ **Torch**: For managing GPU and CPU devices.

## 📦 Installation

1. Clone the repository:

   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. Install the required packages:

pip install gradio
pip install transformers
pip install newspaper3k
pip install langdetect

🚀 Usage
1. Run the Python script:

python your_script_name.py

Open the Gradio interface in your browser.
Enter the URL of an article to fetch, translate, and summarize.

⚡ For Best Results: Run on Google Colab ⚡
To get better performance (especially with GPU), it's recommended to run this project on Google Colab. You can access GPU resources for faster translation and summarization:

Open Google Colab.

Upload your script or notebook to Colab.

Ensure the runtime is set to GPU (go to Runtime -> Change runtime type -> Select GPU).

Install the required packages by running:

!pip install gradio
!pip install transformers
!pip install newspaper3k
!pip install langdetect
Execute the cells, and enjoy improved performance!

🌟 Example
Simply input the URL of an article written in Arabic, Chinese, or Japanese, and the application will:

🕵️ Detect the language.
🔄 Translate the article into English.
📝 Provide a summarized version of the translated article.
🔗 Example URLs
🇦🇪 Arabic: BBC Arabic
🇯🇵 Japanese: BBC Japanese
🇪🇸 Spanish (Unsupported): BBC Mundo
Note: Spanish articles are not supported yet in this version.

🧠 Model Details
Translation Models: Helsinki-NLP's OPUS-MT models for Arabic, Chinese, and Japanese translations.
Summarization Model: Facebook's BART-Large-CNN for summarizing the translated text.
⚡ GPU Support
The application checks for GPU availability and will utilize it if present. If no GPU is available, the application will run on the CPU. For faster results, especially with larger texts, using Google Colab with GPU is recommended.

🤝 Contributing
Feel free to open issues or submit pull requests to enhance the project!
