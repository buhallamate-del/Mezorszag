# Mézország

Méhészkedős incremental játék rajokkal, anyai tulajdonságokkal, évszakokkal és vidékről vidékre költözéssel.

Játszható a böngészőben: https://buhallamate-del.github.io/Mezorszag/

Egyetlen fájl (`index.html`), a mentés a böngésző helyi tárhelyén él.

## Multiverzum

A Mézország a szerző többi játékával közös naplót vezet (Eseményhorizont, Kísérleti Lőtér, Raktár 3D, Égtorony):
az Anyaméh fül alján a „Más világok” kártya mutatja, hol jártál már, és a Csillagméhes kaput nyit az Eseményhorizont felé.

## Heti mézverseny

Az Anyaméh fülön heti rangsor: ki gyűjt a héten több mézet (anyaváltáson és költözésen át is). Élő hírek a többiek
költözéseiről; hétfőn új hét, a múlt heti győztes +10 méhpempőt kap. A név és a heti eredmény egy nyilvános MQTT
üzenetközvetítőn (HiveMQ) megy át; a könyvtár: `vendor/mqtt/` (MIT licenc).
