![Homepage View](./screenshots/ss1.png)
![Add Todo Form](./screenshots/ss2.png)

🚀 Project Showcase: Dynamic Todo Application with Full Stack Implementation 🚀

I’m excited to share my latest project—a dynamic Todo List application that I developed using a full stack approach. This project highlights both the frontend and backend components, seamlessly integrated to provide a robust and user-friendly experience.

Frontend: Built with React
🔹 Dynamic UI: Developed a responsive and intuitive user interface with React, allowing users to add, edit, and delete tasks effortlessly.

🔹 Real-time Updates: Leveraged React hooks (useState, useEffect, useCallback) to manage state and ensure real-time updates.

🔹 Debounced Input: Implemented debounce functionality to optimize performance and prevent excessive API calls.

🔹 Edit Functionality: Users can seamlessly switch to edit mode, with clear options to update or cancel changes to tasks. The UI dynamically updates to reflect these changes.

🔹 Scrollable Task List: Ensured a smooth user experience by adding a scrollbar when the number of tasks exceeds the visible area, maintaining a clean and organized layout.

🔹 Modern Styling: Applied advanced CSS techniques, including flexbox for layout, hover effects, and custom button styles, to ensure the app is both visually appealing and responsive.

Backend: Powered by Express.js and AWS DynamoDB
🔹 Tech Stack: Built with Node.js, Express.js, AWS SDK, and DynamoDB for a robust and scalable backend.

🔹 RESTful API: Created endpoints to handle CRUD operations:

GET /todos: Fetch all todos from the DynamoDB table.
POST /todos: Add a new todo item to the DynamoDB table.
DELETE /todos/:id: Delete a todo item based on the ID.
PUT /todos/:id: Update an existing todo item based on the ID.
🔹 AWS DynamoDB Integration: Configured AWS SDK to interact with DynamoDB, utilizing scan, put, delete, and update operations for efficient data management.

🔹 Environment Variables: Secured sensitive information like AWS credentials using environment variables with the help of the dotenv package.

🔹 CORS Enabled: Enabled Cross-Origin Resource Sharing (CORS) to ensure seamless communication between frontend and backend.

🔹 Error Handling: Implemented robust error handling for all endpoints to ensure reliable API responses and better debugging.

🔹 Middleware: Utilized body-parser for parsing JSON requests and cors for handling CORS.

Project Highlights
Real-time Data Management: The integration between the frontend and backend ensures that data is consistently updated and synchronized across the application.
User-Friendly Interface: A clean and responsive UI that provides a seamless user experience, with dynamic editing capabilities and smooth transitions.
Scalable and Secure Backend: A powerful backend setup with AWS DynamoDB ensures data is stored securely and can scale as needed.
This project has been an incredible learning experience, providing me with hands-on expertise in both frontend and backend development. I’m excited to continue building and refining applications that offer both functionality and aesthetic appeal.

Feel free to check out the code and share your feedback!

#FullStackDevelopment #ReactJS #NodeJS #ExpressJS #AWSDynamoDB #WebDevelopment #JavaScript #CSS #TodoListApp #ProjectShowcase

## Installation

### Prerequisites

- Node.js and npm installed.
- AWS account for DynamoDB.

### Setup

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory:**

    ```bash
    cd <project-directory>
    ```

3. **Install backend dependencies:**

    ```bash
    cd backend
    npm install
    ```

4. **Install frontend dependencies:**

    ```bash
    cd ../frontend
    npm install
    ```

5. **Set up environment variables:**

    - Create a `.env` file in the `backend` directory.
    - Add the required environment variables for AWS DynamoDB.

6. **Run the application:**

    - **Start the backend server:**

        ```bash
        cd backend
        npm start
        ```

    - **Start the frontend development server:**

        ```bash
        cd ../frontend
        npm start
        ``
