# Lazo_Angel_1190_3W_Pr3
prueba de envio del codigo y de screenshot
print ("Lazo Jimenez Angel Jesus 3W")

divisas = {'Euro': '€', 'Dollar': '$', 'Yen': '¥'} #Este es el diccionario de las divisas

divisa = input("Introduce una divisa (Euro, Dollar, Yen): ") #En esta linea se le pide al usuario que ingrese una de las divisas que estan en el diccionario 

if divisa in divisas: #Verifica si la variable "divisa" esta en el diccionario
    print(f"El símbolo de {divisa} es: {divisas[divisa]}") #Si la divisa esta en el diccionario se imprime el simbolo de la divisa
else: 
    print("La divisa no está en el diccionario.") #Si la divisa ingresada no esta en el diccionario se imprime un mensaje de error
![image](https://github.com/user-attachments/assets/b27ad744-7d83-40a7-89ba-e18b3d4c77ff)
print ("Lazo Jimenez Angel Jesus 3W")

nombre = input("Introduce tu nombre: ") #En esta linea se pide al usuario que ingrese su nombre
edad = input("Introduce tu edad: ") #En esta linea se le pide al usuario ingresar su edad
direccion = input("Introduce tu dirección: ") #En esta linea se le pide ingresar su direccion
telefono = input("Introduce tu número de teléfono: ") #En esta linea se ingresa el numero de telefono del usuario

informacion_de_usuario = {
    "nombre": nombre,
    "edad": edad,
    "direccion": direccion,
    "telefono": telefono
} #De las lineas 8 a 13, es el diccionario donde se guarda la informacion del usuario

print(f"{informacion_de_usuario['nombre']} tiene {informacion_de_usuario['edad']} años,") #En esta linea se acomodan los datos de el nombre y edad del usuario 
print(f"vive en {informacion_de_usuario['direccion']} y su número de teléfono es {informacion_de_usuario['telefono']}.") #En esta linea se acomodan los datos de la direccion y numero de telefono del usuario

![image](https://github.com/user-attachments/assets/e9e79007-13e3-4426-a5a7-5ca420b4a59c)
print ("Lazo Jimenez Angel Jesus 3W")

precios_frutas = {
    "manzana": 3.0,  
    "plátano": 2.5,
    "naranja": 4.0,
    "fresa": 5.0
} #Esta linea es el diccionario donde se registran las frutas disponibles y sus precios 

fruta = input("Introduce el nombre de la fruta: ") #En esta linea se le pide al usuario que ingrese el nombre de la fruta

kilos = float(input("Introduce el número de kilos: ")) #En esta linea se le pide al usuario que se ingrese cuantos kilos quiere de la fruta

if fruta in precios_frutas: #El "if" es para verificar si la fruta ingresada esta en el diccionario
    precio_total = precios_frutas[fruta] * kilos #Esta linea es para que el precio de la fruta se multiplique por el kilo ingresado
    print(f"El precio de {kilos} kilos de {fruta} es: ${precio_total:.2f}") #Esta linea es para que se ponga un el comentario final 
else:
    print(f"La fruta '{fruta}' no está en el diccionario.") #Esta linea es por si el usuario ingresa una fruta que NO esta en el diccionario
    ![image](https://github.com/user-attachments/assets/22dc5cb3-799b-4a89-822d-ca90fa488499)

