# Funkcionalnosti spletne strani ByteFix

ByteFix je predstavitvena spletna stran izmišljenega računalniškega servisa in ponudnika IT podpore. Obiskovalec lahko spozna podjetje, preveri storitve in informativne cene ter poišče kontakt. Načrt obsega štiri zaslone: **Domov**, **Storitve**, **Cenik** ter **O nas in kontakt**.

## Prioritete

- **Visoka (P1):** nujno za prvo uporabno različico strani.
- **Srednja (P2):** koristna dopolnitev, ki jo izvedemo po osnovnih funkcionalnostih.
- **Nizka (P3):** dodatna izboljšava, če ostane čas.

## Seznam funkcionalnosti

| ID | Kratko ime | Opis | Prioriteta |
| --- | --- | --- | --- |
| F01 | Navigacija med stranmi | Uporabnik z enotno navigacijo prehaja med vsemi štirimi zasloni. Označena trenutna stran mu pomaga pri orientaciji. | Visoka (P1) |
| F02 | Pregled ponudbe na domači strani | Uporabnik na domači strani prebere kratek opis ByteFixa in glavnih storitev. Prek gumbov odpre vse storitve ali kontakt. | Visoka (P1) |
| F03 | Seznam storitev | Uporabnik pregleda diagnostiko, popravila, nadgradnje in IT podporo. Pri vsaki storitvi vidi kratek opis, s katerim ugotovi, ali ustreza njegovi težavi. | Visoka (P1) |
| F04 | Prehod od storitve do cene | Uporabnik pri predstavitvi storitve izbere povezavo na cenik. Tam primerja informativne stroške posameznih posegov. | Visoka (P1) |
| F05 | Informativni cenik | Uporabnik v tabeli preveri storitev, opis obsega in okvirno ceno. Ob tabeli vidi pojasnilo, da so cene za izmišljeni projekt informativne in da je končna cena odvisna od posega. | Visoka (P1) |
| F06 | Povpraševanje iz cenika | Uporabnik iz cenika odpre kontaktni zaslon z gumbom za povpraševanje. Tako lahko po pregledu cene poišče način za dogovor o storitvi. | Visoka (P1) |
| F07 | Predstavitev podjetja | Uporabnik prebere zgodbo, vizijo in področje delovanja ByteFixa. Jasno je navedeno, da gre za izmišljeno podjetje v študentskem projektu. | Srednja (P2) |
| F08 | Kontaktni podatki in delovni čas | Uporabnik na kontaktnem zaslonu poišče telefon, e-pošto, lokacijo in delovni čas. Prikazani podatki so označeni kot predstavitveni podatki izmišljenega podjetja. | Visoka (P1) |
| F09 | Kontaktni obrazec | Uporabnik v predstavitveni obrazec vnese ime, e-pošto, izbrano storitev in opis težave. Obrazec jasno pove, da v začetni različici ne pošilja sporočil. | Visoka (P1) |
| F10 | Preverjanje vnosa obrazca | Uporabnik ob poskusu potrditve vidi opozorilo za manjkajoča obvezna polja ali nepravilen zapis e-pošte. Osnovno preverjanje omogočajo vgrajene omejitve HTML. | Srednja (P2) |
| F11 | Prilagojen prikaz na telefonu | Uporabnik lahko prebere vsebino in uporabi navigacijo tudi na manjšem zaslonu. Kartice, tabela in obrazec se prilagodijo širini naprave. | Visoka (P1) |
| F12 | Uporaba s tipkovnico | Uporabnik s tipko Tab doseže povezave in polja ter prepozna trenutno izbran element. Polja imajo vidne oznake, gumbi pa razumljiva imena. | Visoka (P1) |
| F13 | Pojasnilo poteka servisa | Uporabnik na domači strani prebere tri korake: kontakt, dogovor in diagnostika oziroma popravilo. Tako razume naslednje korake pred obiskom. | Srednja (P2) |
| F14 | Pogosta vprašanja | Uporabnik na kontaktnem zaslonu odpre kratka pojasnila o pripravi naprave, varnostni kopiji in informativnih cenah. Odgovori mu pomagajo pripraviti opis težave. | Nizka (P3) |

## Obseg prve različice

Stran bomo izdelali v HTML in CSS. Obrazec je predstavitev vmesnika: vnos in preverjanje podatkov ne pomenita dejanskega pošiljanja sporočila. Spletna trgovina, prijava uporabnika, rezervacija termina, plačevanje in spremljanje servisnih nalog niso del tega načrta.

## Povezava z žičnimi modeli

- **WF01 - Domov:** F01, F02, F13.
- **WF02 - Storitve:** F01, F03, F04.
- **WF03 - Cenik:** F01, F05, F06.
- **WF04 - O nas in kontakt:** F01, F07, F08, F09, F10, F14.
- F11 in F12 veljata za vse zaslone.
