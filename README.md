# Final Project: Infinite
![coding1.png](https://github.com/Yvonne202202/Coding1/blob/a6eaec6308d069bc687b76fc5bb51390ed312a01/coding1.png)
MIMIC: https://mimicproject.com/code/2fc91290-133d-02e8-00de-3cff5bf5ab36

Please use Safari to open it (Google Chrome does not load properly).
## Project brief
The project incorporates technology from Sound and Signal processing and 3D graphics.

## Sound Part
* Three maxiSample objects are created using the Maximilian library, which are beat, loop, and chord. 

* The maxiSample.play() function was used to create different condition triggers and so on to manipulate the sound. 
* To make the sound more distinctive, the method sinewave() in maxiOsc is used. 
* The clock speed is set to 120 by using setTempo(). And the number of beats is set to 4 by setTicksPerBeat().
* The maxiClock system is also used. Call ticker() inside the play() function to advance the clock.
The song() function is created and the conditional statement and modulus % are used in it to produce a more interesting rhythm.

## 3D Graphics
Basic perspective projection is used. 
* The x, y, and z coordinates are used to create the basic 3D graphics. 
* The 3D model is a sphere of points with a ring number of 80.
* CanvasRenderingContext2D.CreateRadialGradient() is used, and through in which access to the mouse parameters for interaction of graphics and the gradient effect.

