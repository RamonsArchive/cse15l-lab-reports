This is only the beginning.
Hello. Welcome to my blog. My name is Ramon and I am a first year at Muir college.

# Lab 1


1. **Examples using commands with no arguments**

   ![Image](cdNoArgs2.png)
   
   The working directy for this command was `/home/lecture1`. I got this output because `cd` changes your directory but when called in a directory and not passed any arguments, it changes your directory to it's parent one. The output is not an error because the command executed with resonable behavior and no unnessessary baggage.

   ![Image](lsnoarguments.png)
   
   The working directory for this command was `/home`. I got this output of lecture1 because the ls command lists all that's in the           directory which in this case is `lecture1`. This output is not an error because it printed out the contents of the current directory as expected.

   ![Image](catsNoArguments2.png)
   
   The working directory for this command was `/home/lectrue1`. I got this output because the `cat` command is expecting the user to pass a file to print so by passing in pie and apple, it resorts to printing out my input. This output is not an error because it correctly and consistently prints out my input.

2. **Examples using commands with a path to a directory as an argument**

   ![Image](cddirectory.png)

   The working directory for this command was `/home`. I got this output of nothing but a new pointer with my changed path because the command correclty changed my directory to the one I passed as an arguemnt. This output is not an error becuase I correclty changed my directory. 

   ![Image](lsdirectory.png)

   The working directory for this command was `/home/lecture1`. I got this output of listing all the files in the messages directory becuase I passed the command `ls messages/` where there exists a `/mesages` directory to list. This output is not an error beceause it correclty lists all the contents in the `/messages` directory I passed as my argument.

   ![Image](catdirectory.png)

   The working directory for this command was `/home/lecture1`. I got this output telling me `/messages` is a directory because the `cat` command expects a file name as an arguemnt for it to print. This output is an error because I passed a directory in place of a file name and thus the `cat` command can't print the contents of a directory and instead prints an error.

3. **Examples using commands with a path to a file as an argument**

   ![Image](cdfile.png)

   The working directory for this command was `/home/lecture1`. I got this output that the argument I passed was not a directory because the command `cd` is suppsed to change the directory which cannot be a file. This output is an error because I passed a file in place of a directory for me to change into thus prompting the error.

   ![Image](lsfile.png)

   The working directory for this command was `/home/lecture1`. I got this output of the listed directory and filename I passed as an argument because ls prints the contents of the current directory but when passed a file as an arguemnt, prints that filename and any directory passed to access that file. This output is not an error because the command correctly prints the filename and the directory leading to that file as expected when passed a file as the arguemnt.

   ![Image](catfile.png)

   The working directory for this command was `/home/lecture1`. I got this output of "Hello World!" because the cat command prints the message of a file passed as an argument. In this case, I passed the `en-us.txt` file in the `/messages` directory as the argument. This output is not an error because the command correctly prints the contents in the file I passed as an argument.
    

      
    
