# Palestra degli Angoli

Gioco didattico per allenare la geometria degli angoli: otto allenamenti interattivi,
pensati per un ragazzo di seconda media che sta studiando angoli, bisettrici e rette parallele.

**Gioca:** https://fomynangoli.vercel.app

## Che cosa c'è dentro

| Allenamento | Che cosa allena |
|---|---|
| Occhio di falco | stimare l'ampiezza di un angolo senza strumenti |
| Il goniometro | leggere la scala giusta (la trappola delle due scale) |
| Il costruttore | costruire un angolo trascinando il lato mobile |
| Coppie | complementare, supplementare, esplementare |
| La catena | ricavare l'anello intermedio e poi la risposta |
| F · Z · C | corrispondenti, alterni, coniugati fra due parallele |
| Trappola // | capire se il parallelismo c'è davvero, prima di applicare la regola |
| Angolo di tiro | il problema completo: parallele, alterni interni, angolo piatto |
| La partita | otto domande pescate da tutti gli allenamenti |

Ogni serie genera esercizi nuovi: numeri e figure cambiano a ogni giro.

## Impostazione didattica

Ispirata al modo di lavorare delle scuole finlandesi:

- si sceglie liberamente da dove cominciare, senza percorso obbligato e senza timer;
- sbagliare non toglie punti: al primo errore compare un indizio, al secondo la risposta con la regola;
- ogni risposta esatta viene spiegata, non solo premiata;
- a fine serie il gioco riepiloga **solo** le regole delle domande sbagliate.

## Aspetti tecnici

- Una sola pagina statica, senza build e senza dipendenze: HTML, CSS e JavaScript in `index.html`.
- Tutte le figure sono SVG generati a runtime, quindi restano nitide a ogni dimensione.
- I progressi (XP, livelli, stelle) sono salvati in `localStorage`, sul dispositivo di chi gioca.
- Nessun cookie, nessun tracciamento, nessuna chiamata di rete a parte i font di Google.

### Collaudo

Due parametri di verifica, utili dopo ogni modifica:

- `?test=1` genera 360 esercizi da tutti i moduli e controlla che risposta, alternative
  e disegno siano coerenti; stampa l'esito in fondo alla pagina.
- `?demo=N` apre direttamente l'allenamento N (0-8); aggiungendo `&auto=1` risponde da solo,
  utile per gli screenshot.

## Licenza

Materiale didattico personale, pubblicato così com'è: usalo pure se ti serve.
