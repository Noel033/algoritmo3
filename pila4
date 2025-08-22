# llenar pilaFia con los 15 primeros numeros consecutivos
#eliminas el tercero y septimo y lo imprimes nuevamente

pilafia = []
# Llenar la pila con 15 números (del 1 al 15)
for i in range(1, 16):
    pilafia.append(i)

print("Pila original:", pilafia)

aux = []
eliminar_indices = [2, 6]  # Tercero y séptimo desde el fondo
eliminados = []

# Sacar elementos y guardar temporalmente
contador = 0
while pilafia:
    elemento = pilafia.pop()
    if contador in eliminar_indices:
        eliminados.append(elemento)
    else:
        aux.append(elemento)
    contador += 1

# Restaurar la pila sin los elementos eliminados
while aux:
    pilafia.append(aux.pop())

print("Elementos eliminados:", eliminados)
print("Pila final:", pilafia)
