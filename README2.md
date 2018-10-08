latihan2.cpp
Mencari luas segitiga
Masukan nilai alas segitiga (a) dan nilai tinggi segitiga (t),
menghitung luasnya dengan alas dan tinggi tertentu.
Luas segitiga dihitung dengan rumus L= 1/2*a*t,
nilai luas (L)

berikut cara penyelesaiannya

#include<iostream>
int main () {

    int A, T;

    float L;

    A = 5;

    T = 7;

    L = A = T / 2.0;

    std::cout << "Program Menghitung Luas Segitiga" << std::endl;

    std::cout << "Alas segitiga = " << A << std::endl;

    std::cout << "Tinggi segitiga = " << T << std::endl;

    std::cout << "Luas segitiga adalah = " << L << std::endl;
}