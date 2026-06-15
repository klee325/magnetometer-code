Descriptions of each file:

csv.and.plot
- Records per second bx, by, bz and total magnetic field measures in daily csv files stored in a folder called 'data'. Live plotting of minute average values using matplotlib. UTC time. 

csv.log
- Records per second bx, by, bz and total magnetic field measures in daily csv files stored in a folder called 'data' (no live plotting). UTC time.

print.values
- Prints per-second bx, by, bz and total magnetic field reading directly into the terminal.

pyqtgraph.live
- Live plotting of per-second values for bx, by, bz and total magnetic field using pyqtgraph. Time is seconds from start of code. 

Note: when saving live plots, save them as .svg files to preserve image quality. 

All outputs in nanotesla (50000 nT per volt).
To change to microtesla change the SENSITIVITY to 50 (50 µT per volt).
