
#prerequisites-
1. Install Node.js
Before you can start using React, you need to have Node.js installed on your computer. Node.js comes with npm (Node Package Manager), which you'll use to install React and other JavaScript libraries.

Download and Install Node.js: Go to the official Node.js website and download the installer for your operating system. The website should automatically suggest the best version for you (LTS version recommended for most users). Run the installer and follow the prompts to install Node.js and npm.
2. Create a New React Project
Once Node.js is installed, you can create a new React project using create-react-app, which is an officially supported way to create single-page React applications. It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production.

Open your command line interface (CLI): This could be Command Prompt on Windows, Terminal on macOS, or any terminal application you prefer.

Run the following command to create a new React application:

bash
Copy
npx create-react-app my-app
npx is a package runner tool that comes with npm 5.2+ and higher. It lets you use packages from npm without installing them globally.
create-react-app is the package you're running.
my-app is the name of your new project folder. You can choose any name you prefer.
3. Navigate into Your Project Directory
After creating your project, you need to change into your project directory to start working on your application:

bash
Copy
cd my-app
4. Start the Development Server
Once inside your project directory, you can start the development server using npm:

bash
Copy
npm start
This command runs the app in development mode. It will open your default web browser and navigate to http://localhost:3000, where you can see your new React application running. The page will automatically reload if you make changes to the code.

5. Build Your App for Production
When you’re ready to deploy your application, you can create a minified bundle using:

bash
Copy
npm run build
This command builds the app for production to the build folder. It correctly bundles React in production mode and optimizes the build for the best performance.

Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Available Scripts

In the project directory, you can run:

npm start

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

npm test

Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

npm run build

Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

npm run eject

Note: this is a one-way operation. Once you eject, you can't go back

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

 npm run build` fails

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
![image](https://github.com/user-attachments/assets/c7d26bcd-5a28-492b-99ea-e74a89e655ab)
