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

**Game Impact**: It adds to the overall theme change

**Technical Details**: In the actual object's settings (ex: score label, borders, player boost, obstacles) I changed the colors.

**Known Issues**: N/A


### 2. Change Your Entire Game Concept (3 points)

**Implementation**: I changed the sprites from meteors and a spaceship to pumpkins and a ghost.

**Game Impact**: It changes the concept from a ship avoiding meteorites to a ghost avoiding pumpkins.

**Technical Details**: I just switched the sprites out with some custom ones I made (using the basic shapes).

**Known Issues**: N/A


### 3. Destroy the Borders on Game Over (4 points)

**Implementation**: I removed them when the ghost crashes in the PlayerControll script by setting their visibilty to false on collision.

**Game Impact**: This allows for the obstacles to venture off the map at the end of the game.

**Technical Details**: I sort of described this before, but I just removed the borders in the PlayerControll script.

**Known Issues**: On some aspects the borders don't fully appear..they're cut off on the sides.


### 4. Add Ambient Background Particles (4 points)

**Implementation**: 

**Game Impact**:

**Technical Details**:

**Known Issues**: N/A


### 5. Increase Difficulty Over Time (5 points)

**Implementation**: 

**Game Impact**: 

**Technical Details**: 

**Known Issues**: N/A


### 6. Add Sound Effects and Background Music (5 points)

**Implementation**: 

**Game Impact**: 

**Technical Details**: 

**Known Issues**: N/A


### 7. Animate the Booster Graphic with Audio (6 points)

**Implementation**: 

**Game Impact**: 

**Technical Details**: 

**Known Issues**: N/A


## Credits
- I only used audios provided in the tutorial

## Reflection
**Total Points Claimed**: [Base: 80% + Extensions: X% = Total%]
**Challenges**: [What was difficult]
**Learning Outcomes**: [What you learned]

## Development Notes
[Any additional notes about your development process]
