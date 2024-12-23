# open-programming
Code to find the factorial of a number using recursion
#include<bits/stdc++.h>
using namespace std;
int Fact(int a)
if(a==1){
return 1;
}
return a*Fact(a-1);
}
int main(){
int n=5;
cout<<Fact(n)<<endl;
return 0;
}
