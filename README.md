# MECH SITE
## Descrizione

MechSite è una piattaforma sviluppata per l'ausilio del meccanico, il quale avrà una semplificazione nella gestione del lavoro e dell'organizzazione.
La piattaforma permette inoltre di faar visualizzare a quet'ultimo una sezione denominata "Bacheca" la quale permetterà la visualizzazione delle riparazioni effettuate in precedenza, provviste di Nome cliente, Targa del mezzo e data di quando è stata effettuata.
## Indice
1. [Status del progetto](#status-del-progetto)
2. [Descrizione](#descrizione)
3. [Documentazione](#documentazione)
4. [Tecnologie usate](#tecnologie-usate)
5. [Architettura](#architettura)
6. [Funzionamento](#funzionamento)
7. [Struttura del progetto](#struttura-del-progetto)
8. [Licenze](#licenze)
## Status del progetto


## Documentazione

*
*
*
*
*
*
## Tecnologie usate

* [Flask](https://flask.palletsprojects.com/en/1.1.x): Version
* [Bootstrap](https://getbootstrap.com): Version
* [SQLAlchemy](https://www.sqlalchemy.org): Version
* [Git](https://git-scm.com): Version
* 
## Linguaggi

* [Python](https://www.python.org): Version 3.8.6
* [Html](https://html.com): Version 5
* [CSS](https://www.css.com): Version 3
* [JavaScript](https://www.javascript.com): Version 	ECMAScript 2018

## Funzionalità della piattaforma

La piattaforma è divisa in due sezioni principali:
* Lato Amministrativo
* Lato Cliente

### Lato Amministrativo

All'interno della parte amministrativa saranno disponibili le seguenti funzionalità:
* Aggunta nuovi clienti
* Aggiunta nuovi mezzi
* Aggiunta nuovi interventi
* Visualizzazione di una bacheca che contiene tutti i clienti, i mezzi e gli interventi
* Visualizzazione di una pagina che contiene tutte gli inteventi in corso nel quale è possibile terminare gli interventi
* Possibilità di modificare i dati relativi ai clienti presenti
* Possibilità di modificare i dati relativi ai mezzi presenti
* Possibilità di modificare gli interventi

#### Aggunta nuovi clienti
All'arrivo di un nuovo cliente l'amministratore potrà utilizzare i dati forniti da quest'ultimo per poterlo inserire all'interno del database.

*screenshot*

#### Aggiunta nuovi mezzi
Per l'aggiunta di un nuovo mezzo all'interno del database sarà necessario specificare oltre alle informazioni del mezzo inserire anche il codice fiscale del proprietario del mezzo.
Il codice fiscale a differenza degli altri dati non sarà da inserire scrivendolo, ma sarà selezionabile da una lista di codici fiscali già esistenti.
Se il codice fiscale del proprietario non fosse presente sarà possibile selezionare la voce apposita che reindirizzerà alla sezione dedicata per aggiungerlo.

*gif*

#### Aggiunta nuovi interventi
Per l'aggiunta di un nuovo intervento sarà necessario specificare oltre alle informazioni dell'intervento anche la targa del mezzo su cui dovrà essere effettuato l'intervento.

Anche in questo caso, la targa del mezzo, a differenza degli altri dati non sarà da inserire scrivendola, ma sarà selezionabile da una lista di targhe già esistenti.
Se la targa del mezzo non fosse presente sarà possibile selezionare la voce apposita che reindirizzerà alla sezione dedicata per aggiungerla.

*gif*

#### Visualizzazione di una bacheca che contiene tutti i clienti, i mezzi e gli interventi
#### Visualizzazione di una pagina che contiene tutte gli inteventi in corso nel quale è possibile terminare gli interventi
#### Possibilità di modificare i dati relativi ai clienti presenti
#### Possibilità di modificare i dati relativi ai mezzi presenti
#### Possibilità di modificare gli interventi

### Lato Cliente

All'interno della parte dedicata al cliente le funzionalità saranno diverse.
Esse saranno limitate al visualizzare le proprie riparazioni e i propri mezzi e alla modifica dei propri dati personali con i quali si esegue l'accesso alla piattaforma.

Al primo accesso alla piattaforma utilizzando la mail fornita in precedenza al personale dell'officina sarà richiesto la creazione e l'inserimento di una password che sarà utilizzata poi per tutti gli accessi seguenti.

*gif*

Questa password sarà poi modificabie all'interno dell'area dedicata alla modifica del profilo

*gif*

## Architettura

Qui si parla della macchina Linode

## Struttura del progetto

## Licenza

### Licenza generale

### Autori e copyright

### Licenze software dei componenti di terzi parti

