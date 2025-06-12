# To Do List

## What I learned 
This is my third project with Mimo.

It has helped me to learn the following:
- Grouping data in lists, changing that data within the list and updating the data in the list
- Looping over lists and deciding with lists
- Finding extreme data
- Sorting data
- Summing data
- Joining lists
- Counting Elements

## How this works
First the to do list is defined with todo_list = []
This allows for a list to be created, and added to later.

We start with a while loop as some of the functions will require this.
The program begins by checking the to do list for tasks and if it is empty it conveys that it is empty to the user.

Next the else statement runs the objective here is to get the program to display the number of the task alongside the task name. Therefore we must define the index as 1 and use a for / in statement on the task and to do list. Then an f string is used to correctly define where the index and task must be shown and once completed it addsone to the next index and task.

Now we come to the options, wherby we show 3 options in total, 1. Add Task, 2. Remove Task, and 3. Quit.
The choice must then be givn to the user. It is defined as choice = input("Enter your choice (1, 2,or 3): ")
Next we have the meat of the program, the if statement. It is here that I define what happens when the user presses 1, 2, or 3.

For choice 1 we allow the user to add to the list. The computer asks the user to enter the task by assigning an input to new_task. For the task to be added we use an append which adds the input to the list alongside confirmation from the pc explaining it has been added successfully.
Choice 2 is an elif statement which allows the user to remove a task. Here we define if the list is greater than 0 it is allowed to remove an item from the list. This uses the pop function which removes the last itemfrom the list.
Finally choice 3 quits the program utilising a "quitting" notificaiton and then break to leave the program.

## Screenshots of my code
<img width="955" alt="todo3" src="https://github.com/user-attachments/assets/e19c71dc-adb2-46cd-9afb-abb40942a847" />
<img width="958" alt="todo4" src="https://github.com/user-attachments/assets/d35007ba-6882-4d74-b19e-b1964464084f" />

### Back to Main Page


