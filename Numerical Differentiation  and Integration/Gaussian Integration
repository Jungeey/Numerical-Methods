// Guass
#include<iostream>
#include<cmath>
using namespace std;

float f(float x){
    return exp(-x);
}
float point(int n,float d, float c){
    if(n==1){
        return 2*f(c*0+d);
    } else if(n==2){
        return f(c*-1/sqrt(3)+d) + f(c*1/sqrt(3)+d);
    } else {
        float weight1 = 5.0/9.0; 
        float weight2 = 8.0/9.0; 
        float weight3 = 5.0/9.0; 
        return weight1 * f(c*-0.77460+d) + weight2 * f(c*0+d) + weight3 * f(c*0.77460+d);
    }
}
float formula(float c,float d, int n){
    return c*(point(n,d,c));
}

int main(){
    float a,b,result;
    int n;
    cout<<"Enter Lower Limit: ";
    cin>>a;
    cout<<"Enter Upper Limit: ";
    cin>>b;
    cout<<"Enter the value of n: ";
    cin>>n;
    float c=(b-a)/2;
    float d=(b+a)/2;
    
    result=formula(c,d,n);
    
    cout<<result;
    return 0;
}
