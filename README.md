# Le palestre di matematica

Giochi didattici di matematica per la scuola media: due sugli **angoli**, costruiti su impostazioni
pedagogiche opposte, uno sui **triangoli**, uno sulle **potenze**, uno sui **numeri naturali e le quattro
operazioni**, uno su **divisibilità e poligoni** e uno sulle **frazioni**. Una pagina d'ingresso li presenta
e mette a confronto i metodi.

**Vai al sito:** https://fomynangoli.vercel.app

| Pagina | Che cos'è |
|---|---|
| `index.html` | l'atrio: le due porte e il confronto fra i due metodi |
| `finlandia.html` | **Palestra degli Angoli** — otto allenamenti liberi, errore senza penalità |
| `singapore.html` | **Metodo Singapore** — cinque unità in sequenza, C-P-A, modello a barre |
| `triangoli.html` | **Cantiere dei Triangoli** — otto allenamenti liberi (metodo finlandese) |
| `potenze.html` | **Laboratorio delle Potenze** — otto allenamenti liberi (metodo finlandese) |
| `naturali.html` | **Officina dei Numeri** — otto banchi di lavoro sui naturali (metodo finlandese) |
| `fabbrica.html` | **Fabbrica dei Numeri** — otto reparti su divisibilità e poligoni (metodo finlandese) |
| `frazioni.html` | **Cucina delle Frazioni** — otto postazioni sulle frazioni (metodo finlandese) |

## Le due impostazioni

|  | Palestra finlandese | Metodo Singapore |
|---|---|---|
| Percorso | libero, otto allenamenti | sequenza obbligata, cinque unità sbloccabili |
| Rappresentazione | figura → numero | concreto → pittorico → astratto |
| Strumento chiave | l'occhio e le cinque regole | modello a barre e legami numerici |
| Esercizi | generati a caso | variazione sistematica: cambia un elemento per volta |
| Errore | indizio e si prosegue | la scheda torna in coda fino alla padronanza |
| Domanda tipica | «quanto misura?» | «come lo sai?» |

## La cucina delle frazioni

Segue il corso stampabile `Corso-Frazioni.html`. Otto postazioni: **il tagliere** (leggere una frazione da una
figura, comprese le improprie e le apparenti), **il metro del banco** (la frazione come punto sulla retta,
con la trappola delle tacche contate al posto dei passi), **la riduzione** (equivalenti e minimi termini),
**la bilancia** (confronto, denominatore comune, il riferimento di un mezzo), **il pentolone** (addizione e
sottrazione in due passi), **il mattarello** (moltiplicazione, divisione, reciproco e il controllo «cresce o
cala?»), **le porzioni** (la frazione di un numero, anche al contrario) e **il menu del sabato** (problemi con
il modello a barre: stadio, album di figurine, minuti di partita).

Due scelte di impianto:

- **Si scrive la frazione, non si sceglie fra quattro.** La risposta si dà su una tastiera a due piani
  (numeratore sopra, denominatore sotto) e va data **ai minimi termini**. Se il valore è giusto ma la scrittura
  no, il gioco lo dice con parole diverse — «giusto il valore, non la scrittura» — e fa riprovare senza penalità.
- **Due passi, non uno.** Nel pentolone e nelle porzioni al contrario la domanda è spezzata: prima il
  denominatore comune (o quanto vale una parte), poi il risultato. È il passaggio che nei compiti salta sempre.

## La fabbrica dei numeri

