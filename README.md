# Introduction 
HTML Starter Template

## Features
### HTML Partials
HTML Partials refer to reusable chunks of HTML code that you can include in multiple HTML files. This helps in maintaining consistency across your project and reduces redundancy. Using HTML partials with Gulp involves defining these partials (e.g., header, footer) in separate files and then using Gulp to concatenate them into your main HTML files during the build process.

### Only Bootstrap Grid - No extra components
The Bootstrap Grid is a responsive grid system provided by Bootstrap, a popular front-end framework. It allows developers to create responsive layouts easily by dividing a webpage into rows and columns. Gulp can be configured to include Bootstrap in your project, making it straightforward to use its grid system for responsive design without manually including and managing Bootstrap files.

### Actions Folder for PHP Action Files
In web development, PHP action files often handle server-side tasks like processing form submissions or interacting with databases. Having an Actions folder dedicated to these files organizes your backend logic separately from your frontend code. Gulp can manage tasks related to these files, such as moving them to the correct server directory during deployment or watching for changes during development.

### SCSS Compiler
SCSS (Sassy CSS) is a CSS preprocessor that extends the functionality of CSS with variables, nested rules, mixins, and more. Gulp can be configured to compile SCSS files into regular CSS files. This allows you to write modular and maintainable CSS code using SCSS syntax and then automatically compile it into browser-readable CSS.

### Node Modules CSS Vendor File
Similar to JavaScript, Node Modules CSS Vendor files are CSS files from npm packages. Gulp can bundle these CSS files together, ensuring that styles from external dependencies (like Bootstrap's CSS or other CSS frameworks) are included in your project's final CSS file.

### JS Minifier / Uglify
JS Minification or Uglification is the process of reducing the size of JavaScript files by removing unnecessary whitespace, comments, and renaming variables to shorter names without changing functionality. Gulp can integrate plugins like UglifyJS to minify your JavaScript files, making them load faster and reducing bandwidth consumption.

### Node Modules JS to Import
Node Modules are JavaScript packages installed via npm (Node Package Manager). When you use Node modules in your project, Gulp can help manage these dependencies by bundling them into a single JavaScript file. This ensures that your project's dependencies are properly included and optimized for deployment.

### Gulp Localhost
Gulp Localhost refers to using Gulp to spin up a local development server. This server supports features like live reloading (using tools like BrowserSync) to automatically refresh the browser whenever changes are made to your HTML, CSS, or JavaScript files. It provides a convenient environment for testing and developing your web applications locally before deployment.

These features combined make Gulp a powerful tool for automating repetitive tasks, optimizing code, and streamlining the development workflow in web projects.

# Steps for Setup

### Install NPM Modules and Dependencies
```
yarn install
```

### Compile the Gulp File
```
gulp
```

### Watch Files to update gulp
```
gulp watch
```

### Run Localhost
```
gulp localhost
```
