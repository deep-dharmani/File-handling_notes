>>>>File handling:
when we re run a program then previous data should be deleted it should not
save previous like if we have application of bank and some customers deposit
some amount of money in his account and when he re open the application then
there balance become zero because it did'nt save previous data so we have to
use file handling in which it saves all our data in a file.

>>>Modes in file handling:
For creating a file we have some modes in python we have to write variable and
assingn this data: write open and in parenthesis in double codes write address
of file comma and in double code it auttomatically suggest all modes and we use
that we need at that time.

>>"r" mode:
"r" mode is use to read a file for reding a file we have to use we have to just 
open by write "r" at the place of mode in parenthesis and write file name and assign
that in a variable. 
>.read():
"r" mode just call and open  a file for read and store that in variable for 
read that we have to use read() just write that variable name .read() which 
read and print text in output which is inside that file and if that file 
does'nt exisist then it passes eror.
>.close():
Using "r" mode it opens a file , using .read() it read that file and print
statements inside our that file in output after reading that file we have to
importantly close that file using .close().                                                                                                                       
>>"w" mode:
"w" mode is use for writting something inside a file we just  using open 
and in parenthesis we have to write "w" as mode and write that file name 
in parenthesis of file and assign that in a variable
>.write():
Like .read() in "r" mode , we have .write() in "w" takes some data in 
parenthesis which we want to write in that file if that file is present
then it create new file of that name and store but if it is exisist then 
remove previous data inside that file and store new data which we give.
>close():
we have to also importantly close that file in same way.                                                                                                             
>>"a" mode:
Basically "a" means append anything in a file, means like we use append in
list to add some new item without removing other previous item in list like
that we have append in file handling when we open just writ "a" as module in
way.
>.write():
.write() for "a" mode is different from .write() in "w" mode ,it only only add that
data in that file not remove previous data of file so it is safer than the .write()
of "w" but it gives eror if eror if that file is'nt present.
>.close():
we have to also importantly close that file in same way.                                                                                                                                                                                                      
>>"x" mode:
We open this in same way just write "x" at the place of mode it is also use to write
some thing in any file.
>.write():
.write() is use in "x" mode if our  that file is exisist then it gives eror and if it 
is not exisist then it directly new file and store our data means it is used when we 
want to make a new file.
>close():
we have to also importantly close that file in same way.                                                                                                                                                                                                      
>>"b" mode:
We open this in same way just write "b" at the place of mode it is use to read a
video file and image file and return result in binary language/computer language.
>.read():
This mode only read a video file and image file and gives output in a binary language 
which is not human readable. 
>.close():
we have to also importantly close that file in same way.                                                                                                                                                                                                                     
>>"r+" mode:
using this in open as mode it can do both reading and writting of a file we use both
both function .read() and write().
>.write():
we have to use .write() with "r+" mode in this it only write some statement in given 
file if that file did'nt exisist then it passes eror and if it is exisist then only 
write store not remove previous data.
>read():
we have to use .read() with "r+" mode in this it only read  data in file if that file
did'nt exisist then it passes eror.                                                                                                                                 
>>with statement:
At that time we are using manually open and close which make did'nt makes our code clean
but if we use with statement then don't have to manually .close() and write variable we 
have first write ,with open and in parenthesis in first double code comma in double code
mode and as that variable name where we want to store and give identation enter and use 
function inside that.
