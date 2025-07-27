#include<iostream>
using namespace std;
int fact(int n){
    int fact=1,i;
    for(int i=1;i<=n;i++){
        fact=fact*i;
    }
    return fact;
}
int main(){
    int n;
    cout<<"Enter number to find factorial=";
    cin>>n;
    cout<<fact(n)<<endl;
}
