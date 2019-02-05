# TechMeUp

TechMeUp workshop su come realizzare il proprio blog personale utilizzando Nuxt.js e Vue.js

## Installazione di Nuxt.js

1. Vai nel desktop e crea una cartella con il nome `tech-me-up`
2. Apri la cartella creata con il programma per scrivere codice: Visual Studio Code
3. Apri il terminale e vai sul desktop con il comando `cd desktop`
4. Questo comando ti permetterà di creare un esempio di progetto Nuxt.js già funzionante. Digita  `npm create nuxt-app tech-me-up`
Vi chiederà se installare dei programmi aggiuntivi a noi servirà Bulma, un framework CSS che permettere di rendere lo stile del nostro sito carino senza troppe fatiche

Il terminale è un programma già installato nel tuo computer dal quale puoi comunicare con il computer in modo testuale puoi avviare programmi, navigare nelle cartelle, creare cartelle, e tante altre cose.

5. Entra nella cartella utilizzando il comando `cd tech-me-up`
6. Per aprire il tuo sito basta digitare 
`npm run dev`
Per avviare il progetto

Cartella Pages è la più importante che contiene il file `index.vue` è la tua homepage
Puoi create tante pagine quante ne vuoi

Il file .vue è diviso in 3 parti:
Template deve avere 1 solo elemento
Script
Style

* cancellare tutti gli stili
* salvataggio automatico su Visual Studio Code --> file > autosave
* tasto destro `format document`

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