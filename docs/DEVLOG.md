# 🚀 AshaSathi AI - Development Log

This document records the day-by-day engineering journey of building AshaSathi AI.

---

# Day 1 - Project Foundation

**Date:** 19 July 2026

## 🎯 Goal
Set up the development environment and establish the project foundation.

## ✅ Completed

- Created the GitHub repository.
- Added the initial README and MIT License.
- Created the Android Studio project using Kotlin and Jetpack Compose.
- Successfully completed the first Gradle build.
- Verified the app runs on the emulator.
- Designed the initial project architecture.
- Created packages:
    - ai
    - data
        - local
        - model
        - remote
        - repository
    - ui
        - components
        - navigation
        - screens
        - theme
    - viewmodel
    - utils
- Initialized Git locally.
- Connected the local project to the GitHub repository.
- Learned how Git differs from GitHub.
- Resolved the first Git merge conflict (.gitignore).
- Successfully pushed the Android project to GitHub.

---

## 📚 What I Learned

- Git vs GitHub
- Why project architecture matters
- Repository pattern
- Local vs Remote data
- MVVM folder organization
- MIT License
- Basic Git workflow:
    - git add
    - git commit
    - git pull
    - git push

---

## ⚠ Challenges

- Initial Gradle sync took a long time.
- Git merge conflict occurred because both local and remote repositories contained a `.gitignore` file.

---

## 💡 Key Decisions

- Project Name: **AshaSathi AI**
- Architecture: MVVM
- Language: Kotlin
- UI: Jetpack Compose
- Minimum SDK: API 26
- AI package kept separate for future Gemini integration.

---

## 🚀 Next Goal

Design the Dashboard screen and begin building the first user interface.