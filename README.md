# While-loop
questions on while loop in c++


// WAP to count the number of digits 

#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the number..";
    cin>>n;
    int count =0;
    while(n>0){
        count=count +1;
        n/=10;
        
    }
    cout<<"number of digits are.."<<count;
}










/ wap to print the sum of digits
// step 1= lastdigit
//step 2=sum=lastdigit+sum
//step 3= n=n/10
#include <iostream>
using namespace std;
int main() {
   int n,lastdigit;
    cout<<"enter the number.";
    cin>>n;
    int sum=0;
    while(n>0)
    {
        lastdigit=n%10;
        n=n/10;
        sum+=lastdigit;
        
    }
    cout<<sum;
    
}
