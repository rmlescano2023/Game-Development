# Game-Development

### This is a repository for Game Development (CMSC 197) laboratory exercises using Unity.

<br>

## Machine Problem 1

**Instructions:**
1. Download and Import Challenge 1 - Starter Files from Unity: Create with Code: https://bit.ly/49lcIkA
2. Follow the instructions in the Create with Code page to “fix” the Plane Flying game.
3. In addition to the fixes, implement the following requirements:
* An accompanying Zip File will contain a sample of the Plane Game. You may use this as reference for the additional requirements.
* Camera must be positioned behind the plane similar to the driving simulator and should follow the plane while it flies around. Hint: This does not require coding.
* The Plane should still move at a constant pace, however, we will add changes to the movement controls.
* The Plane should be able to tilt and turn to left or right depending on user input. You may use the Horizontal Axis for this.
* Create additional obstacles for the Plane/Player to go through. These should includea moving obstacle and one turning/rotating obstacle. You could also use a combination of both. This is where you should get creative!

<br>

## Machine Problem 2

**Instructions:**
1. Using the Assets from Unit 2: Basic Gameplay, create a game that is similar to the attached file Playing_Fetch.zip.
2. Specifications:
* Dog: the player should be able to control the dog with arrow keys or WASD control.Using the left joystick of a controller is also acceptable. The dog should be able tomove up, down, left, and right depending on the input of the user. Rotate the dogaccordingly. Hint: You may use transform.LookAt()
* Farmer: this game object will simply throw a Ball game object in the beginning of theexecution. The direction, distance, and when to throw are at random withminimum and maximum values. The farmer may not throw a Ball if it does not haveit in it’s possession.
* Ball: when the Ball is thrown, the Dog should be able to fetch it. Once caught orfetched, the ball should follow the Dog’s position and the Dog should be able toreturn it to the Farmer. Once returned to the Farmer, it should be thrown again forthe Dog to fetch.
3. You may add your own creative twists to this activity but the main specifications shouldbe followed. Enjoy!

<br>

## Machine Problem 3

**Instructions:**
1. Using the Assets from Unit 3: Sound and Effects and Challenge 3: Balloons, Bombs, &Booleans, create a game that is similar to the attached file Machine_Problem_3.zip.
2. Specifications:
### Player:
* Player will use a humanoid (farmer or city worker) sprite
* Player can do the following inputs:
> Jump: Press Spacebar to make the player jump. Utilize Rigidbody Physics.2. Crouch/Slide: Press the Down Arrow Key or S key to make the Player Slide. You may change the size of the collider here or have 2 different collidercomponents which you can turn on or off. Other approaches would also bewelcome.
* There are a bunch of animations that are given along with the sprite. Makesure to select the appropriate animation for each action. You may change, add,or manipulate the animation parameters as well as the animation map toachieve what you want.

### Background and obstacles:
* Background and obstacle must be proceduraly generated. It must seem thatthe background is seamless.
* Obstacles must also be procedurally generated.
* There must be at least 2 types of obstacles. One which the player can jumpover, and one that the player can crouch to avoid.
* Make sure that the player has a “way-out” of every situation. There should beno obstacle that is impossible for the player to avoid or get through.
* Nice to have: background and obstacles have the same theme. i.e (wildernessand tree branches, suburban area and fences, etc).

### Powerups:
* Create at least two powerups. The Balloon and the Bomb.
> The Balloon will allow the player to do a second jump or carry the playerupwards a second time. This cannot be used while on ground. In the example, the balloon will attach itself to the player once picked up. This move is bound with the Spacebar/Jump Key.
> 
> The Bomb will allow the player to throw it to destroy obstacles and/or anyother game objects (including powerups). When thrown by the player, thebomb explodes and destroys everything (excluding the player, ground, andbackground) in a certain radius. This may only be performed when on theground. This move is bound to the Fire key (left mouse click).In theexample, the bomb is carried by the player on its right hand when pickedup.
* When not picked up, the powerups bomb in the air. You may also add certain visual effects to emphasize that they are to be picked up.
* In the example, only one of each type can be picked up at a given time, theothers are destroyed. However, you may change this to have multiplepowerups of the same type at a time!

### Sound and Particle effects:
* Game must have a background music.
* Apply appropriate sound and visual effects.
* Other visual effects can be made or imported as long as you understand how it works.

<br>
3. Be creative!
* Explore the animator, particle effects, and sound effects as well as different gamemechanics and simple physics.
* You can get wacky and creative with your output but it should have the above requirements in the end product.
* If you can, you may improve on certain aspects of the game as well!

<br>

## Machine Problem 4

**Instructions:**
1. Using the Assets from the Unity package that comes along with this file(MP4.unitypackage), create a game that is similar to the attached zip file, MP4_Whack-aZombie.zip. Download and extract the zip file to play the attached game.
2. Specifications:
### Player Controls
* The player must be able to select the difficulty or intensity of the game fromthe title screen.
* The player will use left mouse click to defeat a ghoul that rises from the grave.iii. Points can be gained from every ghoul defeated.
### Ghouls:
* 3 types of ghouls can be spawned from the 15 graves in the graveyard.
* Depending on the difficulty/intensity of the game, a number of ghouls can popup at a time. In the given example, WHACK! Will spawn 1 ghoul every 2.5 ~ 3seconds. WHACK!! spawns 2 every 2.5s ~ 3s and WHACK!!! spawns 3 ghoulsevery 1.5s ~ 2s.
* Ghouls will only start spawning after the player clicks on a specificdifficulty/intensity.
* Ghouls can only be defeated within 60 seconds, after which they cannot beclicked on and they will stop spawning.
* Ghouls may only spawn at a grave that is not occupied by another ghoul.
* Ghouls should have varying score values when defeated. In the example, theVampire provides 3 points while the skeleton and zombie provide 1.
* Ghouls return to the grave after 3 seconds after spawn. You may choose tomake this time shorter.
* Dirt particle effects should be played whenever the ghoul rises, dies, or goesback to the ground.
### UI Elements
* Start screen should have the title of the game and 3 buttons to select from.These buttons will dictate the intensity of the game.
* Score and time should show up after the game begins. The score should beupdated whenever the player defeats a ghoul. Time should be updated everysecond.
* After the time is over, the game over screen will be displayed and the scoreand time displays should disappear. A restart button should also be shown thatrestarts the game back to the title screen when clicked.

3. Be creative!
* Explore the animator, various fonts, and various sprites that can be used for thegame.
* You may import fonts directly to unity by dragging it to the project explorer window.You can then transform these fonts to font assets that can be used by text meshpro.
* You can find more sprites from the unity store or from kenney.nl. The assets used inthe package are from kenney after all.


<br>

## Prototype 1

This prototype...

<br>

## Prototype 2

This prototype...

<br>

## Prototype 3

This prototype...

<br>
