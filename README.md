# PR1_SEGUNDO_PARCIAL

#imprime el nombre y grupo de la autora

print("Jimenez Gamboa Issis Alexa")

print("3ro W")


#imprime la fecha de hoy

import datetime

x = datetime.datetime.now()

print(x)


#se imprime el titulo del bellisimo programa 

print("PRACTICA 1, SEGUNDA UNIDAD")

print("") #imprime una linea en blanco tipo para que se vea mas limpio el programita 

# Programa no.1: Imprimir lista 
#se almacena una lista 

thislist = ["43", "57", "92", "20", "37", "5", "9"]


#imprime la lista 

print(thislist)

#Indica que numero es mayor y menor dentro de la lista 

mayor = max(thislist)

menor = min(thislist)


#Imprime lo anterior dicho 

print("El numero mayor de la lista es:", mayor)

print("El numero menor de la lista es:", menor)


#se imprime una linea en blanco 

print("")


# Programa no.2: Almacenar materias y desplegarlas

#Se crea una lista con las materias

materias = ["Pensamiento matematico", "Ingles", "Español", "Quimica", "Fisica"]

print("Materias del curso:", ", ".join(materias))


# Programa no.3: Mensaje para cada materia

for materia in materias:

    print(f"Estoy cursando {materia}")


# Programa no.4: Calificaciones por materia

calificaciones = {}

for materia in materias:

    calificaciones[materia] = input(f"Ingrese la calificación para {materia}: ")
    
for materia, calificacion in calificaciones.items():

    print(f"En {materia} has obtenido {calificacion}")


# Programa no.5: Números triunfadores de la lotería

numeros_triunfadores = []

while True:

    numero = input("Ingrese un número triunfador (o 'fin' para terminar): ")
    
    if numero.lower() == 'fin':
    
        break
        
    numeros_triunfadores.append(int(numero))
    
print("Números triunfadores (ordenados):", sorted(numeros_triunfadores))


# Imagenes
![image](https://github.com/user-attachments/assets/ba73c5bb-9cb9-4615-a746-f495f2071336)

![image](https://github.com/user-attachments/assets/1df1c1fa-fc1c-448b-aa20-0f854f5067c7)
