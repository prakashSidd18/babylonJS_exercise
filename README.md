This repository contains code that creates a simple scene in Babylon JS, implementing a set of post-processing effects as listed below.

The code achieves these tasks:
  - Create a simple scene using any model from the internet.
  - Set up postprocessing to make the below effects
    - A kind of “smudge”/ “ghost” effect of the model
    - Selective blur

In practice, these post-processing effects were achieved:
1. Horizontal blur effect: applied globally on the entire scene.
2. Selective contrast enhancement effect: applied selectively on pixel whose intensity crosses a predefined threshold value.
3. Selective directional blur / smudge effect: a per-pixel directional blur effect in vertical direction, applied selectively on pixels following the same criteria as in 2.
4. Negative effect: to invert the color of the given pixel.
5. Time warp effect: to modify the blur radius of a given pixel over time using a sinusoidal function to create time warp effect.

Each of these effect can be turned on/off using the checkboxes provided on the upper-right corner of the screen.
Multiple effects can be checked to create combination of these post-processing effects as well.

The repository is also deployed live on this webpage: https://prakashsidd18.github.io/holition/test/

The link can be accessed on any browser/device.

