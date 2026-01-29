<details>
<summary><strong>IncidentenApp Backend – Quickstart Guide</strong></summary>
Deze quickstart beschrijft hoe je de IncidentenApp backend lokaal start met Docker.

## Vereisten
- [Docker Desktop](https://docs.docker.com/desktop/setup/install/windows-install/)
- [Java 17](https://adoptium.net/temurin/releases/?version=17) 

## Installatie en opstarten

### 1. Repository clonen

```bash
git clone https://github.com/rivm-syso/IncidentenAppAndroid
cd IncidentenAppAndroid
```

### 2. Docker configuratie toevoegen

1. Download `dockernew.zip`
2. Pak het zip-bestand uit
3. Plaats de uitgepakte map in de root van de repository

Verwachte structuur:

```text
IncidentenAppAndroid/
├── docker/
├── app/
├── ...
```

### 3. Docker Desktop starten

Zorg dat Docker Desktop actief draait voordat je verdergaat.

### 4. Docker containers starten

```bash
cd docker
docker compose up --build
```

## Backend UI bereiken

### 5. Webinterface openen

Ga in de browser naar:

`http://localhost:8080`

### 6. Inloggen

- E-mailadres: `admin@admin.com`
- Wachtwoord: `admin`

### 7. Demo-account activeren

1. Ga naar **Instellingen**
2. Activeer het **demo-account**

Als je dan in de Android app probeert in te loggen met demo@demo.com wordt het automatisch goedgekeurd.

### 8. Apparaten handmatig goedkeuren
Mocht je accounts handmatig willen goedkeuren dan kan je dat op de volgende manier doen: 
1. Ga naar **Goedgekeurde apparaten**
2. Keur hier de geregistreerde apparaten goed

## Afronding
De backend draait nu officieel!

</details>

<details>
<summary><strong>IncidentenApp Android app – Quickstart Guide</strong></summary>
Deze quickstart beschrijft hoe je de IncidentenApp in Android Studio kan draaien.


## Vereisten
- [Android Studio](https://developer.android.com/studio)
- [Java 17](https://adoptium.net/temurin/releases/?version=17) 


## Installatie-instructies

**Stap 1**  
Clone de volgende repository:  
https://github.com/rivm-syso/IncidentenAppAndroid

**Stap 2**  
Open de geclonede map in **Android Studio**.

**Stap 3**  
Stel in Android Studio de **Java-versie in op Java 17**.

**Stap 4**  
Zodra het project is geopend, configureer en start je een **emulated Android-device (zie stap 5)**.

**Stap 5**  
Volg onderstaande YouTube-video voor uitleg over het gebruiken van een Android emulator in Android Studio:  
https://www.youtube.com/watch?v=zcrhTrfE1e4

**Stap 6** 
Druk bovenin op run en de applicatie zal draaien op de android emulator!




</details>


