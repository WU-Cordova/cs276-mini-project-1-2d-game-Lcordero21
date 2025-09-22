# Pumpkin Dash

## Play the Game
**Unity Play Link**: https://play.unity.com/en/games/48eb627f-a9a9-4188-b99d-1ab972eb21b0/pumpkin-dash

## Game Overview
In this silly little game, you play as "Boo the Ghost" who is terrified of pumpkins since they are commonly used on halloween to scare off evil spirits. Be sure to not touch the pumpkins or you might get trapped forever in one! 

### Controls
- For this game you only need the left-mouse button, Boo will follow your mouse as long as you're holding it down.

### How to Play
- Fly around and avoid the pumpkins (and borders)! The difficulty will increase overtime.

## Base Game Implementation

### Completion Status
- [x] Player movement and controls
- [x] Obstacle spawning system
- [x] Collision detection
- [x] Score system
- [x] Game over state
- [x] Audio stuff
- [x] Destroy borders when ghost crashes
- [x] Create new sprites
- [x] Change Color Scheme
- [x] Increase difficulty overtime

### Known Bugs
- The only thing I can really think of it that in the extension where I added ambient background particles, I couldn't quite get it to look like the example. Also, the particles go over the borders...

### Limitations
- I wanted to add the high score extension, but I was kind of confused by the instructions.

## Extensions Implemented 

### 1. Create a Cohesive Color Scheme (2 points)

**Implementation**: To create the color scheme, I just went with typical Halloween Colors: "Purple, Green, and Orange"

**Game Impact**: It adds to the overall theme change.

**Technical Details**: In the actual object's settings (ex: score label, borders, player boost, obstacles) I changed the colors in the inspector window.

**Known Issues**: N/A


### 2. Change Your Entire Game Concept (3 points)

**Implementation**: I changed the sprites from meteors and a spaceship to pumpkins and a ghost.

**Game Impact**: It changes the concept from a ship avoiding meteorites to a ghost avoiding pumpkins.

**Technical Details**: I just switched the sprites out with some custom ones I made (using the basic shapes) and added a new rigidbody and collision2d to them.

**Known Issues**: N/A


### 3. Destroy the Borders on Game Over (4 points)

**Implementation**: I removed them when the ghost crashes in the PlayerControll script by setting their visibilty to false on collision.

**Game Impact**: This allows for the obstacles to venture off the map at the end of the game.

**Technical Details**: I sort of described this before, but I just removed the borders in the PlayerControll script.

**Known Issues**: On some aspects the borders don't fully appear..they're cut off on the sides.


### 4. Add Ambient Background Particles (4 points)

**Implementation**: I added ambient particles in the background.

**Game Impact**: It just adds to the visuals overall of the game, I like to think of it as little ghost sparkles.

**Technical Details**: I created a new particle system and adjusted it according to the dimensions of the screen, I also used the alpha scale (I think that's what it is called) to adjust the color so it fades in and out. The particles also disperse into seperate direction.

**Known Issues**: The particles don't quite look like the example, and the particles go over the borders rather than behind them.


### 5. Increase Difficulty Over Time (5 points)

**Implementation**: The obstacles will steadily get faster and faster the more it bounces off of things.

**Game Impact**: It adds more of a challenge to the game.

**Technical Details**: In PhysMat_Bouncy I changed the bounciness from 1 to 1.1

**Known Issues**: There is no cap of the speed of the obstacles, so eventually it will become impossible.


### 6. Add Sound Effects and Background Music (5 points)

**Implementation**: I used the given audio files in the tutorial to implement background music and a crash sound effect.

**Game Impact**: It enhances the game experience (although, I didn't change the audios after changing the theme because I thought the huge explosion sound is so out of place for a ghost crashing, but I find it kind of funny)

**Technical Details**: I made a new assets folder and called it "Audios", adding all the audios in this folder. I then added the background music as its own element in the hierarchy, while I assigned the explosion audio to the explosion particle effect as an audio source (turning down all the audios as needed).

**Known Issues**: N/A


### 7. Animate the Booster Graphic with Audio (6 points)

**Implementation**: When the booster graphic is activated on the ghost, a sound will play.

**Game Impact**: It's a nice little touch to the game experience, similarly to the other sound effects.

**Technical Details**: In order to do this, I saved the audio to my audios folder. I then attatched the booster audio to the actual BoosterFlame (and turned down the audio a bit), so it will activate when the booster is activated.

**Known Issues**: N/A


## Credits
- I only used audios provided in the tutorial

## Reflection
**Total Points Claimed**: [Base: 80% + Extensions: 20% = 100%] [Total extension points claimed: 29 pts.]
**Challenges**: [I didn't have much difficulty with this project, it just took me awhile to actually sit down to do it (which is no fault of the game, it's just a me thing]
**Learning Outcomes**: [Honestly, there is so, so much that I learned. I learned a bit of the coding but a ton about how to build a basic 2D game with elements that can interact with eachother]

## Development Notes
Not really, I did realize the game is really laggy on the web version, but I don't know how to fix that...
