# Memory-Dumper
Python Android Memory Dumper




# Installation

1. Termux

2. Python Installed in Termux

- To install python use this command - pkg install python

3. tsu Installed in Termux or bash ./Required.bash

- To install tsu use this command - pkg install tsu





# Screenshot

<img src="https://user-images.githubusercontent.com/56850970/119896657-f26c1c80-bf5c-11eb-878e-6a7af2835139.png" width="145" height="300">







# Usage

1. find pid of main process using pidof command

- tsudo pidof com.tencent.ig (replace com.tencent.ig with your choice)

2. Run the dumper and follow the syntax below

- tsudo ./MemoryDumper PID DROPLETNAME (Replace PID and DROPLET NAME)

# Example

For Example if you want to dump libGoxome.so from memory and PID of main app process id is 1234 then the command would be 

- tsudo ./MemoryDumper 1234 libGoxome.so

# Note

- ~~This dumper writes Byte By Byte so it may take some time to dump the data if data size is heavy like 100s of MBs. I may update it later to support quick dumping.~~

- Updated the script to enable quick dumping. Please use python script.

