# DodgeBall_Checkpoint
//this is my goal
Make Players, add them to a bracket, extend their class, place them on teams, then tests and a GUI

here is my process
start from scratch
Create a class constructor for all the players who will join the game
give the constructor name, gander, age, height
Have that constructor place each new player into a standby array, moving them to the next phase to be place on teams
look at austins code and realize there is more required for the assignment
copy starter code and start over
look at starter code and figure out what I am working with
set up class constructor
set up extended player constructor
take players off listOfPlayers array when the "Make Player" button is clicked
bug test and fix with examples
create a random array of player attributes and randomize the players joining
make an on/off button for placing dodgeballplayers on teams red/blue
button should extend their current class to add a color team and a mascot
when clicked, remove them from their current array, and put them on a team array
Build test with mocha or chai, or at the very least write some psuedocode to test code
when everything works, hook the rest up to a GUI
Bug test





20pts - Code Plan - Include this in a README.md file in your folder with comment in your code.
20pts - Can add People to Players - When clicked the people are added to the Players column and removed from the People list while getting new values of a player added to them.
20pts - Can add Players to different Teams - When we click on the blue button the Player is added to the blue team and removed from the Player list while also getting the keys color and mascot extended to them when they are moved to a team.
20pts - Uses class - This is not a hack job. You should use class to add the new properties you need and extend when you need.
20pts - Minimum 3 Unit Tests - Use Mocha and Chai to give us at least 3 unit tests that prove a person becomes a player and a player becomes a teammate.

Work through the follow challenges:
Use the class keyword to create a template of a dodgeBallPlayer that requires canThrowBall, canDodgeBall, hasPaid, isHealthy, yearsExperience.

Push these new dodge ball Player objects into a new array and then display them in the DOM as available players to pick.
******
Add a button to each new player that will allow each one to be selected for either Blue Team or Red Team and now has mascot and teamColor

Use the this keyword to assign each player to a team with an onclick. Assign them to either Blue Team or Red Team.

Display the two teams in a new list in the DOM with appropriate titles.
Create 3 tests for your application.