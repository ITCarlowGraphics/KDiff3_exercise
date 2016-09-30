# KDiff3_exercise

Clone this repo and try the merge exercises below.

*For this exercise, use only the KDiff3 tools. DO NOT manually edit the output window*

## Merge1
1. merge branch x into branch y so that the merged code looks like below
2. use KDiff3 to merge the files: 
```
#include <iostream>
using namespace std;
 
int main ()
{
   // for loop execution
   for( int a = 10; a < 20; a = a + 1 )
   {
       cout << "value of a: " << a << endl;
   }
  
   for( int i=0;i<10;i++ )
   {
       cout << "hello world" << a << endl;
       cout << "have a nice day" << endl;
   }
   return 0;
}
```

## Merge2
1. undo the previous merge
2. merge branch x into branch y so that the merged code looks like below
2. use KDiff3 to merge the files (hint: Join selected Diffs)
```
#include <iostream>
using namespace std;
 
int main ()
{
   // for loop execution
   for( int a = 10; a < 20; a = a + 1 )
   {
       cout << "value of a: " << a << endl;
   }
  
   for( int i=0;i<10;i++ )
   {
       cout << "have a nice day" << endl;
   }
   
   cout << "C++ is the best"
   
 
   for( int i=0;i<10;i++ )
   {
       cout << "hello world" << a << endl;
   }
   return 0;
}
```

## Merge3
1. undo the previous merge
2. merge branch z into branch y so that the merged code looks like below
2. use KDiff3 to merge the files  (hint: Split Diff At Selection)
```
#include <iostream>
using namespace std;
 
//This is a comment (A) 
//this is another comment (B)
int main ()
{
   // for loop execution
   for( int a = 10; a < 20; a = a + 1 )
   {
       cout << "value of a: " << a << endl;
   }
  
   for( int i=0;i<10;i++ )
   {
       cout << "have a terrible day day" << endl;
   }
 
   cout << "C++ is the worst"
   
   return 0;
}
```
