# Patterns-in-c++-
patterns printing question in c++

// print the given pattern
/*
1234
1234
1234*/


#include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the no of rows..";
    cin>>n;
    
    
    int m;
    cout<<"enter the no of columns..";
    cin>>m;
    
    
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=m;j++)
        {
            cout<<"1 2 3 4";
        }
        cout<<endl;
    }
}






// print the [attern]
//*****
//****
//***
//**
//* 


#include<iostream>
using namespace std;
int main()
{
    int n,stars;
    cout<<"enter the  number..";
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n+-i;j++)
        {

            cout<<"*";
        }
        cout<<endl;
    }
}
