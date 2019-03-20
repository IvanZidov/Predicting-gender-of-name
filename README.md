# Predicting-gender-of-name
Pretpostavimo da imamo program koji automatski detektira vlastite imenice u rečenici i nama je bitno odrediti rod te imenice<br>
Tome problemu možemo pristupiti na više načina:
1. Odrediti rod preko skupa pravila
Npr. Ženska imenica završava na -a te dodati izuzetke
2. Na skupu kategoriziranih imena istrenirati model koji će sam naučiti pravila
3. Gledati odnos imenice u odnosu na cijelu rečenicu

<br>
hrvatska i srpska imena ~ 93% preciznost<br>
slavenska imena ~ 96% preciznost<br>
U bazi hrvatskih i srpskih imena ima dosta imena koja se preklapaju dok je u bazi slavenskih imena to pročišćeno i nema preklapanja<br>
**Bolji podaci čine razliku i daju bolje rezultate**
