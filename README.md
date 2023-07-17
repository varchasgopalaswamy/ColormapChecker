# ColormapChecker
A jupyter notebook to see how good your colormaps are. 

The Buddhabrot generation code comes from https://loiseaujc.github.io/Scientific_Computing_on_a_Laptop/Maths/Mandelbrot/buddhabrot.html. The default samples are 10^7, but you may want to pull that down if it takes too long.

The test cases come from http://inversed.ru/Blog_2.htm. 

1. Sine Ramp: Linear ramp in y with sine wiggle intensity increasing in x.
2. Z ordering: Interleaved squares. You should see 3 levels of subdivision
3. XOR: Interleaved squares. You should see 4-5 levels of subdivision
4. Sprial: Interleaved spirals. The thickness of the two spirals should be the same and the transition to from min to max should be smooth
5. Sine product: Smooth transitions between extrema
6. Fractal: Should be able to resolve fine features, and should be symmetric
