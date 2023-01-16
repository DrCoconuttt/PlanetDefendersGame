# Planet Defenders

Planet Defenders is a 2D arcade-styled defense game. The player must defend their home planet from incoming projectiles. 

![](https://github.com/DrCoconuttt/PlanetDefendersGame/blob/main/Planet%20Defenders%20Demo.gif)

###### Game Instructions for GUI Version.

1. Defend the planet and Increase your score by destroying asteroids, the goal is to survive as long as possible.
2. If a asteroid hits the planet, you will get hit and lose 1 of 3 lives.
3. Any asteroid that collides with the barrier will be destroyed, click or use tap the screen (if you have a touch screen) to move the barrier.

Asteroid types:
- White: The standard asteroid, just moves towards the planet.
- Green: Starts slow and gradually speeds up.
- Purple: Rotates around the planet while approaching.
- Red: Rare and very fast, when destroyed all asteroids on screen will also be destroyed.

###### How to Run GUI version

1. Install Java and JavaFX
 -Tested with Java 17.0.1.4, which can be downloaded here: https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
 -Tested with JavaFX 19, which can be downloaded here: https://gluonhq.com/products/javafx/ 
2. Download PlanetDefendersGameGUI.jar file found in releases or directly downloaded below:
 -https://github.com/PlanetDefendersGame/pdef/releases/download/1.0/planetDefendersGameGUI.jar
3. Open the command prompt in the directory that contains PlanetDefendersGameGUI.jar
4. Enter: Java --module-path **/path/to/javafx-sdk-15.0.1/lib** --add-modules javafx.controls,javafx.fxml -jar PlanetDefendersGameGUI.jar
Replace the part in bold with the path to the JavaFX.
 
 
 ###### Game Instructions for Text Version
 
1. Increase your score by destroying projectiles, and survive as long as possible.
2. If a projectile gets too close, you will get hit and lose 1 of 3 lives.
3. Type the character of the projectile you want to destroy (Ex. \<A\>).
4. Type \<Reset\> at any time to start over.

###### How to Run GUI version

1. Install Java and JavaFX.
 -Tested with Java 17.0.1.4, which can be downloaded here: https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
 -Tested with JavaFX 19, which can be downloaded here: https://gluonhq.com/products/javafx/ 
2. Download PlanetDefendersGameText.jar file found in releases or directly downloaded below.
 -https://github.com/PlanetDefendersGame/pdef/releases/download/1.0/planetDefendersGameText.jar
3. Open the command prompt in the directory that contains PlanetDefendersGameTexg.jar
4. Enter: Java --module-path **/path/to/javafx-sdk-15.0.1/lib** --add-modules javafx.controls,javafx.fxml -jar PlanetDefendersGameText.jar
Replace the part in bold with the path to the JavaFX.

*Richard Harder, Peter Bignold, Aiden Taylor, Alex Tran, and Nick Zhao*
