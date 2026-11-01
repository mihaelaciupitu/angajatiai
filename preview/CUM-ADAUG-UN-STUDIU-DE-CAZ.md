# Cum adaug un studiu de caz

Secțiunea „Rezultate reale" există deja în pagină, dar e ascunsă. Apare abia când adaugi primul caz.

## Regula de bază
Doar lucruri reale. Fără cifre rotunjite în sus, fără citate inventate, fără logo-uri sau conturi fără acordul clientului.

## Ce strângi de la client, înainte
1. **Acordul scris** (un mesaj e suficient) că poți pune pe site numele contului, cifra și fraza lui.
2. **Numele contului** de Instagram, de exemplu `@studio.exemplu`.
3. **Tipul de afacere**, de exemplu „videograf de nunți".
4. **Situația de dinainte**, într-o propoziție.
5. **O cifră din Instagram**, cu perioada exactă, de exemplu „vizualizări +40% între 1 sep și 31 oct 2026". Păstrează o captură din Instagram ca dovadă.
6. **O frază de la client**, exact cum a spus-o.
7. **Linkul spre cont**.

## Unde îl pui
Deschide fișierul `preview/index.html` (sau `index.html`, după publicare) și caută textul `ŞABLON STUDIU DE CAZ`.

1. Copiază blocul dintre „copiază de aici" și „până aici".
2. Lipește-l imediat sub el, **fără** semnele `<!--` și `-->`.
3. Înlocuiește textele-exemplu cu datele clientului.
4. Mai sus, la rândul care începe cu `<section id="rezultate"`, șterge cuvântul `hidden`. Doar la primul caz.

Pentru al doilea și al treilea caz repeți pașii 1-3.

## Mai simplu
Trimite-i lui Claude datele de mai sus și cere-i: „Adaugă acest studiu de caz pe site și verifică pagina."
