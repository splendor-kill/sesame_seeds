### * windows 7 shared dirs for tensorflow docker
0. share on C:\Users only at the beginning
1. in VirtualBox, find the VM(e.g. default)
2. Settings/Shared Folders, map your dirs to somewhere(say /my_data)
3. docker run -it -v /my_data:/my_data _your_tensorflow_image_ bash
