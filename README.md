# 4-bit-binary
convert decimal number to 4 bit binary

#include <bits/stdc++.h>

using namespace std;

int binary(int n)

{

    int arr[4]={0};

    int i=0;

    while(n>0)

    {

        arr[i]=n%2;

        n/=2;

        i++;

    }

    for(int i=3;i>=0;i--)

    {

        cout<<arr[i];

    }

        return 0;

}

int main()

{

    int n;

    cin>>n;

    binary(n);

    return 0;

}
