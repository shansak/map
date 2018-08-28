#include<iostream>
#include<map>

using namespace std;

int main()
{
    map<int,string>d;
    d[10]="nitin";
    d[20]="balli";
    d[30]="khushi";
    d[40]="aditi";
    d.insert(pair<int,string>(50,"sakshi"));

    map<int,string>::iterator t=d.begin();
    while(t!=d.end())
    {
        cout<<t->second<<endl;
        t++;
    }
    cout<<d.at(30);

}
