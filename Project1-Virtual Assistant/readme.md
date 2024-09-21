# Siya - Virtual Assistant

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)
7. [Voice Commands](#voice-commands)
8. [Future Improvements](#future-improvements)
9. [Author](#author)

## Project Overview
Siya is a virtual assistant powered by HTML, CSS, and JavaScript. It uses browser-based speech recognition and speech synthesis to interact with users via voice commands. With Siya, users can perform tasks like opening websites, checking the time, and browsing the web, all by speaking.

## Features
- **Voice Recognition**: Supports voice commands using the Web Speech API.
- **Speech Output**: Replies with spoken responses via the SpeechSynthesis API.
- **Task Automation**: Executes voice-controlled tasks such as opening websites (e.g., YouTube, Google).
- **Real-Time Updates**: Provides the current time and date on request.
- **Dynamic Web Searches**: Conducts web searches when specific queries are given.

## Technologies Used
- **HTML5**: For structuring the web page.
- **CSS3**: To style the web interface.
- **JavaScript**: Implements voice command recognition and response logic.
  - **SpeechRecognition API**: Captures and processes user voice inputs.
  - **SpeechSynthesis API**: Provides voice responses.

## Project Structure
/siya-virtual-assistant │ ├── /Images │ ├── logo.png │ ├── mic.svg │ ├── voice.gif │ ├── index.html # Main HTML structure ├── style.css # CSS file for styling ├── script.js # JavaScript file containing the logic └── README.md # Documentation

## Installation and Setup
1. **Clone the Repository**  
   Clone the repository to your local machine using: Run live server
   ```bash
   git clone https://github.com/your-username/siya-virtual-assistant.git
  
2. **Open the Project**
Navigate to the project folder and open the index.html file in your preferred web browser.

3. **Start Interacting**
Once opened, click on the microphone icon to start giving commands.

## Usage
Siya listens for voice commands once you click the "Click here for talk to me" button. The assistant can perform tasks such as:

Opening popular websites (e.g., YouTube, Google, Facebook).
Telling you the current time and date.
Conducting Google searches for user queries.

## Voice Commands
Here are some of the commands you can try:

## Greeting
- Command: "Hello"
- Response: "Hello, what can I help you with?"
## Introduction
- Command: "Who are you?"
- Response: "I am Siya, your virtual assistant, created by Supriya."
## Open Websites
- Command: "Open YouTube"
- Response: "Opening YouTube..."
(Siya will open the YouTube website.)
## Current Time
- Command: "What time is it?"
- Response: Siya will tell you the current time.
## Current Date
- Command: "What is the date today?"
- Response: Siya will provide the current date.

## Siya can also search the web for anything you ask!

## Future Improvements
- Expand the range of tasks Siya can perform.
- Integrate additional languages for broader accessibility.
- Implement a more advanced natural language processing for better understanding.

## Author
Created by Supriya.
   
