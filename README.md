Overview

This is a simple Android quiz application designed to test users about their knowledge on water conservation and water usage. The app presents multiple-choice questions related to everyday water consumption and calculates a score based on the user’s answers.
The application is built using Java and standard Android UI components.

Features

Multiple-choice quiz format (4 options per question)
Tracks total questions and current score
Button-based answer selection with visual feedback
Sequential question navigation
Centralized question and answer storage
App Structure
MainActivity.java
Handles UI interactions
Manages question navigation, answer selection, and scoring
Implements View.OnClickListener for button handling

QnA.java Stores:

Questions
Answer choices
Correct answers

How It Works: 

The app displays a question with four possible answers.
The user selects an answer (highlighted visually).

On submission:

The answer is checked against the correct one.
The score is updated.
The next question is loaded.
The quiz ends once all questions are completed.

Technologies Used: 

Android SDK
Android Studio

Purpose: This project was created as an educational application to create awareness of water conservation practices and showcase the impact of taking the first steps towards water conservation. 
