#include <bits/stdc++.h>
using namespace std;
int a[100], n=100, top = -1;

void push(int val){
    if(val>=n-1) cout<<"Stack Overflow"<<endl;
    top++;
    a[top]=val;
}

void pop(){
    if(top<0) cout<<"Stack Underflow"<<endl;
    top--;
}

void display(){
    if(top<0) cout<<"Stack Empty"<<endl;
    for(int i=top;i>=0;--i){
        cout<<a[i]<<endl;
    }
}

int main(){
    int ch, val;
    cout<<"1)Push"<<endl;
    cout<<"2)Pop"<<endl;
    cout<<"3)Display"<<endl;
    cout<<"4)Exit"<<endl;
    do{
        cout<<"Enter the choice"<<endl;
        cin>>ch;
        switch(ch){
        case(1):{
        cout<<"Enter the value"<<endl;
        cin>>val;
        push(val);
        break;
        }
        case(2):{
            pop();
            break;
        }
        case(3):{
            display();
            break;
        }
        case(4):{
            cout<<"Exit"<<endl;
            break;
        }
        default:{
            cout<<"Invalid choice"<<endl;
            break;
        }
    }
    }
    while(ch!=4);
    return 0;
}
