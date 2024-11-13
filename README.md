# FabGenie_ChatBot
FabGenie is a fashion chatbot that provides personalized outfit recommendations based on weather, occasion, and preferences. Using Google’s Gemini AI, it offers specific clothing tips, styling advice, and even shopping links—all within a visually engaging CLI experience. Perfect for anyone wanting style guidance tailored to their needs!


# FabGenie - Your Personal Fashion Assistant 👗👔👠

FabGenie is a stylish and intuitive chatbot that helps users make fashion choices based on personal preferences, the weather, and the occasion. Leveraging Google’s Gemini AI, FabGenie generates tailored fashion advice and even suggests shopping links to make finding items easy and convenient.

## 📋 Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [API Keys and Configuration](##api-keys-and-configuration)
6. [Technologies Used](#technologies-used)
7. [Acknowledgements](#acknowledgements)

## 🎉 Project Overview
FabGenie is designed to serve as your virtual stylist. With user input on gender, location, and occasion, the chatbot uses Google Gemini API to offer specific fashion advice, including:
- **What to wear**: suggestions on tops, bottoms, footwear, and accessories
- **Style tips**: color coordination, style dos and don'ts, and more
- **Weather-based suggestions**: seasonal clothing and accessories

Users can interact with FabGenie through follow-up questions, making it a conversational and dynamic experience. Additionally, FabGenie provides shopping links to help you find fashion items directly on Amazon.

This project is developed and tested on **Google Colab**, making it accessible and easy to run in an online environment.

## ✨ Features
- **Weather-Adapted Styling**: Fetches real-time weather information based on city input to recommend seasonally appropriate attire.
- **Shopping Suggestions**: Generates Amazon links for recommended items, so you can start shopping right away.
- **Interactive Q&A**: Users can ask specific questions about their outfit or seek more tailored advice.
- **Stylish Console UI**: Built with `rich` library for a visually engaging CLI experience.

## 🚀 Installation
To get started with FabGenie, clone this repository and install the necessary dependencies.

```bash
git clone https://github.com/your-username/fabgenie.git
cd fabgenie
pip install -r requirements.txt
```

## 🔑 API Keys and Configuration
- **Google Gemini API Key**: To use the Gemini AI for generating fashion advice, please enter your Gemini API key. **(On line 17 of FabGenie.txt)**
- **OpenWeather API Key**: For real-time weather data, get a free API key from [OpenWeather](https://openweathermap.org/api). **(On line 77 of FabGenie.txt)**

**Add both keys to your project code before running FabGenie.**

## 💻 Usage
Copy paste the FabGenie.txt file in your google Collab 

## 🛠 Technologies Used
- Google Gemini API - For generating tailored fashion advice.
- OpenWeather API - To fetch real-time weather data.
- Rich Library - To create an engaging console-based UI.
- Python - Core language for scripting and logic.


## ❤️ Acknowledgements
Special thanks to Google Colab for providing a collaborative environment to develop and test this project.


