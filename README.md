# Project 1: Plotting Tiles

## How to Run the Program

1. Download the HTML file.
2. Open the file in a web browser.
3. The image will automatically generate on the screen.

## Design Choices

The artwork is constructed using a repeating tile template consisting of:

- An outer white frame
- A thick vertical bar
- A thinner horizontal bar
- A corner square

All tiles are generated from the same blueprint to maintain consistency.

Tiles are randomly assigned one of four rotations:

- 0°
- 90°
- 180°
- 270°

The design uses a limited color palette to avoid too much chaos:

- Blue
- Pink
- Green
- Yellow

White is used for the frame outline.

## Adjustable Parameters

The following variables can be modified to change the artwork:

- COLS - Controls the columns across the canvas. Increasing this value makes tiles smaller and the pattern denser.
- rotations array - Controls allowed tile rotation angles.
- COLORS array - Controls the color palette of the tiles.
- Stroke scaling percentages - Adjust line thickness relative to tile size.

## Reflection 
Working on this project helped me understand how tiling can be used to create art in a structured way. One of the harder parts was making sure the contents of the tiles were still clearly visible when I changed the grid density, because I didn’t want the pattern to look weird or break visually. Using SVG templates and scaling the strokes relative to tile size helped keep everything balanced. Another hard part was actually deciding what I wanted to make because as I was doing research everything just looked boring and it was the same thing over and over again. Eventually, I did find a vibe that I liked which inspired this piece. I wanted to go for an electronic board type thing you would see in puzzles within games. Other than that, I liked seeing how small rules like rotation and color selection could still create something interesting without making the design feel random or messy. Overall, this project showed me how SVG art can be both technical and creative.



