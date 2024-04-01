# LLM-Interest-Rates-Sentiments

## Introduction

LLM-Interest-Rates-Sentiments is a cutting-edge Generative AI project designed to analyze the sentiment surrounding interest rates in Germany. By harnessing the power of machine learning and natural language processing, this project aggregates and processes data from numerous news articles. Utilizing LangChain to embed data into a Qdrant vector database, the project enables deep insights into the public and financial sector's perception of interest rate changes. The project is encapsulated in a user-friendly Streamlit application, making it accessible to both technical and non-technical users interested in financial sentiment analysis.

## Features

- **Sentiment Analysis**: Utilizes advanced NLP techniques to gauge sentiment towards interest rates from various news sources.
- **Data Aggregation**: Automatically pulls data from a curated list of news websites, ensuring a broad spectrum of opinions and reports.
- **Vector Database Embedding**: Employs LangChain to embed processed data into the Qdrant vector database for efficient retrieval and analysis.
- **Streamlit Application**: Offers a Streamlit-based web interface that allows users to interact with the model, query data, and receive insights in real-time.
- **Customizable Queries**: Users can specify their queries to focus on particular aspects of interest rate discussions, allowing for tailored analysis.
- **Support for Multiple Libraries**: Integrates with several key Python libraries including OpenAI for NLP tasks, Groq for potential acceleration of computations, and LangChain for chaining LLMs with databases.

## How to Use

To use LLM-Interest-Rates-Sentiments, follow these steps:

1. **Setup**: Ensure you have Python installed on your system.
2. **Installation**: Clone the repository and install the required dependencies.
3. **Configuration**: Set up your OpenAI API key and any other necessary configurations in the provided settings file.
4. **Running the Application**: Launch the Streamlit application to start analyzing interest rate sentiments.
5. **Querying**: Use the web interface to input your queries and receive sentiment analysis results.

For detailed instructions, refer to the Installation and Usage sections below.

## Installation

bashCopy code

`git clone https://github.com/yourusername/LLM-Interest-Rates-Sentiments.git cd LLM-Interest-Rates-Sentiments pip install -r requirements.txt`

Ensure you have an OpenAI API key and configure it as per the documentation inside the project.

## How to Contribute

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

This template provides a comprehensive overview that not only introduces the project but also guides users on how to install, use, and contribute to it, enhancing the project's accessibility and community engagement.