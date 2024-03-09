// Simpson`s 1/3 Rule
#include<iostream>
#include<cmath>
using namespace std;

float f(float x){
    return exp(x);
}
float formula(float h, float a, float b,float x1){
    return (h/3)*(f(a)+4*f(x1)+f(b));
}

int main(){
    float a,b,x1,h,result;
    cout<<"Enter Lower Limit: ";
    cin>>a;
    cout<<"Enter Upper Limit: ";
    cin>>b;
    
    h=(b-a)/2;
    x1=a+h;
    result=formula(h,a,b,x1);
    cout<<"Final output: "<<result;
    return 0;
}
