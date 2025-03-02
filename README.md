# Pothole Detection App 🕳️🚗

A Streamlit application for detecting and classifying road conditions, including potholes, cracks, and other obstacles.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Pothole Detection App is designed to help users analyze road conditions by uploading images and classifying various features such as potholes, cracks, lane markings, and more. The app provides a user-friendly interface and integrates with Firebase for user authentication and data storage.

## Features
- **User Authentication:** Secure login and sign-up system.
- **Project Management:** Create and manage multiple projects.
- **Image Upload & Analysis:** Upload images of roads to detect potholes and cracks.
- **Road Condition Classification:** Classify roads as Good, Bad, or Unclear.
- **Feature Detection:** Identify lane markings, shadows, obstacles, and more.
- **Data Storage:** Store classification results in a Firebase database.
- **Interactive UI:** Easy-to-use interface with visual feedback.

## Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.8 or higher
- Streamlit
- Firebase Admin SDK
- Pillow (PIL)
- Google Cloud Firestore

You can install the necessary packages using pip:
```bash
pip install streamlit firebase-admin pillow
