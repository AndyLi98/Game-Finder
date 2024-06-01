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
  - Have dropdown list of certain game category where user can click on that takes the client to a specific endpoint that renders 50 random games from the category of their choice.
  - Home Button that returns the user to homepage.
  - Favorite Button that sends the client to the favorite endpoint that contains games the save in their favorites.
  - Search display, where user can type a name of a specific game of their choosing. Doing so will bring user to endpoint that displays up to 50 games with related to the serach term the user inputs.

















