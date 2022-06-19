# EMTECH
EVIDENCIAS DE CERTIFICACIÓN
# Ejercicio Retador 1
# Funciones y operaciones básicas en Python
hom=1494815
muj=1532128
Cul=33.15
Maz=16.57
pob_tot=hom+muj
por_tot=Cul+Maz
tma=25.45
clima="Calido, subhumedo, seco y semiseco."

# Ejercicio Retador 2
# Índices y listas
habitantes,municipios=[],[]
for x in range(3):
    municipios.append(input("ingresa el nombre de tu municipio: "))
    habitantes.append(int(input("ingresa el numero de habitantes del municipio: ")))
print("El total de habitantes es: ",sum(habitantes))
print("El promedio de habitantes : ",(sum(habitantes)/3))


# Ejercicio Retador 3
# Manejo de operadore
cme=int(input("Ingresa el numero de costales de Cemento que requiere: "))
yes=int(input("Ingresa el numero de costales de Yeso que requiere: "))
total=(cme*30)+(yes*40)
if total>=1627 and total <= 3254:
    print("Se puede realizar el envio: True")
else:
    print("Se puede realizar el envio: False")

# Ejercicio Retador 4
# Sentencias condicionales: if, if-else, if-elif-else

idprod=0
cajas=int(input("Ingresa el numero de cajas a vender: "))
idprod=int(input("Ingresa el ID del producto: "))

if idprod==1:
    print("El producto es Maiz de Grano")
    print("El precio por caja es: $285.55")
    print("El precio total a pagar es :",cajas*285.55)
elif idprod==2:
    print("El producto es Pepino")
    print("El precio por caja es: $334.72")
    print("El precio total a pagar es :",cajas*334.72)
elif idprod==3:
    print("El producto es Tomate verde")
    print("El precio por caja es: $129.00")
    print("El precio total a pagar es :",cajas*129.00)
else:
    print("El producto no existe")
