# 30-days-of-code
''C++ Lesson 3.
#include <iostream>

using namespace std;

int main()

{
    // soat va mitutni sekunda chiqarish, 10_36
   
    int h;
    int m;
    cout<<"Vaqtni kiriting"<<endl;
    cin>>h;
    cin>>m;

    cout<<"Minutda="<<h*60+m<<endl;
    cout<<"Sekuntda="<<h*3600+m*60<<endl;
    return 0;
}
'''
'''C++ Lesson 4.
#include <iostream>

using namespase std;

int main()
{

    //uch xonali sonni teskarisini chiqarish
    
int a,b,c,d,f;
    cin>>a;
    b=a/100;
    c=a/10-b*10;
    d=a%10;
    f=d*100+c*10+b;
    cout<<"Natija "<<f;
    return 0;
    }
    '''
  ...C++ lesson 6
 
     //sonni qiymatini o'zgartirish
     int a,b,c,d,f;
     cout<<"kiriting: "; cin>>a;
     cout<<"kiriting: "; cin>>b;
     a=a+b;
     b=a-b;
     a=a-b;

     cout<<a<<endl;
     cout<<b;
     return 0
  ...
