# Palestra degli Angoli · Metodo Singapore

Due giochi didattici sugli angoli per un ragazzo di seconda media, costruiti su **due impostazioni
pedagogiche opposte**, più una pagina che le mette a confronto.

**Vai al sito:** https://fomynangoli.vercel.app

| Pagina | Che cos'è |
|---|---|
| `index.html` | l'atrio: le due porte e il confronto fra i due metodi |
| `finlandia.html` | **Palestra degli Angoli** — otto allenamenti liberi, errore senza penalità |
| `singapore.html` | **Metodo Singapore** — cinque unità in sequenza, C-P-A, modello a barre |

## Le due impostazioni

|  | Palestra finlandese | Metodo Singapore |
|---|---|---|
| Percorso | libero, otto allenamenti | sequenza obbligata, cinque unità sbloccabili |
| Rappresentazione | figura → numero | concreto → pittorico → astratto |
| Strumento chiave | l'occhio e le cinque regole | modello a barre e legami numerici |
| Esercizi | generati a caso | variazione sistematica: cambia un elemento per volta |
| Errore | indizio e si prosegue | la scheda torna in coda fino alla padronanza |
| Domanda tipica | «quanto misura?» | «come lo sai?» |

## Contenuti

**Finlandia** — stima a occhio, lettura del goniometro (con la trappola delle due scale), costruzione
per trascinamento, complementari/supplementari/esplementari, catene di ragionamento, coppie fra parallele
(F · Z · C), verifica del prerequisito di parallelismo, angolo di tiro, partita mista.

**Singapore** — l'apertura (ventagli, barra di ampiezza), legami numerici di 90°/180°/360°, modello a barre
(doppio, triplo, differenza, lettura inversa del modello), variazione e invarianti («sempre · a volte · mai»,
l'intruso), traduzione figura → modello → numero fino al problema in più passi.

## Aspetti tecnici

- Tre pagine statiche, nessuna build, nessuna dipendenza: HTML, CSS e JavaScript in ogni file.
- Tutte le figure sono SVG generati a runtime (angoli, goniometro, modelli a barre, number bond, campo da gioco).
- I progressi restano in `localStorage`, separati per gioco.
- Nessun cookie e nessun tracciamento; l'unica risorsa esterna sono i font di Google.

### Collaudo

- `finlandia.html?test=1` → 360 esercizi generati e verificati
- `singapore.html?test=1` → 660 schede generate e verificate
- `finlandia.html?demo=N&auto=1` e `singapore.html?unit=N` aprono direttamente un modulo (utile per gli screenshot)

## Licenza

Materiale didattico personale, pubblicato così com'è: usalo pure se ti serve.
