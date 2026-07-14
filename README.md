# MedTerm Master

MedTerm Master is an interactive medical terminology study platform designed for HOSA competitors, health-science students, and anyone trying to learn medical vocabulary/terminology.

The project combines quizzes, explanations, flashcards, medical word breakdowns, progress tracking, account syncing, and verified usage analytics in one responsive web application.
## Live Website

https://shashankpadala43267.github.io/medterm-master/

## Project Purpose

Medical terminology can be difficult because many students memorize complete definitions without understanding how medical words are built.

MedTerm Master was created to make studying more active and understandable. In addition to testing users, the platform helps them learn from mistakes, review difficult concepts, break down medical words, and track improvement over time.

## Main Features

- 673 medical terminology questions
- 14 study categories
- Timed test mode
- Study mode with explanations
- Multiple quiz-length options
- Shuffled questions and answer choices
- Missed-question review
- Retry-missed-questions mode
- Searchable study guide
- Flashcard mode
- Saved questions and bookmarks
- Progress dashboard
- Quiz history
- Study streak tracking
- Achievement system
- Light and dark themes
- Full-screen mode
- Medical term breakdown tool
- Google Sign-In
- Cross-device progress syncing
- Verified-user tracking
- Private administrator analytics
- Responsive design for desktop and mobile devices

## Explain Term Feature

The Explain Term feature helps users understand how medical words are formed.

Example:

### Cardiomyopathy

- `cardi/o` means heart
- `my/o` means muscle
- `-pathy` means disease or disorder

Overall meaning: disease of the heart muscle.

This feature encourages users to recognize prefixes, roots, combining forms, and suffixes instead of memorizing every term as a separate word.

## Quiz System

Users can choose:

- A medical category
- The number of questions
- Test mode or study mode
- A timer setting

During a quiz, the platform tracks score, progress, remaining questions, and time. After finishing, users can review missed questions, study explanations, retry incorrect questions, or begin a new quiz.

## Account and Progress System

MedTerm Master uses Google Sign-In through Firebase Authentication.

Signed-in users can save and sync:

- Best score
- Number of completed quizzes
- Total questions answered
- Correct-answer total
- Study streak
- Recent quiz history
- Saved questions
- Achievement progress

When a user signs in with the same Google account on another supported browser or device, their saved progress can load from the cloud.

## Verified-User Tracking

The platform does not count page views as users.

A user is counted only after:

1. Signing in with Google
2. Completing at least one quiz

The same Google account can return many times and complete many quizzes while still counting as one authenticated active user.

The private administrator analytics section tracks:

- Authenticated users who completed at least one quiz
- Total quizzes completed
- Total questions answered

This provides a more meaningful measure of usage than page views or repeat visits.

## Privacy and Security

- User emails are not displayed publicly
- Each user can access only their own saved progress
- Aggregate analytics are visible only to the authorized administrator
- Firestore security rules restrict access to user records
- The platform does not collect medical records or health information
- MedTerm Master is intended only for educational use

## Technologies Used

- HTML
- CSS
- JavaScript
- Firebase Authentication
- Cloud Firestore
- GitHub Pages
- Browser local storage
- Responsive web design
- Accessibility-focused interface design

## Development History

MedTerm Master went through 7 major development versions.

### Version 1: Original Quiz Platform

Created the first working medical terminology quiz with a basic question-and-answer system.

### Version 2: Expanded Question Bank and Categories

Expanded the platform to 673 questions across 14 medical terminology categories.

### Version 3: Study and Review Tools

Added explanations, study mode, missed-question review, retry mode, and multiple quiz lengths.

### Version 4: Flashcards and Progress Features

Added flashcards, bookmarks, study-guide search, quiz history, streaks, achievements, and local progress tracking.

### Version 5: Medical Term Breakdown

Added the Explain Term feature, allowing users to break medical words into prefixes, roots, combining forms, and suffixes.

### Version 6: Interface and Accessibility Improvements

Improved answer shuffling, keyboard behavior, mobile responsiveness, focus states, light mode, and accessibility support.

### Version 7: Authentication, Analytics, and Cloud Sync

Added Google Sign-In, verified-user tracking, private administrator analytics, Firestore storage, and cross-device account progress syncing.

## Current Impact

- Authenticated active users: To be updated
- Quizzes completed: To be updated
- Questions answered: To be updated

## What I Learned

Through this project, I learned how to:

- Build and organize a large JavaScript application
- Manage a database of hundreds of quiz questions
- Design a responsive and accessible user interface
- Debug keyboard, quiz, and account behavior
- Work with Firebase Authentication
- Store and synchronize user progress with Firestore
- Write security rules for user data
- Track meaningful product usage
- Deploy and update a public website with GitHub Pages
- Improve a project through repeated testing and revision

## Future Improvements

- Expand the medical word-part dictionary
- Add more verified medical terminology questions
- Add category-specific performance reports
- Improve accessibility testing
- Gather structured feedback from HOSA students
- Add optional teacher or chapter-level study reports
- Continue improving mobile usability

## Project Value

MedTerm Master combines health science, education, and computer science. It was built to solve a real study problem and was improved through multiple development versions rather than being treated as a one-time assignment.

The project demonstrates software design, database organization, user authentication, cloud data storage, analytics, responsive interface design, debugging, product iteration, and educational tool development.

## Disclaimer

MedTerm Master is an educational study tool. It does not provide medical advice, diagnosis, or treatment.

## Creator

Created by Shashank Padala as a student project combining interests in medicine, health science, HOSA, and computer science.
