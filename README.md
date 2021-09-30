# 30-days-of-code
'''C++ Lesson 3.
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
  '''C++ lesson 6
 #include <iostream>

using namespace std;

int main()
    {
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
    }
  ...
    '''C++ Lesson 7
    #include <iostream>

using namespace std;

int main()
    {
    int n,i,j,k,l;      //sonlarni xar xilligini tekshirish
    cout<<"uch xonali sonni kiriting: "; cin>>n;

    i=n%10; //birlik
    n/=10;

    j=n%10; //o'nlik
    n/=10;

    l=n%10; //yuzlik
    if (!(i==j||j==l||i==l)) cout<<"true";
    else cout<<"false";
    return 0;
    }
    '''
    ...C++  Lesson 9      //karra jadval tuzish 
    int m;  
       cin>>m;
     for (int i=1; i<=10; i++){

        cout<<m<<" * "<<i<<" = "<<i*m<<endl;
     }
    ...
    ...C++ Lesson 12
                                            
      //berilgan songa teng qadamlar bilan fibonachi sonnini aniqlash;
       void fibonachi(int n){
       int f1=1,f2=1,a=1;
       while (n>a){
        int f3=f1+f2;
        f1=f2;
        f2=f3;
        cout<<f3<<",";
        a++;
       }
       }
       int main(){
           int n; cin>>n;
           fibonachi(n);
       }                                      
      ...                                      
                                            
                                            
                                            
                                            
                                            
                                            
