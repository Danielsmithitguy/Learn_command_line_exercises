I like to think of it as a selected stack of plates, pushd will add that dir to the list
while popd will move back one, you can not pushd and popd back and forth, nor can you do popb
with out pushd

I could do
pushd ~/workspace/davinci_coders_t1_2016/
pushd ~/workspace/davinci_coders_t1_2016/building_the_toolbelt_t1_2016/
pushd ~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_8

and by doing popd it takes me right back to the tool belt vs cd .. going back to Learning_command_line_exercise
once more takes me back to the davinci folder and once more will not work, end of the stack of plates
