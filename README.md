//Author - Satyam Dubey
// Minimum_of_two_number in C++
#include<iostream>
#include<conio.h>
using namespace std;
int main()
{
    int a,b;
    cout<<"Enter two number check for minimum";
    cin>>a>>b;
    if(a==b)
        cout<<"Please enter different number";
    else
    {
        if(a<b)
        cout<<a<<"is less than"<<b<<"means"<<a<<"is smaller";
        else 
        cout<<b<<" is smaller than"<<a<<"means"<<b<<"is smaller";
    }
}
