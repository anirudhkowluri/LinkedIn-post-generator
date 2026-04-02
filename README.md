🚀 AI-Powered LinkedIn Post Generator (Style-Aware GenAI)

An intelligent Generative AI application that analyzes a LinkedIn creator’s past posts and generates new posts in the same writing style using few-shot learning and LLMs.

This project goes beyond simple text generation — it learns tone, structure, and patterns from historical content to produce highly personalized posts.

🌐 Live Demo

👉 https://linkedin-post-generator-imvzz7q2yhtm9oalz6zkgg.streamlit.app/

💡 Problem Statement

Creating consistent, high-quality LinkedIn content is difficult and time-consuming.

This tool solves that by:

Learning from your past posts
Extracting patterns (tone, length, topics)
Generating new posts that feel authentic and personalized
✨ Key Features
🧠 Style-Aware Content Generation (based on past posts)
🎯 Topic-based post generation
🌍 Multi-language support
📏 Adjustable post length
⚡ Real-time generation using LLMs
🧩 Few-shot learning for better personalization
💻 Clean UI with Streamlit
🧠 How It Works
🔹 Stage 1: Content Analysis
Input: Past LinkedIn posts
Extracts:
Topics
Language
Length
Writing patterns
🔹 Stage 2: Post Generation
User selects:
Topic
Language
Length
System:
Retrieves similar past posts
Uses them as few-shot examples
Generates a new post using LLM

👉 This ensures the output matches the user's unique writing style

🏗️ Technical Architecture
Input Layer: User past LinkedIn posts
Processing Layer:
Feature extraction (topic, tone, length)
Similarity-based retrieval
Generation Layer:
Few-shot prompt construction
LLM inference (Groq API)
Output Layer: Generated LinkedIn post
🛠️ Tech Stack
Language: Python
Frontend: Streamlit
LLM Provider: Groq API
Core Concepts:
Prompt Engineering
Few-shot Learning
Retrieval-based Generation
Libraries:
LangChain (if used)
Pandas / Data Processing
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/anirudhkowluri/LinkedIn-post-generator.git
cd LinkedIn-post-generator
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Setup Environment Variables

Create a .env file:

GROQ_API_KEY=your_api_key_here

👉 Get API key: https://console.groq.com/keys

4️⃣ Run Application
streamlit run main.py
📊 Example Use Case

A LinkedIn creator uploads their past posts →
The system learns their tone →
They select a topic →
AI generates a new post that sounds like them

🔥 What Makes This Project Stand Out
Not just a text generator — style-aware AI system
Implements few-shot learning in a real product
Uses retrieval + generation hybrid approach
Real-world application for personal branding & content automation
🚀 Future Enhancements
📈 Engagement prediction (likes/comments estimator)
🔖 Auto hashtag generation
🧑‍💼 Audience-specific tone adaptation
📅 LinkedIn scheduling integration
🌐 Multi-platform support (Twitter, Medium, etc.)
