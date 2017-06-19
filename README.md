# ADP-project
Creator: Steven Cunningham 

The Goal of this project is to take SonTek ADP data and output velocities / depth bin and direction in .csv.

ADP output is .ADP. SonTek ViewADP software exports 3 velocity files (.VE,.VN,.VU), and 3 signal amplitude files (.a1,a2,a3)

1. Download an ADP signal amplitude file (.a#), and velocity files for North and South(.VE, .VN) [here](https://github.com/mlmldata2017/ADP-project/tree/master/Code%20test)
1. Download python [code](https://github.com/mlmldata2017/ADP-project/blob/master/ADP%20signal%20amplitude%2C%20velocity%2C%20and%20direction.ipynb).
1. Import pandas and numpy.
1. Define path, sig_amp as .a file, VE_file as .ve file, VN_file as .ve file. 
1. Run all cells
1. output CSV file is named same as the sig_amplitude filename with "done" at end.

