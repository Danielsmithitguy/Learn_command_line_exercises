>###Show me the lines in foo.txt that have "ERROR" in them.

grep error foo.txt

>###Show me the lines in bar.txt that have "davinci" in them.

grep davinci bar.txt

>###Can you print all the lines in text files that have your first and last name in them?

grep 'daniel smith' *.txt

>###Use quotes to find "new file" and "old file" and "This is".

```grep 'new file' *.txt```
```grep 'old file' *.txt```
```grep 'This is' *.txt```

>###Take the list of videos you created (or any other list) and use it to find some videos you want to find.

grep -f output.txt 

-f should be 'file' so grep looks for a file (the -f flag) named move.txt to do it's search with?

>###What does -i do with grep?

It will ignores case, so The is the same as the or tHe or any other combination, case dose not matter with -i
