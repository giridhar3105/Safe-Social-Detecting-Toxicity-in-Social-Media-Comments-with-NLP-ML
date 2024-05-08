# Safe Social: Detecting Toxicity in Social Media Comments with NLP & ML

Safe Social is a machine learning-based tool designed to detect toxicity in social media comments. Leveraging natural language processing (NLP) techniques and machine learning algorithms, Safe Social helps identify potentially harmful or offensive comments, allowing users to create safer online communities.

## Features

- **Toxicity Detection:** Safe Social analyzes text comments to determine their level of toxicity, providing a probability score indicating the likelihood of a comment being harmful.
  
- **User-Friendly Interface:** The tool offers an intuitive user interface built with Streamlit, allowing users to input text comments and receive toxicity predictions in real-time.

- **Scalable Deployment:** Safe Social is deployed as a Flask API, making it easy to integrate into various applications and platforms, including social media platforms, forums, and chat applications.

## How It Works

Safe Social utilizes a combination of TF-IDF vectorization and Bayesian classification algorithms to process text comments and classify them as toxic or non-toxic. Here's a brief overview of the workflow:

1. **TF-IDF Vectorization:** The text comments are transformed into numerical features using TF-IDF vectorization, capturing the importance of each term in the comments relative to a corpus of documents.

2. **Bayesian Classification (Naive Bayes):** The TF-IDF features are fed into a Naive Bayes classifier, which calculates the probability of each comment belonging to the toxic or non-toxic class based on the occurrence of words.

3. **User Interface:** Safe Social provides a user-friendly web interface powered by Streamlit, allowing users to input text comments and receive toxicity predictions instantly.

4. **Flask API Deployment:** The trained model is deployed as a Flask API, enabling seamless integration into various applications and platforms.

## Getting Started

To use Safe Social, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/safe-social.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

4. Access the application at [http://localhost:8501](http://localhost:8501) in your web browser.

## Contributing

Contributions to Safe Social are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
