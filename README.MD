# Zapis številk v slovenščini - testni primeri

Ta zbirka zapisov slovenskih števil je namenjena vsem programerjem in 
programerkam, ki so ali še bodo kadarkoli pojasnjevali našim silicijevim 
prijateljem, kako se števila pravilno zapiše s slovenskimi besedami. Mišljena je
kot testni primer, s katerim se lahko preveri algoritem, spisan v kateremkoli
programskem jeziku, saj bi moral format JSON razumeti praktično katerikoli 
jezik pod soncem. Naš cilj je, da bi za program, ki pravilno zapiše vse naštete
primere, lahko z veliko gotovostjo rekli, da zna v slovenščini pravilno zapisati
katerokoli število.

Vsem implementacijam seveda ni potrebno znati vseh možnih spolov in sklanjatev,
zato lahko vam odvečne podatke mirno ignorirate. Razen tega, da so JSON ključi
napisani brez šumnikov, so podatki v datoteki zapisani preprosto in očitno.
Edina posebnost, na katero mora paziti programer je, da je zaradi 
enostavnejšega pregledovanja in urejanja pri nekaterih številih namesto
naštevanja vsakega spola posebej uporabljen nadpomenski ključ "vsi".


# Slovene numbers written with words - test cases

This is a collection of test cases for writing numbers as Slovene words. It is
intended as test case for any programmer that has or will be explaining the 
topic to our silicon friends and is thus written in the JSON format since it
is widely supported in various programming languages. A program that can 
correctly pass all these test cases should probably be able to write 
practically any number in Slovene.

Every implementation doesn't need to handle all grammatical cases and genders
of course so feel free to skip what you don't need. Besides not using letters
with carons in JSON keys, the data should be structured obviously to anyone who
has a basic knowledge of Slovene grammar with one exception that was used to
make writing and editing this document easier: where the examples for all 
genders would be equal, the key "vsi" (all) is used instead of listing the "z",
"m" and "s" individually.


# Zahvala

Za popravke in predloge se zahvaljujem:

Štefan Baebler, Marina Valenčič, Gregor Anželj, Peter Holozan, Teja Cetinski,
Žiga Hajduković, Žiga Šebenik
