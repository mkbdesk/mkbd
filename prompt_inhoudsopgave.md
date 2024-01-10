We zijn een bedrijfsrapport op aan het stellen dat buiten de introductie, 1 tot 8 hoofdstukken zal bevatten. Elk onderdeel wordt gemaakt door een losse API call naar ChatGPT, waarvan de responses al beschikbaar zijn. Als respons op deze prompt willen we dat je een inhoudsopgave van het rapport maakt, zodat we deze toe kunnen voegen aan het begin van het rapport om het compleet te maken.

De 8 hoofdstukken zijn optioneel, benoem de hoofdstukken dan ook alleen als deze gekozen zijn door de gebruiker, en daarmee ook gegenereerd zijn.

Voorbeeld: Als er 8 hoofdstukken worden meegegeven, nummer je de hoofdstukken van 1 tot 8. Als er maar 3 hoofdstukken zijn gegenereerd - bijvoorbeeld hoofdstuk 2, 6 en 8 - dan nummer je deze hoofdstukken van 1 tot 3.

///

/// BELANGRIJK ///

Gebruik NOOIT een inleiding of andere lopende tekst, genereer enkel de inhoudsopgave

Gebruik overal markdown formatting.

Zorg dat je overal in het document een hierarchie toepast en headings (heading level 4 voor de hoofdstuk titels) verwerkt in dezelfde markdown formatting waarmee deze gegenereerd is.

BELANGRIJK: Zorg dat je ook overal alle onderdelen (3 tot 5 kopjes) van de hoofdstukken includeert in een opsomming (cijfers, optellend) per hoofdstuk. Let op: gebruik nooit listicles

Gebruik NOOIT paginanummers, aangezien we deze nog niet weten. Gebruik daarom alleen een opsomming van de hoofdstukken die gegenereerd zijn.

Gebruik NOOIT autolinking. De inhoudsopgave komt uiteindelijk in een pdf, en de links zullen niet klikbaar zijn. Gebruik gewoon text zonder link of url.

Voorbeeld: Gebruik nergens '1. [Strategie Analyse](#)'

Maar gebruik in deze situatie '#### 1. Strategie Analyse' (heading level 4)

Verwijs dus NOOIT met een link naar een onderdeel!

//////

In het volgende deel van deze prompt sommen we de gegenereerde responses op:

///

${response1}

${response2}

${response3}

${response4}

${response5}

${response6}

${response7}

${response8}

${response9}

///

/// BELANGRIJK ///

Houd ten alle tijde de volgende hierarchische structuur aan:

///

## Inleiding

##### 1. {hoofdstuk 1}

<li>

1.1 Onderdeel 1 van dit hoofdstuk

1.2 Onderdeel 2 van dit hoofdstuk

1.3 Onderdeel 3 van dit hoofdstuk

1.4 Onderdeel 4 van dit hoofdstuk

</li>

##### 2. {hoofdstuk 2}

<li>

2.1 Onderdeel 1 van dit hoofdstuk

2.2 Onderdeel 2 van dit hoofdstuk

2.3 Onderdeel 3 van dit hoofdstuk

2.4 Onderdeel 4 van dit hoofdstuk

</li>

##### 3. {hoofdstuk 3}

<li>

3.1 Onderdeel 1 van dit hoofdstuk

3.2 Onderdeel 2 van dit hoofdstuk

3.3 Onderdeel 3 van dit hoofdstuk

3.4 Onderdeel 4 van dit hoofdstuk

</li>

##### 4. {hoofdstuk 4}

<li>

4.1 Onderdeel 1 van dit hoofdstuk

4.2 Onderdeel 2 van dit hoofdstuk

4.3 Onderdeel 3 van dit hoofdstuk

4.4 Onderdeel 4 van dit hoofdstuk

</li>
