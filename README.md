# ThinkMate-StudyBuddy

[![Visit Site](https://img.shields.io/badge/Live%20Demo-Access-green?style=flat-square)](https://neo-cyphers.github.io/ThinkMate-StudyBuddy/ThinkMate_code/app.html)

**ThinkMate-StudyBuddy** is a versatile web-based learning platform designed to empower students and lifelong learners with personalized study tools. It offers a suite of features including customizable study sessions, interactive quizzes, flashcard creation, and a detailed dashboard to track progress. The application integrates advanced AI technologies to provide an adaptive learning experience, supporting a variety of topics and learning preferences.

## Interface Preview

<img width="1595" height="761" alt="image" src="https://github.com/user-attachments/assets/75c1e232-fd69-4567-8f79-a080c5201172" />


##  Table of Contents

- Features 
- Installation 
- Usage 
- Technologies Used 
- Project Structure
- 
##  Features

### Personalization Center (`settings.html`)

- Customize themes: Light, Dark, Blue, Green
- Choose AI personality: Professor, Mentor, Researcher, Coach
- Set learning preferences: visual explanations, real-world examples, technical terminology
- Select difficulty: Beginner to Expert
- Save/reset preferences

### Study Sessions (`app.html`)

- Upload study material (PDF/TXT)
- Select topics: General Knowledge, AI, History, Science, Math
- AI buddy assistance with voice input (speech-to-text)
- Save, download, and manage sessions
- Vector DB status tracking (e.g., 0 chunks)

### Quizzes (`quiz.html`)

- Custom quiz creation by topic, number, and difficulty
- Real-time score tracking and result review
- API key status refresh and fallback contact support
- Loading feedback: “Generating your custom quiz…”

### Flashcards (`flashcards.html`)

- Create decks by subject, number, difficulty
- Auto-flip, shuffle, and save progress
- Mark as “I Knew This” or “Needs Review”
- Metrics: Time spent, known/unknown cards
- Feedback: “Building your deck…”

### Dashboard (`dashboard.html`)

- Progress metrics: Overall, Concepts, History
- Manage notes, bookmarks, and materials
- View recent activity and continue sessions
- “Ask AI Buddy” button for real-time help

###  Speech-to-Text Support

- Voice input for hands-free topic selection and Q&A
- Integrated across study sessions

### Integration of 3+ AI Technologies

- **NLP:** For AI explanations and learning conversations  
- **Vision AI:** Extracts content/images from uploaded PDFs  
- **Speech Recognition:** Enables voice commands

### Language, AI & Data Integration

- Language AI for conversation
- Vision & speech AI for interaction
- Vector DB for persistent material storage

### User-Friendly UI

- Unified navigation bar across all pages
- Drag-and-drop interface, visual timers, and auto-progress tracking

### Persistent Storage & Fallbacks

- Saves user settings, decks, scores, and study history
- Graceful error handling and status prompts
- Secure API key management


## Installation

To run ThinkMate-StudyBuddy locally, follow these steps:

1. **Clone the Repository**:

        git clone https://github.com/neo-cyphers/ThinkMate-StudyBuddy.gitcd ThinkMate-StudyBuddy
2. **Set Up Environment**:

    - Ensure you have a modern browser (e.g., Chrome, Firefox) installed.
    - Configure API keys if required (contact system administrator as noted in app.html and quiz.html).
3. **Run the Application**:

    - Install a local server (e.g., Node.js with http-server):

            npm install -g http-server
    - Start the server from the ThinkMate\_code directory:

            cd ThinkMate_codehttp-server
    - Open http://localhost:8080 in your browser to access app.html.

## Usage

- Start at app.html or navigate via the navigation bar to settings.html, quiz.html, flashcards.html, or dashboard.html.
- Use the form below to access the live version:

    Access ThinkMate-StudyBuddy

## Technologies Used

- **HTML5**: Core structure of the application pages.
- **CSS3**: Responsive and visually appealing interface.
- **JavaScript**: Dynamic interactions.
- **Vector Database**: Stores study material chunks.
- **API Integration**: Secure API key management.
- **Speech-to-Text API**: Voice input support.
- **AI APIs**: NLP, vision AI, speech recognition.

## Project Structure

    ThinkMate-StudyBuddy/
    ├── ThinkMate_code/│ 
            ├── app.html # Main study session page│ 
            ├── dashboard.html # Study progress and resource management page│ 
            ├── flashcards.html # Flashcard deck creation and study page│ 
            ├── quiz.html # Quiz creation and interaction page│ 
            ├── settings.html # Personalization settings page
    ├── README.md # Project documentation
