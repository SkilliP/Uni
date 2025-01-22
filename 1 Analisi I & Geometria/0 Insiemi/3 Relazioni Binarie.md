19/01/25 - 20/01/25

Definite binarie perchè o sono vere o sono false, e relazioni perchè legano tra di loro due oggetti.

Se $X$ e $Y$ sono due insiemi, un sottoinsieme di $X \times Y$ si definisce come una relazione da $X$ a $Y$. ^b18d93

Se $\mathcal{R}$ è un sottoinsieme di $X \times X$ diremo che $\mathcal{R}$ è una *relazione* in $X$. Se la coppia $(x,y) \in \mathcal{R}$ diremo che $x$ è in relazione $\mathcal{R}$ con $y$ e scriveremo:
$$x \mathcal{R} y$$
Quindi la relazione binaria è un criterio/regola che associa ad un elemento di un insieme $A$ elementi di un insieme $B$, non importa se associo elementi di due sottoinsiemi di $A$ o se associo ad un elemento di $A$ più elementi di $B$ o di un sottoinsieme di $A$.

###### Esempi

Per definire una relazione che ha per criterio/regola il fatto che due elementi $a$ e $b$ di due insiemi $A$ e $B$ siano in relazione $\mathcal{T}$ se e solo se $a \in A + b \in B = numero \space pari$ scriveremo
$$a \mathcal{T} b \Longleftrightarrow a + b = numero\space pari$$
Volendo fare un esempio numerico avremmo che:

$A \lbrace 1,2,3 \rbrace$
$B \lbrace 1,2,5 \rbrace$

Ora per verificare queli coppie $a \in A$ e $b \in B$ appartengono alla relazione $a \mathcal{T} b \Longleftrightarrow a + b = numero\space pari$ possiamo fare il prodotto cartesiano $A \times B$ e la somma degli elementi delle coppie. 
$A \times B \lbrace (1,1),(1,2),(1,5),(2,1),(2,2),(2,5),(3,1),(3,2),(3,5)\rbrace$
ora con delle semplici addizioni possiamo verificare che solo le seguenti coopie appartengono alla relazione $a \mathcal{T} b \Longleftrightarrow a + b = numero\space pari$:
$(1,1), (1,5), (2,2), (3,1), (3,5)$

Le quali sono sottinsieme di $A \times B$, che potremmo definire con $C = (1,1), (1,5), (2,2), (3,1), (3,5)$, e questo sottoinsieme definisce la relazione $\mathcal{T}$, ovvero che la somma di due elementi di due insiemi dia come risultato un numero pari, tra $a \in A$ e $b \in B$ 

Si noti come non ho usato $\mathcal{R}$ per indicare che il simbolo non è importante tanto quanto il contesto, ovvero in questo caso un esempio sulle relazioni binarie tra due insiemi e le regole date ovvero che $a$ e $b$ sono relazionati se e solo se la loro somma dia un numero pari. Questo stesso esempio vale anche per una relazione binaria in un insieme $X$ con due sottoinsiemi.

>[!note] Osservazione
Se $\mathcal{R} = \emptyset$ diremo che $\mathcal{R}$ è la *relazione vuota* in $X$. Questo significa che nessun elemento di $X$ risulta in relazione $\mathcal{R}$ con qualche altro elemento di $X$.

##### Proprietà

- $\forall x \in X \space x \mathcal{R} x$    *riflessiva*

- $x \mathcal{R} y \Longrightarrow y \mathcal{R} x$    *simmetrica*

- $x \mathcal{R} y, \space y \mathcal{R} x \Longrightarrow x = y$    *antisimmetrica*

- $x \mathcal{R} y, \space y \mathcal{R} z \Longrightarrow x \mathcal{R} z$    *transitiva* 

##### Relazioni Complesse

Una relazione che soddisfi le proprietà:

- $\forall x \in X \space x \mathcal{R} x$    *riflessiva*

- $x \mathcal{R} y \Longrightarrow y \mathcal{R} x$    ==*simmetrica*==

- $x \mathcal{R} y, \space y \mathcal{R} z \Longrightarrow x \mathcal{R} z$    *transitiva* 

si dice relazione di **equivalenza**. 

Invece una relazione che soddifsfa le proprietà:


- $\forall x \in X \space x \mathcal{R} x$    *riflessiva*

- $x \mathcal{R} y, \space y \mathcal{R} x \Longrightarrow x = y$    ==*antisimmetrica*==

- $x \mathcal{R} y, \space y \mathcal{R} z \Longrightarrow x \mathcal{R} z$    *transitiva* 

si dice relazione di **ordine**.

###### Alcuni esempi

1. Sia $X$ l'insieme delle rette del piano ordinate e sia $\perp$ la relazione di perpendicolarità tra le rette, quindi una relazione definita come:
$$x \perp y \Longleftrightarrow x \space è \space perpendicolare \space ad \space y $$ Questa relazione soddisfa la proprietà simmetrica, perchè se una retta $a$ blu è perpendicolare ad una retta $b$ verde allora anche la retta $b$ sarà perpendicolare alla retta $a$ 

```desmos-graph
---
f(x) = 2
g(y) = -1/2

```

ma non quella riflessiva in quanto una retta non può essere perperdicolare a se stessa, o transitiva perchè non è detto che una retta $c$ perpendicolare ad $a$ sia perpendicolare anche a $b$, anzi è impossibile, inoltre neanche la relazione antisimmetrica è valida in quanto $a$ e $b$ non solo la stessa retta e non possono esserlo per la ragione citata sulla riflessività delle rette.

