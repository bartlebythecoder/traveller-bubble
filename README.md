# traveller-bubble
Bubble Graphs with Traveller (sub) sector data

This program uses an input file that requires a Law Level, Acceptance Level (in the Cx data), Tech Level, and Starport
You must use a header line with the Travellermap.com headers.  It assumed the second line is a series of '---' so that is not read.
After reading the header the program identifies which column number to find the key stats and starts looking for them on line 3.

It was built to copy and paste the input data into a file called bubblesec.txt.  
