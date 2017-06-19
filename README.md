# ADP-project
Creator: Steven Cunningham 

The Goal of this project is to take SonTek ADP data and output velocities / depth bin and direction in .csv.

ADP output is .ADP. SonTek ViewADP software exports 3 velocity files (.VE,.VN,.VU), and 3 signal amplitude files (.a1,a2,a3)

1. Download an ADP signal amplitude file (.a#), and velocity files for North and South(.VE, .VN, .VU) [here](https://github.com/mlmldata2017/ADP-project/tree/master/Code%20test)
1. Download python [code](https://github.com/mlmldata2017/ADP-project/blob/master/ADP%20signal%20amplitude%2C%20velocity%2C%20and%20direction.ipynb).
1. Import pandas and numpy.
1. Define path, and file_group. File_group should be the name for all files exported from ViewADP ex: 'SWC0610131152' This will populate signal and all velocity file fields for code. 
1. Run all cells
1. output CSV file is named same as the sig_amplitude filename with "done" at end.

[ADP glob csv](https://github.com/mlmldata2017/ADP-project/blob/master/ADP%20glob%20csv.ipynb) takes all .csv files in path and appends them. output = combine.csv

