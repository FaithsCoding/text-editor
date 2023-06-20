# Text Editor (JATE)

## Description

This project is a text editor allowing the user to create notes or code snippets. This can be downloaded and used offline as well as within a browser. The integrated service workers and cache API's ensure that the app can run offline.

## Table of Contents

- [Title](#title)
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Demo](#demo)
- [Contributing](#contributing)
- [Questions and links ](#questions-and-links)

## Installation

To run this application you will need to have installed VS code, node and npm packages. This app relies on an indexedDB database to build up. You will use the node package manager (npm) to install your dependencies. The dependencies you will need are as follows: You can also run npm i which will install neccessary dependencies that have been outlined in your package.json file.

## Usage

You will start the application by going to your terminal and runnin npm start, this begins running the application and will tell you what PORT your browser is listening to.You will then be able to type directly into the text editor. You will be able to see in yuour browser dev tools that in your local storage, in shows you what is being retrieved from the indexed db. You can also go to the service workers tab which shows you the static assets pre cached upon loading. Additionally, you can click install and this editor will be available to you locally, offline.

## Tests

You can test this application by running npm start, this should build the application, cd to server and run node server.js which begins running the app. You can then navigate to the localhost PORT number and ensure that it loads the application. You can check the information in the browser dev tools and ensure all of the correct information is being retrieved and displayed. You can follow the heroku deployed link and ensure that is fully functional. You can also install the app, turn your internet off and ensure that the app is still fully functional.

## Demo

Screeshot showing file structure:
![Screenshot 2023-06-20 at 10 54 31](https://github.com/FaithsCoding/text-editor/assets/122907573/1287c02e-e42f-4930-bfed-a0c7fd5dea72)

Screenshot to show the npm i:
![Screenshot 2023-06-20 at 11 10 29](https://github.com/FaithsCoding/text-editor/assets/122907573/17bb4724-f2f7-472a-9677-7a01cca903d6)

Screenshot to show npm start:
![Screenshot 2023-06-20 at 11 11 35](https://github.com/FaithsCoding/text-editor/assets/122907573/25655afc-ac54-46ce-b352-5969d1650717)

Screenshot to show JATE loaded in browser:
![Screenshot 2023-06-20 at 11 12 18](https://github.com/FaithsCoding/text-editor/assets/122907573/7bbf1720-f8bd-4897-9a19-932774883854)

Screenshot to show the functionality of JATE and localstorage:
![Screenshot 2023-06-20 at 11 13 27](https://github.com/FaithsCoding/text-editor/assets/122907573/279923b7-cd44-4660-be67-40a33ba4bf14)

Screenshot to show the prompt for installing JATE:
![Screenshot 2023-06-20 at 11 15 06](https://github.com/FaithsCoding/text-editor/assets/122907573/5199e9d3-ce2e-42cc-9779-47f3665b3005)

Screenshot to show what JATE looks like offline which has kept the data inputeed on the browser:
![Screenshot 2023-06-20 at 11 15 29](https://github.com/FaithsCoding/text-editor/assets/122907573/1da4a86a-8ea7-462b-ab31-a15494248f2e)

## Contributing

Faith Meades

## Questions and links

- Username: FaithsCoding
- URL: [FaithsCoding GitHub](www.github.com/FaithsCoding)
- Repository (REPO): [Text Editor Repository](https://github.com/FaithsCoding/text-editor)
- Heroku Deployed Link: [JATE Text Editor](https://faiths-jate-8803879369c0.herokuapp.com/)
- Contact email: faithscoding@outlook.com
