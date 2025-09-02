# 📚 StudyBuddy – Your Smart Academic Companion  

StudyBuddy is a modern, responsive, and feature-rich web application designed to make learning and academic organization easier for students. It caters to students across multiple courses (11th–12th, BCA, BBA, B.Tech, M.Tech, MBA, Law) by offering personalized dashboards, study materials, quizzes, previous year papers, and a fully functional timetable planner with alarms and notes.  

---

## 🚀 Features  

- 🎨 **Modern UI/UX** – Clean, animated, and responsive design with dropdown menus and course-specific themes.  
- 📂 **Modular Structure** – Every section (Dashboard, Timetable, Notes, Quizzes, Papers) is built as a separate file for easy maintenance and scalability.  
- 🗂 **Course + Year Organization** – Content is neatly divided according to course and academic year.  
- 📝 **Notes Section** – Upload, view, and organize study notes.  
- 🕒 **Timetable Planner with Alarms** – Add/edit tasks, set reminders, and keep your day structured.  
- ❓ **Interactive Quizzes** – Test your knowledge with subject-based quizzes.  
- 📑 **Previous Year Papers** – Easy access to past exam papers for practice.  
- 🎭 **Custom Themes** – UI dynamically adapts based on the chosen course/stream.  

---

## 📂 Project Structure  

```bash
StudyBuddy/
│
├── index.html            # Entry point – homepage with navigation
├── dashboard.html        # Personalized student dashboard
├── timetable.html        # Timetable planner + alarms
├── notes.html            # Notes management
├── quizzes.html          # Quizzes by subject
├── papers.html           # Previous year papers
│
├── css/
│   ├── style.css         # Global styles
│   ├── dashboard.css     # Dashboard-specific styles
│   ├── timetable.css     # Timetable-specific styles
│   └── themes.css        # Course-based theming
│
├── js/
│   ├── main.js           # Core scripts
│   ├── timetable.js      # Logic for timetable + alarms
│   ├── notes.js          # Notes-related functionality
│   ├── quizzes.js        # Quiz logic
│   └── papers.js         # Previous year paper handling
│
├── assets/
│   ├── images/           # Icons, backgrounds, logos
│   └── data/             # JSON/CSV for quizzes, papers, etc.
│
└── README.md             # Project documentation

🛠️ Technologies Used

Frontend: HTML5, CSS3 (with Tailwind for responsiveness), JavaScript (Vanilla + minor libraries if needed)

Styling: Modern UI principles, animations, grid layouts, rounded corners, soft shadows

Organization Tools: Timetable planner, reminder system, task management

Version Control: Git + GitHub


🎯 Usage

Dashboard: Access all modules from a single place with dropdown menus.

Timetable: Add/edit/delete tasks, set alarms for reminders.

Notes: Organize study material by subject and course.

Quizzes: Test yourself with interactive MCQs.

Papers: Browse and practice previous year exam papers.


🌱 Future Enhancements

🔐 User authentication & login system

☁️ Cloud storage for notes and timetable

📊 Performance analytics & progress tracker

📱 Mobile-first PWA (Progressive Web App) support


🤝 Contributing

Contributions are welcome! To contribute:

Fork the repository

Create a new branch (feature/your-feature-name)

Commit your changes

Push to your fork and open a Pull Request
