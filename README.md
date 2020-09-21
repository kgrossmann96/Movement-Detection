# Movement Detection
One of the projects in my senior capstone
A company came to our class and told us they created devices that were meant to monitor employees in case of a fall
This project centers around detecting abnormal movement
We affected our movement by spinning around to move while dizzy as well as using "drunk goggles"
My team generated data using an accelrometer and built our models using the first ten seconds worth of data
I tried a few different sci-kit learn algorithms and found that nearest neighbor had the highest accuracy
As part of preparation, each observation was given an identifier corresponding to one of the five categories of conditions for collection: walking, fast walking, spinning, wearing goggles, and spinning while wearing goggles. 
They were also given a binary category with a one for the most extreme case, goggles and spinning, and a zero for everything else.
