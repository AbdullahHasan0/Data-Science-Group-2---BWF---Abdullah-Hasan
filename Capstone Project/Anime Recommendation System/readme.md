# 🎥 Anime Recommender System 🌟

This project recommends anime based on the similarity of genres and synopsis. It uses NLP techniques such as TF-IDF and cosine similarity to identify similar anime titles. Built with **Gradio**, this app provides an interactive interface for anime lovers to get personalized anime recommendations.

## 🌟 Features

- 🔍 **Anime Search**: Search from a huge database of anime by selecting your favorite one.
- 🤖 **Similarity Based Recommendations**: Get recommendations based on the genres and synopsis of the selected anime.
- 🖼️ **Anime Posters and Synopses**: View anime posters and read their synopses directly in the interface.
- ⚡ **Gradio Integration**: Combines the power of **Gradio**  for easy interaction.

## 🚀 Setup

1. Clone the repository:

   git clone https://github.com/your-username/anime-recommender.git
   cd anime-recommender

2. Install the dependencies:
pip install gradio streamlit nltk scikit-learn pandas numpy

🎬 How to Run

Run the script to launch the Gradio interface:
Open the Gradio interface in your browser and start exploring anime recommendations! 🎉

🎯 Example Usage

* Select an anime from the dropdown, and the system will recommend 5 similar anime titles based on their genres and synopsis.
* Along with the recommendations, you can view anime posters and read their brief synopses.

🛠️ Technologies Used

* **Gradio**: For building the user interface.
* **NLP**: Used for text processing and similarity matching.
* **Cosine Similarity**: To calculate the similarity between anime genres and synopses.
* **Count Vectorizer**: To extract important words from the anime descriptions.

🖼️ Interface Preview

The recommendations come with anime posters and synopses:

1. Anime Poster 🎨: See the cover image of each anime.
2. Anime Synopsis 📖: Read a short description of the recommended anime.

⚡ Want Faster Results? Try Google Colab!

You can run this project on Google Colab for better performance:

1. Open Google Colab.
2. Upload your script or notebook to Colab.
3. Install the required packages:
    !pip install gradio streamlit pyngrok
4. Run the cells and enjoy faster recommendation results with a GPU!

📊 Anime Dataset

The dataset used for this project contains:

* anime_id: The unique ID of the anime.
* Name: The name of the anime.
* Genres: The genres associated with the anime.
* Synopsis: A brief description of the anime.
* Image URL: The URL of the anime poster.

📸 Example Animes

Here are a few example animes from the dataset:

* Naruto: A young ninja strives to be the greatest.
* Attack on Titan: Humanity fights against giant creatures.
* Death Note: A high school student uses a mysterious notebook to eliminate evil.

🤝 Contributing
Feel free to submit pull requests or open issues to improve the project! All contributions are welcome. 😊
