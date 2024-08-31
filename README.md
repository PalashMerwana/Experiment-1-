# Experiment 1
# Aim
Downloading and installing Vs Code (Hello World and calculator) 
# Software used 
Vs Code 
# Theory 
VS code is a code editor that allows you to run all types of programs and codes if the suitable extensions are added. In the codes, MinGW is used to add the c++ extension printing hello world uses the "cout" character output and the calculator program uses the sum(+), difference(-), multiplication(*), division(/) arithmetic operators

# codes
~~~
hello world:
#include< iostream >

using namespace std;

int main()

{

cout << "Hello World";

return 0;
}
~~~
output:
![image](https://github.com/user-attachments/assets/940fa4f2-0311-4552-81a9-19feab7dd525)


# Calculator
~~~
#include< iostream >

using namespace std;

int main()

{ int a,b,sum=0, diff, mult, div ;

cout<<"enter a number a: ";

cin>>a;

cout<<"enter a number b: ";

cin>>b; 

sum=a+b;

cout<<"sum is: "<<sum<<endl; 

diff=a-b; 

cout<<"diff is: "<<diff<<endl;

mult=a*b;

cout<<"mult is: "<<mult<<endl;

div=a/b;

cout<<"division is: "<<div<<endl; 

return 0;
}
~~~
#Output
![image](https://github.com/user-attachments/assets/1fb1e60b-dbb5-44f4-8cd2-72fb579f4746)
