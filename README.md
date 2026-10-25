# reviving-colours-opengl
Reviving Colours - an interactive 2D OpenGL/GLUT game in C++ where the player restores color to a grayscale city across four scenes.
# Reviving Colours

An interactive 2D story-driven game built with **C++, OpenGL, and GLUT**. The player controls a hero named Luma through four scenes to find a magic paintbrush and restore color to the grayscale city of Lumina.

Developed as a Computer Graphics course project (CS2206) at **Umm Al-Qura University**, College of Computer Science (2026).

## Team (Group 3)
- Mariya Musab Alhajajy - Intro scene, project setup, scene navigation, user manual
- Ghufran Talal Simbawah - Interactive scene 1: paintbrush, character movement, collision, transformations
- Aseel Abdullah Almatrafi - Interactive scene 2: color restoration, glow and lighting, scaling
- Yara Shadi Al-Ansari - Final scene, textures, report, and presentation

**Instructor:** Dr. Omniah H. Nagoor

## Story
Once, the city of Lumina was full of color and light. One dark day, all colors faded away, leaving the world in shades of grey. Only Luma can bring the colors back.

## Scenes
1. **Intro Scene** - A grayscale city with the story text.
2. **Paintbrush Scene** - Move Luma to collect the magic brush.
3. **Color Restoration Scene** - Collect 3 color drops; the city's colors return gradually with glow effects.
4. **Final Scene** - The fully colored city with sky and ground textures.

## Technical Features
- **Translation** for character movement
- **Rotation** for item animation
- **Scaling** for effects when items are collected
- **Color transition** from grayscale to RGB
- **Collision detection** for collecting items
- **Glow and lighting effects**
- **Textures** applied to the sky and ground
- **Keyboard and mouse input** for movement and navigation

## Controls
| Key | Action |
|-----|--------|
| Enter | Move between scenes |
| Arrow Keys / WASD | Move the character |
| Esc | Exit the game |

## Requirements
- Visual Studio
- OpenGL and GLUT
- C++ standard libraries (`cmath`, `string`, `cstdlib`)

## How to Build and Run
1. Open the project in Visual Studio.
2. Make sure OpenGL and GLUT are configured.
3. Build the project.
4. Click Run. A window titled "Color Revival" will appear.

## Screenshots
Add your screenshots to an `images/` folder and link them here:

```
![Intro Scene](images/intro.png)
![Collecting the Brush](images/brush.png)
![Color Restoration](images/restoration.png)
![Final Scene](images/final.png)
```

## Future Work
- Move from 2D to 3D for more depth
- Add more levels and visual puzzles
- Add background music that changes as colors are restored

## References
- Nagoor, O. H. Computer Graphics Lecture Slides (CS2206), Umm Al-Qura University, 2026.
- Nagoor, O. H. Lab Tasks and Materials (CS2206), Umm Al-Qura University, 2026.
- Nagoor, O. H. CG Project Instructions 2026.
