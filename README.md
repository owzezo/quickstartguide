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
