# Operating-System
Algo 

-terminal

-create a program->

``
-nano (file name).c(using c language)
``
 
write a simple program;


`` 
#include<unistd.h>
int main()
{
write(1,"welcome to learn OS",20);//size of string20
}
``


for compile this code write

``
-gcc (file name)
``

for output


``-./a.out
``

<b>for print new line</b>

`` 
  #include<unistd.h>
  #include<stdio.h>
  int main()
  {
  int n;
  write(1,"welcome to learn OS\n",20);
  }
``

