### * Windows 7 shared dirs for tensorflow docker
only C:\Users are shared at the beginning, to add more, you can  
1. in VirtualBox, find the VM(e.g. default)  
2. Settings/Shared Folders, map your dirs to somewhere(say /my_data)  
3. docker run -it -v /my_data:/my_data _your_tensorflow_image_ bash  
the first /my_data is the VM path, not Windows'  
4. see [the blog](http://stackoverflow.com/questions/30864466/whats-the-best-way-to-share-files-from-windows-to-boot2docker-vm) and [stackoverflow](https://blog.pavelsklenar.com/5-useful-docker-tip-and-tricks-on-windows/)
