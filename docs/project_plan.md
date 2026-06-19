# Project Plan: Spaced Repetition Vocabulary Tracker

## 1. Project Overview
This project is a vocabulary memorization application designed for new language learners.
The application uses a spaced repeition system to schedule vocabulary reviews based on user performance.

Users can add vocabulary words, review due words, and mark each word as correct or incorrect.
Based on the result, the word moves to a higher or lower review stage.

## 2. Problem Statement
As a new language learner, I found that consistently review vocabulary at the correct time is difficult.
Manually tracking which words should be reviwed daily, every 3 days, every 7 days, or monthly was time consuming and overwhalmed.

Thus, making this application solves the problem by autometically calculating the next review date for each word.

## 3. Goals

- Allow users to add, edit, and delete vocabulary words.
- Organize words by review stage.
- Autometically calculate next review dates.
- Move words forward when memorized.
- Move words backward when answered incorrectly.
- Show words due for review today.
- Provide notification or reminder support.

## 4. Target Users

- Any new language learners.
- Self-study users who want structured vocabulary review.

## 5. Milestones

### Milestone 1: Core Database and Review Logic
- Design database schema
- Implement vocab insert/update/delete
- Implement review stage transition logic

### Milestone 2: Basic UI
- Build Streamlit UI 
- Add vocab form
- Daily review page
- Review history page

### Milestone 3: Notification Feature
- Add due-date reminder (email)
- Show number of due words
- Optional desktop notification

### Milestone 4: Teesting and Documentation
- Add unit tests
- Write README
- Add screenshots
- Finalize GitHub repo
