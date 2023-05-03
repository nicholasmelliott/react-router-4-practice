React Router App
This is a simple React application that demonstrates how to use React Router for routing. The application consists of a header and several pages, each with a different URL path.

How to Run
To run this application, follow these steps:

Clone the repository to your local machine.
Open a terminal window and navigate to the project directory.
Install dependencies by running npm install in the terminal.
Start the development server by running npm start.
Open a web browser and go to http://localhost:3000 to view the application.
App Components
The following components are used in this application:

Header: Renders the header of the application.
Home: Renders the homepage of the application.
About: Renders the "About" page of the application.
Teachers: Renders the "Teachers" page of the application.
Courses: Renders the "Courses" page of the application.
NotFound: Renders a "404 Not Found" error page when no matching routes are found.
Featured: Renders the "Featured" page of the application for a specific teacher.
Routing
The application uses React Router to handle routing. The routes are defined in the App component and specify which component to render for each URL path. The Switch component ensures that only one route is matched at a time.

The home page is mapped to the / path using the exact prop.
The "About" page is mapped to the /about path.
The "Teachers" page is mapped to the /teachers path using the exact prop.
The "Featured" page is mapped to the /teachers/:topic/:name path, where :topic and :name are route parameters.
The "Courses" page is mapped to the /courses path.
The "Not Found" page is rendered for any other URL path.
