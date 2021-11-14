#include <iostream>
#include <string>
using namespace std;
int main()
{
    
 int n,Sum=0;
 cout<<"\n\t Integer Numbers that are divisible by 9 : ";
 for(n=100;n<=200;n++)
 {
 if(n%9==0) 
 {
 cout<<n<<", ";
 Sum = Sum + n; 
 }
 }
 cout<<"\n\t Sum = "<<Sum;
 return(0);
}
