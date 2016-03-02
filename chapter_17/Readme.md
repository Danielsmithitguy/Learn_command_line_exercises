>###Can you show me all the files in slash temp slash foo?

find /tmp/

>###What log files are in your log directory?

find ./log/ -name "*.log"

>###Look for all the video files on your computer starting at the home drive and use the > to save the list to a file

find ~/ "<name_of_file.File_format>" > output.txt
