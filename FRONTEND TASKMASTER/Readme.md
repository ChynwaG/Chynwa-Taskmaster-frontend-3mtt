#### TaskMaster Frontend
TaskMaster Frontend is the client-side interface for managing tasks in the TaskMaster application. This application allows users to register, log in, and manage their tasks (create, update, delete, filter, and search tasks).

### Features
- User Authentication: Register and log in with secure token-based authentication.
- Task Management:
Create tasks with attributes like title, description, priority, and deadline.
Update or delete tasks.
- Task Filtering: View tasks by priority or due date.
- Task Search: Quickly find tasks using a search bar.
- Responsive UI: User-friendly interface with seamless navigation.

### Technologies Used
- HTML5: Structure of the application.
- CSS3: Styling and layout.
- JavaScript (ES6+): Dynamic functionality and API integration.
- Fetch API: Communicate with the backend for task management and authentication.

### Setup and Deployment
  # Prerequisites
- Ensure the backend API is up and running. Update the API URL in script.js to match your backend URL.
- Install Node.js and Vercel CLI (optional) for deployment.

### API Endpoints
- The frontend communicates with the backend using the following API endpoints:

  # Authentication:
- POST /api/auth/register: Register a new user.
- POST /api/auth/login: Log in and get a JWT.
- Task Management:

- GET /api/tasks: Get all tasks for the authenticated user.
- POST /api/tasks: Create a new task.
- PUT /api/tasks/:id: Update an existing task.
- DELETE /api/tasks/:id: Delete a task.

### License
This project is licensed under the MIT License.

### Acknowledgments
Vercel for hosting.
OpenAI ChatGPT for guidance and support.
