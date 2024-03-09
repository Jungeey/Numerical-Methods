// Simpson`s 3/8 Rule
#include<iostream>
#include<cmath>
using namespace std;

float f(float x){
    return pow(x,3)+1;
}
float formula(float h, float a, float b,float x1,float x2){
    return (3*h/8)*(f(a)+3*f(x1)+3*f(x2)+f(b));
}

int main(){
    float a,b,x1,x2,h,result;
    cout<<"Enter Lower Limit: ";
    cin>>a;
    cout<<"Enter Upper Limit: ";
    cin>>b;
    
    h=(b-a)/3;
    x1=a+h;
    x2=x1+h;
    result=formula(h,a,b,x1,x2);
    cout<<"Final output: "<<result;
    return 0;
}
