# TechMeUp

TechMeUp è un workshop su come realizzare il proprio blog personale utilizzando Nuxt.js e Vue.js.
Vai su questo link per avere un anteprima di quello che crearemo `sad-pare.netlyfy.com`

## Prerequisiti

- Devi aver installato sul pc [Node.js](https://nodejs.org/it/download/)
- Avere almeno un editor per scrivere codice, noi consigliamo [Visual Studio Code](https://code.visualstudio.com/download)

## Avvio del progetto di Nuxt.js

1. Vai nel desktop e crea una cartella con il nome `tech-me-up`
2. Apri il programma **Visual Studio Code**
3. Da **Visual Studio Code** vai `File > Apri cartella...` e seleziona `tech-me-up`
4. Apri il terminale da **Visual Studio Code** da `Visualizza > Terminale integrato`
5. Digita  `npm create nuxt-app tech-me-up`, questo comando ti permetterà di creare un esempio di progetto Nuxt.js già funzionante.
    > Il **terminale** è un programma già installato dal quale puoi comunicare con il computer in **modo testuale** per esempio puoi avviare programmi, navigare nelle cartelle, creare cartelle, e tante altre cose.

    - Attendi qualche secondo finchè non ti compariranno sul termnale una serie di domande per configurare il progetto fai le sequenti cose:
       - Alla prima domanda premi `invio`
       - Alla seconda domanda premi `invio`
       - Alla terza domanda seleziona `none` con le freccette e premi `invio`
       - Alla quarta domanda premi `invio`
       - Alla quinta domanda seleziona `Bulma`
       - Alla sesta domanda seleziona `none` con le freccette e premi `invio`
       - Alla settima domanda seleziona `universal` con le freccette e premi `invio`
       - Alla ottava domanda inserisci il tuo nome
       - Alla settima domanda seleziona `npm` con le freccette e premi `invio`
    - Attendi la creazione progetto

6. Digita `cd tech-me-up` per entrare nella cartella appena creata e premi `invio`
7. Per aprire il tuo sito basta digitare
    `npm run dev`

## Struttura di un progetto Nuxt

### Pages

La cartella **Pages** è la più importante perchè contiene il file `index.vue` che è la tua homepage.
In questa cartella puoi creare quante pagine
Per ogni altra pagina che vuoi aggiungere, crea dei file che terminano in `.vue`.

Il file `.vue` è diviso in 3 parti:

- **Template** contiene i tag HTML, che definiscono la struttura di una pagina web dal titolo, ai paragrafi, all'impaginazione.
- **Script** contiene tutte le funzioni per rendere interattivo il tuo sito.
- **Style** contiene tutti gli stili in CSS. Il CSS viene utilizzato per gestire tutta la parte estetica di una pagina web come i colori, i caratteri, lo sfondo.

> Oggi utilizzeremo [Bulma](https://bulma.io/) che ti mette a disposizione gli strumenti per costruire la tua pagina web, in particolare ti dà degli stili CSS.

## Ora si comincia

Sostituisci tutto il contenuto di index.vue così possiamo iniziare a creare la nostra pagina web

``` bash
<template>
  <div>

  </div>
</template>
```

## Comandi utili

- salvataggio automatico su Visual Studio Code --> file > autosave
- tasto destro `format document`


Nel template c'è tutta la parte di HTML e CSS

Installare Vuetur che rende il tuo codice più leggibile

Per navigare tra le pagine usa il tag `nuxt-link`, automaticamente crea i collegamenti

Pubblicare con Netlify
Da fare:

I vari passi a grandi linee
Glossario
Comandi utili

Bisongna rendere comprensibile il nostro progetto dal browser

```
npm run generate
```

Refreshe per vedere la dist

Trascinare dal finder la dist