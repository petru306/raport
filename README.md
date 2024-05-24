# raport
LOC=139
complexitatea ciclomatica total 27
complexitatea cognitiva total 37
///
In Start.java la prima linie zice ca ar trebui structurat sa fie mai usor de citit si cum este conectat de cod si ce face.
La linia 6 poate ar trebuiu schimbat numele sa fie mai usor de indentificat ce face expresia dar nu provoaca un impact.

Dar la linia 8 si 19  ar trebui schimbat cu un "logger" pentru a fi usor de accesat si securizat daca se lucreaza cu date impportante.
///
La fisierul Calculator.java linia 4 ar trebui clasa privata sa nu fie public structura codului si public static ar fi mai bine.

Linia 18 "ToString" ar trebui redenumit pentru a previni incurcari din super clasa "java.lang.object" poate provoca un impact destul de mare asupra programului.

Linia 24 "Run" trebuie redenumit din aceleasi motive ca la linia 18 poate provoca confuzie.

Linia 62 la "Float.parsaFloat(numbers[i]" zice faptul ca nui necesar temporar de la string 

Linia 63 "Exception" poate fi schimbat cu multicatch ori alte prinderi specifice exceptiei

Linia 183 "return" nu este necesara si poate fi sters fara sa provoace un impact
