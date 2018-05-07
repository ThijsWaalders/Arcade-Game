# TO-DO list for the arcade game project

## How the game works:

* There are 2 kind of objects, a _player_ and an _enemy_.
* The player should reach the water using the _up_, _right_, _down_ and _left_ arrow keys.
* The player _should not collide_ into an enemy.
* The enemy should only _move to one direction_ (right) on the pavement only.
* The enemy's should move in _varying speeds_.
* Once a player and a enemy collide the game should _reset_.
* One a player reached the water the player wins the game.

# How to begin:

1. - [ ] Start with the _app.js_ file
2. - [ ] **DO NOT EDIT** these files: _styles.css, engine.js, resources.js and the img folder including the images_!
3. - [ ] Add instructions how to load and play the game to the README.md file.
4. - [ ] Inside the app.js file, you will need to implement the Player and the Enemy classes, using Object-Oriented JavaScript. Part of the code for the Enemy is provided to you, and you will need to complete the following:

5. - [ ] The Enemy function, which initiates the Enemy by:
    * - [ ] Loading the image by setting this.sprite to the appropriate image in the image folder (already provided)
    * - [ ] Setting the Enemy initial location (you need to implement)
    * - [ ] Setting the Enemy speed (you need to implement)
6. - [ ] The update method for the Enemy
    * - [ ] Updates the Enemy location (you need to implement)
    * - [ ] Handles collision with the Player (you need to implement)
7. - [ ] You can add your own Enemy methods as needed

You will also need to implement the Player class, and you can use the Enemy class as an example on how to get started. At minimum you should implement the following:

8. - [ ] The Player function, which initiates the Player by:
    * - [ ] Loading the image by setting this.sprite to the appropriate image in the image folder (use the code from the Enemy function as an example on how to do that)
    * - [ ] Setting the Player initial location
9. - [ ] The update method for the Player (can be similar to the one for the Enemy)
10. - [ ] The render method for the Player (use the code from the render method for the Enemy)
11. - [ ] The handleInput method, which should receive user input, allowedKeys (the key which was pressed) and move the player according to that input. In particular:
    * - [ ] Left key should move the player to the left, right key to the right, up should move the player up and down should move the player down.
    * - [ ] Recall that the player cannot move off screen (so you will need to check for that and handle appropriately).
    * - [ ] If the player reaches the water the game should be reset by moving the player back to the initial location (you can write a separate reset Player method to handle that).
12. - [ ] You can add your own Player methods as needed.

Once you have completed implementing the Player and Enemy, you should instantiate them by:

13. - [ ] Creating a new Player object
14. - [ ] Creating several new Enemies objects and placing them in an array called allEnemies


### Adding your own
If you would like you can add additional functionality to the game. You can add more code to the app.js file and to the Enemy and Player classes to accomplish that.


### Additional Functionality
In addition to the basic functionality, you can add more cool functionality to your game. For example, here are some additional features that you can add:

* - [ ] Player selection: allow the user to select the image for the player character before starting the game. You can use the different character images provided in the images folder (we’ll get to that below).
* - [ ] Score: you can implement a score for the game. For example, the score can increase each time the player reaches the water, and it can be reset to 0 when collision occurs (or it can be reduced).
* - [ ] Collectables: you can add gems to the game, allowing the player to collect them to make the game more interesting.
Anything else you like!

