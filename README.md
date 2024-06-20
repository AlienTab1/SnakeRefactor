# SnakeRefactor
Simple CMD line snake game refactoring, school project.
Source: https://codereview.stackexchange.com/questions/127515/first-c-program-snake-game

1st step - Naming and variables usage
- camelCase and PascalCase naming convention
- variable redefinition and sort
- add "using static System.Console;" to remove Console. directive

2nd step - split to functions
- fuction for DrawPixel, DrawBorder and ReadMovement
- directions as enumerator

3rd step - split logic and output layer (preparation for GUI adaptation)


New Class kept intentionally in one file for future use with Godot engine. 

