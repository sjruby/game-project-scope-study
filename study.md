# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.


[Imgur](http://i.imgur.com/xI9FAaw.jpg)


-   The data structure you plan to use.
-
It's going to be an object within an object, I've already created JS logic I can run
in the command line to test if a given tic tac toe board is a win/cats game.
The game board is a constructor function with some methods to check for the win

-   How you will take the markup of the game board and represent it in JS
-
Below was the initial object I created and used to make the constructor function:
const tickTacBoard = {
  board : ['O','O','X','X','X','O','O','O','b']
}
Then there are functions that test for win/cats game

-   How you plan to approach this project.


My approach to building the app will be to break down tasks into 3 steps in the follow order:

1. Get API authentication stuff set up.
2. Get create new game API created, and confirm I can pull a list of games.
3. Set up Game logic, and confirm game save

-   4-8 user stories for your game project.
1. As a tic-tac-toe expert, I want the page to tell me if O or X won
2. As a site user, I want to track my wins/losses/draws
3. As a site user, I want to be able to login/out/change my PW
4. As a tic-tac-toe player, I want the game to automatically switch turns
5. As a user, I want to be able to start a new game whenever I want.

-   How you plan to keep your code modular.
I will follow the same Events/UI/API structure that we used for authentication for game events.

-   What creative spin will you add to your project?
I played a lot of tic-tac-to at playgrounds so this will be playground tic-tact-to.

-   How will you use version control to backup / track your project?
Github, I will commit alot.

-   Do you plan to attempt any of the bonuses?
I'd like to make a robot but not sure.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
