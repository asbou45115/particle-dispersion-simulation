# Particle Dispersion Simulation

This is an "add-on" script to add onto a html website which creates a trail of "particles" that follow the mouse and can produce great aurora like wave patterns.

https://github.com/user-attachments/assets/76de3905-72f6-441c-a047-9b78e2714967

## Installation

To add this to a html website you can:

Add this to your style (to ensure html elements don't block the script or vice-versa):

```bash
#canvas {
    position: fixed;
    top: 0;
    left: 0;
    z-index: -1;
    background: black;
}
```

Add these two lines into body of html after downloading the js script into directory:

```bash
<canvas id="canvas"></canvas>
<script src="particleDispersionSim.js"></script>
```

You can visit this simulation [here](https://asbou45115.github.io/particle-dispersion-simulation/)
