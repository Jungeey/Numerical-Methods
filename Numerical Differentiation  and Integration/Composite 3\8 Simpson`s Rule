// Composite 3\8 Simpson`s Rule
#include<iostream>
#include<cmath>
using namespace std;

float f(float x){
    return 1/(1+pow(x,2));
}
float formula(float h, float x[],int n){
    float result;
    for(int i=0;i<=n;i++){
        if(i==0){
            result=result+f(x[i]);
        }else if(i==n){
            result=result+f(x[i]);
        }else if(i%3==0){
            result=result+2*f(x[i]);
        }else{
            result=result+3*f(x[i]);
        }
    }
    result=(3*h/8)*result;
    return result;
}

int main(){
    float a,b,h,result;
    int n;
    cout<<"Enter Lower Limit: ";
    cin>>a;
    cout<<"Enter Upper Limit: ";
    cin>>b;
    cout<<"Enter the value of n: ";
    cin>>n;
    float x[n+1];
    h=(b-a)/n;
    for(int i=0;i<=n ;i++){
        if(i==0){
            x[i]=a;
        }else if(i==n){
            x[i]=b;
        }else{
            x[i]=x[i-1]+h;
        }
    }
    
    result=formula(h,x,n);
    cout<<"Final output: "<<result;
    return 0;
}
