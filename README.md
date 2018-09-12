# a3_10661010
#include <iostream>
#include <cmath>
using namespace std;
int gcd(int a, int b)
{
while(a!=b){
if(a>b)
a-=b;
else
b-=a;
}
return a;
int main(){
int a;
int b;
cout<<"Enter the numbers"<<endl;
cin>>a;
cin>>b;
cout<<"the gcd = "<<gcd(a,b)<<endl;
return 0;
