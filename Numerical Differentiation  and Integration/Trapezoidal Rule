// trapezoidal rule
#include<iostream>
#include<cmath>
using namespace std;

float f(float x){
    return pow(x,3)+1;
}
float formula(float h, float a, float b){
    return (h/2)*(f(a)+f(b));
}

int main(){
    float a,b;
    cout<<"Enter Lower Limit: ";
    cin>>a;
    cout<<"Enter Upper Limit: ";
    cin>>b;
    
    float h,result;
    h=b-a;
    
    result=formula(h,a,b);
    cout<<"Final output: "<<result;
    return 0;
}
