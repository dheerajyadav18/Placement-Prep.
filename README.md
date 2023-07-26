# Placement-Prep.

#Strings

#What is a CPP string?
A C++ string is an object that is a part of the C++ standard library. It is an instance of a “class” data type,
used for convenient manipulation of sequences of characters. To use the string class in your program,
the <string> header must be included.

#What is string in C++ with example?
Strings in C++ | C++ Strings - Scaler Topics
A string in C++ is an object that represents a sequence of characters. On the other hand, a string in C is represented by an array of characters. 
C++ supports C-style strings as well.

```
#include <iostream>
#include<string>
using namespace std;
int main()
{
   string str = "Dheeraj ";
   string str1("Yadav");
   cout<<str<<str1<<endl;
   
   string str2;
   cin>>str2;
   cout<<str2<<endl;
   
   string str3;
   getline(cin,str3);
   cout<<str3<<endl;

    return 0;
}
```
