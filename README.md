# React-task-tracker
This is task tracker app using ReactJS and json server.

## Basic Function
1. Add the task<br>
When you click the Add button, you can add the new task and enter the information. Then you could click Save button, and the task you created will be shown belowed. Click Close button, the filling page will be closed.

2. Delete the task<br>
Click the red cross on the task will detele the task.

3. Change the reminder<br>
Double click the task rectangle will chagne the reminder status. The task with green block means it has already set the reminder. Otherwise, it means that the task doesn't have the reminder.

## Usage

### JSON server
In this project, we mock an backend and use the JSON server to get the fake REST API. We can amke the request such as POST, PUT, GET, DELETE, and the changes will be automatically saved in db.json. It just like as you were working on a real backend.<br><br>

To build for production

    npm run build
 <br>
Install the JSON server locally  

    npm i json-server
<br>   


Add `"server": "json-server --watch db.json --port 5000"` in `package.json` file `"scripts"` part


<br>


Run JSON server (http://localhost:5000)
    npm run server
    

<br>
 
 
Edit the `db.json` file

    {
      "tasks": [
        {
          "id": 1,
         "text": "Docter Appointment",
          "day": "Feb 5th at 2:30pm",
          "reminder": true
        },
        {
          "id": 2,
         "text": "Meeting at School",
         "day": "Feb 6th at 1:30pm",
          "reminder": true
         },
       {
          "text": "take test",
         "day": "Monday 1pm",
         "reminder": true,
         "id": 3
        }
      ]
    }
 <br>
Run react dev server(http://localhost:3000)

    npm start
<br>
Type the url `http://localhost:5000/tasks` in the web brower, you will see the json file and we can make the post and delete request.

<br>

*The detail can be found in https://github.com/typicode/json-server

