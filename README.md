# Melon Jelly Knife

An interactive material study: pull a soft, spring-simulated watermelon wedge by hand, or choose the knife and draw a stroke to split it into pieces.

## Run it

Open [`melon-jelly-knife.html`](./melon-jelly-knife.html) in a current browser with WebGPU enabled and a compatible GPU. The experiment is a single self-contained HTML file; it uses no external libraries, downloads, or build step. WebGPU is required—if the browser cannot provide an adapter, the page explains why and disables the controls rather than substituting a different renderer.

## Controls

- **Hand:** drag the slice to stretch it; drag empty space to orbit the view.
- **Knife:** select the knife, then drag a line across the slice to animate a cut.
- **Wheel:** zoom the camera; while holding the jelly, change the grab height.
- **Double-click:** reset the camera.
- **N:** nudge; **R:** reset the slice; **K:** toggle the knife; **H:** select the hand; **Space:** pause/resume.
- Use the panel to change the fruit colour, firmness, damping, simulation speed, and mesh display.

The readouts use an illustrative scale (one simulation unit is about 3.5 cm); they are not measurements of real confectionery. This is a visual physics demo, not a food-safety or cutting tool.