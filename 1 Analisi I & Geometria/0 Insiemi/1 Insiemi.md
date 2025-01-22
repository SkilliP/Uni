29-10-2024 - 17/01/2025

Un insieme è una collezione di elementi, indichiamo gli insiemi con lettere maiuscole $(A,B,...)$ e i suoi elementi con lettere minuscole$(a,b,...)$.
Possiamo dividere gli insiemi in due gruppi, quelli **finiti** con pochi o molti elementi e quelli **infiniti** con un numero infinito di elementi.

Per evitare paradossi logici quando parliamo d'insiemi dobbiamo prima di tutto creare un insieme *$X$* che contiene come sottoinsiemi tutti gli insiemi con cui decidiamo di lavorare, poi per descrivere questi insiemi possiamo, se hanno pochi elementi, semplicemente elencarli, sennò possiamo trovare una caratteristica *$c(x)$* comune a tutti gli elementi del sottoinsieme *$A$* che non tutti gli elementi di *$X$* hanno, ma tutti quelli di *$A$* hanno e descrivere l'insieme in base a quella caratteristica.

> Pensala così: Un bit *"a"* con valore 0 è un elemento dell'insieme dei byte con valore 0 *"A"*, considerando *A* come uno di tanti insiemi, che a sua volta è sottoinsieme della totalità memoria di massa *"B"* non necessariamente con valore 0. 

>[!osservazione]
	>Vedendo l'insieme **$A =$ $\lbrace$$1, 2, 3, 4, 6, 12$$\rbrace$** Possiamo dire che *$c(x)$* è un divisore[^1] di $12$, quindi possiamo descrivere l'insieme in due forme:
	>1. Come $A =$ $\lbrace$$1, 2, 3, 4, 6, 12$$\rbrace$
	>2. Come $c(x)$ = "$x$ è divisore di $12$"


30-10-2024 & 16-01-2025

### Gli insiemi dei numeri

$\mathbb{N}$ = Insieme dei **numeri naturali** $= \lbrace 0, 1, 2, 3, 4, 5 ,6 \rbrace$.

$\mathbb{N}^+$ = Insieme dei numeri naturali **diversi da $0$** = {1,2,3,4,5,6...}.

$\mathbb{Z}$ = Insieme dei **numeri interi** {-3,-2,-1,0,1,2,3...}

$\mathbb{Q}$ = Insieme di tutti i **numeri razionali**, ovvero tutte le frazioni          $\frac{p}{q}$ con $p\in \mathbb{Z}$ , $q \in \mathbb{N}^+$ .

$\mathbb{R}$ = Insieme dei **numeri reali** il quale $\supseteq \mathbb{Q}$, e i **numeri irrazionali**       i quali sono $\mathbb{R} \setminus \mathbb{Q}$, ovvero $\pi, e, \sqrt{2}$.

$\mathbb{C}$ = Insieme dei **numeri complessi**, cioè i numeri nella forma           $a+ib$ con $a,b \in \mathbb{R}$. La quantità $i$ viene definita *unità                 immaginaria* e verifica l'uguaglianza $i^2 = - 1$, essa non è           un numero reale.

>[!Note] Osservazione
$\mathbb{N}^+\subset\mathbb{N}\subset\mathbb{Z}\subset\mathbb{Q}\subset\mathbb{R}\subset\mathbb{C}$.

#### Prodotto cartesiano
Esso è definito come l'insieme di tutte le coppie ($x,y$) con $x \in X$ e $y \in Y$ ordinate. 
E viene definito dal simbolo "$\times$" che può essere letto come moltiplicazione o direttamente "cartesiano", come in A cartesiano B.

>Pensala così: Devi mischiare tutti gli elementi di un gruppo almeno una volta con tutti gli altri, guarda [esempio](https://www.youmath.it/lezioni/algebra-elementare/insiemistica/1524-prodotto-cartesiano.html) 

17/01/2025
#### Cardinalità degli insiemi

Si denota con $\lvert X \rvert$ la cardinalità[^2] dell'insieme $X$, ovvero il numero di elementi contenuti nell'insieme $X$, di conseguenza la scrittura $\lvert X \rvert = n$ rappresenta un insieme $X$ che contiene $n$ elementi, se l'insieme fosse infinito usero $\infty$ al posto di $n$.

#### Insieme Potenza

O insieme delle parti di $X$ si denota con $P(X)$ ed è l'insieme i cui oggetti sono tutti e soli i sottoinsiemi di $X$. Gli elementi di $P(X)$ si dividono in ==propri== e ==impropri==:
- Impropri: $X$ e $\emptyset$ 
- Propri: Tutto il resto. Se $X={x}$ l'insieme viene definito come $singleton$ di $x$. 
Esempio:

$Y = {1,2,3}$ allora $P(Y)$ $=$ {$\emptyset$, Y, {1}, {2}, {3}, {1,2}, {1,3}, {2,3} }

>[!Note] Osservazione 
>Se $X$ è un insieme e $\lvert$X$\rvert = n$ allora $\lvert P(X) \rvert = 2^n$


>[!Warning] Attenzione
>Gli insiemi $\lbrace$$\lbrace 2 \rbrace$, $\lbrace 3 \rbrace$$\rbrace$ e $\lbrace 2,3 \rbrace$ sono diversi, il primo sono due $singleton$, il secondo sono due interi.


[^1]: Un divisore è un numero intero b è divisore di a se esiste un numero c tale che a = b  c, ad esempio: 
 a = 42, b = 7, c= 6 $\Longrightarrow$ 42 = 7 $\cdot$ 6 quindi 7 è un divisore a parti invertite anche 6 è un divisore.

[^2]: La parola cardinalità si può interpretare come "legge essenziale/fondamentale che regola un insieme" nel caso della cardinalità matematica.
