# Inleiding

In deze Github repo vinden jullie de stappen om een webapplicatie op te zetten, waar medewerkers zich kunnen registreren. Daarnaast zullen deze zich tijdens het evenement met de aanmeldingsmodule eenvoudig kunnen aanmelden op basis van de verkregen gegevens uit de database.

---

## Vooronderzoek

Om dit project tot een goed einde te kunnen brengen, ging er een grote concept- en analysefase aan vooraf. Deze kan u vinden op [https://datadumpsters.netlify.app/](https://datadumpsters.netlify.app/).

---

## Overzicht van de repositories

### AWS repository

Om onze webapplicatie op te zetten, hebben we een degelijke hostingstructuur nodig, waarbinnen onze frontend en backend draait. Voor onze setup hebben we gekozen voor een AWS-omgeving, volledig opgebouwd met Tofu (vroeger Terraform). 

Wanneer je de README in deze repo volgt, zal je (na het ingeven van de gewenste variabelen) automatisch deze volledige omgeving kunnen opzetten. De AWS-omgeving heeft een publiek (internetkoppeling) en een privaat gedeelte (services voor de frontend en backend, database...) en is voorzien van aparte subnets, security groups..., zodat belangrijke data beschermd kan blijven. Meer info over deze repo vind je in de README van deze repo zelf.

### Gladiolen-frontend repository

In deze repo zal je vanzelfsprekend de bestanden vinden voor de frontend. Deze omvat:

- Al de bestanden voor de opmaak van de repo
- Al de dashboards die beschikbaar zullen zijn
- Een Dockerfile om de applicatie op te zetten

In de README van deze repo vind je meer info hierover.

### Gladiolen-backend repository

In deze repo vind je uiteraard de backend van onze webapplicatie. Hier vind je informatie over:

- De structuur van de database
- De beschikbare entiteiten
- Query-mogelijkheden en database-interacties
- Een Dockerfile en een docker-compose file om de volledige image te kunnen bouwen.

Meer info over deze repo kan je weer terugvinden in de README van de repo zelf.

