This project is a comprehensive AI-based system designed to help individuals identify, understand, and gradually overcome social anxiety through interactive, personalized coaching. 
The system uses a combination of structured input, sentiment analysis, and AI-generated scenarios to guide users in developing social confidence. Here are the key aspects of the project:

🔹 Problem Addressed
Social Anxiety Disorder (SAD) affects millions and limits social functioning.

Many individuals hesitate to seek professional help due to cost, stigma, or lack of access.

There is a need for an accessible, real-time tool that provides emotional support and confidence-building exercises.

🔹 Core Functionalities
Accepts structured questionnaire responses using a 5-point Likert scale to measure anxiety.

Collects and analyzes free-text responses using VADER sentiment analysis.

Computes a Social Anxiety Score (SAS) and classifies users into anxiety levels: Low, Moderate, or High.

Generates personalized “deck cards” (interactive prompts + tips) using the GPT-2 model.

Provides adaptive feedback based on user sentiment and progression.

🔹 AI & NLP Integration
Uses the Hugging Face GPT-2 transformer model for generating realistic and contextual coaching scenarios.

Incorporates VADER (Valence Aware Dictionary for Sentiment Reasoning) from NLTK for emotion detection.

Applies rule-based logic to determine transitions between training phases (Ice Breakers → Bridge the Gap → Deep Dive).

🔹 User Journey & Progress Tracking
Tracks initial and updated SAS to measure user progress.

Displays changes in anxiety levels visually using bar charts and pie charts.

Provides continuous feedback to help users engage in healthier social behavior.

🔹 Benefits
Anonymous and self-paced — suitable for users uncomfortable with therapy.

Interactive and personalized — adapts based on real-time sentiment and behavioral cues.

Scalable and portable — can be extended into a chatbot or mobile application.

🔹 Potential Use Cases
Mental health companion apps

Personal confidence coaching tools

Educational use in psychology/AI projects

Early intervention and self-screening systems

