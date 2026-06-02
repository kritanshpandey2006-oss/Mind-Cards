# 🧠 Mind Cards

Mind Cards is a lightweight and interactive flashcard learning application that helps users create, manage, and review study cards directly in their browser. The application uses **LocalStorage** for persistent data storage and **CSS 3D Transforms** to provide an engaging card-flipping experience.

## 🚀 Features

* ➕ Create custom flashcards
* 🔄 Interactive 3D card flip animation
* ✏️ Edit existing flashcards
* 🗑️ Delete individual flashcards
* 📦 Export flashcards as JSON files
* 📥 Import flashcards from JSON files
* 💾 Automatic data persistence using LocalStorage
* 📱 Responsive design for desktop and mobile devices
* 🎨 Modern and clean user interface
* 🔍 Preserves spaces and line breaks in questions and answers

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* LocalStorage API
* CSS 3D Transforms
* FileReader API
* Blob API

## 📂 Project Structure

```text
Mind-Cards/
│
├── index.html      # Main application structure
├── styles.css      # Styling and animations
├── script.js       # Application logic
└── README.md       # Project documentation
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mind-cards.git
```

### 2. Open the Project Folder

```bash
cd mind-cards
```

### 3. Run the Application

Simply open the `index.html` file in your preferred web browser.

No additional installation or dependencies are required.

## 📖 How It Works

### Creating a Flashcard

1. Click the **New Card** button.
2. Enter a question and answer.
3. Click **Save Card**.
4. The card is automatically stored in LocalStorage.

### Reviewing Flashcards

* Click on any flashcard to flip it.
* The front side displays the question.
* The back side displays the answer.

### Managing Flashcards

* **Edit:** Modify existing flashcards.
* **Delete:** Remove unwanted flashcards.
* **Clear All:** Delete all stored flashcards.

### Import & Export

* Export your flashcards as a JSON file for backup.
* Import previously exported flashcards to restore your collection.

## 🧠 Key Concepts Demonstrated

* DOM Manipulation
* Event Handling
* LocalStorage Management
* Dynamic UI Rendering
* CSS 3D Transformations
* File Upload & Download Handling
* JSON Serialization & Parsing
* Responsive Web Design

## 🎯 Learning Objectives

This project demonstrates how to:

* Store and retrieve data using LocalStorage.
* Build CRUD (Create, Read, Update, Delete) functionality.
* Create interactive user interfaces with JavaScript.
* Implement import/export functionality.
* Design responsive layouts using CSS Grid.
* Build smooth animations using CSS 3D transforms.

## 📸 Application Workflow

```text
Create Card
      ↓
Save to LocalStorage
      ↓
Render Flashcard Grid
      ↓
Flip Card to Study
      ↓
Edit / Delete / Export
```

## 🔮 Future Enhancements

* Categories and tags for flashcards
* Search and filter functionality
* Study mode with score tracking
* Dark/Light theme toggle
* Spaced repetition learning algorithm
* Cloud synchronization
* Progress analytics dashboard

## 👨‍💻 Author

**Kritansh Pandey**

B.Tech (Computer Science & Engineering)
IIMT University, Greater Noida

## 📄 License

This project is created for educational and learning purposes. Feel free to modify and use it for personal projects.
