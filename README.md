# repositorio_com-n
#include <iostream>
using namespace std;
int main () {
	int numero1=0, numero2=0, result;
	int num, num2, result1; 
	double num1, num3, result2; 
	cout << "introduce primer para la resta numero:  ";
	cin >> numero1;
	cout << "introduce segundo para la resta numero:  ";
	cin >> numero2;
	result = numero1 - numero2;
	cout << "el resultado es   : " << result << endl; 
	cout << "introduce numero para la multiplicacion: ";
	cin >> num;
	cout <<"introduce segundo numero: ";
	cin >> num2;
	result1 = num * num2;
	cout <<"el resultado es :" <<result1 << endl;
	cout <<"introduce numero para la division: ";	
	cin >> num1;
	cout <<"introduce segundo numero para la division: " ;
	cin >> num3;	
	result2 = num1 / num3;
	cout << "el resultado es   : " << result2 << endl;
	cout << endl;
}