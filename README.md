# acode
#include <iostream>
#include <cstdio>
using namespace std;
 
int main() {
    long long n,k,j,t,o,sum;
    cin>>n;
    cin>>k;
    cin>>t;
    sum=(n*k*t)/100;
    o=sum/k;
    j=sum%k;
    for(int i=0;i<o;i++)
    {
      cout<<k<<" ";
    }
    cout<<j<<" ";
    o++;
    for(int op=o;op<n;op++)
    {
        cout<<"0 ";
    }
    return (0);
}
