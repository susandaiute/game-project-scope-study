# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss on Monday morning.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
  - How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code moodular.
-   What creative spin will you add to your project.
-   How you will use version control to backup / track your project.
-   Do you plan to attempt any of the bonuses.

Wireframes:
https://moqups.com/susandaiute/OS08vY6k

I plan to use HTML, CSS, Javascript and AJAX to build this project.  I will have separate
HTML, CSS, JS and AJAX files in Atom.  Users will need to sign up or sign in first.  Then they
can play the game with a friend, sign out, or update their password.  Player x plays first.
Once a win or a tie has occurred, text with "Player __ Wins" will appear.  A new game
can be started at any time by pressing the New Game button.

Writing the JS will be perhaps the most difficult part.  Or perhaps the AJAX.  For the
JS, I intend to make the game board an array with each cell having an index of [0-8].
Then, I will have a list of winning combinations that will end the game.

I will keep the code modular by writing it semantically and without unnecessary repetition.

User stories:
As a user, I want to be able to register so that I can play the game.
As a user, I want to be able to update my password so I can maintain security
of my account.
As a user, I want to be able to log in and out so I can return to the site to
play more games.
As a user, I want to be able to see how many games I have won so I can track
my progress.
As a user, I want to play against a friend so that I have a better user experience.
As a developer, I want to write code that is functional and readable so that the
product is usable.
As a developer, I want to maintain a development schedule so that the project is
finished on time.

I will keep the code modular by writing it semantically and without unnecessary repetition.

My creative spin will probably involve cartoon cats - if I have the time to add in fun CSS bits.

I will commit frequently and test my code manically.

I will attempt the bonuses if I have enough time, but in the past, I've tended to get stuck in 
a CSS-perfection wormhole.
