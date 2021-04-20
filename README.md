#include<iostream>
  using namespace std;
  
  //iterative approach
  int fact(int n){
  
  int f=1;
  
  for(int i=2;i<=n;i++){
  f=f*i;
  }
  
  return f;
  }
  
  //recursive approach
  int fact(int n)
  {
  
  if(n==1)
  return 1;
  
  return f*fact(n-1);
  }
  
  int main(){
  
  int n;
  cin>>n;
  
  cout<<fact(n);
  
  return 0;}
