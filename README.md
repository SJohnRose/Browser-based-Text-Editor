# Browser-based-Text-Editor
A text editor that runs in the browser and uses service workers, manifests and Webpacks to function as a Progressive Web Application.

# Features
* A text editor that runs in the browser.
* Can be installed locally as a Progressive Web Application (PWA).
* Data is stored in an IndexedDB database.
* Bundled with Webpack and uses service workers for precaching assets.
* Application can run without internet connection.

# User Story
AS A developer  
I WANT to create notes or code snippets with or without an internet connection  
SO THAT I can reliably retrieve them for later use  

# Acceptance Criteria
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

# Mock-up
The following images shows the application's appearance and functionality:
![image](https://user-images.githubusercontent.com/115912745/231039842-9fbb79a2-0064-4564-9302-9b690ac6949f.png)
![image](https://user-images.githubusercontent.com/115912745/231040020-f46a5767-03b3-4bdb-aad3-ede1c9674030.png)

# How to access the JATE application?
Please use this link: https://github.com/SJohnRose/Browser-based-Text-Editor   
Deployed at: https://browser-based-jate.herokuapp.com/
