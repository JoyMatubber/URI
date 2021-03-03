#include <bits/stdc++.h>

using namespace std;

int main()
{
    float a,b,c;
    cin>>a>>b>>c;
    if(a<(b+c) &&b<(c+a)&& c<(a+b))
    {

        double s=a+b+c;
        cout<<fixed<<setprecision(1)<<"Perimetro = "<<s<<endl;

    }

    else
    {

        double s=(a+b)*c/2;
        cout<<fixed<<setprecision(1)<<"Area = "<<s<<endl;
    }
    return 0;
}
