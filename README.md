# Emotion Detection Application

## Overview

This project is an Emotion Detection application that uses functions from embeddable AI libraries to analyze emotions in text. The application extracts relevant information from the AI model's output, handles errors, and is deployed using Flask.

## Features

- **Emotion Detection**: Analyzes text to identify and score various emotions such as anger, disgust, fear, joy, and sadness.
- **Error Handling**: Incorporates error handling to manage invalid inputs and provide meaningful error messages.
- **Web Deployment**: Deployed as a web application using Flask, allowing users to interact with the emotion detection functionality through a web interface.
- **PEP8 Compliance**: Code adheres to PEP8 guidelines, ensuring readability and maintainability. Achieved a 10/10 score in static code analysis.

## Setup and Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/your-repository.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd your-repository
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask Application**:
    ```bash
    python server.py
    ```

5. **Access the Application**:
    Open your web browser and go to `http://localhost:5000` to interact with the application.

## Usage

- **Emotion Detection**: Enter text into the provided form on the web interface and submit. The application will display the detected emotions and the dominant emotion.

## Error Handling

- **Invalid Input**: If the input text cannot be processed, the application will display a message: "Invalid text! Please try again!"

## Code Quality

- The code follows [PEP8](https://www.python.org/dev/peps/pep-0008/) guidelines, ensuring it is clean and maintainable.
- Static code analysis results: 10/10

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements. For detailed guidelines, refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Contact

For any inquiries or support, please contact [Ismail Bajwa](mailto:ismailbajwa2003@gmail.com).
