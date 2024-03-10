Name: Ramon McDargh-Mitchell

PID: A17939555

Email: rmcdarghmitchell@ucsd.edu

# Lab Report 5

1. ![Image](originalPost.png)
   Hey, I getting an IndexOutOfBoundsException when testing my merge method. The bug occurs at line 28 but I'm adding `arr2.get(index2)` to result and which is not at `index1` so I'm not sure what's the issue. Any help is much apprecaited. Thank you!

2. Hey there, I don't have enough information to direclty fix your error. However, I suggest you run a debugger and compare `arr2.size()` to the value of `index2`. To run the debugger, run `javac -g -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` and then run `jdb -classpath .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore $1`. While in the jdb prompt, type `stop at Merge:28` where the error occurs and then type `run` to hit break point. When break point is hit. Type `locals` to get all the local variables and then compare `index2` to `arr2.size()`. To get the size of the `arr2` and the value of `index2`, type `print arr2.size()` and `print index2`.

3. 
   
