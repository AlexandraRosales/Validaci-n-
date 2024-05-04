# Validacion
Programa en python para identificar la longitud de una palabra ingresada que cumpla las condiciones especificas. 
Código:
#Definimos la función verificar_palabra que toma como un argumento llamado palabra.
def verificar_palabra(palabra):
    #Con la función len() calculamos la longitud de la palabra y la guardamos en la variable longitud.
    longitud = len(palabra)
    #Con la condidicón if escribimos cual es el rango de longitud que pueden tener las palabras.
    if 4 <= longitud <= 8:
        #Imprime la leyenda si cumple con especificación anterior.
        print("Muy bien, la palabra se encuentra en el rango especificado :D")
    #En la condición elif declaramos el rango menor a 4 letras 
    elif longitud < 4:
        #Imprime la siguiente leyenda si la longitud de letras es menor junto con el numero de letras que tiene la palabra.
        print(f"Hacen falta letras. Solo tiene {longitud} letras. ):")
    else:
        #Imprime el mensaje indicando que el numero de letras que tiene la palabra excede el rango.
        print(f"¡Ups! La palabra tiene {longitud} letras. ):")

#Solicitamos al usuario que ingrese una palabra en ele rango de 8 a 4 letras y la guardamos en la variable palabra.
palabra = input("Ingrese una palabra entre 4 y 8 letras por favor:")
#Llamamos a la función verificar_palabra con la variable palabra como argumento.
verificar_palabra(palabra)
#Fin del código.

Reflexión: El bootcamp ha sido de mucha ayuda y aprendizaje para la resolución de problemas lógicos y un tanto matemáticos mostrando las posibilidades y lo útil que es la condicional if else en los programas.
Hasta el momento Python es un lenguaje muy interesante y con una sintaxis muy simple.
