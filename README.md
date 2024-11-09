GLAB 320H.2.1 - Building a Simple React Application

Learning Objectives
After this lab, learners will have demonstrated the ability to:

Use create-react-app to make a pre-configured React application.
Create React components.
Render React components within an application.
Pass props to React components to modify their behavior.

Instructions
If you have not yet installed Node.js and npm, please take the time to do so. If you have trouble installing Node, speak with your instructors.

The first step to creating a React application is making an App.js file inside of a project directory, but we have a tool for this, so we won't be doing it manually.

For this application, this is the only file we'll be working with. In future applications, you'll want to compartmentalize your applications components, features, and other elements in order to stay organized.


Create-React-App
There is a wonderful tool that allows us to focus on code, rather than build, called Create React App. We will use this tool to setup our application.

It is important to note that create-react-app is now deprecated by the React team. Though it remains functional, developers are encouraged to use alternative tools and frameworks. Since these frameworks are beyond the scope of this course, we will continue to use create-react-app for our purposes.

We encourage exploration of other React frameworks like Next.js, Vite, and Remix as part of your learning efforts.

To create a project, run the following command:

npx create-react-app simple-react-application
Once complete, you should have a fully-configured application file system!

Note that there is a recommendation to run the following two commands, which you should do:

cd simple-react-application
npm start
This should open your broswer to localhost:3000 and display the template application.

Note: If your application displays an error, it is most likely a Windows-specific issue that can be easily resolved. Check that the casing of your file path in the command line is the same as the one seen by Node (/documents/simple-react-app is not the same as /Documents/simple-react-app). Navigate to the correctly cased file path. If the error persists, speak to your instructors.

Explore the Default App
Take some time to look through the default application's file structure and contents.

We have a node_modules folder, which holes all of our external packages and dependancies.
The public folder contains all of the files that will be served directly to the client.
The src folder contains our application files, including our .css files.
In a fully-fledged application, you'll want to create additional folders for things like features, components, and styles, but for this simple application we will work solely within the src/App.js file. Open that file in your code editor of choice.

https://ps-react-curriculum.herokuapp.com/320/2/lab/