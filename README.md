#include<iostream>
using namespace std;

int main(){
    int Temp1, Temp2, Temp3;

    //Input temperature readings
    cout<<"Enter first temperature.";
    cin>>Temp1;
    cout<<"Enter second temperature.";
    cin>>Temp2;
    cout<<"Enter third temperature.";
    cin>>Temp3;

    //Checking conditions
    if(Temp2-Temp1>50){
        cout<<"Reduce fryer heat before taking the third reading"<<endl;
    }
    else if(Temp2-Temp1<10){
        cout<<"Increase fryer heat before taking third reading"<<endl;
    }
    //Final temperature check
    if(Temp3 >= 150 & Temp3 <= 190){
        cout<<"You may start fryin the Magwinyas";
    }else{
        cout<<"Oil is not ready for frying"<<endl;
    }

    return 0;
    }
