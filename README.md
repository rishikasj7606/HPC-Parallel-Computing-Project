ML Learning Chatbot
An educational chatbot built with Streamlit to help students and early-career learners understand machine learning concepts, connect theory to practical projects, and prepare for internship interviews.

The application combines a lightweight semantic retrieval layer with a pretrained text generation model so answers stay focused on core ML topics while remaining easy to understand.

Overview
This project is designed for learners who want support with questions such as:

How does a machine learning model work?
When should one algorithm be chosen over another?
How can theory be applied in a real project?
What is the right way to train and evaluate a model?
How should an ML project be explained in an interview?
Key Features
Streamlit-based conversational interface
Three guided learning modes: Concept Tutor, Project Guide, and Interview Prep
Clickable starter prompts for faster exploration
Session-based conversation flow for follow-up questions
Sidebar session snapshot with question count and retrieved topics
Semantic retrieval using sentence-transformers
Pretrained text generation using google/flan-t5-base
Curated built-in knowledge base for common ML topics
Beginner-friendly, application-oriented answers
How It Works
The chatbot follows a simple retrieval-augmented workflow:

The user asks a machine learning question.
The app retrieves the most relevant learning notes from the internal knowledge base.
A prompt is built using the selected assistant mode and retrieved context.
The pretrained language model generates a structured educational response.
The interface shows the retrieved topic area used to ground the answer.
This helps the chatbot stay grounded in the project knowledge base while still producing natural explanations.

Tech Stack
Python
Streamlit
transformers
sentence-transformers
torch
numpy
scikit-learn
Project Structure
.
|-- app.py                # Streamlit user interface and chatbot flow
|-- knowledge_base.py     # ML lesson content and semantic retrieval logic
|-- requirements.txt      # Project dependencies
|-- README.md             # Project documentation
Installation
1. Clone the repository
git clone https://github.com/rishikasj7606/HPC-Parallel-Computing-Project.git
cd HPC-Parallel-Computing-Project
2. Create a virtual environment
python -m venv .venv
3. Activate the virtual environment
On Windows PowerShell:

.\.venv\Scripts\Activate.ps1
4. Install dependencies
pip install -r requirements.txt
5. Run the application
streamlit run app.py
After launching, Streamlit will provide a local URL in the terminal where the chatbot can be accessed in the browser.

Example Questions
Explain bias vs. variance in simple terms.
When should I use linear regression instead of random forest?
How do I evaluate a classification model?
What is a good workflow for a churn prediction project?
How can I explain overfitting in an internship interview?
Why is feature scaling important for some algorithms?
Interface Highlights
Use the sidebar to switch between learning modes
Start a fresh session with the Start New Chat button
Click a starter prompt to instantly send a sample question
Ask follow-up questions in the same session for more natural learning flow
Expand the grounding section below an answer to see which knowledge topics were retrieved
Knowledge Areas Covered
The built-in knowledge base includes topics such as:

machine learning pipelines
regression and classification basics
random forests, SVMs, and neural networks
overfitting and underfitting
evaluation metrics
feature engineering
cross-validation
clustering
embeddings
baseline models
error analysis
deployment and monitoring
Intended Audience
This project is especially useful for:

students learning machine learning fundamentals
interns preparing for technical discussions
beginners building their first ML mini-projects
learners who want practical explanations instead of only theory
Limitations
The chatbot relies on a compact built-in knowledge base and is not a replacement for full coursework or domain-specific research.
Response quality depends on the pretrained model and retrieved context.
The first run may take time because the embedding and generation models need to be loaded.
Future Improvements
Expand the knowledge base with more topics and examples
Add support for chat history-aware responses
Improve response formatting for longer explanations
Introduce evaluation or feedback mechanisms for answer quality
Add deployment instructions for cloud hosting
License
This repository currently does not include a license file. Add a license if you plan to distribute or reuse the project publicly.
