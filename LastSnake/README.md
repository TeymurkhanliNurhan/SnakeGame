# SnakeTry
Planning:
Game Features Definition:
Users can specify the map size and their name.
Snake moves at a constant speed of 1 square per second.
Snake cannot pass through walls.
Database will store user's name, map size, and points earned (1 point for each lengthening of the snake).

User Interface Design:
Design interface for inputting map size and name.
Display game board with appropriate dimensions.
Show user's name and current score during gameplay.

Game Mechanics Design:
Define snake movement mechanics.
Implement collision detection with walls.
Determine scoring system and how points will be calculated.



Testing:
Unit Testing:
Develop unit tests for core functionalities: snake movement, collision detection, and score calculation.
Verify that the snake moves correctly, detects collisions with walls, and updates the score accurately.



Proof of Concept (POC):
Basic Game Implementation:
Develop a basic version of the game to demonstrate core mechanics.
Implement user input for map size and name.
Create a simple game board with a snake that moves at a constant speed.
Add collision detection with walls and basic scoring mechanism.



Replanning + Database Integration:
Refinement of Game Features:
Revisit initial planning based on POC feedback and add any necessary features or adjustments.
Refine user interface elements and game mechanics for better usability and experience.

Database Integration:
Integrate a database to store user data, including name, map size, and points earned.
Implement functionality to update and retrieve user scores.



Containerization:
Container Setup:
Containerize the game application using Docker or similar technology.
Package the game and its dependencies into a container for easy deployment and scalability.



Deployment:
Basic Deployment Setup:
Deploy the containerized game application to a hosting platform.
Set up a basic web interface to allow users to access and play the game via a web browser.

Testing Deployment:
Conduct testing to ensure the deployed game functions correctly in a web browser environment.
Verify that user inputs are processed accurately and game mechanics operate as intended.

Final Deployment:
Once testing is successful, finalize deployment of the game application.
Make any necessary adjustments based on user feedback or performance issues en
