# Final project

## AI-Based Emotion Detection Web Application

This project implements an **AI-powered Emotion Detection web application** using Python, Flask, and IBM Watson NLP services.
The application analyzes user-provided text and detects the emotional tone expressed in the statement.

The system identifies five core emotions:

* Anger
* Disgust
* Fear
* Joy
* Sadness

The application also determines the **dominant emotion** in the input text and displays it through a web interface.

---

## Project Overview

Emotion detection extends traditional sentiment analysis by identifying **specific emotional states** rather than simply classifying text as positive or negative.
This technology is widely used in:

* Customer feedback analysis
* Chatbots and conversational AI
* Product review systems
* Social media analytics
* Mental health monitoring tools

This project demonstrates how to build a **complete AI-powered web service pipeline**, including API integration, backend logic, testing, and web deployment.

---

## Features

* AI-based emotion detection using IBM Watson NLP
* Flask web application for user interaction
* Automatic identification of dominant emotion
* Unit testing for validation
* Error handling for invalid or empty inputs
* Static code analysis with PyLint
* Modular Python package structure

---

## Project Architecture

Frontend (HTML + JavaScript)
⬇
Flask Web Server
⬇
Emotion Detection Python Module
⬇
IBM Watson NLP Emotion Detection API

---

## Project Structure

```
Final_project
│
├── emotion_detection
│   ├── __init__.py
│   └── emotion_detection.py
│
├── server.py
├── test_emotion_detection.py
│
├── templates
│   └── index.html
│
└── static
    └── mywebscript.js
```

---

## Installation

Clone the repository:

```
git clone https://github.com/shinokage999/emotion_detection-ibm_dev_final_project.git
cd emotion_detection-ibm_dev_final_project
```

Install dependencies:

```
pip install flask requests pylint
```

---

## Running the Application

Start the Flask server:

```
python3 server.py
```

Open the web application in your browser:

```
http://localhost:5000
```

Enter a text statement and click **Run Sentiment Analysis** to view the detected emotions.

---

## Example Output

Input:

```
I think I am having fun
```

Output:

```
For the given statement, the system response is
'anger': 0.02, 'disgust': 0.01, 'fear': 0.03, 'joy': 0.91 and 'sadness': 0.03.
The dominant emotion is joy.
```

---

## Unit Testing

Run unit tests with:

```
python3 test_emotion_detection.py
```

All tests validate that the correct dominant emotion is detected for sample statements.

---

## Error Handling

If the user submits an empty input, the application responds with:

```
Invalid text! Please try again!
```

---

## Static Code Analysis

PyLint is used to ensure compliance with **PEP8 coding standards**.

Run analysis:

```
pylint server.py
```

Target score: **10.00 / 10**

---

## Technologies Used

* Python
* Flask
* IBM Watson NLP
* HTML
* JavaScript
* PyLint
* Git & GitHub

---

## Author

Anubhav Saha

---

## License

This project is developed as part of the **IBM AI-based Web Application Development course** on Skills Network Labs.
