# Variabili
contenitore di un valore o collezioni di valori

```
x = 5
y = 6
età = 34
altezza = 1.55
peso_persona = 47

```
molto importante la nomenclatura della variabile

```
x, y, z = 32, 34, 67
print(x, y, z)

x = y = z = 32
print(x, y, z)

x = 2
y = 4
z = x + y + x + x

```
Posso avere un avalore associato a più variabili e in questo caso uso uguale altrimenti metto la virgola se i valori sono diversi.

# Tipi di dati

str: x = "Serena"
int: x = 10
float: x = 5.6
bool: x = True
list: x = ["roma", "milano", "venezia"]
tupla: x = ("roma", "milano", "venezia")
dict: x = {"pane: 3", "latte: 2", "banane: 5"}
set: x = {"roma", "milano", "napoli"}
range: x = range(6)

# Casting

Convertiamo un tipo di variabile in un altro tipo convertire una stringa in un intero o un intero in un float.

```
x = "5"
x = int("5")
y = 6

print(x + y)

nome = "Serena: "
età = str(35)
print(nome + età)

x = float(4)
print(x)

```

Ho trasformato la str "5" in un numero int in modo da poter fare l'operzione e ho trasformato int 35 in stringa per poter concatenare il testo.
Nell'ultimo caso ho trasformato un int in un float da 4 a 4.0.

# Stringa

```
x = "ciao"

poesia = """ciao 
sono
serena
piacere"""

```
con i tripli apici posso mettere le stringhe in più righe

```
lista = "Jacopo"
print(lista[0])

J

frase = "Ciao sono Serena"
print(len(frase))

16

```
Ho stampato l'indice 0 della stringa e successivamente ho contato quanti caratteri ci sono nella stringa e in questo caso parto da 1.

```
frase_2 = "compro il latte"
print(frase_2[:4])

comp

print(frase_2[2:])

mpro il latte

print(frase_2[-4])

a

```
In questo caso prendiamo i caratteri da 0 a 4, tutti i caratteri tranne i primi 2 e partendo dal fondo il carattere 4.

```
frase_2 = "compro il latte"
print(frase_2.replace("o", "y"))

cympry il latte

```
vado a sostituire le lettere

```
prova = "ciao sono serena e ho {} anni"
print(prova.format(34))

prova_2 ="ho comprato {} mele"
mele = 6
print(prova_2.format(mele))

personale = "Sono alta {} m, peso {} kg e ho {} anni"
print(personale.format(1.55, 47, 34))

ciao sono serena e ho 34 anni
ho comprato 6 mele
Sono alta 1.55 m, peso 47 kg e ho 34 anni

jacopo = "Jacopo è alto {1} m, pesa {0} kg e ha {1} anni"
print(jacopo.format(1.80, 90, 28))

Jacopo è alto 90 m, pesa 1.8 kg e ha 90 anni

prova_3 = "ciao sono Serena e sono \"bella\""

ciao sono Serena e sono "bella"
```
Sono andata a prendere dei valori e li inserisco nella stringa utilizzando le parentesi graffe. 
Nell'ultimo caso ho usato gli indici nelle sostituzioni delle graffe.











