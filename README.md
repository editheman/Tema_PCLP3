# Tema_PCLP3 - Titanic

## Timp de rezolvare

A durat aproximativ 2 zile calendaristice sa implementez cerintele cerute,
folosind cat de des se poate github pentru a mi sincroniza munca, si a fi sigur
ca in caz de corupere a fisierului in care lucrez, am o copie online pe care
o pot accesa in acest caz nefavorabil.

> **NOTE:** Chiar daca am facut singur proiectul, lucrul cu git mi a fost foarte
folositor deoarece mi am reamintit ultimele parti din materia de USO si m a 
facut sa fiu mai confortabil cu a lucra la proiecte mai mari folosind git.



> ***NOTE:*** link de github: 
```bash
https://github.com/editheman/Tema_PCLP3.git
```

## Descrierea codului

### Cerinta 1:

Codul citeste fisierul ```train.csv``` folosind Pandas, afiseaza informatii despre 
datele incarcate si analizeaza setul de date pentru valori lipsa si duplicate. 
Mai intai, utilizeaza `data.info()` pentru a obtine si a tipari informatii despre 
tipurile de date si numarul de intrari din fiecare coloana. Apoi, calculeaza si 
afiseaza numarul de valori lipsa, duplicate si totalul de randuri si coloane.

### Cerinta 2:

Aceasta functie calculeaza si afiseaza procentele de supravietuire, distributia 
pe clase si distributia pe sexe dintr-un set de date. Foloseste `value_counts` 
cu `normalize=True` pentru a obtine procentele, le afiseaza sub forma de 
grafice folosind Matplotlib si Seaborn. Graficele reprezinta procentul de 
supravietuire, distributia pe clase si distributia pe sexe.

### Cerinta 3:

Aceasta functie selecteaza coloanele numerice dintr-un set de date Pandas. 
Pentru fiecare coloana numerica, creeaza un grafic de tip histogram folosind 
Seaborn. Histogramele afiseaza distributia valorilor pentru fiecare coloana 
numerica.

### Cerinta 4:

Aceasta functie identifica coloanele cu valori lipsa intr-un set de date Pandas.
Calculeaza si afiseaza numarul si procentul valorilor lipsa pentru fiecare
coloana. De asemenea, afiseaza procentul valorilor lipsa pentru fiecare clasa de
supravietuire.

### Cerinta 5:

Aceasta functie imparte varsta pasagerilor in categorii si le adauga in
setul de date. Calculeaza numarul de pasageri pentru fiecare categorie de varsta
si il afiseaza. Foloseste Seaborn pentru a crea un grafic cu distributia
pasagerilor pe categorii de varsta.

### Cerinta 6:

Aceasta functie calculeaza numarul de barbati supravietuitori pentru fiecare 
categorie de varsta. Afiseaza rezultatele grupate pe categorii de varsta folosind 
`print`. Creeaza un grafic Seaborn pentru a vizualiza numarul de barbati 
supravietuitori in fiecare categorie de varsta.

### Cerinta 7:

Aceasta functie calculeaza si afiseaza procentul copiilor din setul de date. 
De asemenea, calculeaza rata de supravietuire a copiilor si adultilor. 
Creeaza un grafic cu ratele de supravietuire pentru copii si adulti folosind
Seaborn.

### Cerinta 9:

Aceasta functie extrage titlurile din numele pasagerilor din setul de date. 
Creeaza un tabel incrucisat pentru a potrivi titlurile cu genurile pasagerilor. 
Afiseaza un grafic Seaborn cu distributia titlurilor, rotind etichetele pe axa X.

### Cerinta 10:

Aceasta functie creeaza un subset de date care contine primele 100 de randuri. 
Apoi, foloseste Seaborn pentru a crea un grafic swarm plot care arata relatia 
dintre clasa calatoriei, supravietuire si sexul pasagerilor din subsetul de date.

