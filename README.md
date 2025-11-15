<h1>React To-Do App</h1>  
A simple and elegant To-Do List application built using React.js.
This app allows users to add, view, and delete tasks with a clean and responsive UI.

<h2> Features</h2>  
.Add new tasks
.Delete tasks
.Fully responsive UI
.Clean and minimal design
.Built using React Hooks (useState)
.Real-time updates without page refresh

<h2>Tech Stack</h2>
.React.js (Vite)
.JavaScript (ES6+)
.CSS3
.HTML5

<h2>Folder Structure</h2>
react-todo-app/
 src
   - App.jsx
   - index.css
   - main.jsx
 public/
 package.json
 vite.config.js
 README.md

<h2>How It Works</h2>

<h4>1️.Adding a Task</h4>
Type a task in the input box
Click "Add Task"
The task instantly appears below

<h4>2️.Deleting a Task</h4>
Each task has a ❌ button
Clicking it removes the task from the list

<h4>3️.State Management</h4>

I used:
const [tasks, setTasks] = useState([]);
const [newTask, setNewTask] = useState("");

React re-renders automatically when the state updates.

<h2> Code Overview</h2>
Main Logic (App.jsx)
Handles:
.adding tasks
.deleting tasks
.managing state
.Entry Point (main.jsx)
.Renders your <App /> inside #root.

<h2>What I Learned</h2>

.How to create and manage React components
.Using the useState hook
.Handling real-time UI updates
.Building interactive apps with React
.Styling components using CSS
.File and folder structure for React (Vite)

