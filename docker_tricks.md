### * Windows 7 shared dirs for tensorflow docker
only C:\Users are shared at the beginning, to add more, you can  
1. in VirtualBox, find the VM(e.g. default)  
2. Settings/Shared Folders, map your dirs to somewhere(say /my_data)  
3. docker run -it -v /my_data:/my_data _your_tensorflow_image_ bash  
the first /my_data is the VM path, not Windows'
