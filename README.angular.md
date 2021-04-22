

## Inserimento del foglio di stile di Bootstrap

Installazione del css di Bootstrap tramite [**pacchetto npm**](https://www.npmjs.com/package/bootstrap)
 
```bash
$ npm install bootstrap --save
```

Adesso dentro la cartella **node_module** del progetto
possiamo trovare il file: **bootstrap.css**

    node_modules\bootstrap\dist\css\bootstrap.min.css

Aggiungiamo il file ai fogli di stile del progetto.

**file: angular.json**

```json   
"styles": [
    "src/styles.css",
    "node_modules/bootstrap/dist/css/bootstrap.min.css"
],
```

> Importante: RIAVVIARE 
>
> $ ng serve
>
> Bisogna ricompilare il codice

## Creazione di un componente

Creazione del MainHeader \<component>

```bash
$ ng generate component MainHeader 
```




### passaggio dati dal componente padre al componente figlio

@Input()

