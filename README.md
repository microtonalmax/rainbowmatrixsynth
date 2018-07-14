# rainbowmatrixsynth
An intuitive rainbow-colored synthesizer that requires no previous musical experience to play

The Rainbow Matrix Synth uses a box of multi-colored pixels to create xenharmonic music.  
Each pixel location (x,y) is assigned a frequency, determined by the equation:
PixelFrequency = CenterFrequency * x / y
such that x and y are natural positive numbers.
(1,1) is the origin point of the matrix.  There is no (0,0).
Each pixel can be on or off.
On pixels are brightly colored, while off pixels are dimly lit.
The hue of each pixel is determined by its pitch class, with the pitch class of the location (1,1) assigned to red.
While each pixel connotes one frequency, some frequencies correspond to multiple pixel locations.  
For example, the locations (2,2), (3,3), (4,4) and so forth, all correspond to the center frequency.
For more detailed info, read "Harmonic Matrix Analysis of Chris Otto's Octet."
The sonoritylog.txt records presets in the matrix.   
The "poly" file is a simple sawtooth synthesizer, which runs multiple instances inside the larger Max patch.
Feel free to email me if you have any more questions or suggestions.  
