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

    
    
    
    /*

print a pattern forn the given problem 
*   *
 * * 
  *  
 * * 
*   *
*/

#include<iostream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n;j++)
        {
            if(i==j || i+j==n+1) cout<<"*";
            
          
            else cout<<" ";
            
            
            
    
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
    
    
    
    
    
    
    
    
    
    
    
    //print the pattern 

/*
1
13
135
1357
*/


#include<iostream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    
    for(int i=1;i<=n;i++)
    {
        
        for(int j=1;j<=2*i-1;j+=2)
        {
           
    
            
            cout<<j;
        
    
        }
        cout<<endl;
    }
}
    
    
    
    
    
    
    
    
    /*

print the pattern

1111
2222
3333
4444
*/





#include<iostream>
using namespace std;
int main()

{
    int n;
    cin>>n;
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n;j++)
        {
            cout<<i;
            
        }
       
            
        
        cout<<endl;
    }
}
    
    
    
    
    /*

print the pattern

1234
123
12
1
*/





#include<iostream>
using namespace std;
int main()

{
    int n;
    cin>>n;
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n+1-i;j++)
        {
            cout<<j;
            
        }
       
            
        
        cout<<endl;
    }
}
    
    
    
    
    
    /*

print the pattern

A
AB
ABC
ABCD
*/





#include<iostream>
using namespace std;
int main()

{
    int n;
    cin>>n;
    for(char i=1;i<=n;i++)
    {
        for(char j=1;j<=i;j++)
        {
            cout<<char ('A'+ j-1);
            
        }
       
            
        
        cout<<endl;
    }
}
