CSS         cascade         style sheet


Separation of Concerns

Come può essere applicatio il CSS agli elementi HTML:
- inline -> attributo style
- embedded -> elemento HTML style
- file esterno


Sintassi:

selector {
    property1: value1;  /* dichiarazione o regola */
    property2: value2;  /* dichiarazione o regola */
    property3: value3;  /* dichiarazione o regola */
}


Selettori CSS (ordinati dal meno specifico al più specifico)
5) universal selector *
4) tag selector  tagName
3) class selector .nomeDellaClasse
2) id selector   #id
1) attributo HTML style

Ereditarietà

Combinazione dei selettori:
- descendant selector   space
- child selector        >
- group selector        ,
- class selector multipli

Valori per i colori:
1) named colors
2) funzione rgb(r, g, b)         con 0 <= r, g, b <= 255
3) hex colors #rrggbb   con 0 <= rr, gg, bb <= FF


font-family lista di font con un sistema di fallback


font-weight spessore del carattere:
- 100
- 300
- 400 normal
- 700 bold
- 900 bolder