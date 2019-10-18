# O projektu

Tema projekta, ki ga razvija skupina 26 je platforma za iskanje in organizacijo prevozov.

Portal nam med drugim omogoča:
- objavo prevozov (in vodenih izletov)
- iskanje po katalogu aktualnih prevozov
- obveščanje o novih prevozih, ki ustrezajo podanim parametrom iskanja (vstop, izstop, čas, tip vozila, ipd.)
- upravljanje prevoza (pridružitev, preklic, zapustitev, pregled dejavnosti oziroma aktivnosti v obliki dnevnika dogodkov)
- dodajanje komentarjev (besedila, slik, kratkih videoposnetkov) na oglasno desko posameznega prevoza in
- deljenje geolokacije voznika (opcijsko tudi potnika/ov) v realnem času.

Cilj projekta je torej razviti programsko rešitev ("cloud native"), ki bo izkoriščala prednosti oblačnega okolja in temeljila na arhitekturi mikrostoritev (krajše MS)

Spodaj bomo na kratko predstavili ključne MS.

## Katalog prevozov

Prevoznikom omogoča dodajanje novega prevoza (objave), potnikom pa iskanje po katalogu aktualnih prevozov, naročanje na obvestila o novih prevozih (ki ustrezajo podanim kriterijem) ali spremembah za izbrane prevoze.

## Upravljanje prevoza

Prevoznikom omogoča spreminjanje aktivnega prevoza, (in posledično obveščanje o spremembah vsem naročnikom *), uporabnikom pa pridužitev in zapustitev (tudi *). Vsem je na voljo pregled dejavnosti oziroma aktivnosti v obliki dnevnika dogodkov in dodajanje komentarjev (besedila, slik, kratkih videoposnetkov) na oglasno desko posameznega prevoza.

## Upravljanje medijskih vsebin

Omogoča nalaganje slik, procesiranje slik, analizo slik z uporabo zunanjih API-jev (za potrebe avtomatskega moderiranja), morda tudi krajših videoposnetkov.

## Geolociranje in usmerjanje

Omogoča deljenje geolokacije prevoznika (opcijsko tudi potnika/ov) v realnem času, obveščanje o medsebojni bližini voznika in aktualnih potnikov ter navodila za pot (glede na dane parametre). Uporabno: [graphhopper](https://github.com/graphhopper/graphhopper) routing engine.