Copre il capitolo su **divisibilità e poligoni** e segue il corso stampabile `Corso-Divisibilita-Poligoni.html`.
Otto reparti: i criteri di divisibilità (selezione multipla: si sceglie *l'insieme* dei divisori giusti),
il collaudo dei numeri primi, la catena di montaggio che smonta un numero un primo alla volta,
M.C.D. e m.c.m., lo smistamento dei problemi (prima si sceglie l'attrezzo, poi si calcola),
il banco dei poligoni e il perimetro delle figure a gradini.

**La regola della fabbrica — il disegno non anticipa mai la risposta.** Nei giochi precedenti capitava che la figura
mostrasse un passaggio già svolto (per esempio «il lato più lungo è 16 cm»), cioè metà del lavoro. Qui vale una regola
esplicita: `draw()` disegna **solo i dati**, la soluzione compare in `drawAnswer()`, cioè dopo la risposta.
Non è una promessa: l'autotest, su ogni domanda generata, rende la figura, ne legge tutte le stringhe di testo
e **fallisce se contiene la risposta**. Dove il risultato si leggerebbe comunque fra i dati (per esempio un M.C.D.
che è uno dei fattori già scritti sul banco), il gioco copre da solo le scomposizioni e le fa fare a mano.

## Il cantiere dei triangoli

Segue il corso stampabile `Corso-Triangoli.html` e ne mette in gioco le stesse mosse, con tre allenamenti
in cui si agisce invece di rispondere:

- **Il costruttore** — la base AB è fissa, il vertice C si trascina col dito e i tre angoli si aggiornano
  in tempo reale: «porta l'angolo in A a 40°», «rendilo isoscele sulla base», «rendi retto l'angolo in C».
- **Base e altezza** — fra quattro segmenti che partono dallo stesso vertice bisogna toccare l'**altezza**,
  distinguendola dalla mediana, da un obliquo e da un lato; nei casi ottusangoli il piede cade fuori dalla base.
- **Modello a barre** — problemi di perimetro e di angoli in proporzione risolti in due o tre mosse:
  prima si toglie, poi si divide.

Gli altri: la disuguaglianza triangolare con i bastoncini (e l'intervallo del terzo lato), i due cognomi
(scaleno/isoscele/equilatero × acutangolo/rettangolo/ottusangolo, comprese le due caselle impossibili),
la somma dei 180°, l'isoscele nei due sensi (dato il vertice o data la base) e l'angolo esterno come somma
dei due interni lontani, più il collaudo misto.

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

## L'officina dei numeri

Copre l'intero capitolo 1 (numeri naturali e quattro operazioni): l'insieme ℕ e i numeri che non ne fanno parte,
precedente e successivo, la retta orientata e graduata (con l'esercizio INVALSI sulle distanze proporzionali,
le bandierine mancanti e i numeri romani), il valore posizionale e i numeri grandi, i nomi dei termini e dei
risultati, le quattro proprietà con le loro trappole, i casi con 0 e 1 (`n : 0` impossibile, `0 : 0` indeterminato),
l'ordine delle espressioni risolte **una mossa alla volta**, i problemi reali con divisione e resto,
e gli enigmi del libro (cifre mancanti, crittarritmetica, quadrato magico, il trucco del 9).

## Contenuti

**Finlandia** — stima a occhio, lettura del goniometro (con la trappola delle due scale), costruzione
per trascinamento, complementari/supplementari/esplementari, catene di ragionamento, coppie fra parallele
(F · Z · C), verifica del prerequisito di parallelismo, angolo di tiro, partita mista.

**Singapore** — l'apertura (ventagli, barra di ampiezza), legami numerici di 90°/180°/360°, modello a barre
(doppio, triplo, differenza, lettura inversa del modello), variazione e invarianti («sempre · a volte · mai»,
l'intruso), traduzione figura → modello → numero fino al problema in più passi.

## Aspetti tecnici

- Pagine statiche, nessuna build, nessuna dipendenza: HTML, CSS e JavaScript in ogni file.
- Tutte le figure sono SVG generati a runtime (angoli, goniometro, modelli a barre, number bond, campo da gioco).
- I progressi restano in `localStorage`, separati per gioco.
- Nessun cookie e nessun tracciamento; l'unica risorsa esterna sono i font di Google.

### Collaudo

- `finlandia.html?test=1` → 360 esercizi generati e verificati
- `singapore.html?test=1` → 660 schede generate e verificate
- `potenze.html?test=1` → 360 domande generate e verificate
- `naturali.html?test=1` → 405 domande generate e verificate
- `triangoli.html?test=1` → 360 domande generate e verificate
- `fabbrica.html?test=1` → 360 domande generate e verificate, **compreso il controllo anti-anticipazione**
- `frazioni.html?test=1` → 360 domande generate e verificate, con il controllo anti-anticipazione esteso
  alle frazioni disegnate (nessuna figura può contenere la frazione chiesta) e ai singoli passi delle catene
- `finlandia.html?demo=N&auto=1`, `triangoli.html?demo=N&auto=1`, `fabbrica.html?demo=N&auto=1`,
  `frazioni.html?demo=N&auto=1`,
  `singapore.html?unit=N`, `potenze.html?mod=N` e `naturali.html?mod=N` aprono direttamente un modulo

## Licenza

Materiale didattico personale, pubblicato così com'è: usalo pure se ti serve.
