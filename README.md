For the React Project:
Setup:
1)Install Visual Studio Code: Download and install Visual Studio Code if you haven't already.
2)Install Dependencies: Open the terminal in your project directory and run npm install to download all required packages.
3)Start the Project: Execute npm run start in the terminal to launch the development server.


Features:
Add a User: You can add a new user with all the required attributes.
Search for a User: Look up users by name and email.
Edit User Information: Update the first name of an existing user.
Delete a User: Remove a user from the system.


For the Java Project (Spring Boot):
Setup:
1)Install Prerequisites: Ensure that Java is already installed on your system.
2)Download Spring Boot STS IDE: Download and install the Spring Tool Suite (STS).
3)Maven Update: In STS, right-click your project and select "Maven" -> "Update Project".
4)Maven Clean and Install: Right-click on the project, choose "Run As" -> "Maven clean" and then "Run As" -> "Maven install".
5)Run the Application: Launch the Spring Boot application.


Features:
As mentioned above for the React project.


For AWS Interaction:
1)Log In: Sign in to your AWS account using your credentials.
2)Navigate to Services: Go to the AWS Services dashboard.
3)Locate SQS: In the search bar, type "Simple Queue Service" or "SQS" and select it.
4)Open Pre-configured Queue: Since the queue is already set up, simply click on it.
5)Send and Receive Messages: Click the "Send and Receive Messages" button.
6)Send a Message: Type your message in the provided field and hit the "Send" button.
7)Check Application Console: The Java application will consume this message from the AWS SQS queue, and you'll see the message logged in the application console, thanks to the JMS listener that continuously monitors the queue.


To Run Test Cases:
Execute JUnit Tests: Right-click on the project in your IDE and choose to run JUnit tests. All tests should pass successfully, as the JUnit tests are also written and configured
