# 🎓 One-Stop Career & Education Advisor

## Overview

The "One-Stop Career & Education Advisor" is a web-based platform designed to address the critical lack of awareness among students and parents regarding the importance of graduation, available career opportunities, and how to choose appropriate subject streams. This platform acts as a personalized career and education advisor, guiding students through key academic and career decisions after completing Class 10 or 12.

It aims to improve enrollment in government degree colleges, reduce dropouts, and empower students with reliable, localized career guidance.

## 🛠️ Features

* **Aptitude & Interest-Based Course Suggestion**
    * Short quizzes assess student interests, strengths, and personality traits.
    * Based on results, the app suggests suitable streams and subjects (Arts, Science, Commerce, Vocational).
    * Students can compare career paths based on different combinations.

* **Course-to-Career Path Mapping**
    * Detailed visual charts illustrate what each degree (B.A., B.Sc., B.Com., BBA, etc.) offers.
    * Shows industries or sectors each course leads to.
    * Highlights relevant government exams, private jobs, entrepreneurial options, or higher education available after each stream.

* **Nearby Government Colleges Directory**
    * **Live Google Maps Integration:** Uses Google Maps API to find government colleges within a 40km radius of a user-entered pincode or city in India.
    * **Distance & Rating Display:** Lists colleges in increasing order of distance, along with their Google Maps ratings.
    * **Scrollable Interface:** All college information is presented on a scrollable element on a single page.

* **Timeline Tracker**
    * Provides a notification system for important dates: admission windows, scholarship application deadlines, college entrance tests, or counseling schedules.

* **Customization and Personalization**
    * User profiles track age, gender, class, and academic interests.
    * An AI-driven recommendation engine suggests:
        * Courses to apply for.
        * Colleges nearby.
        * Career paths aligned with aptitude.
        * Study materials tailored to subject choice.

## 🎯 Problem Statement

Many students and parents face confusion regarding post-10th and post-12th academic and career choices, leading to:

* Uninformed decisions about subject streams (Arts, Science, Commerce).
* Lack of knowledge about degree programs in nearby government colleges.
* Uncertainty about job opportunities or higher studies after specific courses.
* Questioning the value of graduation versus short-term skill courses.

This platform provides a comprehensive solution by offering personalized guidance, clarifying career paths, and simplifying college discovery.

## 🧩 Tech Stack

* **Frontend:** React
* **Database:** MongoDB
* **APIs:** Google Maps API (Geocoding API, Places API for Web)

## 📈 Workflow / User Journey

1.  **Welcome Screen:** User enters their name (optional) and clicks "Get Started."
2.  **Dashboard:** User lands on a personalized dashboard. If the quiz hasn't been taken, they are prompted to start it.
3.  **Aptitude Quiz:** User answers a series of questions to assess their interests and strengths.
4.  **Quiz Results:** The quiz provides a recommended stream (e.g., Science (PCM), Commerce).
5.  **Explore Career Paths:** User can navigate to the "Career Paths" tab to explore an interactive tree of career options, with detailed descriptions for each path.
6.  **Find Nearby Colleges:** User enters a pincode or city in India. The platform uses Google Maps to find and list government colleges within 40km, sorted by distance, along with their Google Maps rating.
7.  **Timeline Tracking:** User can view important admission and scholarship dates in the "Timeline Tracker" section.

## 🌐 Future Enhancements

* Integration of AI-driven recommendation engine for personalized course, college, and career suggestions based on user profile and quiz results.
* Real-time analytics for monitoring usage and tracking successful transitions to college enrollment.
* Offline features for areas with poor internet connectivity.
* More detailed information on college facilities, cut-offs, and eligibility criteria.
* Integration of open-source e-books and skill development materials.

## 📜 License

Open-source (MIT License) — contributions welcome!