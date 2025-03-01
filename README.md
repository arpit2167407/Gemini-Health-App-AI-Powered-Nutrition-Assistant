# Gemini-Health-App-AI-Powered-Nutrition-Assistant
# Overview

The Gemini Health App is a Streamlit-based application that leverages the Google Gemini Pro Vision API to analyze food images and estimate total calorie intake. It helps users understand the nutritional content of their meals by identifying food items in an image and providing a calorie breakdown.

# Features

* 📸 Upload an image of food items.

* 🤖 Get an AI-powered analysis of the food items in the image.

* 🔢 Receive a detailed calorie breakdown for each item.

* 🎨 Easy-to-use Streamlit interface.

# Installation

1. Prerequisites

Ensure you have the following installed:

Python 3.7+

pip (Python package manager)

2. Clone the Repository

 git clone https://github.com/your-repository/gemini-health-app.git
 cd gemini-health-app

3. Install Dependencies

a. streamlit
b. Pillow
c. google-generativeai
d. dotenv

3. Setup Environment Variables

Create a .env file in the project root.

4. Add your Google API Key:

GOOGLE_API_KEY=your_google_api_key_here

5. Usage

Run the Streamlit app using the following command:

streamlit run app.py

# How It Works

* Enter a prompt in the input field.

* Upload an image of food items.

* Click the 'Tell me the total calories' button.

* The app will process the image and return a breakdown of food items with their respective calorie counts.
