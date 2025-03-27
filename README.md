# Interactive MBTI Personality Quiz with Gemini AI

![MBTI Types Banner](https://via.placeholder.com/800x200.png?text=MBTI+Personality+Types) <!-- Replace with actual image -->

An AI-powered personality assessment tool that predicts your Myers-Briggs (MBTI) type using Google's Gemini AI.

## ✨ Features

- 🧠 AI-based personality analysis
- ❓ Interactive question-answer format
- 📊 Returns 4-letter MBTI type (e.g., INTJ, ENFP)
- 📝 Personalized trait descriptions
- 🛠️ Error-resistant input handling

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Gemini](https://img.shields.io/badge/Google%20Gemini-API-yellow)
![JSON](https://img.shields.io/badge/Data-JSON-lightgrey)

## 🚀 How It Works

1. User answers psychological questions
2. Gemini AI analyzes response patterns
3. System predicts MBTI personality type
4. Returns personalized description

```plaintext
Example Flow:
Q: Do you prefer plans or spontaneity?
A: I like to keep my options open
→ Your type: ENFP - The enthusiastic, creative innovator 

```
## Install dependencies:

pip install -r requirements.txt

## 🚀 Quick Start

from mbti_quiz import MBTIQuiz

quiz = MBTIQuiz(api_key="your_gemini_key")
quiz.start_quiz()  # Begin interactive session

## 🖥️ Sample Output

🌟 Question 1/5: Do you prefer (1) planning or (2) spontaneity? 
> 2

...

🎉 Your Results:
MBTI Type: ENFP
Description: "The Campaigner - Enthusiastic, creative, and sociable!"
Strengths: Big-picture thinking, connecting with people

## 🔍 How It Works

1. User answers psychological questions

2. Responses are analyzed by Gemini AI

3. System compares patterns against MBTI traits

4. Returns most likely personality type

5. Provides detailed description

## 💡 Why This Project?

1. Demonstrates practical AI/NLP application

2. Makes personality psychology accessible

3. Educational tool for understanding MBTI

4. Easily extendable (add more questions, types)

## 📈 Future Improvements

1. Add visual personality dashboard

2. Implement type compatibility analysis

3. Include career suggestions

4. Multi-language support
