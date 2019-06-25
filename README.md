# bootstrap-override

This project demonstrate the process of overriding bootstrap variables to best suite your theme and design system.

# Environment
- Operating System: Windows 10

# Prerequisite
- Node 10.9+
- Node Package Manager
- Angular CLI 8.0+
- Visual studio Code
- Knowledge of SCSS

# Steps
- Create a new angular application using following command:
`ng new <name of the project>`

- Press "y" when "Would you like to add Angular routing? (y/N)?" question is asked.

- Select "SCSS" when "Which stylesheet format would you like to use? (Use arrow keys)" question is asked.

- This will create an angular project for you with scss as the css pre-processor

- Add Bootstrap: You can install bootstrap by following instruction in blog: https://medium.com/@krishjan05/bootstrap-4-0-and-angular-8-6111056b4700, perform all the steps after step 4

- Open style.scss file and import scss file of bootstrap using following statement:
`@import "node_modules/bootstrap/scss/bootstrap";`

- To override default variables use the following statements before importing bootstrap scss(before step 5):
`$body-bg: #000;
$body-color: #111;`

- When you run the application using the following command you see that the background color of the application is blue as compared to the default white:
`ng serve`