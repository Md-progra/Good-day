# Good-day
Just a simple to do list for personal use; if you want to use it, go ahead and do! 😁
This is a simple **React-based Todo List Application** that allows users to add, complete, and delete tasks. It also includes fun effects like confetti when all tasks are completed and a 24-hour time limit for task completion.

## Features
- Add new tasks
- Mark tasks as completed
- Delete tasks
- Confetti effect when all tasks are completed
- 24-hour time limit to complete tasks (otherwise tasks reset)
- Smooth scrolling and responsive UI

## Tech Stack
- **React** - Frontend framework
- **Tailwind CSS** (optional) - Styling
- **Lucide React** - Icons

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/todo-list-app.git
cd todo-list-app
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Start the Development Server
For Vite-based setup:
```sh
npm run dev
```
For Create React App setup:
```sh
npm start
```

## Folder Structure
```
/todo-list-app
  ├── /src
  │   ├── /components
  │   │   ├── TodoList.jsx  # Main Todo List Component
  │   ├── App.jsx           # Main App Entry Point
  │   ├── main.jsx          # React Root File
  │   ├── index.css         # Styles
  ├── /public
  ├── package.json
  ├── README.md
```

## Dependencies
- `react`
- `lucide-react`
- `tailwindcss` (optional)

## How It Works
1. Users can type a task into the input field and press "Add" to include it in the list.
2. Clicking on a task marks it as completed (strikethrough effect).
3. Clicking the trash icon deletes the task.
4. If all tasks are completed, confetti appears!
5. If tasks are not completed within 24 hours, they disappear as a "penalty."

## License
This project is open-source and available under the MIT License.

---
Happy coding! 🚀


