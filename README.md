**Note: this project is under development!**

# Designing Deliberation

A process framework development tool created by School of Cities in collaboration with Daniel Fusca!

---

## Installing this locally

- Install [Node](https://nodejs.org/en/download)
- Install [Git](https://git-scm.com/install/windows)
- Install [GitHub Desktop](https://desktop.github.com/download/)
- Install [VS Code](https://code.visualstudio.com/download) or an IDE of your choice
- Git clone this repository 
- Open your repo folder in VSCode
- Open a Terminal in VSCode (Terminal -> New Terminal)
- In the terminal, run `npm i` to install dependencies

## Running this locally
- In the terminal, `npm run dev` to run the site on your machine and see your changes update as you save them.
    - If you are encountering an error where "running scripts is disabled", run `Set-ExecutionPolicy RemoteSigned –Scope Process` in the terminal in VS code

## Building and updating the live website
- In GitHub Desktop:
    - Click the `Fetch changes` button to retrieve any changes others have made
- In VS Code:
    - Make your changes, and save the files
- In the terminal in VS Code:
    - Run `npm run build` to generate the build files
    - Run `npm run preview` to run the build on your machine and do testing to ensure it works.
    - Press `Ctrl+C` to close the process 
- In GitHub Desktop: 
    - add all changed files
    - commit them with a nice description
    - Click the `Push` button 

## Updating the case studies, concept library, and resources
The aforementioned pages have content that is being pulled from csv files in `static/content`. When adding a new case study, just add a new row. Adding a new column with information will require updates to the corresponding page in `src/routes`. 


