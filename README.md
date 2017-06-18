# ADP-project
Creator: Steven Cunningham 

The Goal of this project is to take SonTek ADP data and automate velocities / depth bin

1. ADP output is .ADP. SonTek ViewADP software exports 3 velocity files (.VE,.VN,.VU), and 3 signal amplitude files (.a1,a2,a3)
1. Download an ADP [signal amplitude file](https://github.com/mlmldata2017/ADP-project/blob/master/Code%20test/SWC0610130945.a1)
1. Download [code](https://github.com/mlmldata2017/ADP-project/blob/master/ADP%20signal%20amp.ipynb) to eliminate bad profile bins (past the seafloor) # this works now 
1. In code, set file = signal amplitude file downloaded in step one. 
1. Find the length of good profile bins and apply to ADP velocity file # In progress  

