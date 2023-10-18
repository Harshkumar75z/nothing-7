// Print the following pattern
// 1 1 1 1
// 2 2 2 2
// 3 3 3 3
// 4 4 4 4
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n;j++){
        cout<<i;
        }cout<<endl;   
    }
}

// Print the following pattern
// Input: n = 4
// Output:
// 1 2 3 4
// 1 2 3
// 1 2
// 1
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=0;i<=n;i++){
        for(int j=1;j<=n-i;j++){
            cout<<j;
        }cout<<endl;   
    }
}

// Print the following pattern
// Input: n = 4
// Output:
// A
// A B
// A B C
// A B C D
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=i;j++){
            cout<<char(j+64);
        }cout<<endl;   
    }
}

// Print the following pattern
// Input: n = 4
// Output:
// 1
// A B
// 1 2 3
// A B C D
// 1 2 3 4 5
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n+1;i++){
        for(int j=1;j<=i;j++){
            if(i%2==0) cout<<char(j+64);
            else cout<<j;
        }cout<<endl;   
    }
}

// Print the following pattern
// Input n = 4
// Output:
// *
// **
// ***
// ****
// ***
// **
// *
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=0;i<=n;i++){
        for(int j=1;j<=i;j++){
            cout<<"*"<<" ";
        }
        cout<<endl;   
    }
    int m = n-1;
    for(int i=0;i<=m;i++){
        for(int j=1;j<=m-i;j++){
            cout<<"*"<<" ";
        }
        cout<<endl;   
    }    
}

// Print the following pattern
// Sample Input : m = 4, n = 6
// Sample Output :
// ******
// *    *
// *    *
// ******
#include<iostream>
using namespace std;
int main(){
    int m;
    cout<<"Enter the value of m : ";
    cin>>m;
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=m;i++){
        for(int j=1;j<=n;j++){
            if(i==1 || i==m || j==1 || j==n)
            cout<<"*"<<" ";
            else cout<<"  ";
        }
        cout<<endl;   
    }
}

// Print the following pattern
// Sample Input : n = 4
// Output :
//     ****
//    ****
//   ****
//  ****
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n-i;j++){
            cout<<" ";
        }
        for(int i=1;i<=n;i++){
            cout<<"*";
        }
        cout<<endl; 
    }    
}

// Print the following pattern
// Sample Input : n= 4
// Output :
// 1
// 1 2
// 1 2 3
// 1 2 3 4
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=i;j++){
            cout<<j;
        }
        cout<<endl; 
    }    
}

// Print the following pattern
// Input : n = 4
// Output :
//      A
//    A B
//   A B C
// A B C D
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<n;i++){
        for(int j=1;j<=n-i;j++){
            cout<<" ";
        }
            for(int j=1;j<=i+1;j++){
                cout<<char(j+64);
            }
            cout<<endl;
        }
  }

  // Print the following pattern
// Input: n = 4
// Output:
// 1
// 2 1
// 3 2 1
// 4 3 2 1
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=i;j>=1;j--){
            cout<<j;
        }
        cout<<endl;
    }
}

// Print the following pattern
// Input: n = 4
// Output:
//   *
//  **
// ***
//****
// ***
//  **
//   *
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n-i;j++){
            cout<<" ";
        }
        for(int l=1;l<=i;l++){
            cout<<"*";
        }
        cout<<endl;
    }
    int m=n-1;
        for(int i=1;i<=m;i++){
        for(int j=1;j<=i;j++){
            cout<<" ";
        }
        for(int l=1;l<=n-i;l++){
            cout<<"*";
        }
        cout<<endl;
    }
}
