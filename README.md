# Game-Finder

**Objective:** Web application that assists the user in finding a game of their choice.  
**API:** [IGDB API](https://api-docs.igdb.com/#endpoints)

## Getting Started

To use the application, follow these steps:

1. Clone the repo to a local device.
2. Open up the terminal and use the command `npm install` to download all the required dependencies.
3. Start the backend server using the command `node server.js` (server 8000 should be running).
4. Now start up another terminal and use the command `npm run start` (The web application should be running properly after this command).

## Components

Homepage:
  - Displays the Navbar, where user can use to search up a game of their choice.
  - Endpoint to display 8 random games.

NavBar:
 - search-bar(search games by names)
 - Homepage, favorites, and drop-down menu

Search/Similar/Favorites: 
  - Similar pages shows games related to the user inputed into search bar
  - Favortie page is a compilation of all saved favorite games (favorited games are store in MongoDB database)
  - Need to add user login, so favorite game can become more personalize for each user.
  


<h3>Good Luck Finding a game of your choice!!!</h3>
























