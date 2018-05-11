# TO-DO list for the arcade game project


## How the game works:

* There are 2 kind of objects, a _player_ and an _enemy_.
* The player should reach the water using the _up_, _right_, _down_ and _left_ arrow keys.
* The player _should not collide_ into an enemy.
* The enemy should only _move to one direction_ (right) on the pavement only.
* The enemy's should move in _varying speeds_.
* Once a player and a enemy collide the game should _reset_.
* One a player reached the water the player wins the game.


## How to begin:

1. Start with the _app.js_ file
2. **DO NOT EDIT** these files: _styles.css, engine.js, resources.js and the img folder including the images_!
3. - [ ] Add instructions how to load and play the game to the README.md file.
4. - [x] Inside the app.js file, you will need to implement the Player and the Enemy classes, using Object-Oriented JavaScript. Part of the code for the Enemy is provided to you, and you will need to complete the following:

5. - [x] The Enemy function, which initiates the Enemy by:
    * - [x] Loading the image by setting this.sprite to the appropriate image in the image folder (already provided)
    * - [x] Setting the Enemy initial location (you need to implement)
    * - [x] Setting the Enemy speed (you need to implement)
6. - [x] The update method for the Enemy
    * - [x] Updates the Enemy location (you need to implement)
    * - [x] Handles collision with the Player (you need to implement)
7. - [x] You can add your own Enemy methods as needed

You will also need to implement the Player class, and you can use the Enemy class as an example on how to get started.
Make sure the functions you write are **object-oriented** - either class functions (like Player and Enemy) or class prototype functions such as Enemy.prototype.checkCollisions, and that the keyword 'this' is used appropriately within your class and class prototype functions to refer to the object the function is called upon.
At minimum you should implement the following:

8. - [x] The Player function, which initiates the Player by:
    * - [x] Loading the image by setting this.sprite to the appropriate image in the image folder (use the code from the Enemy function as an example on how to do that)
    * - [x] Setting the Player initial location
9. - [x] The update method for the Player (can be similar to the one for the Enemy)
10. - [x] The render method for the Player (use the code from the render method for the Enemy)
11. - [x] The handleInput method, which should receive user input, allowedKeys (the key which was pressed) and move the player according to that input. In particular:
    * - [x] Left key should move the player to the left, right key to the right, up should move the player up and down should move the player down.
    * - [x] Recall that the player cannot move off screen (so you will need to check for that and handle appropriately).
    * - [x] If the player reaches the water the game should be reset by moving the player back to the initial location (you can write a separate reset Player method to handle that).
12. - [x] You can add your own Player methods as needed.

Once you have completed implementing the Player and Enemy, you should instantiate them by:

13. - [x] Creating a new Player object
14. - [x] Creating several new Enemies objects and placing them in an array called allEnemies


### Adding your own

If you would like you can add additional functionality to the game. You can add more code to the app.js file and to the Enemy and Player classes to accomplish that.


### Additional Functionality

In addition to the basic functionality, you can add more cool functionality to your game. For example, here are some additional features that you can add:

* - [ ] Player selection: allow the user to select the image for the player character before starting the game. You can use the different character images provided in the images folder (we’ll get to that below).
* - [x] Score: you can implement a score for the game. For example, the score can increase each time the player reaches the water, and it can be reset to 0 when collision occurs (or it can be reduced).
* - [ ] Collectables: you can add gems to the game, allowing the player to collect them to make the game more interesting.
Anything else you like!


## Project Rubic:

###Game Functions

**Error Free**
The game functions correctly and runs error free
* - [x] Player can not move off screen
* - [x] Vehicles cross the screen
* - [x] Vehicle-player collisions happen logically (not too early or too late)
* - [x] Vehicle-player collision resets the game
* - [x] Something happens when player wins

### Object-Oriented Code

**Object Oriented Code**
* - [x] Game objects (player and vehicles) are implemented using JavaScript object-oriented programming features.

### Documentation

**README**
* - [x] A `README` file is included detailing all steps required to successfully run the application.
**Comments**
* - [x] Comments are present and effectively explain longer code procedures. As a rule of thumb: describe what all custom functions and object methods do.
**Code Quality**
Code is formatted with consistent, logical, and easy-to-read formatting as described in the [http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html](Udacity JavaScript Style Guide).

## Suggestions to Make Your Project Stand Out! (not required)
Provide additional functionality to the game beyond minimum requirements, for example:

* - [ ] Add collectible items on screen
* - [ ] Multiple vehicle types
* - [ ] Timed games
* - [ ] Be creative!




### Resource from Udacity:

[Object Oriented JavaScript](https://classroom.udacity.com/courses/ud015)
[OOJS Notes](https://docs.google.com/document/d/1F9DY2TtWbI29KSEIot1WXRqqao7OCd7OOC2W3oubSmc/pub?embedded=true)
[HTML5 Canvas](https://www.udacity.com/course/ud292)
[Art assets and provided game engine](https://github.com/udacity/frontend-nanodegree-arcade-game)
[Udacity Front End Nanodegree JavaScript Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html)
[Project rubric](https://review.udacity.com/?_ga=1.242571394.1230547285.1451946706#!/projects/2696458597/rubric)
[Student FAQ](https://review.udacity.com/#!/submissions/student-faq)


### Other Resource:

[Front End problemsolving and debugging skills by Cameron Pittman ](https://github.com/ThijsWaalders/README/blob/master/Front%20End%20problemsolving%20and%20debugging%20skills%20by%20Cameron%20Pittman.md)
[Git Cheat Sheet by Roger Dudler](https://github.com/ThijsWaalders/README/blob/master/Git%20cheat%20sheet.pdf)
[Git Merging vs rebasing by Bitbucket](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

[2D Collision Detection](https://developer.mozilla.org/en-US/docs/Games/Techniques/2D_collision_detection)
[How to make a simple HTML5 Canvas game - LDG](http://www.lostdecadegames.com/how-to-make-a-simple-html5-canvas-game/)
[HTML Canvas Reference](https://www.w3schools.com/Tags/ref_canvas.asp)