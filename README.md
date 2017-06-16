# TD_HAPQ_bulk
Bulk hapq converted built in touchdesigner - Takes a single folder input of any movies and outputs a corresponding hapq folder 

# Requirements
Have all the .mov/.mp4 files you want to convert on the root of the same folder (eg d:/filestocovert/<filesgohere>)

Create a folder called 'output' in the same location (eg d:/filestocovert/output)

# To Use
Select the folder with the movies to convert in the folderin dat (titled 'FOLDERTOCHANGE')

Press the 'push to start' button

# output
The system will output a hapq version of everything within the original folder within the '/output' folder you made.
Maintaining duration, name and framerate at the original settings - simply converting it to HAPQ

# To watch for
The folder in is set to ONLY read movies. Any images or 1 frame movies will break this and wont be read.
There are no provision to check if movies have already been encoded so if there is an error and you need to stop you'll need to start again (for now)

# to add
ability to select which video to start on (or automaitcally detect what is in the output folder already)
Package it all slightly nicer
Resolution and format controller
