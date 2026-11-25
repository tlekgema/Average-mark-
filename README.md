#include <iostream>

using namespace std;

int main()
{
    double mark1,mark2,mark3,mark4,mark5;
    double average;
    cout<<"Enter yr test mark 1"<<endl;
    cin>>mark1;
    cout<<"Enter yr test mark 2"<<endl;
    cin>>mark2;
    cout<<"Enter yr test mark 3"<<endl;
    cin>>mark3;
    cout<<"Enter yr test mark 4"<<endl;
    cin>>mark4;
    cout<<"Enter yr test mark 5"<<endl;
    cin>>mark5;
    cout<<"mark1:"<<mark1<<endl;
    cout<<"mark2:"<<mark2<<endl;
    cout<<"mark3:"<<mark3<<endl;
    cout<<"mark4:"<<mark4<<endl;
    cout<<"mark5:"<<mark5<<endl;

    double total = mark1+mark2+mark3+mark4+mark5;
    average = total/5;

    if(average >=85)
    {
        cout<<"Excellent you got Level 7";
    }
    else if(average >=70)
    {
        cout<<"Good you got Level 6";
    }
    else if(average >=60)
    {
        cout<<"Great you got Level 5";
    }
    else if(average >=41)
    {
        cout<<"Great you got Level 4";
    }
    else if(average >=30)
    {
        cout<<"Keep pushing you got Level 3";
    }
    else if(average <=29)
    {
        cout<<"Plz pick up you got Level 2";
    }
    else if(average <=15)
    {
        cout<<"I'm sorry need to pull up yr socks you got Level 1";
    }
    else
    {
        cout<<"Invalid Input";
    }
    cout<<" Yr average is:"<<average<<endl;
    return 0;
}
