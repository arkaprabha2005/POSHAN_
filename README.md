🌱 POSHAN

Precision-based Optimized Smart Harvest for Agricultural Nutrition

POSHAN is a Flutter-based mobile application that supports farmers and agricultural stakeholders with data-driven insights, nutrition awareness, and an intelligent conversational assistant. The app connects agricultural productivity with nutritional outcomes in a simple, mobile-friendly way.

🚀 Features
🔐 Authentication

Google Sign-In using Firebase Authentication
-Secure login & logout
-Persistent user session

📊 Dashboard

-Overview of key agricultural metrics:
-Total crops
-Yield forecast
-Water usage
-Sunlight exposure
-Revenue growth
-Crop health
-Efficiency score
-Sustainability score
-Clean card-based UI optimized for mobile screens

🌾 Crops Module

-Displays recommended crops
-Suitability indicators for each crop
-Designed for easy extension with AI models

🌦 Weather Module
-Weather summary card
-Displays:
-Temperature
-Humidity
-Wind speed
-Visibility
-Helps farmers plan irrigation and crop cycles

🥗 Nutrition Module

-Nutritional comparison of crops
-Protein & carbohydrate analysis
-itamin distribution charts
-Focus on nutritional security along with farming

🤖 POSHAN Assistant (Chatbot)

-Conversational assistant for agriculture & nutrition queries
-Supports questions about:
-Crop cultivation (rice, wheat, maize, millets, vegetables)
-Water usage & irrigation
-Weather impact on crops
-Nutrition & protein sources
-Implemented using intent-based logic for stable demos
-Architecture designed for easy integration with AI APIs (Gemini / LLMs)

🧠 AI Architecture

Current implementation uses:
-Rule-based intent recognition
-Benefits:
-Reliable during demos
-No dependency on external APIs
-Designed to be easily replaced with:
-Google Gemini
-Other LLM APIs

🛠 Tech Stack

-Flutter – Cross-platform app development
-Dart – Application logic
-Firebase Authentication – Google Sign-In
-FL Chart – Data visualization
-Material Design – UI/UX

Project Structure
lib/
 ├── screens/
 │   ├── dashboard_screen.dart
 │   ├── crops_screen.dart
 │   ├── weather_screen.dart
 │   ├── nutrition_screen.dart
 │   ├── login_screen.dart
 │   └── chatbot_screen.dart
 ├── services/
 │   └── gemini_service.dart (optional / future use)
 └── main.dart

assets/
 └── google.png

 🎯 Use Cases

-Farmers planning crop cycles
-Agriculture students & researchers
-Nutrition-focused agricultural programs
-Smart farming demonstrations

📌 Future Enhancements

-Live AI integration (Gemini / LLMs)
-Location-based crop recommendations
-Soil analysis using camera input
-Backend analytics dashboard
-Multilingual support

🏁 Hackathon Note

-This project was built as part of a hackathon with a focus on:
-Practical usability
-Clean architecture
-Reliable demo experience
-Real-world agriculture & nutrition impact

📜 License

This project is intended for educational and hackathon purposes.