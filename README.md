# Turn based combat with dynamic mechanics
A prototype of gameplay for an RPG game in which players have to move their team in order to perform more powerful attacks and to evade enemy attacks.

The initial idea is a mix of Chrono Trigger with Undertale in 3D, in which each attack is a minigame which consists in moving characters around the screen to avoid or do damage. This game has some influence of Arkanoid and PONG in how attacks can bounce between characters to do more damage to enemies.

# Current state:
The player can move 4 characters around an enemy to evade its attacks.

The player has 3 attacks: 
- Piercing ball (that piercess if the enemy is the same colour as the attack)
- Bouncing ball (That bouncess if the enemy is the same colour as the attack)
- Colourless attack (Makes the enemy colourless for attacks to act as if the enemy was the same colour as the said attacks)

This video ilustrates the three attacks and how they interact with the colour mechanic. The yellow cube has two attacks per turn and the enemy just shoots a ball without aiming.

**Blue:** Piercing ball. **Yellow and Red:** Bouncing ball. **Green:** Colourless attack 
![](https://thumbs.gfycat.com/NewQuestionableAltiplanochinchillamouse-size_restricted.gif)


Enemy's attack patterns:

![](https://thumbs.gfycat.com/BetterLimpingCanary-size_restricted.gif)

# Next to do:

- 4 different levels
- To optimize Bouncing Attack for it to not miss their target after bouncing.
- An understandable GUI
- A way for the player to see which button represents each character.
