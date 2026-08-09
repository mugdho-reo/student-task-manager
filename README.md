const taskInput = document.getElementById("taskInput");
const addTaskBtn = document.getElementById("addTaskBtn");
const taskList = document.getElementById("taskList");

let tasks = [];

function renderTasks() {
    taskList.innerHTML = "";
}

addTaskBtn.addEventListener("click", () => {
    console.log("Add task button clicked");
});

renderTasks();