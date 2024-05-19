Algoritmo Primos_Gemelos
	Definir N1, N2, i, contador1, contador2 Como Entero
	Escribir "Ingrese el primer número:";
	Leer N1;
	Escribir "Ingrese el segundo número:"
	Leer N2;
	contador1 <- 0
	contador2 <- 0
	Para i <- 1 Hasta N1 Hacer
		Si N1 mod i = 0 Entonces
			contador1 <- contador1 + 1
		FinSi
	FinPara
	Para i <- 1 Hasta N2 Hacer
		Si N2 mod i = 0 Entonces
			contador2 <- contador2 + 1
		FinSi
	FinPara
	Si contador1 = 2 Y contador2 = 2 Y abs(N1 - N2) = 2 Entonces
		Escribir N1, " y ", N2, " son primos gemelos"
	Sino
		Escribir N1, " y ", N2, " no son primos gemelos"
	FinSi
FinAlgoritmo

