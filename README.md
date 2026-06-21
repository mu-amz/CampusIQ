# 🏢 CampusIQ

### AI-Powered Campus Infrastructure Management Platform

<p align="center">
  <b>Detect • Classify • Assign • Resolve</b>
</p>

CampusIQ is an intelligent infrastructure management platform designed to automate campus maintenance operations through Artificial Intelligence, Computer Vision, NLP, and Smart Work Allocation. The system enables students and faculty members to report infrastructure issues through a Flutter mobile application while administrators manage operations through a centralized Django web dashboard.

By combining AI-driven complaint analysis, image recognition, automated worker assignment, and an intelligent chatbot, CampusIQ significantly improves maintenance efficiency and reduces complaint resolution time.

---

# 🚀 Key Features

## 🤖 AI-Powered Complaint Classification

The platform automatically analyzes complaints and categorizes them into appropriate maintenance departments.

Supported Categories:

* ⚡ Electrician
* 🚰 Plumber
* 🪑 Carpenter
* 🧹 Cleaning Staff
* 🌱 Gardener

This removes the need for manual complaint sorting and ensures faster response times.

---

## 📸 Image-Based Issue Recognition

Users can upload images while submitting complaints.

Using Google Gemini Vision AI, the system:

* Detects objects from uploaded images
* Identifies damaged infrastructure
* Enhances complaint descriptions
* Classifies maintenance requirements automatically

Examples:

* Broken Fan → Electrician
* Damaged Chair → Carpenter
* Leaking Sink → Plumber
* Garbage Accumulation → Cleaning Team
* Damaged Plant Area → Gardener

---

## 🎯 Automated Worker Allocation

Once a complaint is submitted:

1. AI analyzes the complaint
2. Issue category is identified
3. Location is extracted automatically
4. Appropriate worker is selected
5. Task is assigned instantly

This creates a complete automated complaint-to-resolution workflow.

---

## 📍 Smart Location Extraction

The system automatically extracts locations from complaint descriptions.

Examples:

* "Fan not working in Computer Lab"
* "Broken chair in Room 404"
* "Leakage in Chemistry Lab"

Detected locations are stored and used for:

* Worker assignment
* Maintenance tracking
* Administrative reporting

---

## 💬 AI-Powered Infrastructure Assistant

CampusIQ includes an intelligent chatbot that assists users with infrastructure-related queries.

Capabilities:

* Complaint guidance
* Maintenance assistance
* Infrastructure information
* Facility navigation
* Troubleshooting support
* Campus service information

The chatbot combines:

* Custom institutional datasets
* NLP similarity matching
* Google Gemini AI

to provide accurate and context-aware responses.

---

## 📚 Admin Managed Knowledge Base

Administrators can manage chatbot knowledge directly through the web portal.

Features:

* Add custom questions
* Add institutional answers
* Update chatbot dataset
* Improve chatbot accuracy
* Manage campus-specific information

This enables the chatbot to continuously improve without requiring model retraining.

---

# 👥 User Roles

## 🖥️ Administrator (Web Portal)

* Manage departments
* Manage faculty members
* Manage maintenance workers
* Monitor complaints
* View work status
* Manage chatbot datasets
* Analyze maintenance performance
* Track complaint resolutions

---

## 🎓 Students (Flutter App)

* Submit complaints
* Upload issue images
* Track complaint status
* Access AI chatbot
* Submit anonymous reports
* Provide ratings and feedback

---

## 👨‍🏫 Faculty (Flutter App)

* Manage student-related infrastructure issues
* Review complaints
* Access AI assistant
* Track maintenance requests
* Monitor infrastructure activities

---

## 👷 Workers (Flutter App)

* Receive assigned maintenance tasks
* View complaint details
* Access uploaded images
* Update work progress
* Mark tasks as completed

---

# ⚙️ AI Workflow

Complaint Submission

⬇

Image Upload

⬇

Gemini Vision Analysis

⬇

Object Detection

⬇

Issue Classification

⬇

Location Extraction

⬇

Worker Allocation

⬇

Task Assignment

⬇

Status Tracking

⬇

Resolution Monitoring

---

# 🛠️ Technology Stack

### Frontend

* Flutter
* Dart

### Backend

* Django
* Python

### Artificial Intelligence

* Google Gemini Vision
* Google Gemini AI
* NLP Similarity Matching
* Automated Complaint Classification

### Database

* MySQL

### Tools & Libraries

* REST APIs
* PIL
* Regex-based Location Extraction
* Git
* GitHub

---

# 📂 Repositories

## 📱 Flutter Mobile Application

The mobile application is designed for Students, Faculty Members, and Maintenance Workers.

Features:

* Complaint Submission
* Image Upload
* Complaint Tracking
* AI Chatbot
* Work Status Monitoring
* Profile Management

🔗 Repository:

https://github.com/mu-amz/campus_infrastructure_app

---

## ⚙️ Django Backend & AI Services

The backend powers complaint management, AI classification, worker allocation, chatbot services, image analysis, authentication, and administrative operations.

Features:

* Complaint Processing
* Gemini Vision Integration
* AI Complaint Classification
* Smart Worker Allocation
* Dataset Management
* Chatbot Services
* Admin Dashboard

🔗 Repository:

https://github.com/mu-amz/campus_infrastructure_backend

---

# 🌐 System Architecture

Students / Faculty

(Flutter App)

⬇

Submit Complaint + Image

⬇

AI Complaint Analyzer

(Gemini Vision + NLP)

⬇

Issue Classification

(Electrician / Plumber / Carpenter / Cleaning / Gardener)

⬇

Automatic Worker Allocation

⬇

Worker Mobile Application

⬇

Work Progress Updates

⬇

Admin Dashboard

⬇

Monitoring & Analytics

---

# 🎯 Project Objectives

* Automate campus maintenance operations
* Reduce complaint response time
* Improve infrastructure management
* Eliminate manual worker assignment
* Enhance communication between users and maintenance teams
* Provide intelligent support through conversational AI

---

# 🔮 Future Enhancements

* Predictive Maintenance using Machine Learning
* Real-Time Notifications
* QR-Based Asset Management
* Maintenance Analytics Dashboard
* Complaint Severity Prediction
* Voice-Based Complaint Submission
* IoT Device Integration

---

# 👨‍💻 Developer

**Muhammed Ameen**

Full Stack Developer | Flutter Developer | Django Developer | AI Enthusiast

GitHub: https://github.com/mu-amz

---

## ⭐ Support

If you found this project useful, consider giving the repositories a star.

