# JARVis- Aid For The Visually Impaired

Welcome to JARVis! This project aims to assist blind or visually impaired individuals in perceiving and understanding the world around them through image and text processing. This repository contains the backend code for the Vision Aid system.

## Table of Contents

- [Introduction](#introduction)
- [How It Works](#how-it-works)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Vision Aid Project is designed to provide real-time assistance to visually impaired individuals. It uses advanced technologies to recognize and describe scenes in front of the user, extract text from images, and answer user queries. The backend server is responsible for handling image recognition, text extraction, and natural language understanding, making it a vital part of the system.

## How It Works

1. **Image Recognition**: The system analyzes images captured by a camera to identify and describe scenes, objects, and emotions in real-time.

2. **Text Extraction**: Utilizing Amazon Textract, the system can extract text from images, making printed information accessible.

3. **Natural Language Understanding**: Users can interact with the system by asking questions or seeking information. The backend uses GooglePalm for natural language understanding to provide relevant answers.

4. **Voice Output**: The system offers voice output capabilities using gTTS (Google Text-to-Speech) to convey image descriptions and textual content to users.

5. **Real-time Communication**: The backend communicates in real-time with the frontend using WebSockets, enabling seamless user interactions.

## Features

- **Image Recognition**: Detects and describes scenes and emotions in real-time.
- **Text Extraction**: Extracts text from images using Amazon Textract for OCR.
- **Natural Language Understanding**: Answers user queries and provides contextual information.
- **Voice Output**: Converts text to speech for user-friendly communication.
- **Real-time Communication**: WebSocket integration for instant interaction with the frontend.
- **External Service Integration**: Connects with HumeStream for image analysis and Milvus for image similarity search.

## Getting Started

To start using the Vision Aid Project, follow these steps:

1. Clone this repository to your local machine.

2. Install the required Python libraries using `pip install -r requirements.txt`.

3. Configure external services such as HumeStream, Milvus, and MongoDB as needed.

4. Run the Flask application using `python app.py`.

## Usage

- **Image Recognition**: Capture images and send them to the server for real-time scene and emotion recognition.

- **Text Extraction**: Extract text content from images using the OCR feature.

- **Question and Interaction**: Ask questions and interact with the system to obtain answers and descriptions.

- **Real-time Communication**: Utilize WebSocket-based communication for image analysis and interaction.

## Contributing

We welcome contributions to the Vision Aid Project. If you'd like to contribute, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
