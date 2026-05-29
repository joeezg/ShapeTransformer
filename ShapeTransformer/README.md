# Shape Transformer

Small Blazor app for a pre-interview technical exercise.

## What it does

The page is split into four quadrants:

- Top Left: Circle
- Top Right: Hexagon
- Bottom Left: Square
- Bottom Right: Triangle

Five circles start in the top-left quadrant. Dragging a shape into another quadrant moves it there and changes its appearance.

## Stack

- C#
- Blazor Web App
- Basic HTML/CSS
- Native browser drag-and-drop events

I used Blazor because the exercise allowed any stack and my strongest production experience is in C#/.NET. This allowed me to focus on state modelling, event handling, and clean component structure rather than spending the exercise learning an unfamiliar frontend framework.


## How to run

Open the solution in Visual Studio and run the project.



## Trade-offs

I kept the implementation intentionally small. I used CSS for the visual shape transformations and simple in-memory state instead of backend APIs, or external libraries. 

I kept the layout simple because the requirement was for typical laptop usability rather than full mobile optimisation.

I did not add a separate mobile layout or advanced responsive behaviour.

With more time, I would add unit/component tests, improve keyboard accessibility, add clearer drag/drop visual feedback, and refine responsive behaviour.

## References
- Microsoft Learn: Build your first web app with Blazor
- Microsoft Learn: ASP.NET Core Blazor event handling
- MDN: Basic concepts of CSS Grid layout
- MDN: HTML Drag and Drop API
- MDN: CSS clip-path
- MDN: CSS polygon()