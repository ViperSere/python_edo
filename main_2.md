# Boolean

x = True
y = False

```
print(5<10)
print(5>11)

if 5<10:
    print("sono MINORE di 10")
else:
    print("sono MAGGIORE di 10")

True
False
sono MINORE di 10

x = 0
y = 1
print(bool(x))
print(bool(y))

False
True

```
il valore 0 è sempre False mentre 1 è True

```
pane = 0
if pane:
    print("stai a casa")
else:
    print("vai a comprare il pane")

list = ["latte"]
if list:
    print("vai al supermercato")
else:
    print("non serve niente")

vai a comprare il pane
vai al supermercato

```
Dato che pane è 0 sarà false quindi else: vai a comprare il pane, se il pane fosse stato 1 ci sarebbe stato if cioè True.
Nel secondo caso se la lista fosse stata vuota ci sarebbe stato l'else (0 o False), invece essendo piena c'è l'if (1 o True).

# Operazioni aritmetiche

```
a = 5
b = 10

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a ** 2)
print(a // 2)

15
-5
50
0.5
5
25
2

```

% il modulo ci da il resto della divisione
// la flordivision risultato divisione arrotondato per difetto

```
c = 5
c = c + 2
print(c)

d = 6
d += 2
print(d)

```
Voglio assegnare un nuovo valore di c quindi al suo stesso valore assegnatogli in precedenza vado ad aggiungere 2.
Nel secondo caso voglio fare la stessa cosa ovvero aggiungere il valore 2, quindi vado a scrivere +=.
Posso usare tutti gli operatori.

### Metodi

min, max, abs, pow

```
f = min(23, 17, 278, 30)
print(f)
g = max( 3, 6, 7, 9)
print(g)
e = abs(8)
print(e)
h = pow(5,2)
print(h)

17
9
8
25

```

# if

andiamo a mettere una condizione 

```
if 10 < 20:
    print("è minore")

x = 6
if x < 10:
    print("x è minore")

y = 11
if y < 10:
    print("è minore")
    print("è vero")
    print("hai ragione")
print("non sono in if")

è minore
x è minore
non sono in if

```
Nell'ultimo caso non mi stampava nessuna condizione per che y è maggiore di 10, quindi mi ha solo stampato la frase che non era più inclusa in if.

### operatori di comparazione

==
!=
<, >
>=, <=

```
z = 10
if z == 10:
    print("condizione verificata")

w = 11
if w != 10:
    print("è diverso da 10")

condizione verificata
è diverso da 10

```
con else ed elif

```
num_2 = 11
if num_2 < 10:
    print("minore di 10")
elif num_2 == 10:
    print("uguale a 10")
else:
    print("maggiore di 10")

maggiore di 10

num_3 = 6
if 5 < num_3 < 10:
    print("è compreso tra 4 e 10")

è compreso tra 4 e 10

```
con and, or e not

```
es = 8
if es < 10 and es > 6:
    print("è compreso tra 10 e 6")

es_1 = 7
es_2 = 10
if es_1 > 4 and es_2 <3:
    print("condizione verificata")
else:
    print("condizione NON verificata")

var_1 = 3
var_2 = 10
if var_1 < 5 or var_2 > 13:
    print("condizione vera")
else:
    print("condizione falsa")

s = 11
if not(s<10): 
    print("ok")
else:
    print("non ok")

condizione NON verificata
condizione vera
ok

```
Con AND devono essere entrambe verificate invece con OR può esserlo solo una.

```
short = 88
if short < 100: print("è valido")

```
posso usare questa short hand se ho solo un print

### if innestati

numeri pari resto 0 dispari resto 1

```
inn = 9
if inn % 2 == 0:
    print("è pari")
else:
    print("è dispari")

è dispari

inn_1 = 6
if inn_1 % 2 == 0:
    print("è pari)
    if (inn_1 < 10):
        print("numero pari e minore di 10")

è pari
è pari e minore di 10

```
Ha stampato entrambi perchè sono entrambi verificati altrimenti avrebbe stampato solo uno

