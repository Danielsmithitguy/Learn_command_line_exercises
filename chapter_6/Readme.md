#What's in the tmp directory?
ls -lr shows me that I have a test.md file somewhere
#while ls -1R gives me
Readme.md
tmp

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp:
stuff

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp/stuff:
things

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp/stuff/things:
frank

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp/stuff/things/frank:
joe

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp/stuff/things/frank/joe:
alex

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp/stuff/things/frank/joe/alex:
john

/Users/danielsmith/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_6/tmp/stuff/things/frank/joe/alex/john:
test.md

#Can you show me what files are in that directory?
ls -1R will show all folders and files under a directory tree.

#What files are in your home directory?
/Users/danielsmith/:
Applications       Documents          Movies             Pictures
BitTorrent Sync    Downloads          Music              Public
Desktop            Library            PdaNetUninstall.sh workspace

#What's in slash temp?
Igors-MacBook-Pro:Learn_command_line_exercises $ ls -1R /tmp
KSOutOfProcessFetcher.0.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
com.apple.launchd.mQXRgCJdhD
com.apple.launchd.t1hQv9Pk3H

/tmp/KSOutOfProcessFetcher.0.sAglCyxY5lzPoNgfmEvv-ZqGl-w=:
ls: KSOutOfProcessFetcher.0.sAglCyxY5lzPoNgfmEvv-ZqGl-w=: Permission denied

/tmp/KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=:
ksfetch

/tmp/com.apple.launchd.mQXRgCJdhD:
Listeners

/tmp/com.apple.launchd.t1hQv9Pk3H:
Render


