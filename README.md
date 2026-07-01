In this project, I used Python's turtle graphics to dynamically generate a 10x10 'Hirst Dot Painting' art piece.
I implemented RGB color mode to handle a custom tuple-based color palette and used the modulo operator within a 
conditional loop to automatically structure the dots into a perfectly aligned grid. The program showcases efficient 
path movement and coordinates manipulation to render generative algorithmic art.

# Generative Hirst Dot Painting (Python)

An algorithmic art generator built with Python's native `turtle` graphics library. This project programmatically recreates the famous "Spot Paintings" style by contemporary British artist Damien Hirst, 
generating a perfectly aligned 10x10 grid of multi-colored dots.

## Features
* **Generative Digital Art:** Automatically draws a 10x10 canvas grid using unique coordinates calculations.
* **Realistic Color Palette:** Utilizes a custom list of extracted RGB values to mimic authentic modern art styles.
* **Randomized Selection:** Uses pseudo-random distribution so that the pattern and arrangement of colors are unique on every single run.
* **Clean UI Visualization:** Hides the drawing cursor and maximizes execution speeds to provide instant visual rendering.

## Technical Concepts Used (What's Under the Hood)
In this project, I implemented several key programming and mathematical logic practices:
* **RGB Color Mapping (`.colormode(255)`):** Configured the graphic engine to read precise RGB tuple structures `(R, G, B)` for detailed color management.
* **Grid Formatting via Modulo Arithmetic (`%`):** Implemented a conditional statement (`dot_count % 10 == 0`) to seamlessly reset the drawing vector and shift up to create a new row after every 10 dots.
* **Vector Heading Control (`.setheading()`):** Manipulated absolute angular directions (0°, 90°, 180°, and 230°) to guide the turtle along a smooth snake-like trajectory across the canvas.

* ## Preview Concept
```text
[ Window Opens ]
-> Turtle instantly shifts to the bottom-left corner.
-> Loops 100 times, placing a random colored dot every 50 pixels.
-> Resets rows every 10 dots to build a flawless 10x10 matrix.
[ Window remains open until clicked ]
```
