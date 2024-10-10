# pr7-Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

#7. Función que devuelve la longitud de la última palabra en una cadena

def longitud_ultima_palabra(cadena):

  # Eliminamos los espacios en los extremos y dividimos la cadena en palabras
    
   palabras = cadena.strip().split()
    
   # Si hay palabras, devolvemos la longitud de la última
    
   if palabras:
    
   return len(palabras[-1])
    
   else:
    
   # Si no hay palabras, devolvemos 0
        
  return 0


# Pedimos al usuario que introduzca una cadena

cadena_usuario = input("Introduce una cadena: ")

# Calculamos la longitud de la última palabra y mostramos el resultado

longitud = longitud_ultima_palabra(cadena_usuario)

print(f"La longitud de la última palabra es: {longitud}")

![image](https://github.com/user-attachments/assets/d7a464fb-a748-4006-ac9f-4e73ea1cf0b8)
![image](https://github.com/user-attachments/assets/7bca1e83-df3c-47e4-8756-127d59c9d882)

