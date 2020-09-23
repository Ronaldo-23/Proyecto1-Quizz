#Proyecto: Cuestionario sobre Xelajú M.C
#Autores: Ronaldo Barrios y Bryan Sajche
#Carnets: 1660520, 1530420
#Cuestionario Superchivo sobre el Club departamental más Grande!

from screen import clear
from time import sleep
cont=0

print('Hola! Espero te encuentres bien :)')
print('Vamos a ponerte a prueba con este cuestionario si eres un Superchivo que siente los colores')
sleep(5)
clear() 
sleep(1)
name = input("Ingresa tu nombre: ")
gen =  input("Ingresa tu género: ")
clear() 
sleep(1)
a = input("""¿Cuál es el año en el que se fundo el Club Xelajú M.C?
1. 1942
2. 1945
3. 1962
4. 1978
""")
a= int(a)
if a == 1:
    cont=5
else:
    cont=cont
clear() 
sleep(1)
b = input("""¿Quien es el goleador historico del equipo?
1. Juan Carlos Plata
2. Kamiani Félix
3. Carlos"El pescadito" Ruiz
4. Israel silva
""")
b= int(b)
if b == 4:
    cont=cont+5
else:
    cont=cont
clear() 
sleep(1)
c = input("""¿Cuántos campeonatos de liga a ganado Xelajú?
1. 2 Lunas
2. 3 Lunas
3. 5 Lunas
4. 1Luna
""")
c= int(c)
if c == 3:
    cont=cont+5
else:
    cont=cont
clear() 
sleep(1)
d = input("""¿Cuál es su mascota?
1. Chivo
2. León
3. Toro
4. Jaguar
""")
d= int(d)
if d == 1:
    cont=cont+5
else:
    cont=cont
clear() 
sleep(1)
e = input("""¿Cuál es el campeonato mas iconico del Xelajú?
1. 2012
2. 1996
3. 2007
4. 1962
""")
e= int(e)
if e == 2:
    cont=cont+3
else:
    cont=cont
clear() 
sleep(1)
f = input("""¿A qué equipo mexicano elimino Xelaju en la Concachampions?
1. Monterrey 
2. Tigres
3. América
4. Chivas
""")
f= int(f)
if f == 4:
    cont=cont+5
else:
    cont=cont
clear() 
sleep(1)
g = input("""¿Hasta donde llego Xelajú en su mejor participacion en la Concachampions?
1. Final 
2. Cuartos
3. Semifinales
4. Fase de grupos
""")
g= int(g)
if g == 2:
    cont=cont+3
else:
    cont=cont
clear() 
sleep(1)
h = input("""¿Cuántas victorias tiene Xelajú en la liga?
1. * 
2. *
3. *
4. *
""")
h= int(h)
if h == 2:
    cont=cont+3
else:
    cont=cont
clear() 
sleep(1)
i = input("""¿Como se llama el estadio donde juega el equipo de Xelajú?
1. Mario Camposeco 
2. Marquesa de la ensenada
3. David Ordoñez Vardales
4. Israel Barrios
""")
i= int(i)
if i == 1:
    cont=cont+3
else:
    cont=cont
clear() 
sleep(1)
j = input("""¿En qué año se fundo el estadio de Xelajú?
1. 1945 
2. 1956
3. 1950
4. 1949
""")
j= int(j)
if j == 3:
    cont=cont+5
else:
    cont=cont
clear() 
sleep(1)
k = input("""¿En qué año gano su primera luna Xelajú?
1. 1996 
2. 1956
3. 1979
4. 1962
""")
k= int(k)
if k == 4:
    cont=cont+5
else:
    cont=cont
clear() 
sleep(1)
l = input("""¿Qué jugador de alto nivel vino a jugar a Xelajú?
1. Israel Silva
2. Mauricio Copete
3. Marco Pappa
4. David Montsalve
""")
l= int(l)
if l == 3:
    cont=cont+3
else:
    cont=cont
clear() 
sleep(1)
#Genero femenino
if cont == 50 and (gen == 'Femenino' or gen == 'FEMENINO' or gen == 'femenino'):
    print(str(name) + ' tu eres una Superchiva 100% que siente los colores y estas orgullosa de esta tierra') 
elif (cont < 50  and cont >= 25) and (gen == 'Femenino' or gen == 'FEMENINO' or gen == 'femenino'):
    print(str(name) + ' tu eres una Superchiva de ratos') 
elif cont < 25  and (gen == 'Femenino' or gen == 'FEMENINO' or gen == 'femenino'):
    print(str(name) + ' tu eres una Superchiva infiel') 
#Genero masculino
if cont == 50 and (gen == 'Masculino' or gen == 'MASCULINO' or gen == 'masculino'):
    print(str(name) + ' sos un Superchivo al 100% que siente los colores y esta orgulloso de esta tierra') 
elif (cont < 50  and cont >= 25) and (gen == 'Masculino' or gen == 'MASCULINO' or gen == 'masculino'):
    print(str(name) + ' sos un Superchivo de momentos') 
elif cont < 25  and (gen == 'Masculino' or gen == 'MASCULINO' or gen == 'masculino'):
    print(str(name) + ' sos un Superchivo infiel')
#Para que cuando lo compile el inge le funcione
input('')