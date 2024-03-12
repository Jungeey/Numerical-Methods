#include<iostream>
#include<cmath>
using namespace std;
float f(float x,float y){
    return x*y;
}
float formula(float a,float b,float c,float d){
    float result;
    result=(d-c)*(b-a)*.5*.5*(f(b,d)+f(b,c)+f(a,c)+f(a,d));
    return result;
}

int main(){
    float a,b,c,d;
    cout<<"Enter value of a: ";
    cin>>a;
    cout<<"Enter value of b: ";
    cin>>b;
    cout<<"Enter value of c: ";
    cin>>c;
    cout<<"Enter value of d: ";
    cin>>d;
    float result=formula(a,b,c,d);
    cout<<"Output: "<<result;
    return 0;
}
