# App: Gestione Del Personale

Progetto Sviluppo delle Applicazioni Software (SAS) UniTo anno 2024-2025

***NB! Questo repository contiene solo una descrizione del progetto.
Il codice sorgente completo non è pubblicato per rispettare le linee guida accademiche dell'Università.
Può essere condiviso privatamente su richiesta***.

## Introduzione
Partendo da una commessa contenente degli User Stories di Event Organizers, il progetto consiste nello sviluppo di un applicazione che gestisce tutto il personale in preparazione di un evento richiesto da un cliente.

## Tecnologie e Strumenti Usati

### Linguaggi e Framework
+ Java
+ JUnit

### Metodo di Sviluppo 
+ Unified Process

### Database
+ Sqlite3

### Modellazione e Diagrammi
+ draw.io
+ Umlet 

## Contenuto Relazione Finale
La relazione finale comprende tutta la documentazione partendo dalla fase di Ideazione fino alla Progettazione Tecnica (DSD e DCD).
 **In Ordine:** 
 1. Scenario Principale Di Successo
 1a. Estensioni
 1b. Eccezioni
 2. Modello di Dominio
 3. Diagrammi di Sequenza di Sistema
 4. Contratti
 5. Design Sequenze Diagram 
 6. Design Class Diagram

## Contenuto Codice
Il codice rappresenta lo sviluppo effettivo dell'applicazione, rispettando i principi di progettazione ***Grasp*** e i ***Pattern Gof***.
Le principali attività svolte comprendono:
+ Implementazione dei ***Pattern Grasp*** (Controller, High Cohesion, Low Coupling, Creator...)
+ Applicazione di alcune pattern ***GoF*** (Singleton, Observer...)
+ Gestione e popolamento del database
+ Sviluppo di metodi di delega e accesso ai dati con query SQL
+ Scrittura di test unitari con JUnit per verificare il funzionamento dei metodi principali.
+ Gestione della **persistenza dei dati** tramite un layer dedicato e l'uso di query SQL via JDBC. 

