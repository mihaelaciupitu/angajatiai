# Cum activez secțiunile ascunse

Pe pagină sunt 4 secțiuni pregătite, dar ascunse. Fiecare are pe primul ei rând cuvântul `hidden`. Când ștergi cuvântul, secțiunea apare.

Deschide `preview/index.html` (sau `index.html`, după publicare), caută textul din coloana „Caută" și șterge doar cuvântul `hidden` de pe acel rând.

| Secțiunea | Caută | Ce pregătești înainte |
|---|---|---|
| Demo video (la „Cum funcționează") | `<figure id="demo" hidden` | Fișierul `demo.mp4`, pus în același folder cu pagina. Pe rândul care începe cu `<video` schimbi și `preload="none"` în `preload="metadata"`, ca să se vadă primul cadru. |
| Rezultate (studii de caz) | `<section id="rezultate"` | Cel puțin un caz real, adăugat după `CUM-ADAUG-UN-STUDIU-DE-CAZ.md`. |
| Cine e în spate | `<section id="cine"` | Poza ta `mihaela.jpg` (pătrată, cel puțin 400×400), cele două rânduri despre tine în locul lui `[două rânduri]` și 2 recenzii reale (nume întreg, meserie, cont de Instagram), cu acordul clienților. |
| Foaia gratuită | `<section id="foaia"` | Foaia gata de trimis pe WhatsApp. |

## Exemplu
Înainte:
```
<section id="foaia" aria-labelledby="t-foaia" hidden>
```
După:
```
<section id="foaia" aria-labelledby="t-foaia">
```

## De înlocuit înainte de publicare
- `[Nume]`: caută `[Nume]` și înlocuiește peste tot (apare și în titlul paginii și în previzualizare).
- `[Datele firmei]`: în subsol.
- `og.png` (imaginea de previzualizare) conține și ea `[Nume]`, deci trebuie refăcută după ce alegi numele.

## Regula
Nimic inventat: fără recenzii, cifre sau poze care nu sunt reale.

## Mai simplu
Scrie-i lui Claude: „Activează secțiunea Foaia gratuită și verifică pagina."

## Galeria de sus („Așa arată pe Telegram”)
E vizibilă și are 3 slide-uri desenate după mesaje reale ale asistentului (traduse, fără numele clientului). Ca să schimbi un text sau să adaugi un slide, scrie-i lui Claude.
