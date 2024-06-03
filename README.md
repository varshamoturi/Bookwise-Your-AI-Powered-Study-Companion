# Bookwise: Your AI-Powered Study Companion

Bookwise is an innovative application that revolutionizes the way you study and explore books. By leveraging advanced AI techniques, Bookwise simplifies the process of finding precise information within books, making studying more efficient and enjoyable.

## Features

- **Effortless Book Exploration:** Upload PDF books and pose inquiries seamlessly. Bookwise provides detailed answers, complete with contextual details such as page numbers and topics.
- **Enhanced Learning :** Quickly find answers, enhance lesson planning, streamline data gathering, and enjoy a richer reading experience.
- **Optimized Learning Experience:** Elevate your learning journey with quick and accurate answers to specific questions. Enjoy a global reach and inclusive access to valuable knowledge.

## Technology Stack

Bookwise utilizes a sophisticated AI-driven pipeline that combines text extraction, chunking, vectorization, and language model querying to deliver accurate and contextually relevant answers.

- **Text Extraction:** Extracts text from PDFs using a robust PDF loading library.
- **Text Chunking:** Splits extracted text into smaller, manageable chunks.
- **Vectorization and Similarity Search:** Vectorizes text chunks and stores them in a FAISS index for efficient similarity searches.
- **Language Model Querying:** Utilizes a fine-tuned version of OpenAI's GPT-4 model for accurate and contextually relevant answers.
- **User Interface:** User-friendly interface developed using Streamlit.

## Getting Started

To get started with Bookwise, follow these steps:

1. Install the required dependencies listed in `requirements.txt`.
2. Run the Streamlit application using `streamlit run main.py`.
3. Upload your PDF books and start exploring effortlessly!

## Contributing

We welcome contributions from the community! If you have any ideas or suggestions for improving Bookwise, please feel free to submit a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
