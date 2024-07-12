

#include<iostream>
using namespace std;
int main(){

    int choice, a, b,s;
    float o,c,d;
    cout<<"enter the value of a\n";
    cin>>a;
    cout<<"enter the value of b\n";
    cin>>b;
    cout<<"1.addition\n 2. subtraction\n 3.multiplication\n 4. division\n";
    cout<<"enter the operation to perform"<<endl;
    cin>>choice;


    switch(choice){

        case 1:
         cout<<"the addition of a and b \n";
          s=a+b;
         cout<<s<<endl;
         break;
          case 2:
         cout<<"the subtraction of a and b \n";
          s=a-b;
         cout<<s<<endl;
          break;
          case 3:
         cout<<"the multiplication of a and b \n";
         s=a*b;
         cout<<s<<endl;
         break;
          case 4:
            
             c= int (a);
             d= int(b);
           if(b!=0)
               cout<<"the division of a and b \n";
           o=c/d;
           
           cout<<o<<endl;
          break;
       
       
        default:
        cout<<"operation is not possible\n";
        break;

          }
    
return 0;
}


