# Assignment 4: Cross-Modality UI and Something Fun

In this assignment, you will implement a "fun interactive 3D world" that needs to satisfy a few constraints. As with A2 and A3, you may implement this using any of the 3 environments from Assignment 1 (Babylon.js, Playcanvas Editor, or Playcanvas Engine).  You may reuse any of your code from previous assignments. This template is empty (except for a .gitignore file and this README.md);  you should fill in the project with something similar to 1(a), 1(b), or 1(c) and follow the corresponding instructions for submission.

The goals of the assignment are to 
- implement a simple UI that works reasonably in both desktop 3D and VR (details below),
- implement the VR menu so it "lazily" follows the user's view when visible (details below), and
- have the UI change the scene contents/behaviors and how the user interacts (details below).

What the scene is, how it behaves, and what the user can do in it are up to you.  There are some guidelines and constraints you should satisfy (laid out below and in the rubric) but you are encouraged to do something you find interesting.

## Due: Tuesday November 24th, 11:59pm (midnight)

## Name and GT user-id

Name: 
User ID:
Playcanvas Username (if appropriate): 

## Additional Details 

There are two parts to consider: the menu, and the scene.

### Menu Behavior

All of the 2D UI for this application should fit within a single 2D panel.  In both the 2D view and the VR view, it should be possible to summon and dismiss the menu.

*2D View.*  When the web page loads in the browser in 2D, a small button labeled "Menu" should be on the top edge of the screen, horizontally in the middle of the screen. Clicking it causes the menu to appear in the middle of the screen.  Clicking it again dismisses the menu.  When the window is resized, the button's position and the menu position should be adjusted appropriately (to remain in the middle).  You should be able to interact with the menu appropriately.

*VR View.*  When in VR, the menu should be bound to one of the buttons on the controller (Y or B on the Quest)

![Windows MR system menu](/resources/WindowsMR-menu.gif)


## Rubric

Graded out of 10.

1. Your project runs locally using `npm run start` (1)

Up to two bonus points can be received for doing the following (1 each) enhancements:


# Collaboration

You are free to discuss technical questions and issues in the Teams channels, but the code you submit should be your own.  So, please do not post large chunks of code, but providing pointers to examples or documentation pages or components and methods, along with discussion of how to use them, is fine.

# Submission

You will submit your assignment based on the instructions in 1(a), 1(b), or 1(c) (depending on if you used Babylon, Playcanvas Editor, or Playcanvas Engine, respectively.)

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Material for 3D User Interfaces Fall 2020</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.blairmacintyre.me/3dui-class-f20" property="cc:attributionName" rel="cc:attributionURL">Blair MacIntyre</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

The intent of choosing (CC BY-NC-SA 4.0) is to allow individuals and instructors at non-profit entities to use this content.  This includes not-for-profit schools (K-12 and post-secondary). For-profit entities (or people creating courses for those sites) may not use this content without permission (this includes, but is not limited to, for-profit schools and universities and commercial education sites such as Corsera, Udacity, LinkedIn Learning, and other similar sites).   