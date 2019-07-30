# Rubric-file-structure
File structure for iX Full stack Project 

## Project Setup

### Create Project Via CLI

Navigate to the project file

```bash
cd Rubric-file-structure
cd Admin Panel
```
Create project

```bash
ng new admin-panel
```
Do the same for projects:

Consumer Mobile App

```bash
ionic start consumer-mobile-app
```

Provider Mobile App

```bash
ionic start provider-mobile-app
```

API

Create file structure with server.js located in a folder called api

```bash
mkdir api
cd api 
npm init
```

### Project Structure 

Generate a mark down table similar to the one in root directory of this project. The following website can be used to do https://www.tablesgenerator.com/markdown_tables or edit the Project File Structure.txt file in the root directory

Only files included in this mark down table with be marked!

Ensure that the files included in the mark down table related the sections specified in the table.

Please include the mark down table in the README.md file in the root directory of the project.

### Example of Project Structure 

| PROJECT             | COMPONENT          | FILE NAMES                                                                                                                                                                              |
|---------------------|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Consumer mobile app | Login              | TomaselliAirBnbProj/consumerapp/src/app/pages/login               |
| Consumer mobile app | Registration       | TomaselliAirBnbProj/consumerapp/src/app/pages/register |
| Consumer mobile app | User Profile       | TomaselliAirBnbProj/consumerapp/src/app/pages/profile                 |
| Consumer mobile app | List of Properties | TomaselliAirBnbProj/consumerapp/src/app/pages/tab1     |
| Provider mobile app | Login              | TomaselliAirBnbProj/providerapp/src/app/login               |
| Provider mobile app | Registration       | TomaselliAirBnbProj/providerapp/src/app/register |
| Provider mobile app | User Profile       | TomaselliAirBnbProj/providerapp/src/app/tab3                 |
| Provider mobile app | List of Properties | TomaselliAirBnbProj/providerapp/src/app/tab2     |
| Provider mobile app | List of Bookings   | TomaselliAirBnbProj/providerapp/src/app/tab2         |
| Admin Panel         | Users              | TomaselliAirBnbProj/fs-bnb-admin/src/app/components/users                                   |
| Admin Panel         | Bookings           | TomaselliAirBnbProj/fs-bnb-admin/src/app/components/bookings                                  |
| API                 | Users              | TomaselliAirBnbProj/fs-bnb-api/src/api/pages/users                                                                 |
| API                 | Bookings           | TomaselliAirBnbProj/fs-bnb-api/src/api/pages/bookings                                                           |

### Change Git Remote URL

Create new repository on GitHub.

Change the git URL associated with the project 

```bash
git remote set-url origin < new URL of your GitHub project (click 'Clone or download' button on GitHub site to see URL) >
```

Ensure that the git URL has been updated.

```bash
git remote -v
```

