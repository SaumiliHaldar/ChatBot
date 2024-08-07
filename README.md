# ChatBot

This repository contains the source code for ChatBot, an advanced chatbot integrated into an e-learning platform. ChatBot provides conversational support, code generation, and resource recommendations, utilizing cutting-edge NLP techniques.

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

ChatBot is designed to enhance the learning experience by providing a sophisticated, interactive chatbot that supports both students and teachers. The chatbot can engage in natural conversations, generate code snippets, and recommend relevant learning resources.

## Features

- **Conversational Support**: Engage in natural-sounding conversations with users.
- **Code Generation**: Provide high-quality code snippets for various programming languages.
- **Resource Recommendation**: Suggest learning materials, articles, and online courses.
- **Integration with E-learning Platform**: Seamlessly integrated into an existing e-learning platform.

## Technologies Used

- [Hugging Face Transformers](https://huggingface.co/transformers/): For state-of-the-art NLP models and chatbot functionality.
- [NLTK (Natural Language Toolkit)](https://www.nltk.org/): For foundational NLP tasks such as tokenization, parsing, and classification.
- [spaCy](https://spacy.io/): For efficient text processing, named entity recognition, and dependency parsing.
- [Python](https://www.python.org/): Core language for developing the chatbot.
- [Django](https://www.djangoproject.com/): For backend development and API creation.

## Installation

To get a local copy up and running, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/SaumiliHaldar/ChatBot.git
    ```

2. Navigate to the project directory:
    ```sh
    cd ChatBot
    ```

3. Set up a virtual environment:
    ```sh
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On Windows:
      ```sh
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```sh
      source venv/bin/activate
      ```

5. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

6. Run database migrations (if applicable):
    ```sh
    python manage.py migrate
    ```

7. Start the development server:
    ```sh
    python manage.py runserver
    ```

## Usage

1. Open your browser and navigate to `http://localhost:8000`.
2. Interact with the ChatBot by asking questions or requesting code assistance.
3. Explore the chatbot's functionalities including resource recommendations and code generation.

## Contributing

Contributions are welcome! To contribute to ChatBot:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Saumili Haldar - haldar.saumili843@gmail.com  
Project Link: [https://github.com/SaumiliHaldar/ChatBot](https://github.com/SaumiliHaldar/ChatBot)
