# Integrazione numerica di ODE

## Cos'è questo corso?

L'analisi numerica delle equazioni differenziali è un'area di ricerca ancora molto attiva e davvero ricca di metodi e risultati. Non è quindi chiaramente il mio obiettivo coprire ogni tecnica nota o essere super rigoroso nelle derivazioni. Ciò che voglio fare con questo corso è fornire le basi per poi poter approfondire questo mondo, cercando di motivare in maniera chiara ed intuitiva i metodi con i quali lavoreremo. Inoltre, voglio anche accompagnare le lezioni con dei notebook Python con cui potrete lavorare e giocare liberamente. Trovo che questo approccio all'analisi numerica basato sulla sperimentazione supportata da alcune nozioni teoriche sia molto efficace e per questo ho deciso di seguire questa strategia in questo corso.

## Richieste

Nel caso ci siano richieste in merito ad argomenti da trattare o problemi da affrontare, puoi scrivermi alla mail davide.murari@ntnu.no . Ti chiedo però di specificare nell'oggetto "Corso ODE Mathone".

## Programma del corso

Idealmente ogni settimana usciranno 2 di queste lezioni sul canale Youtube. Cercherò di fare il mio meglio per seguire questo piano. In linea di massima ogni punto elencato qui sotto corrisponde ad una lezione, quindi il corso dovrebbe essere completato in circa 3 mesi. Ovviamente questa stima suppone che non perda neanche un colpo, però comunque credo il corso non mi prenderà più di 4-5 mesi per essere completato.

### Integrazione "classica"
- [Teoria di base sulle equazioni differenziali ordinarie](Lezione 1.md)
- Teoria di base interpolazione polinomiale
- Basi di approssimazione numerica di integrali (formule di quadratura)
- Primi esempi di metodi numerici ad un passo
  - Esempi ed intuizione
  - Introduzione di alcuni aspetti fondamentali dei metodi numerici per ODE
- Metodi di collocazione
  - Derivazione 
- Metodi Runge-Kutta
  - Basi e derivazione
  - Risoluzione di un metodo implicito
  - A-Stabilità ed L-Stabilità dei metodi Runge-Kutta
  - Adattività del passo
  - Equazioni stiff
- Brevi cenni sui metodi a più step

### Integrazione geometrica
- Cos'è l'integrazione geometrica
- Equazioni con integrali primi
  - Cos'è un integrale primo ed esempi
  - Conservare integrali primi lineari e quadratici
  - Conservare integrali primi generici : "discrete gradient methods"
- Metodi di splitting e di composizione
- Metodi simmetrici ed ODE reversibili
  - Esempi ed idee principali
- Sistemi Hamiltoniani
  - Cos'è una funzione simplettica
  - Equazione variazionale
  - Metodi Runge-Kutta simplettici
- Equazioni differenziali per matrici di rotazione