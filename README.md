# Primer_Examen_Parcial_Sabatinos
1412211
#Colocamos un número al azar y se realiza la suceción factorial
numero_inicial = int(input("Coloca un número entero al azar y te dare la suma factorial: "))
sumatoria = 0
for numero in range(numero_inicial):
    sumatoria = sumatoria + (numero + 1)
  
print("La suceción factorial de tu número elegido es: ",sumatoria)
