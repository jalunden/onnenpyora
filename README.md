# Kohtalonpyörä 🎃

Halloween-aiheinen kosketusnäytöllä toimiva onnenpyörä. Ei palvelinta, lokitusta eikä riippuvuutta ulkoisista rajapinnoista. `index.html` sisältää sovelluksen.

## Käyttö

Avaa `index.html` selaimessa tai julkaise GitHub Pagesilla (Settings → Pages → Deploy from a branch → main → /root).

Paina keskeltä pyöräyttääksesi. Pidä KOHTALONPYÖRÄ-otsikkoa painettuna 5 sekuntia avataksesi asetukset. Asetukset tallentuvat vain tämän laitteen selaimeen.

## Palkinnot

12 sektoria: pääkallo 4, kurpitsa 4, aave 3, vapaavalintainen 1. Sektorin valinta tehdään selaimen `crypto.getRandomValues`-arvonnalla. Jokainen sektori on yhtä todennäköinen.

## Huomioita

Ääni aktivoituu ensimmäisestä käyttäjän kosketuksesta. Fontit ladataan Google Fontsista, mutta peli toimii myös ilman verkkoyhteyttä selaimen varafonteilla. Jos haluat täydellisen offline-tuen, fontit voi myöhemmin paketoida paikallisesti.
