# [Michael Jackson Trivia Quiz]

Think you know the King of Pop? Test your Michael Jackson Knowledge!

## Overview

This program is a knowledge-based quiz about Michael Jackson, one of the most influential musicians and performers in music history. The quiz asked users six multiple-choice questions about Michael Jackson's music, albums, career, and performances. 

The user enters an answer for each question, and the program uses conditional statements to determine whether the answer is correct.
Users earn one point for everywhere correct answer. At the end of the quiz, the user's total score determines their final result.

Sample Questions and Responses

Question 1

Which Michael Jackson album is the best-selling album of all time?

Bad

Thriller

Dangerous

Off the Wall

Correct answer: 2 — Thriller

Question 2

Which Michael Jackson song is famous for its iconic music video featuring zombies and other horror elements?

Beat It

Billie Jean

Thriller

Smooth Criminal

Correct answer: 3 — Thriller

Question 3

Which Michael Jackson song focuses heavily on environmental issues and damage to the planet?

Earth Song

Rock With You

The Way You Make Me Feel

Remember the Time

Correct answer: 1 — Earth Song

Question 4

Which Michael Jackson album includes "Bad," "Smooth Criminal," and "Man in the Mirror"?

Dangerous

HIStory

Bad

Invincible

Correct answer: 3 — Bad

Question 5

What is the name of the famous dance move Michael Jackson became known for in which he appears to walk backward while facing forward?

The Robot

The Moonwalk

The Spin

The Glide

Correct answer: 2 — The Moonwalk

Question 6

Which group did Michael Jackson perform with before becoming a successful solo artist?

The Temptations

The Jackson 5

New Edition

The Supremes

Correct answer: 2 — The Jackson 5

Variables

name (str): stores the user's name so the program can personalize the quiz.

score (int): keeps track of how many questions the user answers correctly. One score variable works because all correct answers contribute to one final total.

answer (str): stores the user's answer to each question so it can be compared with the correct answer.

total_questions (int): stores the total number of questions in the quiz.

percentage (float): calculates the user's final percentage based on their score.

Conditional Logic Outline

Conditional statement 1 — Question 1

Related to the question asking which Michael Jackson album is the best-selling album of all time.

if the response is 2: display a message saying the answer is correct and increase score by 1.

else: display an incorrect message and tell the user that the correct answer is Thriller.

Conditional statement 2 — Question 2

Related to the question asking which song has the famous horror-themed music video.

if the response is 3: display a correct message and increase score by 1.

else: display an incorrect message and explain that the correct answer is Thriller.

Conditional statement 3 — Question 3

Related to the question about Michael Jackson's environmental song.

if the response is 1: display a correct message and increase score by 1.

else: display an incorrect message and explain that the correct answer is Earth Song.

Conditional statement 4 — Question 4

Related to the question asking which album contains "Bad," "Smooth Criminal," and "Man in the Mirror."

if the response is 3: display a correct message and increase score by 1.

else: display an incorrect message and explain that the correct answer is Bad.

Conditional statement 5 — Question 5

Related to the question asking about Michael Jackson's famous backward dance move.

if the response is 2: display a correct message and increase score by 1.

else: display an incorrect message and explain that the correct answer is the Moonwalk.

Conditional statement 6 — Question 6

Related to the question asking which group Michael Jackson performed with before his solo career.

if the response is 2: display a correct message and increase score by 1.

else: display an incorrect message and explain that the correct answer is the Jackson 5.

Conditional statement 7 — Final result

After all six questions, the program calculates the user's percentage and determines their final result.

if the percentage is 90% or higher: display "MJ Superfan!"

elif the percentage is 70% or higher: display "Dedicated MJ Fan!"

elif the percentage is 50% or higher: display "Casual MJ Fan!"

else: display "Time for an MJ Marathon!"

The final score and percentage are displayed to the user.

## How to Run
1. Clone this repo
2. Run `python3 main.py` or `python main.py`

## Demo Video
[DELETE AND REPLACE ME: link to your 5-minute explanation video]
