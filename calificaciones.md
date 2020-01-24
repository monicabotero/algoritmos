
**Promedio ponderado**

Proceso Promedioponderado

	Definir P1, P2, Participa, Final, N1, N2, N3, N4, PP Como Real
	
	P1<-0.25
	
	P2<-0.25
	
	Participa<-0.2
	
	Final<-0.3
	
	Escribir "Introduzca la nota obtenida en el primer parcial"
	
	Leer N1
	
	Escribir "Introduzca la nota obtenida en el segundo parcial"
	
	Leer N2
	
	Escribir "Introduzca la nota obtenida por participación"
	
	Leer N3
	
	Escribir "Introduzca la nota obtenida en el parcial final"
	
	Leer N4
	
	pp<-((P1*N1) + (P2*N2) + (Participa*N3) + (Final*N4))/ (P1+ P2+ Participa + Final)
	
	Escribir "Su promedio ponderado para este curso es:", pp
	
FinProceso
