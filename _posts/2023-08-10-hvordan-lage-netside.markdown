---
layout: post
title:  "Hvordan lage en nettsied"
date:   2023-08-10 09:54:28 +0200
categories: jekyll update
---
# Lag nettside med Jekyll
Første gjøremål for faget ADA525 som undervises ved HVL skal man lage seg en nettside. Den skal være være på **github.io**. Dette er da et forsøk på å 

## Før man starter
Før man kan sette i gang med nettsiden er det et par ting som må være på plass. Det er følgende:
1. Homebrew
2. Ruby
3. Jekyll
4. GitHub Desktop
5. VS Code

Punkt 4 og 5 er valgfrie men jeg valgte å bruke disse programmene. De 3 første punktene kan gjøres ved å følge instruksjoen som er på denne siden:
<https://jekyllrb.com/docs/installation/macos/>


## Side fra github.io
Her lager man et ny repositori. I navnet på repositori'et må man ha *brukernavn*.github.io. I mitt tilfelle ble det MaxThyes.github.io. Når repositori'et er laget kan man åpne det i *GitHub Desktop*. Det blir nå laget en lokal mappe på din mac med navnet på repositori'et som mappenavn. 

## Lag nettsiden
Her "jukset" jeg litt å brukte jekyll sin eksempel nettside. Følgende måte ble brukt for å leg siden.
I terminalen navigere man seg til hvor man ønsker å lagre siden.Jeg valgte å lagre denne på skriveborde. Når man er i mappen man vil lagre siden bruker man følgende komando:
**jekyll new *navn på filen*** 
Det lages nå en jekylleksempel side. For å bygge siden kan man må man navigere seg inn i den ny opprettede mappen. og bruke følgende komando for å bygge siden.
**jekyll serve**
Kopier alt innholde i mappen inn mappen som ble opprette av GitHub Desktop, altså mappen med repossitori nevnet. Da gjenstår bare å commit og push for å få siden på nett. Dette tar tid for github å lage nettsiden. Så nå er det bare å vente. 

## Rydd opp på siden og poste nye innlegg
Siden dette er en eksempel side er det mye eksempelfyll fra før på siden. Dette kan man bytte ut. Ønsker man å legge til nye poster er dette beskrevet i posten som allerede ligger inne på siden fra før. Her må man huske at det er viktig å formatere navnet på filen rett og plasser den i rett mappe.