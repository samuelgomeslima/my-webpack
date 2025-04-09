# My Webpack Project

This project is set up with Webpack to handle JavaScript and Sass/CSS files. Follow the instructions below to set up and run the project.

## Setup Instructions

1. **Initialize the Project**

   Start by creating a new Node.js project. This will generate a `package.json` file with default settings.

   ```bash
   npm init -y
   ```

2. **Install Webpack and Webpack CLI**

   Install Webpack and its CLI as development dependencies to bundle your JavaScript files.

   ```bash
   npm install --save-dev webpack webpack-cli
   ```

3. **Install Project Dependencies**

   Install the necessary dependencies for handling Sass and CSS files.

   ```bash
   npm install sass@^1.32.8 webpack@^5.99.5
   ```

4. **Install Development Dependencies**

   Install loaders for processing CSS and Sass files, along with the Webpack CLI.

   ```bash
   npm install --save-dev css-loader@^5.1.3 sass-loader@^11.0.1 style-loader@^2.0.0 webpack-cli@^6.0.1
   ```

5. **Run a Local Server**

   Use `http-server` to serve your project locally. This command will start a simple HTTP server in the current directory.

   ```bash
   npx http-server .
   ```

## Additional Notes

- Ensure you have Node.js and npm installed on your machine.
- The `http-server` command will serve files from the current directory, accessible at `http://localhost:8080` by default.