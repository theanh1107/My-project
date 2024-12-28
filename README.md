
#include <iostream>
#include <string>
#include <math.h>
#include <unistd.h>
#include <stdlib.h>



using namespace std ;
int main() {
    cout<< " em bé à"<<endl<< sleep(1);
    cout <<" anh muốn nói là..."<< endl<<sleep(1);
    cout<<" anh yêu em bé nhiều lắm ạ😘"<<endl<<sleep(2);
    cout<<"❤️"<<endl<<sleep(1);
    cout<<"❤️"<<endl<<sleep(1);
    cout<<"❤️"<<endl<<sleep(3.6);
    cout<<"Tràn ngập bộ nhớ nhớ nhớ nhớ em"<<endl<<sleep(2.1);
    cout <<"      Cho anh cảm giác không sao quên được"<<endl<<sleep(2.1);
    cout<<".           Tràn ngập bộ nhớ nhớ nhớ nhớ em"<<endl<<sleep(2.1);
    cout<<"                 Nhưng anh mong có cảm giác này mãi"<<endl<<sleep(2.1);
     int i,j;
    for( int i =1; i< 7; i++){
for(int j=1;j<=7;j++ )
{
if(!((i==1&& (j==1||j==4||j==7)
    ||(i==4 && ( j==1|| j==7))
    || ( i==5&& ( j<=2|| j>=6))
    || ( i==6 && (j<=3||j>=5)))))
  { cout << " ❤️ ";}
    else
    cout << "   ";
    
    
} 
    cout <<""<<endl;}
    return 0;
}
