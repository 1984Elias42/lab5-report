# Lab report 5
## Researching Commands
In lab3, I did some exploration in command __grep__ and give 8 examples of this command. Now I will keep my exploration on another command in lab5.
I will choose the command __less__ and give 8 examples of it.\
Before I use the less command, I will use __find written_2/ > find-results.txt__ to get the list files and directories inside the directory __written_2__ in a txt file called __find-results__.\
# Command-line operation 1:
Then I will use my first less-line command on the directory __written2__ which is __less find-results.txt__, this command will display all files' name in find-results.txt. And the command screen will be full of these lines, we can use q to back to normal screen:
```
# fixed code
written_2/
written_2/non-fiction
written_2/non-fiction/OUP
written_2/non-fiction/OUP/Abernathy
written_2/non-fiction/OUP/Abernathy/ch1.txt
written_2/non-fiction/OUP/Abernathy/ch14.txt
written_2/non-fiction/OUP/Abernathy/ch15.txt
written_2/non-fiction/OUP/Abernathy/ch2.txt
written_2/non-fiction/OUP/Abernathy/ch3.txt
written_2/non-fiction/OUP/Abernathy/ch6.txt
written_2/non-fiction/OUP/Abernathy/ch7.txt
written_2/non-fiction/OUP/Abernathy/ch8.txt
written_2/non-fiction/OUP/Abernathy/ch9.txt
written_2/non-fiction/OUP/Berk
written_2/non-fiction/OUP/Berk/CH4.txt
written_2/non-fiction/OUP/Berk/ch1.txt
written_2/non-fiction/OUP/Berk/ch2.txt
written_2/non-fiction/OUP/Berk/ch7.txt
written_2/non-fiction/OUP/Castro
written_2/non-fiction/OUP/Castro/chA.txt
written_2/non-fiction/OUP/Castro/chB.txt
written_2/non-fiction/OUP/Castro/chC.txt
written_2/non-fiction/OUP/Castro/chL.txt
written_2/non-fiction/OUP/Castro/chM.txt
written_2/non-fiction/OUP/Castro/chN.txt
written_2/non-fiction/OUP/Castro/chO.txt
written_2/non-fiction/OUP/Castro/chP.txt
written_2/non-fiction/OUP/Castro/chQ.txt
written_2/non-fiction/OUP/Castro/chR.txt
written_2/non-fiction/OUP/Castro/chV.txt
written_2/non-fiction/OUP/Castro/chW.txt
written_2/non-fiction/OUP/Castro/chY.txt
written_2/non-fiction/OUP/Castro/chZ.txt
written_2/non-fiction/OUP/Fletcher
written_2/non-fiction/OUP/Fletcher/ch1.txt
written_2/non-fiction/OUP/Fletcher/ch10.txt
written_2/non-fiction/OUP/Fletcher/ch2.txt
written_2/non-fiction/OUP/Fletcher/ch5.txt
written_2/non-fiction/OUP/Fletcher/ch6.txt
written_2/non-fiction/OUP/Fletcher/ch9.txt
written_2/non-fiction/OUP/Kauffman
written_2/non-fiction/OUP/Kauffman/ch1.txt
written_2/non-fiction/OUP/Kauffman/ch10.txt
written_2/non-fiction/OUP/Kauffman/ch3.txt
find-results.txt
```
Now lets change the file from __find-results.txt__ to __grep-results.txt__. That will track the file's name in __grep-results.txt__. The command we will use is __less grep-results.txt__. And here is what it looks like:
```
# fixed code
$ ssh cs15lwi23avn@ieng6.ucsd.edu\
> ssh cs15lwi23avn@ieng6.ucsd.edu
ssh: Could not resolve hostname ieng6.ucsd.edussh: Name or service not known
written_2/non-fiction/OUP/Abernathy/ch1.txt
written_2/non-fiction/OUP/Abernathy/ch14.txt
written_2/non-fiction/OUP/Abernathy/ch15.txt
written_2/non-fiction/OUP/Abernathy/ch2.txt
written_2/non-fiction/OUP/Abernathy/ch3.txt
written_2/non-fiction/OUP/Abernathy/ch6.txt
written_2/non-fiction/OUP/Abernathy/ch7.txt
written_2/non-fiction/OUP/Abernathy/ch8.txt
written_2/non-fiction/OUP/Abernathy/ch9.txt
written_2/non-fiction/OUP/Berk/CH4.txt
written_2/non-fiction/OUP/Berk/ch1.txt
written_2/non-fiction/OUP/Berk/ch2.txt
written_2/non-fiction/OUP/Berk/ch7.txt
written_2/non-fiction/OUP/Castro/chA.txt
written_2/non-fiction/OUP/Castro/chB.txt
written_2/non-fiction/OUP/Castro/chC.txt
written_2/non-fiction/OUP/Castro/chL.txt
written_2/non-fiction/OUP/Castro/chM.txt
written_2/non-fiction/OUP/Castro/chN.txt
written_2/non-fiction/OUP/Castro/chO.txt
written_2/non-fiction/OUP/Castro/chP.txt
written_2/non-fiction/OUP/Castro/chQ.txt
written_2/non-fiction/OUP/Castro/chR.txt
written_2/non-fiction/OUP/Castro/chV.txt
written_2/non-fiction/OUP/Castro/chW.txt
written_2/non-fiction/OUP/Castro/chY.txt
written_2/non-fiction/OUP/Castro/chZ.txt
written_2/non-fiction/OUP/Fletcher/ch1.txt
written_2/non-fiction/OUP/Fletcher/ch10.txt
written_2/non-fiction/OUP/Fletcher/ch2.txt
written_2/non-fiction/OUP/Fletcher/ch5.txt
written_2/non-fiction/OUP/Fletcher/ch6.txt
written_2/non-fiction/OUP/Fletcher/ch9.txt
written_2/non-fiction/OUP/Kauffman/ch1.txt
written_2/non-fiction/OUP/Kauffman/ch10.txt
written_2/non-fiction/OUP/Kauffman/ch3.txt
written_2/non-fiction/OUP/Kauffman/ch4.txt
written_2/non-fiction/OUP/Kauffman/ch5.txt
written_2/non-fiction/OUP/Kauffman/ch6.txt
written_2/non-fiction/OUP/Kauffman/ch7.txt
written_2/non-fiction/OUP/Kauffman/ch8.txt
written_2/non-fiction/OUP/Kauffman/ch9.txt
written_2/non-fiction/OUP/Rybczynski/ch1.txt
written_2/non-fiction/OUP/Rybczynski/ch2.txt
grep-results.txt
```
# Conclusion for the first command-line operation:
By using this command-line operation we can quickly take a lot at the specific files.
# Command-line operation 2:
Then we will do another grep command which is __less -N __, this command line will display all the lines inside the .txt files with a number before each line. We will use __find-results.txt__ as our first example. Here is what it looks like:
```
# fixed code
$ ssh cs15lwi23avn@ieng6.ucsd.edu
Last login: Mon Mar 13 21:09:53 2023 from cpe-66-75-251-149.san.res.rr.com
      1 written_2/
      2 written_2/non-fiction
      3 written_2/non-fiction/OUP
      4 written_2/non-fiction/OUP/Abernathy
      5 written_2/non-fiction/OUP/Abernathy/ch1.txt
      6 written_2/non-fiction/OUP/Abernathy/ch14.txt
      7 written_2/non-fiction/OUP/Abernathy/ch15.txt
      8 written_2/non-fiction/OUP/Abernathy/ch2.txt
      9 written_2/non-fiction/OUP/Abernathy/ch3.txt
     10 written_2/non-fiction/OUP/Abernathy/ch6.txt
     11 written_2/non-fiction/OUP/Abernathy/ch7.txt
     12 written_2/non-fiction/OUP/Abernathy/ch8.txt
     13 written_2/non-fiction/OUP/Abernathy/ch9.txt
     14 written_2/non-fiction/OUP/Berk
     15 written_2/non-fiction/OUP/Berk/CH4.txt
     16 written_2/non-fiction/OUP/Berk/ch1.txt
     17 written_2/non-fiction/OUP/Berk/ch2.txt
     18 written_2/non-fiction/OUP/Berk/ch7.txt
     19 written_2/non-fiction/OUP/Castro
     20 written_2/non-fiction/OUP/Castro/chA.txt
     21 written_2/non-fiction/OUP/Castro/chB.txt
     22 written_2/non-fiction/OUP/Castro/chC.txt
     23 written_2/non-fiction/OUP/Castro/chL.txt
     24 written_2/non-fiction/OUP/Castro/chM.txt
     25 written_2/non-fiction/OUP/Castro/chN.txt
     26 written_2/non-fiction/OUP/Castro/chO.txt
     27 written_2/non-fiction/OUP/Castro/chP.txt
     28 written_2/non-fiction/OUP/Castro/chQ.txt
     29 written_2/non-fiction/OUP/Castro/chR.txt
     30 written_2/non-fiction/OUP/Castro/chV.txt
     31 written_2/non-fiction/OUP/Castro/chW.txt
     32 written_2/non-fiction/OUP/Castro/chY.txt
     33 written_2/non-fiction/OUP/Castro/chZ.txt
     34 written_2/non-fiction/OUP/Fletcher
     35 written_2/non-fiction/OUP/Fletcher/ch1.txt
     36 written_2/non-fiction/OUP/Fletcher/ch10.txt
     37 written_2/non-fiction/OUP/Fletcher/ch2.txt
     38 written_2/non-fiction/OUP/Fletcher/ch5.txt
     39 written_2/non-fiction/OUP/Fletcher/ch6.txt
     40 written_2/non-fiction/OUP/Fletcher/ch9.txt
     41 written_2/non-fiction/OUP/Kauffman
     42 written_2/non-fiction/OUP/Kauffman/ch1.txt
     43 written_2/non-fiction/OUP/Kauffman/ch10.txt
     44 written_2/non-fiction/OUP/Kauffman/ch3.txt
find-results.txt
```
Let's change the file fromm __find-results.txt__" to __grep-results.txt__ and here is that the result will looks like:
```
# fixed code
$ ssh cs15lwi23avn@ieng6.ucsd.edu
      1 written_2/non-fiction/OUP/Abernathy/ch1.txt
      2 written_2/non-fiction/OUP/Abernathy/ch14.txt
      3 written_2/non-fiction/OUP/Abernathy/ch15.txt
      4 written_2/non-fiction/OUP/Abernathy/ch2.txt
      5 written_2/non-fiction/OUP/Abernathy/ch3.txt
      6 written_2/non-fiction/OUP/Abernathy/ch6.txt
      7 written_2/non-fiction/OUP/Abernathy/ch7.txt
      8 written_2/non-fiction/OUP/Abernathy/ch8.txt
      9 written_2/non-fiction/OUP/Abernathy/ch9.txt
     10 written_2/non-fiction/OUP/Berk/CH4.txt
     11 written_2/non-fiction/OUP/Berk/ch1.txt
     12 written_2/non-fiction/OUP/Berk/ch2.txt
     13 written_2/non-fiction/OUP/Berk/ch7.txt
     14 written_2/non-fiction/OUP/Castro/chA.txt
     15 written_2/non-fiction/OUP/Castro/chB.txt
     16 written_2/non-fiction/OUP/Castro/chC.txt
     17 written_2/non-fiction/OUP/Castro/chL.txt
     18 written_2/non-fiction/OUP/Castro/chM.txt
     19 written_2/non-fiction/OUP/Castro/chN.txt
     20 written_2/non-fiction/OUP/Castro/chO.txt
     21 written_2/non-fiction/OUP/Castro/chP.txt
     22 written_2/non-fiction/OUP/Castro/chQ.txt
     23 written_2/non-fiction/OUP/Castro/chR.txt
     24 written_2/non-fiction/OUP/Castro/chV.txt
     25 written_2/non-fiction/OUP/Castro/chW.txt
     26 written_2/non-fiction/OUP/Castro/chY.txt
     27 written_2/non-fiction/OUP/Castro/chZ.txt
     28 written_2/non-fiction/OUP/Fletcher/ch1.txt
     29 written_2/non-fiction/OUP/Fletcher/ch10.txt
     30 written_2/non-fiction/OUP/Fletcher/ch2.txt
     31 written_2/non-fiction/OUP/Fletcher/ch5.txt
     32 written_2/non-fiction/OUP/Fletcher/ch6.txt
     33 written_2/non-fiction/OUP/Fletcher/ch9.txt
     34 written_2/non-fiction/OUP/Kauffman/ch1.txt
     35 written_2/non-fiction/OUP/Kauffman/ch10.txt
     36 written_2/non-fiction/OUP/Kauffman/ch3.txt
     37 written_2/non-fiction/OUP/Kauffman/ch4.txt
     38 written_2/non-fiction/OUP/Kauffman/ch5.txt
     39 written_2/non-fiction/OUP/Kauffman/ch6.txt
     40 written_2/non-fiction/OUP/Kauffman/ch7.txt
     41 written_2/non-fiction/OUP/Kauffman/ch8.txt
     42 written_2/non-fiction/OUP/Kauffman/ch9.txt
     43 written_2/non-fiction/OUP/Rybczynski/ch1.txt
     44 written_2/non-fiction/OUP/Rybczynski/ch2.txt
grep-results.txt
```
# Conclusion for the second command-line operation:
Compared with the first mode, by using this command-line operationwe, we can not only use every lines in that txt file but also see how many lines are there in the txt file.
# Command-line operation 3:
Now I will use the command line __less -p__, this command will display all lines in the file and highlight the string you type in after __p__. Let's do it on __find-results.txt__, and here is what it looks like:
```
# fixed code
[cs15lwi23avn@ieng6-201]:docsearch:389$ less -pch find-results.txt
```
![Image](https://github.com/1984Elias42/lab5-report/blob/main/1.png)
Then let's try to change the keyword from __find-results.txt__ to __grep-results.txt__. Here is what it looks like:
```
# fixed code
[cs15lwi23avn@ieng6-201]:docsearch:390$ less -pch grep-results.txt
```
![Image](https://github.com/1984Elias42/lab5-report/blob/main/2.png)
# Conclusion for the 3rd command-line operation:
By using the command-line __less -p__ we can not only see all the lines in the txt file but also use the highlight string chosen by us, we can use this to do specific search.
# Command-line operation 4:
The last command-line operation I will use is __less -X__, this command-line will keep displaying the all the lines even we pressed __q__ to quit. Here is what it looks like:
```
# fixed code
[cs15lwi23avn@ieng6-201]:docsearch:391$ less -X find-results.txt    
written_2/
written_2/non-fiction
written_2/non-fiction/OUP
written_2/non-fiction/OUP/Abernathy
written_2/non-fiction/OUP/Abernathy/ch1.txt
written_2/non-fiction/OUP/Abernathy/ch14.txt
written_2/non-fiction/OUP/Abernathy/ch15.txt
written_2/non-fiction/OUP/Abernathy/ch2.txt
written_2/non-fiction/OUP/Abernathy/ch3.txt
written_2/non-fiction/OUP/Abernathy/ch6.txt
written_2/non-fiction/OUP/Abernathy/ch7.txt
written_2/non-fiction/OUP/Abernathy/ch8.txt
written_2/non-fiction/OUP/Abernathy/ch9.txt
written_2/non-fiction/OUP/Berk
written_2/non-fiction/OUP/Berk/CH4.txt
written_2/non-fiction/OUP/Berk/ch1.txt
written_2/non-fiction/OUP/Berk/ch2.txt
written_2/non-fiction/OUP/Berk/ch7.txt
written_2/non-fiction/OUP/Castro
written_2/non-fiction/OUP/Castro/chA.txt
written_2/non-fiction/OUP/Castro/chB.txt
written_2/non-fiction/OUP/Castro/chC.txt
written_2/non-fiction/OUP/Castro/chL.txt
written_2/non-fiction/OUP/Castro/chM.txt
written_2/non-fiction/OUP/Castro/chN.txt
written_2/non-fiction/OUP/Castro/chO.txt
written_2/non-fiction/OUP/Castro/chP.txt
written_2/non-fiction/OUP/Castro/chQ.txt
written_2/non-fiction/OUP/Castro/chR.txt
written_2/non-fiction/OUP/Castro/chV.txt
written_2/non-fiction/OUP/Castro/chW.txt
written_2/non-fiction/OUP/Castro/chY.txt
written_2/non-fiction/OUP/Castro/chZ.txt
written_2/non-fiction/OUP/Fletcher
written_2/non-fiction/OUP/Fletcher/ch1.txt
written_2/non-fiction/OUP/Fletcher/ch10.txt
written_2/non-fiction/OUP/Fletcher/ch2.txt
written_2/non-fiction/OUP/Fletcher/ch5.txt
written_2/non-fiction/OUP/Fletcher/ch6.txt
written_2/non-fiction/OUP/Fletcher/ch9.txt
written_2/non-fiction/OUP/Kauffman
written_2/non-fiction/OUP/Kauffman/ch1.txt
written_2/non-fiction/OUP/Kauffman/ch10.txt
written_2/non-fiction/OUP/Kauffman/ch3.txt
[cs15lwi23avn@ieng6-201]:docsearch:392$
```
Then let's try to change the keyword from __find-results.txt__ to __grep-results.txt__. Here is what it looks like:
```
# fixed code
[cs15lwi23avn@ieng6-201]:docsearch:392$ less -X grep-results.txt
written_2/non-fiction/OUP/Abernathy/ch1.txt
written_2/non-fiction/OUP/Abernathy/ch14.txt
written_2/non-fiction/OUP/Abernathy/ch15.txt
written_2/non-fiction/OUP/Abernathy/ch2.txt
written_2/non-fiction/OUP/Abernathy/ch3.txt
written_2/non-fiction/OUP/Abernathy/ch6.txt
written_2/non-fiction/OUP/Abernathy/ch7.txt
written_2/non-fiction/OUP/Abernathy/ch8.txt
written_2/non-fiction/OUP/Abernathy/ch9.txt
written_2/non-fiction/OUP/Berk/CH4.txt
written_2/non-fiction/OUP/Berk/ch1.txt
written_2/non-fiction/OUP/Berk/ch2.txt
written_2/non-fiction/OUP/Berk/ch7.txt
written_2/non-fiction/OUP/Castro/chA.txt
written_2/non-fiction/OUP/Castro/chB.txt
written_2/non-fiction/OUP/Castro/chC.txt
written_2/non-fiction/OUP/Castro/chL.txt
written_2/non-fiction/OUP/Castro/chM.txt
written_2/non-fiction/OUP/Castro/chN.txt
written_2/non-fiction/OUP/Castro/chO.txt
written_2/non-fiction/OUP/Castro/chP.txt
written_2/non-fiction/OUP/Castro/chQ.txt
written_2/non-fiction/OUP/Castro/chR.txt
written_2/non-fiction/OUP/Castro/chV.txt
written_2/non-fiction/OUP/Castro/chW.txt
written_2/non-fiction/OUP/Castro/chY.txt
written_2/non-fiction/OUP/Castro/chZ.txt
written_2/non-fiction/OUP/Fletcher/ch1.txt
written_2/non-fiction/OUP/Fletcher/ch10.txt
written_2/non-fiction/OUP/Fletcher/ch2.txt
written_2/non-fiction/OUP/Fletcher/ch5.txt
written_2/non-fiction/OUP/Fletcher/ch6.txt
written_2/non-fiction/OUP/Fletcher/ch9.txt
written_2/non-fiction/OUP/Kauffman/ch1.txt
written_2/non-fiction/OUP/Kauffman/ch10.txt
written_2/non-fiction/OUP/Kauffman/ch3.txt
written_2/non-fiction/OUP/Kauffman/ch4.txt
written_2/non-fiction/OUP/Kauffman/ch5.txt
written_2/non-fiction/OUP/Kauffman/ch6.txt
written_2/non-fiction/OUP/Kauffman/ch7.txt
written_2/non-fiction/OUP/Kauffman/ch8.txt
written_2/non-fiction/OUP/Kauffman/ch9.txt
written_2/non-fiction/OUP/Rybczynski/ch1.txt
written_2/non-fiction/OUP/Rybczynski/ch2.txt
[cs15lwi23avn@ieng6-201]:docsearch:393$
```
# Conclusion for command-line operation 4:
By using __--line-number__,we can not only display the required lines but also with the line numbers. We can get more information by using this command-line.
# Cite:
For all these 4 command-line operations, I find them on the website and here is the link for it:
[Link](https://phoenixnap.com/kb/less-command-in-linux#:~:text=The%20less%20pager%20allows%20you,in%20less%20is%20case%2Dsensitive.)
