# StudyForge AI 🎓

StudyForge AI is a fully client-side, browser-based AI Study Assistant powered by **Google Gemini API** and **PDF.js**. It transforms raw study PDFs (lecture slides, notes, textbook chapters) into active recall study guides—including structured summaries, interactive quizzes, 3D flashcards, and predicted exam sheets—entirely in your browser with zero server uploads.

## 🔗 Live Demo
https://studyforge-labs.vercel.app/
......................................................
https://website-0-eng.github.io/StudyForge-AI/

---

## ✨ Features

* **Drag & Drop PDF Parser**: Text content is extracted locally in your browser using `PDF.js`—no files are uploaded to any external server.
* **4 Active Recall Learning Modes**:
  * **Summary**: Structured Markdown-rendered summaries with a one-click clipboard copy tool.
  * **Interactive Quizzes**: Generates exactly **10, 20, or 30 MCQs** with dynamic score tracking, progress indicators, immediate feedback on selection, and detailed explanation text.
  * **3D Flashcards**: Sleek 3D rotating cards (`rotateY` transform) supporting touch/click flips, enter/space hotkeys, and left/right arrow key navigation.
  * **Exam Prep**: An accordion panel showing predicted exam questions and expandable model answers.
* **Client-Side Session History**: Automatically saves generated study resources to `localStorage` so you can review past sessions instantly via the "Sessions" drawer.
* **Rate Limit Estimator**: Integrates a client-side tracking estimator mapping Google Gemini's Free Tier boundaries (**15 requests/min** and **1,000 requests/day**), visual progress bars, and warnings before hitting limits.
* **Privacy & Security First**: Stored API keys are sandboxed inside your local browser storage and requests travel directly to Google endpoints.
* **Responsive Dark Aesthetics**: Gorgeous dark theme layouts styled with modern frosted Glassmorphism and pulsing background glow loops.

---

## 🛠️ Getting Started (For Users)

To start generating active recall study guides:

1. **Get a Free Gemini API Key**:
   * Go to [Google AI Studio](https://aistudio.google.com/).
   * Sign in with your standard Gmail account.
   * Click **Get API Key** in the top-left menu.
   * Copy the generated key.
2. **Launch the App**:
   * Open `index.html` in any browser.
3. **Configure & Study**:
   * Click **API Key** in the top-right header, paste your key, and save.
   * Drag and drop your study PDF.
   * Select a mode, choose your quiz count (if active), and click **Generate Session**!

---

## 📄 License
This project is open-source. Feel free to clone, customize, and share!
