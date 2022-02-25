# basic-calculator
#include <iostream>
using namespace std;
int main(){
int x,y;
int sum;
cout<<"Enter a number";
cin>>x;
cout<<"enter another number";
cin>>y;
sum=x+y;
cout<<"the sum of the numbers entered is "<<sum<<endl;
cout<<&x<<"   "<<&y<<"   "<<&sum<<endl;
  return 0;
}
