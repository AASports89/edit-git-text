# **Edit Git Text** [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](#isc-license)
---

## Overview
---
**Edit Git Text** utilizes ```MongoDB```, a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. The technology behind **Friends Git Social** allows it to operate as a "full-stack" application. ```MongoDB``` centers on the movement of consistently changing data, thus it is a vital part of the functionality of **Edit Git Text**.

Through the use of a dynamic ```API``` **Edit Git Text** is an user-friendly and intuitive social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. ```Express.js``` is utilized for routing, ```MongoDB``` as database, and ```Mongoose ODM``` to retrieve data linked to user activities. Lastly, dynamic ```JavaScript``` ensures that data is accurately and consistently dated.

> **Note**: For a more detailed insight into the functionality and capabilities of **Edit Git Text**, feel free to refer to the video walkthrough link provided below.

## Table of Contents
---

  * [Overview](#overview)
  * [User Story](#user-story)
  * [Acceptance Criteria](#acceptance-criteria)
  * [Installation and Running Locally](#installation-and-running-locally)
  * [Mock Up](#mock-up)
  * [Deployed Webpage URL](#deployed-webpage-url)
  * [GitHUB Repository](#github-repository)
  * [Evaluation Guideline](#evaluation-guideline)
  * [Questions](#questions)
  * [License](#isc-license)

## User Story
---

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria
---
> **Note:** The following criteria is used to determine if the standards set for **Edit Git Text** have been met:

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

## Installation and Running Locally
---

> **Important:** Once, the source code has been cloned from the repository @https://github.com/AASports89/friends-git-social & the ```MongoDB``` database set up:

 Enter the following:

 ```
 npm i express
 ```
 -followed by-
 ```
 npm i mongoose
 ```
 -followed by-
 ```
 npm i nodemon
 ```
 -followed by-
 ```
 node seed/index.js
 ```
 -OR-
 ```
 npm run seed
 ```
 -followed by-
 ```
 node server.js
 ```
 -OR-
 ```
 npm run start
 ```
 in the terminal cmd to install required packages & run **Edit Git Text** locally for testing routes using ```Insomnia```.

## Mock-Up
---
> **Note:**  The following animation shows the application's ```GET```, ```POST```, ```PUT``` & ```DELETE``` routes associated with "api/users" using ```Insomnia```:

> **'GET', 'POST', 'PUT' & 'DELETE' "api/users" routes:** ![In ```Insomnia```, tests for the ```GET```, ```POST```, ```PUT``` & ```DELETE``` api/users routes are depicted.](./images/api-user-routes.gif)

> **Note:** The following animation shows the application's ```POST``` & ```DELETE``` routes associated with "api/user/friends" using ```Insomnia```:

> **'POST' & 'DELETE' "api/users/friends" routes:** ![In ```Insomnia```, tests for the ```POST``` & ```DELETE``` api/users/friends routes are depicted.](./images/api-user-friend-routes.gif)

> **Note:** The following animation shows the application's ```GET```, ```POST```, ```PUT``` & ```DELETE``` routes associated with "api/thoughts" using ```Insomnia```:

> **'GET', 'POST', 'PUT' & 'DELETE' "api/thoughts" routes:** ![In ```Insomnia```, tests for the ```GET```, ```POST```, ```PUT``` & ```DELETE``` api/thoughts routes are depicted.](./images/api-thoughts-routes.gif)

> **Note:** The following animation shows the application's ```POST``` & ```DELETE``` routes associated with "api/thoughts/reactions" using ```Insomnia```:

> **'POST' & 'DELETE' "api/thoughts/reactions" routes:** ![In ```Insomnia```, tests for the ```POST``` & ```DELETE``` api/thoughts/reactions routes are depicted.](./images/api-thoughts-reaction-routes.gif)

## Deployed Webpage URL
---
> https://TBD.com

## GitHUB Repository
---
> https://github.com/AASports89/edit-git-text

## Evaluation Guideline
---
> **Note**: The following evaluation guideline is used to determine if **Edit Git Text** meets the requirements for a minimum viable product:

### Technical Acceptance Criteria: 40%
---
Satisfies all of the above acceptance criteria plus the following:

Uses IndexedDB to create an object store and includes both GET and PUT methods

The application works without an internet connection

Automatically saves content inside the text editor when the DOM window is unfocused

Bundled with webpack

Create a service worker with workbox that Caches static assets

The application should use babel in order to use async / await

Application must have a generated manifest.json using the WebpackPwaManifest plug-in

Can be installed as a Progressive Web Application

### Deployment: 32%
---
Application deployed to Heroku at live URL with build scripts

Application loads with no errors

Application GitHub URL submitted

GitHub repo contains application code

Application Quality: 15%
Application user experience is intuitive and easy to navigate

Application user interface style is clean and polished

Application resembles the mock-up functionality provided in the Challenge instructions

### Repository Quality: 13%
---
Repository has a unique name

Repository follows best practices for file structure and naming conventions

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages

Repository contains a quality README file with description, screenshot, and link to deployed application

## Questions
---
> **Note:** For any troubleshooting and/or functionality related questions, please visit my GitHUB @https://github.com/AASports89.

## **ISC License**
---
**Copyright © 2022 - AASports89**

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

---
---