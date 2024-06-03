# ICG - Night City

## Description
This Three.js web application is a 3D model of an urban city, with a focus on the night time, particularly the lighting. The city is made up of a variety of buildings, with different shapes and sizes, some nature elements and a few cars. There is a day-night cycle, with the city lighting up at night. The user can observe the city from afar, using both Perspective and Orthographic cameras, and can also move around the city using the First Person camera. There are movement mechanics implemented, such as collisions, sprinting, stepping and double jumping.

## Controls
- **Mouse: Look** around
- **W, A, S, D**: Move
- **Space**: Jump
- **Shift**: Sprint
- **P**: Change camera
- **R**: Reset cameras besides FPS
- **H**: Show/Hide controls box

## What was added
This is a list of the features or improvements that were added to the project after the final presentation:
- Cleaned up the repository, removing around 115000 lines of text (mostly on models)
- Improved lighting performance issues, although there is still a small lag spike when the lights turn on (even though it only happens the first time)
- Fixed the step mechanic, which was not working properly when steeping from the ground to the street
- Added static boundaries to the city, so the player can't leave the city
- Added player collisions with the environment, so the player can't go through buildings or other elements
- Added more decorations to the city, such as trees, rocks and a parking lot
- Added this README file
- Added vehicle variety to the city, and the moving car has a chance to change its model
- Added controls box to the screen, showing the player the controls
- Added video to the project page, showing the project in action

## [Project Repository](https://github.com/Sytuz/ICG)

## [Project Page](https://sytuz.github.io/ICG/)

## [Video](./videos/NightCityVideo.mp4)

## Author
- Alexandre Ribeiro (108122)

## Credits
- [Three.js](https://threejs.org/)
- [Blender](https://www.blender.org/)
- [Kenney Assets](https://www.kenney.nl/)
- [Day-Night Cycle (Altered by me, to add shadows and remove certain properties)](https://github.com/jeromeetienne/threex.daynight)
- [First Person Controls (Heavily altered by me)](https://threejs.org/examples/misc_controls_pointerlock.html)
- [Grass Texture](https://ambientcg.com/view?id=Grass003)