# Käyttötapauskuvaukset

## Käyttötapaus: sisäänkirjautuminen

**käyttäjät:**
käyttäjä

**laukaisija:**
käyttäjä haluaa käyttää sovellusta kirjautumista vaativalla tavalla.

**esiehto:**
käyttäjällä on olemassa ja käytössä oleva käyttäjätili.

**jälkiehto:**
käyttäjä on kirjautunut sisään ja pääsee käyttämään mukana tulevia etuja.

### Käyttötapauksen kulku

1. käyttäjä avaa sisäänkirjautumissivun.
2. ohjelma pyytää sisäänkirjautumistietoja.
3. käyttäjä laittaa tiedot.
4. ohjelma suorittaa **varmista salasana**

### Poikkeuksellinen toiminta

jos **varmista salasana** epäonnistuu, pidä käyttäjä samalla sivulla ja suorita **näytä kirjautumisvirhe**



## Käyttötapaus: Varmista salasana

**käyttäjät:**
järjestelmä

**laukaisija:**
käyttäjä painaa sisäänkirjautumis-nappia.

**esiehto:**
käyttäjä on syöttänyt oikeat ja tarvittavat tiedot tekstikenttiin.

**jälkiehto:**
järjestelmä hyväksyy sisäänkirjautumisen, ja päästää käyttäjän käyttäjälleen.

### Käyttötapauksen kulku

1. ohjelma katsoo onko ohjelmistoon kirjattu käyttäjä samoilla tiedoilla, kuin mitä käyttäjä kirjoitti **sisäänkirjautuminen** kohdassa.

### poikkeuksellinen toiminta

jos tiedot on väärin, suorita **näytä kirjautumisvirhe**

## Käyttötapaus: näytä kirjautumisvirhe

**käyttäjät:**
järjestelmä

**laukaisija:**
**varmista salasana** tunnistaa virheen tiedoissa.

**esiehto:**
käyttäjä on yrittänyt kirjautua sisään.

**jälkiehto:**
käyttäjälle näytetään virheilmoitus.

### Käyttötapauksen kulku

1. järjestelmä tunnistaa, että kirjautumistiedot ovat virheelliset.
2. järjestelmä näyttää käyttäjälle virheilmoituksen

### poikkeuksellinen toiminta

aktivoituu ainoastaan, jos salasana on väärin.

## Käyttötapaus: selaile äänestystuloksia

**käyttäjät:**
käyttäjä

**laukaisija:**
käyttäjä haluaa tarkastella äänestysten tuloksia.

**esiehto:**
järjestelmässä on julkisia äänestystuloksia.

**jälkiehto:**
käyttäjä näkee valitsemansa äänestyksen tulokset.

### Käyttötapauksen kulku

1. käyttäjä avaa äänestystulokset.
2. ohjelma näyttää käyttäjälle äänestykset.
3. käyttäjä valitsee äänestyksen.
4. ohjelma näyttää äänestyksen tulokset.

### poikkeuksellinen toiminta

jos tuloksia ei voi näyttää, ohjelma ilmoittaa käyttäjälle.

## Käyttötapaus: uusi äänestys

**käyttäjät:**
ylläpitäjä

**laukaisija:**
ylläpitäjä tahtoo lisätä uuden äänestyksen.

**esiehto:**
ylläpitäjä on kirjautunut sisään.

**jälkiehto:**
ylläpitäjä pääsee vapaasti lisämään äänestyksiä käyttäjille selailtaviksi ja äänestettäviksi.

### Käyttötapauksen kulku

1. ylläpitäjä avaa äänestyksen luomisen.
2. ohjelma pyytää äänestyksen tiedot.
3. ylläpitäjä vahvistaa äänestyksen.
4. ohjelma tallentaa uuden äänestyksen ja näyttää sen käyttäjille.

### poikkeuksellinen toiminta

jos tekijä lähtee julkaisematta äänestystä, käyttäjät eivät voi nähdä eikä äänestää sitä.

## Käyttötapaus: poista äänestys

**käyttäjät:**
ylläpitäjä

**laukaisija:**
ylläpitäjä tahtoo poistaa äänestyksen.

**esiehto:**
ylläpitäjä on kirjautunut sisään ja äänestys on jo olemassa.

**jälkiehto:**
ylläpitäjä voi poistaa äänestyksiä, jottei menneet tai sopimattomat äänestykset näy käyttäjille.

### Käyttötapauksen kulku

1. ylläpitäjä avaa äänestysten hallinnan.
2. ylläpitäjä valitsee äänestyksen.
3. ylläpitäjä valitsee **poista äänestys**.
4. järjestelmä poistaa äänestyksen.

### poikkeuksellinen toiminta

jos tulee ongelmia, ohjelma ilmoittaa ylläpitäjälle.

## Käyttötapaus: tee äänestys

**käyttäjät:**
käyttäjä

**laukaisija:**

**esiehto:**

**jälkiehto:**

### Käyttötapauksen kulku



### poikkeuksellinen toiminta

