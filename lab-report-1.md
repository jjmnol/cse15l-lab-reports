# `cd`
> ## 1. No Arguments
![Image](cd1.png)

The first example is using the command `cd` with no arguments. When this is run, it will return the user to the home directory, which in this case takes the user back from Documents to home. This is because since the `cd` command lacks an argument, it cannot directed anywhere besides the home directory. This does not create an error.

> ## 2. A path to directory as an argument
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/90c03318-5177-48e6-9a92-32746416921b)


The second example is using the command `cd` with a path to directory as an argument. When using a path to directory as an argument using the command `cd`, it will change the working directory to the desired directory. In this case, it is downloads. It can be seen that when we used `cd downloads` the working directory changed to Downloads as it is our desired working directory. This does not create an error.

> ## 3. A path to a file as an argument
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/cb99bafe-a047-4ac1-9b96-7817d7d8294d)


The last example is using the command `cd` with a path to a file as an argument. Becaause lab1.txt is not a directory, an error is produced since `cd` can only change directories into a folder and not a file.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
# `ls`
> ## 1. No Arguments
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/9e2a29d1-abd7-4b83-8c87-03035f86b764)


The first example is using the command `ls` with no arguments. When no arguments are provided with `ls`, it will return the list of files in the current directory in alphabetical order. This is because there is no specific directory that it is being asked to list the files of, so instead it displays everything accessible to the user in the home directory. This does not create an error.

> ## 2. A path to directory as an argument
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/0e5d263f-ac7f-4730-8478-40d57b0c1df8)


The second example is using the command `ls` with a path to directory as an argument. When this is run, it will show the user the contents of the directory that was called upon. In this example, it is being asked to list the files in links and displays it to the user. This is because the user is being more specific in referencing a directory using `ls` compared to using it with no arguments. This does not create an error.

> ## 3. A path to a file as an argument
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/b127b3b6-0386-4f61-bccb-4dd004b8904a)


The last example is using the command `ls` with a path to a file as an argument. When using `ls` on a path to a file as an argument, it listed the directory path to the fie itself. This does not produce an error.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
# `cat`
> ## 1. No Arguments
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/1c053a4d-3947-4a9e-b90b-50832c887ea3)


The first example is using the command `cat` with no arguments. When the 'cat' is used with no arguments, it reads the data from the input and composes it to the output. In the picture above, this is exemplified the program took the user input 'cse15l' and outputted 'cse15l' as well. This occurs because there is no argument used in the original `cat` command, so the input the user types becomes the standard input. This does not create an error.

> ## 2. A path to directory as an argument
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/85d8e66d-aee0-4bdf-9c95-d38a82d484a2)

The second example is using the command `cat` with a path to directory as an argument. In this example, the target directory is lab1 and to access it, we are passing in OneDrive/Desktop/lab1 since that is where the directory is located. This does not create an error.

> ## 3. A path to a file as an argument
![image](https://github.com/jjmnol/cse15l-lab-reports/assets/146889917/e48adf91-23ad-478c-8549-2928aacfdfbb)

The third example is using the command `cat` with a path to directory as an argument. The `cat` command was used to create a file called 'lab1.txt' containing the statement "Hello World!". A new path was then created from the home directory to 'lab1.txt' and this is because the argument was to make a new file under the home directory. This does not create an error.
