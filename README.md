#NOMBRE:MARIAMEDINAAMADOR
#CARRERA ING INFORMATICA
#MATERIA: DESARR DE APP WEB
#PRACTICA2.1 NOMBRE: VOTOS


print("elige un candidato entre A,B,C")
candidato=input("candidato elegido:")
if candidato.upper()=="A":
    print("usted a votado por el partido amarrillo!")


elif candidato.upper()=="B":
    print("usted a votado por el partido morado!")
          
elif candidato.upper()=="C":
    print("usted a votado por el partido rojo!")
else: print("opcion errronea")

