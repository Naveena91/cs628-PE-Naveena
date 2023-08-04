Input:

   The ToDo list app allows users to input their tasks through a text input field. Users can type a description of the task they want to add to the ToDo list.I have created two files ToDoList.js and ToDoTask.js

Process:

   The app utilizes React with the useState hook to manage the state of the ToDo list. When the user enters a task description and clicks the "Add Task" button, the app captures the input value using an event handler. It then validates the input to ensure it is not empty or whitespace-only. If the input is valid, the app updates the list of tasks using the setTasks function, which maintains the state of the ToDo list.For the "Delete" functionality, each ToDo task is rendered as a separate component. When the user clicks the "Delete" button associated with a particular task, the app uses the index of that task to remove it from the list by updating the state.

Output:

   The output of the app is the dynamic rendering of the ToDo list. As the user adds tasks, the list grows dynamically, and each task is displayed with a "Delete" button. When the user clicks the "Delete" button for a specific task, that task is removed from the list, and the list updates instantly on the screen