# TypeScript & Webpack Setup

## Description
This project demonstrates basic TypeScript usage with Webpack.  
It defines a `Student` interface, creates two student objects, stores them in an array, and renders a simple HTML table showing each student’s **first name** and **location**.

## Project Structure
```

task\_0/
│── package.json
│── tsconfig.json
│── webpack.config.js
│── .eslintrc.js
│── main.ts
│── dist/
│   └── bundle.js (generated after build)

````

## Setup & Installation
1. Navigate to the project directory:
   ```bash
   cd task_0
````

2. Install dependencies:

   ```bash
   npm install
   ```

## Running the Project

* Build the project with Webpack:

  ```bash
  npm run build
  ```

  You should see:

  ```
  No type errors found.
  ```

* Open `index.html` in your browser and a table will be displayed with the students’ first names and locations.

## Requirements Met

* TypeScript interface `Student`
* Two student objects created
* Students stored in an array
* Table dynamically rendered with Vanilla JS
* Webpack build succeeds with no type errors

```
