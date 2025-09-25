# UTN-TUPaD-Programacion1
#Crear un programa que imprima por pantalla el mensaje: “Hola Mundo!”
print("Hola Mundo!")

#Crear un programa que pida al usuario su nombre e imprima por pantalla un saludo usando el nombre ingresado
nombre = input("Ingrese su nombre: ")
print(f"Hola, {nombre}!")

#Crear un programa que pida al usuario su nombre, apellido, edad y lugar de residencia e imprima por pantalla una oración con los datos ingresados
nombre = input("Ingrese su nombre:")
apellido = input("Ingrese su apellido:")
edad = input("Ingrese su edad:")
residencia = input("Ingrese su lugar de residencia:")
print(f"Soy {nombre} {apellido}, tengo {edad} años y nací en {residencia}")

#Crear un programa que pida al usuario el radio de un círculo e imprima por pantalla su área y su perímetro
radio = input("Ingrese el radio del círculo:")
radio = int(radio)
pi = 3.14 
pi = float(pi)
area = pi * radio ** 2 
perimetro = 2 * pi * radio 
print(f"El área del circulo es de {area}, y su perimetro {perimetro}")

#Crear un programa que pida al usuario una cantidad de segundos e imprima por pantalla a cuántas horas equivale
segundos = input("Ingrese la cantidad de segundos:")
segundos = int(segundos)
horas = segundos / 3600
horas = float(horas)
print(f"{segundos} segundos equivalen a {horas} horas")
         
#Crear un programa que pida al usuario un número e imprima por pantalla la tabla de multiplicar de dicho número
numero = input("Ingrese un numero:")
numero = int(numero)
print(numero, " * 1 = ", numero*1)
print(numero, " * 2 = ", numero*2)
print(numero, " * 3 = ", numero*3)
print(numero, " * 4 = ", numero*4)
print(numero, " * 5 = ", numero*5)
print(numero, " * 6 = ", numero*6)
print(numero, " * 7 = ", numero*7)
print(numero, " * 8 = ", numero*8)
print(numero, " * 9 = ", numero*9)
print(numero, " * 10 = ", numero*10)

#Crear un programa que pida al usuario dos números enteros distintos del 0 y muestre por pantalla el resultado de sumarlos, dividirlos, multiplicarlos y restarlos
n1 = input("Ingrese el primer número:")
n2 = input("Ingrese el segundo número:")
print(n1, "+", n2, "=", int(n1)+int(n2))
print(n1, "-", n2, "=", int(n1)-int(n2))
print(n1, "*", n2, "=", int(n1)*int(n2))
print(n1, "/", n2, "=", int(n1)/int(n2))

#Crear un programa que pida al usuario su altura y su peso e imprima por pantalla su índice de masa corporal
altura = input("Ingrese su altura en cm:")
peso = input("Ingrese su peso en kg:")
print("Su IMC es de = ", int(peso)/(int(altura)**2))

#Crear un programa que pida al usuario una temperatura en grados Celsius e imprima por pantalla su equivalente en grados Fahrenheit
celsius = input("Ingrese la temperatura en celsius:")
print(celsius, "grados celsius equivalen a ", 9/5 * float(celsius) + 32, "grados Fahrenheit")

#Crear un programa que pida al usuario  3 números e imprima por pantalla el promedio de dichos números
num1 = input("Ingrese el primer numero:")
num2 = input("Ingrese el segundo numero:")
num3 = input("Ingrese el tercer numero:")
print("El promedio de los tres números es de: ", (int(num1)+int(num2)+int(num3))/3) 