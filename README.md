### Setup Clone the Repository: 
git clone https://github.com/vkonga/shanture-web-development-venkatesh-kongara.git 
cd shanture-web-app
# Install backend dependencies
cd shanture-backend
node app.js

# Install frontend dependencies
cd shanture-frontend
npm start
### Task Management:
Add tasks with a name.
Delete tasks.
Update task status (complete/incomplete).
PDF Generation and Storage:
Generate a PDF document of current tasks.
Save generated PDF to a database.
### Technologies Used
Frontend: React.js, @react-pdf/renderer
Backend: Express.js, SQLite
Additional Libraries: react-icons, multer, cors

### Setup SQLite Database:

Create a SQLite database file lists.db.
Define the task and pdfdocument tables within this database.

Backend API Endpoints
GET /

Fetches all tasks from the database.
POST /add-task/

Adds a new task to the database.
PUT /update-task/:id

Updates an existing task in the database.
DELETE /delete-task/:id/

Deletes a task from the database.
POST /api/save-pdf

Saves a generated PDF file to the database.

### Frontend Components
Home Component :
Manages task CRUD operations.
Generates and saves PDFs.
Uses React components and @react-pdf/renderer for PDF generation.
### Usage
Adding a Task:

Enter a task name in the input field and click ADD.
Updating Task Status:

Check/uncheck the checkbox next to a task to mark it as complete/incomplete.
Deleting a Task:

Click the delete icon (MdDelete) next to a task to delete it.
Generating and Saving PDF:

Click Download Task List to generate and download a PDF of the current task list.
Click Save PDF to Database to save the generated PDF to the database.
