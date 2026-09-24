print("="50)
print("    TALLER: ARMANDO TU PC GAMER ")
print("="50)
print()

print(" PASO 1: Elige el PROCESADOR — es el CEREBRO de la PC")
print("A) Intel")
print("B) AMD")
respuesta1 = input("¿Cuál eliges? Escribe A o B: ").upper()

if respuesta1 in ["A", "B"]:
    print(" ¡Bien! Ambos son buenos procesadores ")
else:
    print(" Solo escribe A o B")

print()
print(" PASO 2: La PLACA MADRE — donde se conecta todo")
print("  Importante: Debe coincidir con tu procesador")
placa = input("¿Ya sabes cuál vas a comprar? (sí/no): ").lower()

if placa == "sí" or placa == "si":
    print(" Perfecto, así no te equivocas al comprar ")
else:
    print(" Consejo: Pregunta en la tienda: '¿Esta placa sirve para mi procesador?'")

print()
print(" PASO 3: MEMORIA RAM — mientras más, mejor ")
ram = int(input("¿Cuántos GB quieres? "))

if ram >= 16:
    print(" ¡Eso es GAMER de verdad! 16GB o más = todo corre suave")
elif ram >= 8:
    print(" Sirve bien, pero 16GB te durará más años")
else:
    print("  Con menos de 8GB se traban los juegos grandes")

print()
print(" PASO 4: TARJETA GRÁFICA — la que dibuja los juegos ")
print("Sin esto no hay juegos melos")
grafica = input("¿Vas a comprar una dedicada? (sí/no): ").lower()

if grafica == "sí" or grafica == "si":
    print(" ¡Así se hace! Todo se verá nítido y rápido")
else:
    print("  Las integradas sirven para tareas livianas, no para juegos pesados")

print()
print(" PASO 5: ALMACENAMIENTO — donde guardas todo ")
print("SSD = rápido y carito | HDD = más lento pero más espacio")
disco = input("¿Cuál prefieres? (SSD/HDD): ").upper()

if disco == "SSD":
    print(" ¡Excelente! Enciende en segundos y los juegos cargan rapidísimo")
elif disco == "HDD":
    print(" Tienes mucho espacio para juegos y películas")
else:
    print("Escribe SSD o HDD")

print()
print("="50)
print(" ¡FELICIDADES! Ya sabes armar tu PC Gamer ")
print("Componentes clave:")
print(" Procesador +  Placa madre +  RAM +  Tarjeta gráfica +  Disco")
print("="50)
