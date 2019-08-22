# ArcadeTennis
A HTML5 Canvas remake of arcade classic

Arcade Tennis 
Version 1.3.1
Created by Robert Sibek, Bad Mug Games

TODOS:
    - redesign welcome screen. Show logo, add music, maybe some animation (demo play)
    - add difficulty selection
    - redesign paddles
    - add lights
    - add option to play evening match
    - use custom font
    - let player choose the side
    - allow two player game   
    - add screenshot feature (save canvas to image)
    - find/create better texture for playground (more detailed)
    - settings menu for sfx & graphic options (performance scaling)
    - about menu shows game info
    - bad mug logo

KNOWN BUGS:
    - occasionaly ball is stucked at the top or bottom edge of canvas
    - score is counted before ball reach the canvas edge
    
version 1.0
    - basic game mechanic
    - original graphic
version 1.2
    - dynamic ball size 
    - dynamic ball shadow
    - sound effects
    - multiple script files
varsion 1.3.0
    - single file
    - hattrick (ball boost) feature after 3 points in row
    - drawing ball as image function
    - refactoring
    - variables for graphic settings
    - pressing Q will quit to menu
    - pressing P will pause the game
    - receive both uppercase and lowercase keypress is now working
version 1.3.1
    - applause sfx on win screen
    - custom in-games settings:
        R enable/disable retro mode
        S enable/disable shadows
        F enable/disable sounds
        I enable/disable ball image
        B enable/disable dynamic ball size
        D enable/disable debug mode (console logging) 
        P or SPACE pauses the game
        Q quits to main menu
    - fixed static ball size when image is used
