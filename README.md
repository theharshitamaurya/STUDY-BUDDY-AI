
# StudyBuddyAI – AI-Powered Learning Assistant

StudyBuddyAI is an intelligent study companion that makes learning smarter, faster, and more personalized. It helps students generate **fill-in-the-blank exercises** and **multiple-choice quizzes** on any topic, making test preparation interactive, engaging, and effective.

---

## Table of Contents

* [Project Overview](#project-overview)
* [Setup & Installation](#setup--installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Configuration & Environment](#configuration--environment)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Contacts](#contacts)
* [License](#license)

---

## Project Overview

StudyBuddyAI transforms study materials into interactive practice tools. With simple inputs—like notes, textbook content, or chosen topics—students can:

* Generate **fill-in-the-blank questions** for quick recall practice
* Create **multiple-choice quizzes (MCQs)** to simulate test environments
* Reinforce learning through repetition and active engagement
* Make revision more effective by focusing on key concepts

This assistant reduces manual effort in creating practice material, so learners can spend more time mastering concepts.

---

## Setup & Installation

### Prerequisites

* Python 3.9+
* Streamlit (for frontend)
* Access to LLM API (OpenAI / Groq or custom model)

### Installation Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-org/studybuddyai.git
   cd studybuddyai
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -e .
   ```

4. Run the application:

   ```bash
   streamlit run application.py
   ```

---

## Usage

* Launch the app in your browser (`http://localhost:8501` by default).
* Select a topic or upload notes/text.
* Choose question type (**Fill in the Blanks** or **MCQs**).
* Generate practice questions instantly.
* Use the quizzes for test prep or revision sessions.

---

## Project Structure

```
src/
├── common/
│   ├── logger.py
│   ├── custom_exception.py
├── config/
│   ├── settings.py
├── generators/
│   ├── question_generator.py
├── llm/
│   ├── ai_client.py
├── templates/
│   ├── mcq_template.py
│   ├── fill_blank_template.py
├── utils/
│   ├── helpers.py
application.py
requirements.txt
setup.py
.env
```

---

## Configuration & Environment

* Add your API keys in `.env` (for LLM access).
* Adjust generation parameters (difficulty, number of questions, etc.) in `config/settings.py`.
* Templates for different question styles can be customized in `templates/`.

---

## Roadmap

* Add **true/false** and **short-answer** question generation
* Support for **subject-specific question styles** (math, science, history, etc.)
* Personalized practice sets based on student progress
* Export quizzes to **PDF/Google Forms**
* Mobile app version for on-the-go studying
* Collaborative study groups & leaderboard features

---

## Contributing

We welcome contributions!

* Open issues for new ideas or bugs
* Submit pull requests with detailed explanations
* Follow repository coding standards and logging practices

---

## Contacts

* GitHub Repository: [StudyBuddyAI](https://github.com/theharshitamaurya/studybuddyai)
* Maintainer: \[Harshita Maurya / harshita20maurya@gmail.com]

---

## License

This project is open-source and free for educational use.
See [LICENSE](LICENSE) for details.

---

*Last updated: September 22, 2025*


