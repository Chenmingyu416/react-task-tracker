This is task tracker app usring ReactJS and json server.

In this app you can 
1. Add the task
When you click the Add button, you can add the new task and enter the information. Then you could click Save button, and the task you created will be shown belowed. Click Close button, the filling page will be closed.

2. delete the task
Click the red cross on the task will detele the task.

3. change the reminder
double click the task rectangle will chagne the reminder status. The task with green block means it has already set the reminder. Otherwise, it means that the task doesn't have the reminder.

* In this project, we mock an backend and use the JSON server to get the fake REST API. 
First we will install the JSON server locally use 

`npm install -i json-server`

Create a 'db.json' server file with some data


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


# Getting Started with Create React App

## Available Scripts

In the project directory, you can run:

### `npx create-react-app`

Create a React App

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run build`

Builds the app for production to the `build` folder.\

(https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
