##Pseint 
Algoritmo TernaPitagorico
    //DEFINIREMOS LAS VARIABLES
	Definir a, b, c, rango como Entero
    rango <- 500 // establece el limite de numeros enteros
    
    Escribir "Trio pitagorico:"
    
	//validara la formula para comprobar cuantos resultados pueden dar un trio pitagorico
    Para a <- 1 hasta rango hacer
	Para b <- 1 hasta rango hacer
	Para c <- 1 hasta rango hacer
		Si a^2 + b^2 = c^2 entonces
		Escribir a, ", ", b, ", ", c
			Fin Si
            Fin Para
			Fin Para
			Fin Para
    
FinAlgoritmo

##Pythom
if __name__ == '__main__':
	# DEFINIREMOS LAS VARIABLES
	a = int()
	b = int()
	c = int()
	rango = int()
	rango = 500
	# establece el limite de numeros enteros
	print("Trio pitagorico:")
	# validara la formula para comprobar cuantos resultados pueden dar un trio pitagorico
	for a in range(1,rango+1):
		for b in range(1,rango+1):
			for c in range(1,rango+1):
				if a**2+b**2==c**2:
					print(a,", ",b,", ",c)


 ##C++    
     
#include<iostream>
#include<cmath>
using namespace std;


int main() {
	int a;
	int b;
	int c;
	int rango;
	rango = 10;
	// establece el limite de numeros enteros
	cout << "Trio pitagorico:" << endl;
	for (a=1; a<=rango; ++a) {
		for (b=1; b<=rango; ++b) {
			for (c=1; c<=rango; ++c) {
				if (pow(a, 2)+pow(b, 2)==pow(c, 2)) {
					cout << a << ", " << b << ", " << c << endl;
				}
			}
		}
	}
	return 0;
}

