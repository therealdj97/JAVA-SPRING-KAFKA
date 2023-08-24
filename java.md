# Java

Java was made looking at c, c++

Clanguage : 1972
c++ : late 1970 (more than 40 years)

java : 1995 (1st working version) (27 years)

within 10 15 years java became no1 language
tiobe.com (rankin of programing language)

**Why java was invented ?**

![How c program is executed](./Assets/1Screenshot%202023-08-24%20052309.png)

computer understands machine level language. to make a computer instruction in binary is very tough so we use c,c++ language which are like englsh language. but betweeen those 2 there is a translator.

Who is the translator?

Compilation: ususaly people say compilor is the translator but, thats wrong.
compilor takes aprogram and checks whether the program is written as per the standard of language.

If the condition is satisfied then program is converted to Assembly Code.

**what is assembly level code**
mnemonic instructions  

ADD X Y  
ACC Z  
MUL A B  

**Linking**  
converts machine level code to executable machine level code .exe  

**what does all of this had to do with java**
Assembly level code gets generated as per the platform (hardware & software)  

**Platform Dependancy**  
Depending upon platform being used final executable format changes.  
c,c++ are platform dependant languages.
unlike java  

to convince people to use java people often say that c,c++ had issues in them.which is absolutely wrong if that would've been the case even after 40 years of launch c,c++ wouldnt have been in picture which is clearly not a picture here.  

**is platform dependany a bad thing?**  

Platform dependancy provides best performance because code gets written as per the hardware and software where a program will be executed.

Satelight systems,Video games are platform dependant.  

In Mid 1980: - electronice industry aswa a boom because of invention of semiconductors and suddenly size of all elecronic gadgets started to shrink as a circuit board size shrinked as per the Moore's law.  
lots of invention was happening in home applience industry.

**embeded software development**
programing done for tv's,washing machines, etc  

to ease out the work for embeded software development Engineers came up with concept of write once run anywhere (Platform independancy)

java came in market to support platform independancy.  
many people think java came into market bec of internet. it was a total coincendance.  
Java wanted to become the most famous language so the founding team of java decided to support all the newest features in market at the time which were computer networking and web programing.and java became one of the 1st language which had support web programing and newtork programing.  

**what makes java platform independant**
![cprogram](./Assets/2Screenshot%202023-08-24%20062135.png)

Once bytecode is generated. ultimately it has to be converted  
Java program never gets converted into 1 & 0
so we dont have concept of executable file if we had concept of executable file again there would've been platformm dependancy.  
to execute bytecode we need to have  
JVM (Java virtual Machine),  
JRE(Java Runtime Environment)  

JVM/JRE has interpreter in it.
that interpreter excecuted bytecode in it.
when we talk about interpreter we talk about line by line execution.
line by line (read => convert => execute) this happens temperorily it is not saved anywhere in system.

everytime you run a java program this happens  
henceforth java programs are slower than c,c++ (nanoseconds/microseconds)

for different platforms different jvm are used.

Java is platform independent jvm/jre is not.  
jvm and jre are two sides of same coin.  
jvm is concept and jre is implementation of it.

Why java is platform independant?  
java compiler => converts code into bytecode
jvm => to execute bytecode you need jvm => interpreter executed bytecode directly we dont have executable files in java. we only have interpretation in java.

**JVM**
![java program](./Assets/3Screenshot%202023-08-24%20065451.png)
java is free but jvm is not
the version of jvm which has been given to us is distributed free of cost.  
but there are companies which have their own version of jvm to serve their purposes. these companies have paid enormous amount of money to oracle/sun microsystems.

android apps are made in java which means we jave jvm on our phone.
Bec of economic issues andy Rubin came up with DVM  
Dvm -  Dalvik virtual machine  
Art - Android runtime

Jvm keeps some RAM for its own use  (JVM Memory area)

Class loader= loads bytecode  
reserved part of memory that JVM uses  
Method Area= class file in which we have loaded information about those get stored  
heap=all objects get stored  
Jvm language stack ==== all local (primitive)variables  
Pc registers = next instructions address  
The execution engine is considered the heart of jvm  
Native method stack  
Native method interface  
Native method libraries

When we speak about the native method we speak of platform dependency.
**Features of JAVA**  
**Why we should we learn java**  
