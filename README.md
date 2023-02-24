# PWA Text Editor

## Description 
The aim of this application is to create a text editor that saves data through caching. The single page app can be downloaded as a desktop application therefore can be used offline. Users can generate any type of text such as code, notes etc.

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

## Initialisation
To use this application node.js must be installed: https://nodejs.org/en/download/ <br />

**The main packages required are:**
 * **webpack**  @5.51.1
* **@babel/core**  7.15.0

For a full lost of packages see the package.json file in the src folder.

All dependencies should already be in the package.json file and installed through running ```npm i``` in the terminal.

## Usage
To run the application run `npm run build` followed by `npm run start`

## Licensing 