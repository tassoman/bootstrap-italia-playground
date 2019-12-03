# Bootstrap Italia Playground

Questo progetto è il modo più semplice per iniziare a giocare con [Bootstrap Italia](https://italia.github.io/bootstrap-italia/).

<img src="https://github.com/italia/bootstrap-italia-playground/blob/master/bootstrap-italia-playground.png" width="800"> 

## Cos'è incluso

Troverai una semplice pagina HTML con i riferimenti ai file di Bootstrap Italia e con file CSS e JS vuoti per iniziare.

```
bootstrap-italia-playground/
│   index.html          # main html file
├── css/
│   ├── main.css        # working CSS file
└── js/
    └── main.js         # working JS file
```

## Come iniziare

* Clona o scarica il repository: `git clone https://github.com/italia/bootstrap-italia-playground.git`
* Installa le dipendenze: `yarn install`
* Lancia un server locale: `yarn start`
* Vai all'indirizzo: `http://127.0.0.1:8080/`

## Esempio: aggiornare i colori di Bootstrap Italia

Per aggiornare i colori di Bootstrap Italia, fai riferimento al file `scss/bootstrap-italia-custom.scss`, dove il colore `$primary` è sovrascritto nelle sue componenti.
Per ottenere una versione personalizzata della libreria:

* Compila la libreria Bootstrap Italia personalizzata con `yarn buildCSS`, che creerà dei file nella cartella `css/compiled`

## Modifiche in diretta

* Sviluppa le modifiche copiando il file `index.html` in qualsiasi altro file, ad esempio `pagina.html`, ad ogni salvataggio le modifiche avverranno in diretta nel tuo browser grazie a [Parcel Bundler](https://parceljs.org).

## Riferimento

La [documentazione di Bootstrap Italia](https://italia.github.io/bootstrap-italia/docs/come-iniziare/personalizzazione-della-libreria/) è presente su GitHub pages.

La [documentazione di Parcel Bundler](https://parceljs.org/getting_started.html) si trova sul sito del progetto.