2. Sia $X$ l'insieme delle rette del piano ordinato e sia $\parallel$ la relazione di paralellismo tra le rette, ovvero la relazione così definita:
$$x \parallel y \Longleftrightarrow x \space è \space parallela \space alla \space retta \space y$$
Questa relazione risulta di *equivalenza* infatti due rette parallele si dicono tali se coicidono oppure sono disgiunte. 

```desmos-graph
---
f(x) = 2
g(x) = -2

```

La relazione risulta di equivalenza in quanto un retta è parallela a se stessa(riflassività), se una retta $a$ è parallela ad una retta $b$ allora anche $b \parallel a$ (simmetria) e infine se esiste una retta $c$ parallela a $b$ che a sua volta è parallela ad $a$, questa terza retta $c$ sarà parallela ad $a$. 

3. 

4. Sia $X$ in insieme non vuoto e sia "$=$" la relazione che diremo "identità", ovvero la relazione così definita:
$$x = y \Longleftrightarrow x \space ed \space y \space coincidono$$
Questa relazione definita in $X$ risulta essere una relazione di *ordine* ma anche di *equivalenza*. in quanto:
- $a = a$     *riflessività*

- $a = b \Longleftrightarrow b = a$    *simmetria* e *antisimmetrica*

- $a = b \land b = c, \space a = c$    *antisimmetria*

21/01/25
#### Classe di Equivalenza

Classe formata da tutti elementi equivalenti, non uguali attenzione, tra di loro, possono esserci più classi per gruppo, ogni classe è definita *partizione*

Sia $\mathcal{R}$ una relazione di *equivalenza* $\in$ $X$, se $x \in X$ allora risulta definito il sottoinsieme $\lbrack x \rbrack_\mathcal{R}$ di $X$ nel seguente modo:
$$\lbrack x \rbrack_\mathcal{R} = \lbrace \forall y \in X \colon x\mathcal{R}y \rbrace$$
Questa sottoinsieme è detto *classe di equivalenza* di $x$ rispetto alla relazione $\mathcal{R}$ e ogni elemento della classe si dice che *rappresenta* la classe.^29fc97

##### Proprietà 

- Dalla proprità *riflessiva* delle relazioni di equivalenza si ha che:
  Siano $X$ un insieme non vuoto ed $\mathcal{R}$ una relazione d'equivalenza definita in $X$, allora necessariamente ogni elemento di $X$ appartiene alla sua classe d'equivalenza rispetto ad $\mathcal{R}$, cioè:
$$\forall x \in X \Longrightarrow x \in \lbrack x\rbrack_\mathcal{R}$$
  Abbiamo quindi che ogni elemento di $X$, in questo caso, appartiene alla classe di equivalenza $\mathcal{R}$. 

- Dalle proprietà *simmetrica* e *transitiva* abbiamo che:
  Siano $X$ un insieme non vuoto ed $\mathcal{R}$ una relazione d'equivalenza definita in $X$, se l'elemento $y$ di $X$ appartienene alla classe d'equivalenza $x \in X$ rispetto alla relazione $\mathcal{R}$ allora la classe di $y$ rispetto ad $\mathcal{R}$ coincide con la classe di $x$, cioé:
  $$y \in \lbrack x \rbrack_\mathcal{R} \Longrightarrow \lbrack y \rbrack_\mathcal{R} = \lbrack x \rbrack_\mathcal{R}$$
  Questo è come dire che se $x$ è parallelo a $y$ e $y \parallel z$ allora $x \parallel z$ solo che più generale, in quanto il paralellismo è una relazione d'equivalenza sola, questa regola invece vale per ogni relazione d'equivalenza che segue le regole imposte dalla premessa.

  Da questa proprietà segue che:
  Siano $X$ un insieme non vuoto ed $\mathcal{R}$ una relazione d'equivalenza definita in $X$, se $x$ ed $y$ sono due elementi di $X$ allora necessariamente le classi di equivalenza di $x$ ed $y$ rispetto alla relazione $\mathcal{R}$ coincidono oppure sono disgiunte, ovvero:
  $$\lbrack y \rbrack_\mathcal{R} \cap \lbrack x \rbrack_\mathcal{R} \ne \emptyset \Longrightarrow \lbrack y \rbrack_\mathcal{R} = \lbrack x \rbrack_\mathcal{R}$$
Perchè abbiamo $\lbrack x \rbrack_\mathcal{R} = \lbrace \forall y \in X \colon x\mathcal{R}y \rbrace$ e $\lbrack y \rbrack_\mathcal{R} = \lbrace \forall x \in X \colon y\mathcal{R}x \rbrace$ che quindi le rende uguali, ricorda proprietà simmetrica delle relazioni binarie.

#### Quiziente

L'insieme delle classi di equivalenza relativa alla relazione di equivalenza $\mathcal{R}$ in un insieme $X$ non vuoto viene chiamato *insieme quiziente di $X$ modulo $\mathcal{R}$* ed è indicato con $X / \mathcal{R}$. In altre parole l'insieme quoziente di $X$ è l'insieme delle classi di equivalenza $\mathcal{R}$ contenute dentro $X$, quindi un sottoinsieme di $X$. 
L'insieme di queste classi viene definito *partizione* dell'insieme $X$, ovvero una collezione di sottoinsiemi non vuoti e disgiunti delle parti di $X$ la cui unione è $X$.

---

[Video relazioni binarie pt1](https://www.youtube.com/watch?v=kQfjZxx-SEs)[pt2](https://www.youtube.com/watch?v=92XpBoNNGMg)
