# Smart India Hackathon Workshop
# Date:21/03/2025
## Register Number:212224040366
## Name:V.VISHAL
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The goal is to develop a Web-Based Selector-Applicant Simulation Software that mimics a real-life boardroom interview experience for both interviewers and candidates. This system will automate and enhance the assessment process by evaluating:

The relevancy of interview questions posed by panel members.
The quality and correctness of candidate responses based on expertise and job role.
Overall scoring to determine a candidate’s suitability for the role.
This will help in conducting objective, unbiased, and structured interviews to ensure the selection of the best candidates.

## Proposed Solution / Architecture Diagram
The solution will be a web-based application with the following key components:

User Authentication & Role Management:

Roles: Admin, Interview Panel, Candidates
Secure login for each user role.
Interview Preparation Module:

Experts upload a question bank categorized by domain expertise.
AI/ML-based question recommendations for interviewers.
Interview Execution Module:

Panel members select and ask relevant questions.
Candidates respond verbally or in text format.
AI-based speech-to-text conversion (if voice responses are used).
Scoring & Analysis Module:

AI/ML-powered automatic grading of responses.
Score generation based on question relevance & answer accuracy.
Feedback mechanism for continuous improvement.
Dashboard & Reports:

Performance insights for interviewers and candidates.
Detailed reports for HR and decision-makers.

## Use Cases
Candidate Perspective:

Logs into the system, enters details, and selects a relevant domain.
Undergoes a simulated boardroom interview experience.
Receives AI-evaluated feedback & scores after the session.
Interviewer Perspective:

Logs in and selects or generates questions based on the candidate’s expertise.
Uses AI-based suggestions to improve the interview process.
Evaluates candidate responses and views AI-assisted scoring.
Admin / HR Perspective:

Manages user roles and access control.
Generates reports for selection and promotion decisions.


## Technology Stack
```
Component	Technology Used
Frontend	React.js / Angular / Vue.js
Backend	Node.js (Express.js) / Django / Flask
Database	PostgreSQL / MongoDB / MySQL
AI/ML Processing	Python (NLTK, OpenAI GPT, TensorFlow, or Hugging Face for NLP)
Speech-to-Text (if required)	Google Speech API / Azure Cognitive Services
Authentication	OAuth 2.0 / JWT
Deployment	AWS / Azure / Google Cloud
DevOps & CI/CD	Docker, Kubernetes, GitHub Actions
```
## Dependencies
```
AI/ML Libraries for NLP-based question & response evaluation.
Cloud services for data storage and processing.
Speech-to-text API for voice-based interviews (if implemented).
Security compliance to ensure interview data confidentiality.
WebRTC / Video conferencing API (if live virtual interviews are needed).

```
