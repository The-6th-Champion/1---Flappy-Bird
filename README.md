# 1---Flappy-Bird

This is my first game

This is also my first game in python using pygame

So...the game is done.
It turned out pretty well
Yall can now install it.
It is pretty easy

## Installing
you can 1, install all of the files in this repo, and then run the main.exe

### or

Click this download link for the installer: [Flappy Bird Installer](https://doc-0c-7o-docs.googleusercontent.com/docs/securesc/h3ls8aledk7shkacbpb34j4cld6vfinj/1dfmdb96duuau4jlsd20369jm1q5d85s/1612914450000/00797817819262636083/00797817819262636083/1w6Vpe9Uei3yrjR9aMobESlhfSH4BBWXs?e=download&authuser=0&nonce=rdgqsp725dohi&user=00797817819262636083&hash=9fhef7a1l4ntdj64a64c1aeapv803bjm "Installer for The 6th Champions Flappy Bird game")
Then, run the installer to install the file, and open the folder that is made. then press main.exe to play.

NOTE: This may create anti-virus messages to pop up, and the file may be blocked because it is an executable file from an unknown source. I assure you I didn't put viruses in that executable file.

## Editing the game
If you are a programmer and want to play around with some settings, go ahead (but do it on a local file, not here).
Here are some things you may want to try:
1. Jump Height
  - find a place in the file where it has 
  ```py
  if event.type == pygame.KEYDOWN:
            if event.key == pygame.K_SPACE and game_active:
                bird_movement = 0
                bird_movement -= 6 #this is the spot you edit
                flap_sound.play()
   ```
   
   change the `6` to something bigger or smaller to make your jumps bigger or smaller
2. Bird Color
  - To Be added :)
> Note: This was made using [this](https://youtu.be/qJ94sSyPGBw, "Learning pygame by making Flappy Bird By Clear Code") tutorial from youtube
