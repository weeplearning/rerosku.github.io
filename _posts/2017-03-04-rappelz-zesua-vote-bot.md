---
title: Rappelz Zesua Bot per Voti Automatici
date: 2017-03-04 00:00:00 Z
tags:
- Rappelz
- Trucchi & Hack
layout: post
banner_image: rappelz.jpg
comments: true
---
<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- pdn -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-0310143169496959"
     data-ad-slot="5970575705"
     data-ad-format="auto"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>

<center><img src="http://rerosku.altervista.org/wp-content/uploads/zesua.png" /></center>

Rappelz ha di sicuro ottenuto un grandissimo successo negli anni che vanno dal 2005 al 2012. Anche oggi ci sono moltissimi giocatori attivi, ma giocare nei server ufficiali è ormai noioso e impossibile. Oggi vi parlo di un server privato, chiamato Rappelz Zesua e vi spiegherò come ottenere vote points infiniti grazie ad un piccolo "BOT" casalingo.

<!--more-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/kZor8qgVrMM" frameborder="0" allowfullscreen="allowfullscreen"></iframe>Vi consiglio il miglior server Privato al momento disponibile: sto parlando di **[Rappelz Zesua](http://viid.me/9jM4w).**

Troverete server PvP, PvE e Retro Experience, con **EXP Rate aumentati**, **Contenuti unici** sviluppati dal Team, un **sistema di Voti e Donazioni** per acquistare oggetti nel gioco oltre che tutte le caratteristiche base del gioco originale. Oltretutto, il server uptime è praticamente del 100%, con manutenzione regolare ogni settimana e **[eventi speciali per le festività](http://viid.me/9keS4)** o anche generici.

Quello di cui voglio parlarvi oggi è appunto il <span style="text-decoration: underline;">sistema di votazione per ottenere punti da poter spendere nel gioco</span>. Dopo essersi [registrati](http://viid.me/9kw9D), sarà sufficiente recarsi sulla [pagina delle votazioni](http://viid.me/9keS4), completare il CAPTCHA e cliccare su "Yes" per votare il server sul sito "Topofgames" e contribuire così a far conoscere il server a nuovi giocatori. Questa operazione aggiunge dei punti al vostro account e potrete votare ogni 2 ore.

<img src="http://rerosku.altervista.org/wp-content/uploads/Screenshot_19.png" /></center>
Il mio personaggio principale sul server ZesuaV2

Bello vero?.. **NO**

> <span style="text-decoration: underline;">Il problema nasce dal fatto che i punti accreditati siano pochissimi</span> (in questo momento sono 30, ma di **base si parla di 10/15 punti**). Per acquistare qualcosa di decente **vengono richiesti anche 2000/4000 punti**. Una persona normale, che lavora e ha impegni e dedica al gioco magari una o due orette al giorno, con una media di votazioni giornaliere pari a 2 (e neanche tutti i giorni magari) impiegherebbe quasi <span style="text-decoration: underline;">4 mesi e mezzo</span> per arrivare ad un tal numero di punti. **NON ESISTE.**
>
> Stufo di questa situazione, ho cercato e trovato una soluzione gratuita (per le persone cattive che non vogliono supportare il gioco) e una a pagamento (circa 1,50€ ogni 12 giorni) che vi vado a illustrare.

*RAPPELZ ZESUA AUTOVOTE BOT #1 FOR BAD PEOPLE*

 Il primo metodo consiste nello sfruttare un bug del sistema di voti. Infatti <span style="text-decoration: underline;">non serve completare il captcha</span> e cliccare su "yes" per far sì che i punti vengano accreditati, vi basta visitare la [pagina delle votazioni](http://viid.me/9keS4) ogni 2 ore per ricevere i punti, senza fare altro. Tuttavia come possiamo fare per automatizzare il processo? Ci serve quanto segue:
* 1. [Browser Firefox](http://viid.me/9kmNk)
* 2. [Plugin iMacros](http://viid.me/9kQyr)
* 3. Plugin [My Weekly Browsing Schedule](http://viid.me/9kQbC)

 **Installiamo Firefox**
  <span style="text-decoration: underline;">non serve impostarlo come browser principale</span> o fare login per la sincronizzazione, ci serve solo come mulo per automatizzare la votazione. Se non volete installarlo, potete anche scaricare la versione portable da [QUI](http://viid.me/9kQPE).
  Andiamo sullo store degli AddOn di Firefox, cerchiamo e installiamo i plugin necessari e riavviamo il browser.
  Ora, **aprite iMacros** cliccando sul relativo pulsante nella barra in alto a destra (solitamente). Create una nuova macro e fermatela subito dopo, incollate nella finestra che si aprirà questo codice:
   
   `VERSION BUILD=9030808`
   `RECORDER=FX`
   `TAB T=1`
   `TAB CLOSEALLOTHERS`
   `URL GOTO=https://accounts.rzesua.com/login.php?`
   `TAG POS=1 TYPE=INPUT:TEXT FORM=NAME:NoFormName ATTR=NAME:username CONTENT=XXX`
   `SET !ENCRYPTION NO`
   `TAG POS=1 TYPE=INPUT:PASSWORD FORM=NAME:NoFormName ATTR=NAME:password CONTENT=XXX`
   `TAG POS=1 TYPE=INPUT:SUBMIT FORM=NAME:NoFormName ATTR=NAME:loginAction`
   `URL GOTO=https://accounts.rzesua.com/vote.php`
   `TAG POS=1 TYPE=INPUT:SUBMIT FORM=ACTION:index.php?do=votes&id=79524 ATTR=NAME:yes`  

   <span style="text-decoration: underline;">Nella riga 6 e 8, al posto delle XXX inserite il vostro username e password che usate per fare il login sul server Rappelz Zesua.</span>
   **Salvate la macro come "rappelz"**.
   Ora la vedrete apparire nella barra laterale di iMacros.
   Cliccateci con il tasto destro e selezionate "Aggiungere al Segnalibro".
   La parte relativa a iMacros è finita, **andiamo ora ad utilizzare My Weekly Browsing Schedule** per far sì che il browser apra la macro automaticamente ogni 2 ore, tutti i giorni.
   Così facendo otterremo ben 180 (360 durante gli eventi) punti al giorno, e quindi in poco più di 20 giorni (3 settimane) potremo iniziare a goderci qualche premio di alto livello.
   Apriamo MWBS, nel set di pulsanti quadrati in basso, selezioniamo l'ultimo della prima fila, quello con la freccia che gira **"Aggiungi Pianificazione Ripetizione"** Date il nome che volete alla pianificazione, io ho scelto "Rappelz Vote".
   Nel campo sito web, fate doppio click e inserite "imacros://run/?m=rappelz.iim" (se avete chiamato la macro con un altro nome, cambiate rappelz.iim con quello che avete scelto)
   In 1) Ricorrenza selezionate: **"Giornaliera", spuntate "Nessuna data di fine", impostate l'ora di inizio alle 1 AM, ricarica sito web ogni 2 ORE fino a 11PM**
   Cliccate OK per salvare i cambiamenti.
   Fatto! Ora avete un browser da lasciare aperto, anche ridotto a icona, che ogni 2 ore eseguirà il login sul vostro account e voterà in automatico per voi, massimizzando i voti disponibili in una giornata, ma non aiutando in alcun modo il server... la coscienza è la vostra...

   *RAPPELZ ZESUA AUTOVOTE BOT #2 FOR GOOD PEOPLE*

    Il secondo metodo consiste nell'integrare al metodo descritto sopra il plugin del servizio Tremola, che risolve automaticamente i CAPTCHA per voi.
    Una volta installato e attivato, andate nella pagina di registrazione e acquistate dei crediti (1,50€ = 150 captcha risolti. 12 voti al giorno, sono 12 giorni e mezzo di votazioni...)
    In questo modo, alla spesa di 1,50€, otterrete circa 2250 vote points, che se comprati equivarrebbero a 2,25$.
