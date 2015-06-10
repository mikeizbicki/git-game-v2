#Level 1
Welcome to level one, let’s jump right in! 

This level is designed to show you the power of the [```git ls-files```](http://git-scm.com/docs/git-ls-files) command.
As you can see there are multiple files in this branch when you run ```ls```. 
Your task is to count all the lines of code and text in the files.
Once this is done you are to checkout to the branch that is named after the total number of lines. 

example output:

    110 Timer.h
    234 cp.cpp
    220 ls.cpp
    216 main.cpp
    780 total

So if the total number is 780 then you would checkout to branch name 780.
 
Are you following me? 
Good!

*Hint: * Using ```git ls-files``` may not be enough. You must also use piping with other commands as specificied [here](http://stackoverflow.com/questions/4822471/count-number-of-lines-in-a-git-r).
