<div align="center">

<br/>

# 🎓 InnovaLearn-AI

### *Where Innovation Meets Education*

> An AI-driven educational platform that transforms how students learn and educators teach.

<br/>

[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io)
[![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-777BB3?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<br/>

[![Arabic · English](https://img.shields.io/badge/Language-Arabic%20%7C%20English-38d9a9?style=flat-square)](.)
[![UQU · 2026](https://img.shields.io/badge/UQU-2026-f87171?style=flat-square)](.)
[![Graduation Project](https://img.shields.io/badge/Graduation%20Project-Software%20Engineering-a78bfa?style=flat-square)](.)

<br/>


<br/>

</div>

---

## 📌 About the Project

**InnovaLearn-AI** is derived from *"Innovation"* and *"Learn"* — an AI-driven educational platform built to bridge gaps in modern e-learning, especially for Arabic-speaking students and educators. It integrates real-time transcription, multilingual translation, intelligent chatbots, OCR, quiz generation, and learning analytics in one unified system.

Developed as a **Bachelor of Software Engineering** graduation project at **Umm Al-Qura University**, College of Computing, supervised by **Dr. Ahmed Alharthi**, 2026.

---

## 🗺️ System Overview

```
┌─────────────────────────────────────────────────┐
│                  USER ROLES                     │
│                                                 │
│      👨‍🎓 Student          👩‍🏫 Educator            │
│    Learn & quizzes     Teach & manage           │
└──────────────┬──────────────┬───────────────────┘
               └──────┬───────┘
                      ▼
┌─────────────────────────────────────────────────┐
│           InnovaLearn-AI Platform               │
│   Angular + Laravel · JWT · HTTPS · REST API   │
└─────────────────────────────────────────────────┘
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
  ┌──────────┐  ┌──────────┐  ┌──────────┐
  │Frontend  │  │ Backend  │  │AI Service│
  │ Angular  │  │ Laravel  │  │OpenAI/HF │
  └──────────┘  └──────────┘  └──────────┘
                      │
                      ▼
        ┌─────────────────────────┐
        │      MySQL Database     │
        │ Users · Courses · Tests │
        └─────────────────────────┘
```

---

## ✨ Features

| ID | Feature | Description |
|---|---|---|
| `F-1` | 👤 **User profile** | Register, login, update profile with role-based access |
| `F-2` | 🎙️ **Lecture transcription** | Speech-to-text for live and recorded lectures |
| `F-3` | 🌐 **Lecture translation** | Arabic ↔ English translation for all lecture content |
| `F-4` | 🔤 **Multilingual UI** | Full RTL (Arabic) and LTR (English) interface |
| `F-5` | 📝 **Quiz system** | AI-generates MCQ, True/False, and essay questions |
| `F-6` | 📊 **Learning analytics** | Tracks performance and generates progress reports |
| `F-7` | 🤖 **AI chatbot** | Answers questions, summarizes lectures, generates slides |
| `F-8` | 🔍 **OCR** | Extracts text from images, exports to `.txt` |

---

## 🛠️ Technologies Used

### Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Backend
![PHP](https://img.shields.io/badge/PHP-777BB3?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### Database
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)

### Development Tools
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=flat-square&logo=trello&logoColor=white)
![Teams](https://img.shields.io/badge/Teams-6264A7?style=flat-square&logo=microsoftteams&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat-square&logo=canva&logoColor=white)
![Word](https://img.shields.io/badge/Word-2B579A?style=flat-square&logo=microsoftword&logoColor=white)

---

## 🚶 User Flows

### 👨‍🎓 Student Journey
```
Register → Log in → Enroll in course → View lecture
    → Transcription → Translation → AI chatbot
    → Take quiz → View analytics
```

### 👩‍🏫 Educator Journey
```
Register → Create course → Upload lecture
    → Generate quiz → View reports → AI chatbot
```

---

## 🔮 Future Work

- 🔗 **LMS integration** — Blackboard, Moodle, Google Classroom
- 📱 **Mobile app** — Android and iOS with offline caching
- 🗣️ **Arabic dialect processing** — Saudi and regional Arabic support
- 🧠 **Adaptive recommendations** — personalized study plans
- 📋 **Educator templates** — aligned with Bloom's taxonomy
- 🎙️ **Live lecture AI** — real-time in-session support
- 🔊 **Voice tutoring** — spoken chatbot responses

---

## 👥 Team

| Name | Student ID |
|---|---|
| Eyad Maccawy | 444003279 |
| Enad Alharbi | 444002681 |
| Jawad Alotaibi | 444003256 |
| Turki Alotaibi | 444002785 |
| Abdulrahman Alluhaiby | 444004709 |

**Supervised by:** Dr. Ahmed Alharthi  
**Institution:** College of Computing, Umm Al-Qura University · 2026

---

<div align="center">

*InnovaLearn-AI — Submitted for the partial fulfillment of the Bachelor of Software Engineering degree*

</div>
