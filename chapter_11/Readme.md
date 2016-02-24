>#Move a file in the newplace directory to another directory then move it back.

mv newfile.txt ~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_11/newfolder2
mv ./newfolder2/newfile.txt ./newfolder

>#Can you rename foo.txt to blah.txt?

mv ./newfolder/foo.txt ./newfolder/blah.txt

>#Can you move the production.log file in the log directory to slash temp?

mv ./log/production.log /tmp
