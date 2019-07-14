# csc480

Space Ace

Team Members:
Josh Magera, David James, Luis Armendariz, Dani Lopez

Goal: Design architecture in a way that is easy to automate an agent for neural net training.
Controller Package - inputs ported to the model

User Controller: Map user inputs to commands in the game (WASD controls → move function)

AI Controller: Automated controller so the agent can interact with the environment (calls move directly)

Model Package - controller inputs update state and view
Provides the functionality and rules of the game
Pushes controls and randomly generated environment to the view
View Package - display game state
Draws the state of the model for our viewing pleasure

    Controls: R sets player control, N slows down, M speeds up, WASD for player controls.
