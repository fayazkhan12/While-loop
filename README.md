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
