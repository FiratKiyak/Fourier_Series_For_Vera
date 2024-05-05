This project is inspired by Mathologer and 3Blue1Brown videos about Fourier
series. The Fourier series of a closed loop in the plane can be thought of
as if the loop is being drawn by many compasses appended on top of each
other each of which trace a single circle with uniform velocity. The
visualization of such an intricate motion tracing a shape perfectly is
beautiful, and I decided that this should be my birthday gift to my 
girlfriend.

I first went over her image with Gabor filters to detect edges. This
produced a sketch of her face in black and white. Then I made each
pixel either white or black. This then translates to a graph of
black pixels which has some Euclidean distance between them. Then I
solved the travelling salesmen problem on this graph using one of
networkx's routines. This gave me a closed loop in the plane, which
if traced, will draw her face. I then took the Fourier series of
this path, and created a colorful animation of this series. 


Mathologer video:
https://www.youtube.com/watch?v=qS4H6PEcCCA

3Blue1Brown video:
https://www.youtube.com/watch?v=r6sGWTCMz2k


Author: Fýrat Kýyak