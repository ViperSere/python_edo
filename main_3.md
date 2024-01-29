# While e cicli

si ripete un'operazione fino a quando è verificata una condizione

la variabile i va a contare e fino a quando al variabile i è minore di 6 continua a stampare.
i è un operatore di assegnazione quindi mi prendi i e mi sommi 1, lo vado ad incrementare di 1 ogni volta.

```
i = 1
while i < 6:
    print(i)
    i += 1
print("fine ciclo")

1
2
3
4
5
fine ciclo

```
Quando il ciclo finisce ovvero quando il numero diventa uguale a 6 allora andrà a stampare altro al di fuori del ciclo.

### break, continue, else

break serve a tagliare

```
i = 0
while i < 9:
    print(i)
    if i == 3:
        break
    i += 1
print("il ciclo si è stoppato a 3")

0
1
2
3
il ciclo si è stoppato a 3

```
continue fa saltare un valore ma non blocca il ciclo 

```
i_2 = 0
while i_2 < 5:
    i_2 += 1
    if i_2 == 3:
        continue
    print(i_2)

1
2
4
5

```
else usato quando devo tenere traccia della fine del ciclo

```
i_3 = 0
while i_3 < 6:
    print(i_3)
    i_3 += 1
else:
    print ("ciclo finito")

0
1
2
3
4
5
ciclo finito

```
#for

uso per iterare una sequenza

```
lista_città = ["milano", "roma", "napoli"]
for città in lista_città:
    print(città)

milano
roma
napoli

stringa = "anguria"
for carattere in stringa:
    print(carattere)

a
n
g
u
r
i
a

for x in range(6):
    print(x)

0
1
2
3
4
5

for x in range(6):
    if x == 3:
        break
    print(x)
else:
    print("ciclo finito")

0
1
2

for y in range(6):
    if y == 3:
        continue
    print(y)
else:
    print("ho finito")

0
1
2
4
5
ho finito

for riga in range(4):
    for colonna in range(2):
        print("(" + str(riga) + ":" + str(colonna) + ")")
       
(0:0)
(0:1)
(1:0)
(1:1)
(2:0)
(2:1)
(3:0)
(3:1)

```
innesto il for quando devo passare orizzontalmente e verticalmente in contemporanea 
