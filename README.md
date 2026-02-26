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

