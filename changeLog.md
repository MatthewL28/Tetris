# Tetris changelog

<br>

## Update 1.2 - Statistics & Gameplay Update

#### Bug fixes
- Fixed T-Spin calculations
- Fixed glitch where mute and minimize keybinds could only be clicked in game
- Game now resizes when window size changes
- All themes now show the drop preview by default (including NES)

#### Theme adjustments
- Adjusted the NES and Retro themes to match the same layout of the other themes
- Removed the weird block boarder from NES and Retro theme

#### New piece spawn mechanics
- Pieces spawn above the gameplay area so that they can be moved before entering play
- Pieces that spawn above the gameplay area are not themselves visible, but their drop preview is
- There is now a section at the top that shows a picture of the current piece in play (this still shows the current piece evern if it hasn't entered gameplay yet)

#### New small features
- Added reset to default button in settings (with warning promot)
- Added keybind presets (default, tetr.io)
- Added a keybind to rotate counter clockwise

#### New settings
- New settings dropdown labeled "gameplay" with the following items
    - Option to hide/show the drop preview (default: enabled)
    - Option to rotate hard drop (default: disabled)
    - Option for how many "next" items to show (default: 5, max: 5, min: 0)
    - Option to enable/disable current game drop statistics (default: enabled)
    - Option to enable/disable the current piece preview (default: enabled)

- New settings dropdown labeled "Difficulty" with the following items
    - Option to endable/disable holding (default: enabled)    
    - Option to change start level, can only be changed in main menu (default: 1)

#### New statistics
- Added a statisics tab in home
- Game now has a statistics.txt file that logs the following

    ### Total accross all games
    - Total lines cleared
    - Total score (shortened)
    - Total blocks placed
    - Total of specific blocks placed (I, O, T, S, Z, J, and L)
    
    ### Highest in a single game
    - Score (only #1)
    - Lines cleared
    - Level reached
    - Blocks placed
    - Specific blocks placed (I, O, T, S, Z, J, and L)



## Update 1.1 - Custimization Update
- Uploaded to GitHub for easier downloading
- Added many more themes
- You can now change keybinds in game
- Fixed bug where old theme stays when switching to a new theme
- Added music start and end offsets



## Release 1.0
- A few basic themes
- Had a functional settings menu
- Working music
- Fully functional game



## Beta 0.3
- Added home screen
- Encrypted score
- Hacker theme
- Basic settings menu



## Beta 0.2
- Fixed bug with S and Z block rotation
- Fixed file linking



## Beta 0.1
- Game was mostly functional