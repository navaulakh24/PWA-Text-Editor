# PWA-Text-Editor

## Description
I created a simple, single-page text editor app that runs in the browser, and can function both online and offline. I was required to use a variety of data persistence options in case one of the options is not supported by the browser. 

This application first looks to use the data in the IndexedDB database to populate the editor, if not accessible, will use local storage.


## Table of Contents
[Deployment](#deployment)

[Installation](#installation)

[Usage](#usage)

[License](#license)

[Questions](#questions)

#

## Deployment
Click [here](https://damp-headland-65466.herokuapp.com/) for the deployed app!
#

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```
![Webpage](./client/src/images/Screenshot%20(33).png)
![Webpage](./client/src/images/Screenshot%20(34).png)


## Installation
This application has been deployed on Heroku and does not require an install.

If you would still like download this project, you would simply need to clone the repo and then run the command "npm install" in the terminal to install the dependencies needed, since they are included in the package.json.

## Usage
To use the app, you may open the browser with the deployed link.

For offline use, users can go to the link and click the "Install!" button at the top left corner of the page.

If you have cloned the repo and have already run "npm install", you can now type in "npm start" from the root directory.

## License 
MIT

## Questions

GitHub: navaulakh

GitHub repo: https://github.com/navaulakh24/PWA-Text-Editor

Email: navdeep_aulakh24@hotmail.com