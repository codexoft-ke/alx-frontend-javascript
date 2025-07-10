# 0x04. TypeScript

This project contains TypeScript exercises covering various concepts including basic types, interfaces, classes, functions, DOM manipulation, generics, namespaces, declaration merging, and ambient namespaces.

## Learning Objectives

At the end of this project, you should be able to explain:

- Basic types in TypeScript
- Interfaces, Classes, and functions
- How to work with the DOM and TypeScript
- Generic types
- How to use namespaces
- How to merge declarations
- How to use an ambient Namespace to import an external library
- Basic nominal typing with TypeScript

## Requirements

- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- All files will be transpiled on Ubuntu 18.04
- TS scripts will be checked with jest (version 24.9.*)
- A README.md file, at the root of the folder of the project, is mandatory
- Code should use the .ts extension when possible
- The TypeScript compiler should not show any warning or error when compiling your code

## Tasks

### Task 0: Creating an interface for a student
**Directory:** `task_0/`

Create a Student interface and render a table with student data using vanilla JavaScript.

- Files: `js/main.ts`, `package.json`, `.eslintrc.js`, `tsconfig.json`, `webpack.config.js`

### Task 1: Let's build a Teacher interface
**Directory:** `task_1/`

Create a Teacher interface with specific properties and modifiability constraints.

- Files: `js/main.ts`, `package.json`, `tsconfig.json`, `webpack.config.js`

### Task 2: Extending the Teacher class
**Directory:** `task_1/`

Create a Directors interface that extends Teacher.

- Files: `js/main.ts`

### Task 3: Printing teachers
**Directory:** `task_1/`

Create a printTeacher function with its interface.

- Files: `js/main.ts`

### Task 4: Writing a class
**Directory:** `task_1/`

Create a StudentClass with constructor and methods.

- Files: `js/main.ts`

### Task 5: Advanced types Part 1
**Directory:** `task_2/`

Create Director and Teacher interfaces and classes with a createEmployee function.

- Files: `js/main.ts`, `package.json`, `tsconfig.json`, `webpack.config.js`

### Task 6: Creating functions specific to employees
**Directory:** `task_2/`

Create isDirector and executeWork functions.

- Files: `js/main.ts`

### Task 7: String literal types
**Directory:** `task_2/`

Create a Subjects string literal type and teachClass function.

- Files: `js/main.ts`

### Task 8: Ambient Namespaces
**Directory:** `task_3/`

Work with ambient declarations and external libraries.

- Files: `js/main.ts`, `js/interface.ts`, `js/crud.d.ts`

### Task 9: Namespace & Declaration merging
**Directory:** `task_4/`

Create namespaces with declaration merging for different subjects.

- Files: `package.json`, `tsconfig.json`, `js/subjects/Cpp.ts`, `js/subjects/Java.ts`, `js/subjects/React.ts`, `js/subjects/Subject.ts`, `js/subjects/Teacher.ts`

### Task 10: Update task_4/js/main.ts
**Directory:** `task_4/`

Create and export subject constants and demonstrate their usage.

- Files: `js/main.ts`

### Task 11: Brand convention & Nominal typing
**Directory:** `task_5/`

Create branded interfaces for MajorCredits and MinorCredits with sum functions.

- Files: `js/main.ts`, `package.json`, `webpack.config.js`, `tsconfig.json`

## Usage

To build and run any task:

1. Navigate to the task directory:
   ```bash
   cd task_X
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   npm run build
   ```

4. For development with live reload:
   ```bash
   npm run start-dev
   ```

## Repository

- **GitHub repository:** alx-frontend-javascript
- **Directory:** 0x04-TypeScript
