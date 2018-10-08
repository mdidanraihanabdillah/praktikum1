# praktikum1

##latihan1.cpp : Program menghitung luas persegi panjang

*Alur algoritma*

1. mendeklerasikan variable int `A, T` sebagai variable input
2. mengisi nilai variable input dengan nilai tertentu, misal: `A = `dan `T = `
3. menghitung luas dengan rumus `L = A * T`
4. mencetak hasil kelayar. `cout << L << endl;`

*berikut code lengkapnya:*

```c++
#include <iostream>
#include "conio.h"
using namespace std;
int main ()
{
    float p,l;
    cout<<"::: sofware penghitung luas persegi panjang :::"<<endl;
    cout<<"masukan nilai panjang =";
    cin>>p;
    cout<<"masukan nilai lebar =";
    cin>>l;
    cout<<"luas persegi panjang =";
    cout<<(p*l) ;
    return 0;
}
