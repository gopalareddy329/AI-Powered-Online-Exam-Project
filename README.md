# AI-Powered-Online-Exam-Project
Hello guys



                                                       This project for protect online cheating up to some extent 

In this project we are used : -
1) C Language
2) Python
3) Html
4) Css
5) Javascript
                                                         
                                                         
                                                         Use of C Language in this project
                                                                 
                                                                 
In C Language we created a database for Students Login with File Operation
With File operations in C Language we created a text file database named as stdb.txt
To create Invigilator Data base we integrated C language and Python.
In C Language we use
1)Functions
2)Pointers
3)File Operations 
4)Loops 
5)Conditions 
6)Arrays of Structures
7)Arrays
8)String Functions



                                                                 Use of Python in this project
                                                                 
In python we used Django
For face detection we used Opencv
We used time function in Python
For integration we use ctypes in Python


                                                               This project is website based project
                                                               

For webframe work we used Django
Django is a Python-based free and open-source web framework that follows the model–template–views architectural pattern.
In Django we used Html to create websites
To GUI we used CSS
To display imgs in websites we use javascript


                                                               Integrate C Language with Python
                                                               

In main folder there is two shared files libcalci.dll and studb.o
Studb is file name of c language file this file present in main/authentication/Studb.c
To create studb.o we use gcc -c -fPIC studdb.c -o studdb.o in cmd
To create connection between python and studdb.o and we create libcalci.dll
To create connection between libcalci.dll and python we use gcc studdb.o -shared -o libcalci.dll
To create connetcion between libcalci.dll and studb.o we use gcc -shared -o libcalci.dll -fPIC studdb.c

                                                                 Changes need in your pc
If you need to use this file in your pc please change this two lines
In main/authentication/views.py  in line number 19 change path according to your pc
In  main/authentication/views.py in line number 80 change path according to your pc





