#include <bits/stdc++.h>
using namespace std;

int b;

   int main (){
    cin>>b;
    for (int i=1;i<=b;i++){
        for (int j=0;j<b-i;j++){
            cout<<" ";
        }
        for (int j=1;j<=i;j++){
            cout<<"* ";
        }
        cout<<endl;
    }  

    
    // cin>>b;
    // int c;
    // c=b/2;
    // b=b-c;
    // for (int i=1;i<=b;i++){

    //     for (int j=1;j<=1;j++){
    //         cout<<"*";
    //     }
    //     for (int k=1;k<=i;k++){
    //         cout<<" ";
    //     }
    //     cout<<endl;
    // }  
    //  for (int i=1;i<=b;i++){
    //     for (int j=0;j<=b-i;j++){
    //         cout<<"*";
    //     }
    //     for (int k=1;k<=i;k++){
    //         cout<<" ";
    //     }
    //     cout<<endl;
    // }  
   }
//     int n;
//     cin>>n;
//     int b;
//     b=n;
//     if (n%2==0)n/2;
//     else n=n/2+1;
//     for (int i=1;i<=n;i++){
//         for ()
//     }
// }
