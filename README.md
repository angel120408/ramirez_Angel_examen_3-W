#Examen Del Primer Parcial. Codigo Creado Por Ramirez Torres Angel Manuel De 3°W
-  Solicitar al usuario un número natural y verificar que el número
ingresado se encuentre dentro de la primera docena de números naturales,
es decir entre el 1 y el 12.


print(" ")#Espacio entre lineas
print("-INSTRUCCIONES-")# Imprime las instrucciones del codigo 
print("Solicitar al usuario un número natural y verificar que el número ingresado se encuentre dentro de la primera docena de números naturales,es decir entre el 1 y el 12.")
print(" ")#Espacio entre lineas

print(" ")
d = "Examen del primer parcial:" #Se declara la variable 'd'
a = "/ Alumno: Ramirez Torres Angel Manuel"#Se declara la variable 'a'
b = "/ Grado y Grupo: 3°W"#Se declara la variable 'b'
c = "/ Mi numero de contro es: 1206"#Se declara la variable 'c'
espacio = (" ")#Se declara la variable 'espacio'

info = d +espacio + a + espacio + b + espacio + c #Aqui se juntan los valores (d, a, b, c, espacio) para crear una sola variable 
print (info)#Muestra el contenido de la variable 'info'
print(" ")

# Solicitar un número natural al usuario
numero = int(input("Ingresa un número natural: "))

# Verificar si el número está dentro de la primera docena (entre 1 y 12)
if 1 <= numero <= 12:
    print(f"El número {numero} está dentro de la primera docena de números naturales.")
else:
    print(f"El número {numero} no está dentro de la primera docena de números naturales.")


![image](https://github.com/user-attachments/assets/9ba6eabb-32a8-4cef-942e-f82ea1658964)
![image](https://github.com/user-attachments/assets/76a53c2d-bc6a-469e-a16d-3eac8dfcb7e3)
