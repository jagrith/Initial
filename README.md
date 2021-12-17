
# yampati-usha
=======
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) template.


Every year, details of all the graduate students at UNH are stored in the spreadsheet. The details include student’s name, graduated year, major and
post-graduation employment details. The students of UNH must take an internship course where they will be working for an organization in their field of study,
where they would like to pursue their career. The data management, aggregation and generating a value from such spreadsheets are more challenging. The primary objective of this project is to provide a platform for the admin to view and manage the data through a dashboard which is built in a website which helps to
monitor and manage the data through a user interface. The data from the spreadsheets is transformed into a NoSQL database, preferably Postgres tables. Once the data from spreadsheet passed into the Postgres database, REST API is developed to perform operations on top of this data using spring boot.

The micro-services architecture will help to perform CRUD operations on the student data. After testing the endpoints, a Web portal is developed using ReactJS
and Node JS. Integration of this API data is done so that it can be visualized and managed through the portal.Integrated Google Maps API to display
the location of the student’s internship workplace on the portal dashboard. For testing the application, the back-end microservice will be built as Maven 
project, the application is started where the embedded Apache tomcat server is run, and the REST API’s will be accessed through that port and also 
Postgres SQL server is started to access the data in the tables and to perform database operations. Node, React Server will run UI code to make API calls from the UI portal.  The web portal has a dashboard where admin can view the list of students who have completed their internship in that year/semester. Admin can select any student to see the coursework of the
student, the organization that he/she worked for, and the course comments. The Admin is also provided with an option to edit this data as well.

Technologies Required:

1. Java 8
2. Postgre SQL
3. Spring Boot
4. HTML
5. Java script
6. React JS
7. Node JS
8. REST
9. Springboot
10. maven

IDE's used:

1. IntelliJ for running Java Application
2. Atom for running UI Application

Execution Steps:

Backend:

Step 1: Download and Install Java 8(open JDK 8)

Step 2: Download and Install Postgres SQL, During the installation, set the userName and password while installing.

Step 3: Open the PostgreSQL and Execute the DDL scripts attached.

Step 4: Execute the DML scripts attached which will add sample data into the tables for testing.

Step 5: Open the Project in IntelliJ

Step 6: Update the Postgres username and password in application.yml located under resources package(/student_career_info/src/main/resources/application.yml) in the backend code.

Step 7: Do a maven build in the project

Step 8: Run the application and Backend application will be up and running.


UI:

Step 1: Download and Install Node Modules.

Step 2: Open the project path in command prompt(Windows) or Terminal (MAC)

Step 3: check for node installation using thus command node -v

Step 4: Install NPM using this command npm i

Step 5: start the node server using this command npm start

Step 6: UI application will open in a browser

Step 7: On the opening screen, The list of the student will be shown in a table format

Step 8: The UI page also shows ADD new Student button which will take inputs from Admin to add new student details.

Step 9: For each student, there will be actions displayed to edit/view/delete.

Step 10: When the button clicked, student Details will be displayed and delete/edit options provided on top of it.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
>>>>>>> moving career management system code into git hub repo
