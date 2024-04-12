# MIPS Da3 Shady
## CSC 312 (Computer Architecture)
### Notre Dame University
#### Completion date: 13 May 2023

## Notes:
This project was an assignment done by a group of 2.
<br>"DA3 SHADY" is in Arabic and it means "Shady is lost".
<br>It was implemented on "MARS".

### Story of the Game:
Shady needs to find his family. He must jump through the platforms to reach them. Can you help him?
<br>The game is inspired by Fayrouz’s Hit song “Shady” (The refrain of the song is "Da3 Shady")
["Da3 Shady" song](https://youtu.be/D7AjOZctfTA)

### Running The Game:
Make sure to have the "Bitmap Display" connected to MARS with the configuration above along with the "Keyboard and Display MMIO simulator".

### Bitmap Configuration:
- Unit width in pixels: 8
- Unit height in pixels: 8
- Display width in pixels: 256
- Display height in pixels: 256
- Base Address for Display: 0x10008000 ($gp)

#### Playing The Game:
- Press “D” to move right.
- Press “A” to move left.

<code style="color : red">**IMPORTANT WARNING**:</code> Don’t Hold/Long press A or D because MARS will crash.
- Don’t fall off the platforms or you’ll fall in the lava which will kill Shady.
- The platforms get smaller with time.
- Score will be displayed at the top left while in the game, and the end score will also be displayed at the end, along with the hit line of the song “Da3 Shady” with its music.

### How the Work was split:
Difficulty updates with the related procedures were done by both of us.

#### Anthony Lahoud ([Anthonylhd2](https://github.com/Anthonylhd2)):
- Game Score Display
- Game Score Calculation
- End score Display
- End Message Display
- Background Color
- End of the program (Death of player)

#### Anthony Nasry Massaad([AnthonyNMassaad](https://github.com/AnthonyNMassaad)):
- Sprite and its movement
- Music
- User Input
- End Background (Lava)
- Lava at the bottom of the screen
- Platforms
