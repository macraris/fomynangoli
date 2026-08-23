# Le palestre di matematica

Giochi didattici di matematica per la scuola media: due sugli **angoli**, costruiti su impostazioni
pedagogiche opposte, e uno sulle **potenze**. Una pagina d'ingresso li presenta e mette a confronto i metodi.

**Vai al sito:** https://fomynangoli.vercel.app

| Pagina | Che cos'è |
|---|---|
| `index.html` | l'atrio: le due porte e il confronto fra i due metodi |
| `finlandia.html` | **Palestra degli Angoli** — otto allenamenti liberi, errore senza penalità |
| `singapore.html` | **Metodo Singapore** — cinque unità in sequenza, C-P-A, modello a barre |
| `potenze.html` | **Laboratorio delle Potenze** — otto allenamenti liberi (metodo finlandese) |

## Le due impostazioni

|  | Palestra finlandese | Metodo Singapore |
|---|---|---|
| Percorso | libero, otto allenamenti | sequenza obbligata, cinque unità sbloccabili |
| Rappresentazione | figura → numero | concreto → pittorico → astratto |
| Strumento chiave | l'occhio e le cinque regole | modello a barre e legami numerici |
| Esercizi | generati a caso | variazione sistematica: cambia un elemento per volta |
| Errore | indizio e si prosegue | la scheda torna in coda fino alla padronanza |
| Domanda tipica | «quanto misura?» | «come lo sai?» |

## Il laboratorio delle potenze

Costruito sulla verifica svolta a scuola, con due moduli puntati sugli esercizi andati storti:

- **★ L'ordine giusto** (era E5.b) — l'espressione si risolve *una mossa alla volta*: prima si sceglie
  quale pezzo calcolare, poi si inserisce il risultato e l'espressione si riscrive. Copre le due trappole
  dell'esercizio: l'esponente 0 e la precedenza della divisione sull'addizione.
- **★ La scala dei 10** (era E7.b) — «la decima parte di 10²⁰», «mille volte 10²³», la scala cliccabile
  dei gradini: si abbassa o si alza l'esponente, la base non si tocca mai.

Gli altri moduli: definizione di potenza (senza confonderla con × e +), casi speciali (1ⁿ, n¹, n⁰, 0ⁿ, 0⁰),
proprietà con la stessa base, proprietà con lo stesso esponente e potenza di potenza, esponente mancante,
crescita per raddoppio (il bastoncino, 2¹⁰ = 1024), più una partita mista.

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
- `potenze.html?test=1` → 360 domande generate e verificate
- `finlandia.html?demo=N&auto=1`, `singapore.html?unit=N` e `potenze.html?mod=N` aprono direttamente un modulo

## Licenza

Materiale didattico personale, pubblicato così com'è: usalo pure se ti serve.
