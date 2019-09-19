#include <iostream>

using namespace std;

int addTwoNums(int,int);
int subtactTwoNums(int,int);
int multiplyTwoNums(int,int);
int divideTwoNums(int,int);

int main(){
    cout<<addTwoNums(10,20)<<endl;
    cout<<subtactTwoNums(20,10)<<endl;
    cout<<multiplyTwoNums(10,20)<<endl;
    cout<<divideTwoNums(20,10)<<endl;
    
    return 0;
}
int addTwoNums(int x,int y){
    return x+y;
}
int subtactTwoNums(int x,int y){
    return x-y;
}
int multiplyTwoNums(int x,int y){
    return x*y;
}
int divideTwoNums(int x,int y){
    return x/y;
}


