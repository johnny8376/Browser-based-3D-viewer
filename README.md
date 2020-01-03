# Browser-based-3D-viewer
Render 3D secene based on user's perspective.

Area: Computer Vision, COmputer Graphics

## Why we need this project?
Presenting the power of person tracking for 3D visualization. When you look through a window and moving around, you was able to tell how far are objects by their relative movement. Like normal 3D games, the viewer give users the sense of 3D world based on the movements not the actual distance.

## Why don't you lose depth perception when closing one eye?
https://www.quora.com/Why-dont-you-lose-depth-perception-when-closing-one-eye

## Key steps:
1. 3D scene: example from three.js
2. user tracking: Posenet
3. stablization: Kalman Fiter
4. render warping: WebGL, vertex shader

## Render Details:
3D object --obsereved by--> camera --project to--> virtual screen --warp to--> real screen --seen by--> user
|--------------------existed library---------------------|======this project=======|--------your job--------|
1. Estimate relative position of user and virtual screen.
2. Display necessary part to screen.

## Milestone:
1. Done
2. Done
3. Done
4. Before 2020.01.05.
