# Smart India Hackathon Workshop
# Date: 29/03/2025
## Register Number: 212224040243
## Name: Prasanth T
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Proposed AI-Enabled Interview Assessment System
1. Virtual Board Room Experience
Simulated Interview Panel: A digital interface mimicking a real-life boardroom environment where experts can conduct interviews.

Ice-Breaking & Techno-Managerial Questions: System-generated question flow, starting with warm-up questions and gradually progressing to deeper technical/managerial queries based on the candidate's profile.

2. AI-Driven Question Relevancy Scoring
Expert Question Assessment:

AI evaluates the relevance of expert-generated questions based on the applicant’s expertise.

Scores and feedback are provided to ensure consistency.

Automated Question Suggestions:

System recommends relevant questions based on the job profile and candidate background.

3. AI-Based Candidate Response Evaluation
Relevancy Check: AI compares the candidate’s answer with expected responses (from expert-defined answer banks or AI-generated benchmark responses).

Natural Language Processing (NLP) Analysis:

AI assesses the depth, clarity, and technical accuracy of the answer.

Flags generic or off-topic responses.

Grading Mechanism:

Score assigned based on technical correctness, depth, and coherence.

Weightage varies depending on question difficulty and candidate level.

4. Overall Candidate Suitability Scoring
Final Score Calculation:

Weighted aggregation of question relevancy, response correctness, and overall subject expertise.

Customizable scoring based on job roles and candidate seniority.

Expert Override Option:

Human evaluators can modify AI-generated scores if needed.

5. Additional Features
Automated Report Generation: Summary report of candidate performance with strengths, weaknesses, and improvement areas.

Bias Detection & Fairness Analysis: Ensures objective evaluation and flags any potential biases in questioning or scoring.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/79fe94b5-1237-41a1-b1db-2f534c28daae)

## Use Cases
![image](https://github.com/user-attachments/assets/5ab82446-922f-43ae-9c1b-778e710fa6a7)


## Technology Stack

1. Frontend (User Interface - Web/Software Panel)
Frameworks: React.js / Angular / Vue.js (for an interactive web interface)

UI Libraries: Tailwind CSS / Material-UI / Bootstrap (for styling)

WebRTC / Media APIs: For live interviews & video conferencing

Three.js / Babylon.js: If a 3D virtual boardroom experience is needed

2. Backend (Business Logic & API Layer)
Programming Languages: Python (Django/FastAPI), Node.js (Express/Nest.js)

Database: PostgreSQL / MySQL (for structured interview data), MongoDB (for flexible question/response storage)

Authentication & Security: OAuth2, JWT, Role-based access control (RBAC)

3. AI/ML (Interview Analysis & Scoring Engine)
Natural Language Processing (NLP):

OpenAI GPT / Google BERT / Hugging Face Transformers (for response analysis)

Spacy / NLTK / TextBlob (for keyword extraction, sentiment analysis)


## Dependencies

Core Dependencies:
React.js / Angular / Vue.js → Frontend framework

Tailwind CSS / Material-UI / Bootstrap → UI styling

Redux / Zustand → State management

Axios / Fetch → API calls

React Router / Angular Router → Routing

WebRTC / Jitsi Meet API → Live video interviews

Three.js / Babylon.js → (Optional) 3D Virtual Boardroom

Natural Language Processing (NLP):
Transformers (Hugging Face) → Pre-trained AI models (GPT, BERT, T5)

spaCy / NLTK / TextBlob → Text preprocessing & analysis

Scikit-learn → Machine learning algorithms for scoring

OpenAI API / Google BERT → Language understanding models

Sentence-Transformers → Semantic similarity analysis

IBM AI Fairness 360 / Fairlearn → Bias detection
Mozilla DeepSpeech / Whisper / Google Speech-to-Text API → Speech recognition

Librosa / Pydub → Audio processing

Wavelet Transform (PyWavelets) → Voice feature extraction
