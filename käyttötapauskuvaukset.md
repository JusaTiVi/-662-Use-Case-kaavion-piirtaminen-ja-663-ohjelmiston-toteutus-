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
käyttäjä painaa nappia kirjatessa sisään.

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



### poikkeuksellinen toiminta



## Käyttötapaus: selaile äänestystuloksia

**käyttäjät:**

**laukaisija:**

**esiehto:**

**jälkiehto:**

### Käyttötapauksen kulku



### poikkeuksellinen toiminta



## Käyttötapaus: uusi äänestys

**käyttäjät:**

**laukaisija:**

**esiehto:**

**jälkiehto:**

### Käyttötapauksen kulku



### poikkeuksellinen toiminta



## Käyttötapaus: poista äänestys

**käyttäjät:**

**laukaisija:**

**esiehto:**

**jälkiehto:**

### Käyttötapauksen kulku



### poikkeuksellinen toiminta



## Käyttötapaus: tee äänestys

**käyttäjät:**

**laukaisija:**

**esiehto:**

**jälkiehto:**

### Käyttötapauksen kulku



### poikkeuksellinen toiminta

