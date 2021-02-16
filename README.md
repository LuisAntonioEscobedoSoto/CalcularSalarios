# CalcularSalarios

#include <iostream>

using namespace std;
void calcularSalarios(int ct[], int st[], int ht[]){
for(int i=0; i<=2; i++){
 cout<<"codigo: "<<ct[i]<<"salarios x hr: "<<st[i]<<"horas: "<<ht[i]<<endl;
 cout<<endl;
}
for(int i=0; i<=2; i++){
 cout<<"codigo: "<<ct[i]<<"total: "<<st[i] * ht[i]<<endl;
}
}

int main()
{
    int codigo_trabajadores[]= {101,202,203};
    int salario_trabajadores[]= {100,200,400};
    int horas_trabajadores[]= {90,45,20};
    calcularSalarios(codigo_trabajadores,salario_trabajadores,horas_trabajadores);
    return 0;
}
