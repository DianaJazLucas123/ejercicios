# ejercicios
tareas en clase
//Nombre:Lucas Morales Diana Jazmin 
// Grupo:1TM13
// Fecha:15/marzo/2024
//

#include <iostream>
#include"Eigen/Dense"

using namespace std;
using namespace Eigen;


int x = 123;
float y = 12.58;
double pi = 3.1415926535;
char caracter = 'h';
string texto = "va entre comillas";
bool deci = 0;



int main()
{
    
    cout << "int x= " << x << endl;
    cout << "float y= " << y << endl;
    cout << "double pi= " << pi << endl;
    cout << "chat caracter= " << caracter << endl;
    cout << "texto = " << texto << endl;
    cout << "bool deci = " << deci << endl;



    MatrixXd A(3, 3);
    A << 1, 2, 3, 
         4, 5, 6, 
         7, 8, 9;   
    cout << A;
    cout << endl;
    cout << endl;

    MatrixXd B(3, 3);
    B << 1, 2, 3,
        4, 5, 6,
        7, 8, 9;    
    cout << B;
    cout << endl;
    cout << endl;

    MatrixXd C(3, 3);
    C << 1, 2, 3,
        4, 5, 6,
        7, 8, 9;
    cout << C;
    cout << endl;
    cout << endl;


    /*klseikzjklsdkoset7ut6rfu6dftfdrfujhjkio*/


    cout << "hola tu \"Juan\" como te va" << endl; 

    cout << "hola tu \nJuan\n como te va" << endl;

    cout << "hola tu \tJuan\t como te va" << endl;

    cout << "hola tu \tJuan\t como te va" << endl;
