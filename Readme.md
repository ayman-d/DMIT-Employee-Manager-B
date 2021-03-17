# Employee Manager App

- [Overview](#overview)
- [Purpose](#purpose)
- [How to run](#running-the-project)
- [Dependancies](#dependancies)
- [Contributors](#contributors)

---

### Overview

This app was built with the purpose of managing employee data within the company with regards to their details and statuses.

Currently, the app has the following features: 

1. Home page

2. Dashboard page with department list

<img src="https://puu.sh/HpU1i/18d6619689.png" alt="image" />

3. Department detailed view with all employees listed

<img src="https://puu.sh/HpU2O/2513685e2f.png" alt="image" />

4. Ability to delete employees or edit their details

<img src="https://puu.sh/HpU3d/bbf70c6484.png" alt="image" />

---

### Purpose

This app is made for the purpose of managing employee details, financial data, and keeping a live record of each employee through the company's portal.

---

### Running the project

The repo does not include the node_modules, please run `npm install` in the main project 
directory if you wish to clone it and run it locally

The package.json is already configured with:
- `npm run server` command to run the project in development
- `npm start` to run the application in production

This project also requires the
[Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension. 
If you use it on VS Code, make sure to turn on "watch sass" option when editing the scss style sheets

---

### Dependancies

- Production

| Package                        | Purpose                                                       |
|--------------------------------|---------------------------------------------------------------|
| express                        | Node JS framework to run server side code                     |
| cors                           | Allows cross server communication                             |
| ejs                            | JS view template renderer                                     |
| cookie-session                 | To maintain user's session while logged in                    |
| uuid                           | To create long string id numbers                              |
| snowpack                       | To build and compile the project                              |


- Development

| Package                        | Purpose                                                       |
|--------------------------------|---------------------------------------------------------------|
| Nodemon                        | Package to automatically restart server upon changes          |

---

### Contributors

- [Ayman Al-Dali](https://github.com/ayman-d) :octocat:

---

