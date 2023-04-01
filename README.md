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
    
    
    
    
    
    
    
    
    
    
    
    
    //wap to print the reverse of a number..

//steps =
//1.rev=0*10
// lastdigit
//rev+=lastdigit
//n=n/10

#include<iostream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    int last=0;
      int rev=0;
   while(n>0)
   {
       rev*=10;
       last=n%10;
       rev+=last;
       n=n/10;
   
   }
   cout<<rev;
}

    
    
    
    
    
    // WAP to print the factorial of the given number..

#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the number..";
    cin>>n;
     int fact=1;
    for(int i=1;i<=n;i++)
    {
        fact*=i;
        
    }
    cout<<fact;
}
