# Garfunkel - my first personal gamedev project

The game only has 1 scene - a black circle with 4 subsections, each a quarter of the circle. each will be a different color (pick colors that work for color blindness, but also the rest of the game will work even it you can't see color at all). Internally have an ArrayList to store state. The game will add a random int to the list in the range [0,3], with each one representing a section of the circle. Then I'll animate it by "flashing" that quadrant, which will just a color change to make it brighter. Then the player gets control and they'll press keys (wasd) to repeat the right flash. I'll then add another random number, play the first number again, then the new one, then give control back. The player must repeat both in order this time. This process will continue until the player fails to recreate the full pattern. You score is the number of correct guesses before failure.


### Possible extensions

- You can click the circle sections in addition to using wasd
- Add score multipliers for speed.
- Add sounds
- Use a gradient or other material (is that the right term? I'm thinking some kind of texture) when lighting up the sections to make them prettier.
- Add options for things like how long the sections stay lit up for, if there's a pause between them, etc.

### Stretch extension:

- Add a second circle with sections and have both circles light up independently, with separate keyboard shortcuts for each, and have them both happen simultaneously (but not even necessarily synced together).
