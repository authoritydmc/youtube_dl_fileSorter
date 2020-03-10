# youtube_dl_fileSorter v 1.0
Sort the youtube dl playlist on local downloaded directory..
# how to Install
1. **Clone this Repo**
> git clone https://github.com/authoritydmc/youtube_dl_fileSorter.git
2. goto cloned Directory and run install.sh (make sure it is executable) using sudo
>sudo ./install.sh

# Usage:
## youtubeSorter.py
 
 
### 1. open a **Terminal** and navigate to Playlist Directory(i.e Your current path is playlist directory)

### 2. run the youtubeSorter.py 
  
  ``` youtubeSorter.py <url of playlist> ```
    or 
  > youtubeSorter.py
  
  **note you can pipe it to tee to have a log as well as output on Screen**
  ex : ```youtubeSorter.py | tee log.log```
  
 
  **3. YoutubeSorter.py**
    will ask two things ```url``` and ```shouldEnforceRename``` (1 if url is passed via argument).
    whether it should auto rename all the file when the file  is not found and it suggest a best possible match
    
    >Enter y or  Y to Accept this else any key will make you manually decide what to do
    
    **for the first time it will need Internet Connectivity to fetch filelist Name**
  
  
  
 ## youtubeSorter_Recovery.py
  
  this file should be run to recover any changes made by sort.py
  i.e it undo the renaming of file to Original State.
  
  Please note you can run this multiple times untill you get back to the original fileNames.
  
##### note

Run using python3
