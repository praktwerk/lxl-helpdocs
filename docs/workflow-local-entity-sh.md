---
section: Hjälptexter ämnesord
title: Ämnesord som lokal entitet
order: 115
date: 2019-01-18
tags:
- under arbete
- ämnesord
- koncept
- ämnesord som lokal entitet
---

## Ämnesord som lokal entitet

Hjälptexten beskriver hur man anger ämnesord i verksbeskrivningen i Instans av Verk i de fall ämnesorden inte finns auktoriserade. För auktoriserade ämnesord använd hjälptext [Länka ämnesord](#https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)

Utgår katalogiseringen från en mall finns egenskapen Ämne redan tillagd under Instans av Verk. 
<br/>För att lägga till egenskapen Ämne: Klicka på plustecknet inom Instans av Verk, sök efter och lägg till Ämne (subject).

| [Ämnesord från system med listkod som länkad entitet](#amnesord-från-system-med-listkod-som-länkad-entitet) | [Ämnesord från system med listkod (utan listkod som länkad entitet)](#amnesord-från-system-med-listkod-utan-listkod-som-länkad-entitet) | [Ämnesord utan listkod](#amnesord-utan-listkod)
| ----------- |  ----------- |  ----------- |
| [Enkelt ämnesord som lokal entitet](#enkelt-amnesord-som-lokal-entitet-med-lankbar-listkod) | [Enkelt ämnesord som lokal entitet](#enkelt-amnesord-som-lokal-entitet-utan-lankbar-listkod) |  [Ämnesord utan listkod](#amnesord-utan-listkod) |
| [Sammansatt ämnesord som lokal entitet](#sammansatt-amnesord-som-lokal-entitet-med-lankbar-listkod) | [Sammansatt ämnesord som lokal entitet](#sammansatt-amnesord-som-lokal-entitet-utan-lankbar-listkod)  |


### Ämnesord från system med listkod som länkad entitet
Instruktionen används i de fall man vill ange ämnesord som en lokal entitet från kontrollerade ämnesordslistor vars listkod finns som en länkad enitet, t.ex. **agrovoc**, **kao**, **prvt**, **sfit**, **mesh** m.fl. Vissa ämnesordskonstruktioner från Svenska ämnesord (sao) läggs också in som lokala entiteter om den sammansatta konstruktionen inte finns auktoriserad, t.ex. sammansatta geografiska ämnesord.

#### Enkelt amnesord som lokal entitet med lankbar listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj den typ av ämnesord du vill lägga till i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda lokala entiteten. 
* Sök efter och välj Föredragen benämning och Termlista.
* Skriv in aktuell term i Föredragen benämning.
* Öppna sidorutan Lägg till entitet inom egenskapen Termlista. Sök efter och välj aktuell listkod.

För att lägga till flera termer av samma typ kan den lokala entiteten kopieras.

Exempel:

![Enkelt ämnesord som lokal entitet](LokaltEnkeltKao.png) 


#### Sammansatt amnesord som lokal entitet med lankbar listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Sök efter och välj aktuell listkod.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Underindelning för allmänt ämnesord.
* Skriv in aktuell term i rutan Föredragen benämning.

För att lägga till flera termer av samma typ, eller flera underindelningar inom den sammansatta termen, kan kopierafunktionen användas.

Exempel:

![Lokalt sammansatt ämnesord med listkod kao](LokaltSammansattKao.png) 

Exempel:

</br>![Lokalt sammansatt geografiskt ämnesord med listkod sao](LokaltGeoSammansattSao.png)

### Ämnesord från system med listkod utan listkod som länkad entitet

#### Enkelt amnesord som lokal entitet utan lankbar listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning och Termlista. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Välj Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom egenskapen Termlista. Sök efter och lägg till egenskapen Kod.
* Skriv in aktuell listkod i rutan, t.ex. ”lcsh”.

Exempel:

![Lokalt enkelt ämnesord med listkod lcsh](LokaltEnkeltLcsh.PNG)

#### Sammansatt amnesord som lokal entitet utan lankbar listkod 

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj typen Sammansatt term i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till entitet/termlista inom egenskapen Termlista. Välj Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom egenskapen Termlista. Sök efter och lägg till egenskapen Kod.
* Skriv in aktuell listkod i rutan, t.ex. ”lcsh”.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Allmänt ämnesord.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.
* Öppna sidorutan Lägg till entitet under inom egenskapen Termkomponenter. 
* Välj typ av ämnesord i rullgardinsmenyn Skapa lokal entitet, t.ex. Underindelning för allmänt ämnesord.
* Skriv in aktuell term i rutan.

För att lägga till flera termer av samma typ, eller flera underindelningar inom den sammansatta termen, kan kopierafunktionen användas.

Exempel:

![Lokalt sammansatt ämnesord med listkod lcsh](LokaltSammansattLcsh.png)

#### Amnesord utan listkod

* Öppna sidorutan Lägg till entitet inom egenskapen Ämne. 
* Välj aktuell typ av ämnesord i rullgardinsmenyn Skapa lokal entitet.
* Öppna sidorutan Lägg till egenskaper under inom den tillagda ämnesordstypen. 
* Sök efter och lägg till Föredragen benämning. Skriv in aktuell term i rutan.