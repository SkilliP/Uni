17/01/2025
#### Unione di due Insiemi

L'==unione== di due insiemi $X$ e $Y$ ==genera un terzo insieme== composto da tutti gli elementi di $X$ e $Y$ presi una sola volta. Questa operazione si indica con $X \cup Y$ che si potrebbe definire anche come:
$$X \cup Y = \lbrace x \in X \space vel \space x \in Y \rbrace$$

il "vel" (la congiunzione "o inclusiva" in latino, in simboli *$\lor$*) sta per =="uno o l'altro ma anche tutti e due"== al contrario di *$aut$* che è la o disgiuntiva in latino che si può interpretare come =="o l'uno o l'altro ma non entrambi"== in simboli è $\dot{\lor}$.

##### Proprietà

- $X \cup \emptyset = X$

- $X \subseteq X \cup Y$ 

- $Y \subseteq X \cup Y$

- $X \cup Y = Y \cup X$    *(commutatività)*

- $X \cup (Y \cup Z) = (X \cup Y) \cup Z$     *(associatività)*

- $X \cup X = X$    *(idempotenza)*

- $X \subset Y \Longleftrightarrow X \cup Y = Y$ 


#### Intersezione di due Insiemi

L'intersezione di due insiemi genera un terzo insieme detto *intersezione* di $X$ e $Y$ che è composto da tutti gli elemeti comuni ad $X$ e $Y$. Si indica con $X \cap Y$ che potremmo definire anche come:
$$X \cap Y = \lbrace x \in X \space et \space Y\rbrace$$
L' "et" (la congiunzione "e" in latino, in simboli $\land$) sta a significare "questo e quello insieme", quindi nella definizione di sopra stiamo dice che: L'insieme che si viene a formare dall'intersezione di $X$ e $Y$ è uguale all'insieme formato da tutte le $x$ che appartengono a $X$ e $Y$.

Nel caso in cui $X$ e $Y$ non abbiano elemeti in comune la loro intersezione darà l'insieme vuoto, quindi si ha $X \cap Y = \emptyset$ e in questo caso $X$ e $Y$ vengono definiti *disgiunti*
##### Proprietà

- $X \cap \emptyset = \emptyset$

- $X \cap Y \subseteq X$

- $X \cap Y \subseteq Y$

- $X \cap Y = Y \cap X$    *(commutatività)* 

- $X \cap (Y \cap Z) = (X \cap Y) \cap Z$    *(associatività)*

- $X \cap X = X$    *(idempotenza)*

- $X \subset Y \Longleftrightarrow X \cap Y = X$ 

#### Differenza tra due Insiemi

La differeza tra gli insiemi $X$ e $Y$ genera un terzo insieme chiamato *differenza* di $X$ meno $Y$ composto dagli elementi di $X$ che non appartengono a $Y$. Esso si indica con il simbolo $X - Y$.

>[!info] Osservazione
se $X \ne Y$ allora $X - Y \ne Y - X$

#### Complementarietà

Prendendo un insieme fissato $X$ se $Y$ al suo interno è un sottoinsieme di $X$ allora, il *complementare* di $Y$ in $X$, che si denota con $Y^\prime$, e composto dagli elementi di $X$ che ==non appartengono== ad $Y$, quindi possiamo dire:

$$Y^\prime = X - Y$$
##### Proprietà

$Y \cap Y^\prime = \emptyset$

$Y \cup Y^\prime = X$

$(Y^\prime)^\prime = Y$

$Y \subset Z \Longleftrightarrow Z^\prime \subset X^\prime$ con $Y \subset X$ 

#### Proprietà Miste

##### Unione e Intersezione

$X \cup (Y \cap Z) = (X \cup Y) \cap (X \cup Z)$

$X \cap (Y \cup Z) = (X \cap Y) \cup (X \cap Z)$

##### Unione e Intersezione e Complementarietà

Avendo due insiemi $Y$ e $Z$ entrambi sottoinsiemi di $X$ valgono le seguenti *Leggi di De Morgan*:

$(Y \cup Z)^\prime = Y^\prime \cap Z^\prime$

$(Y \cap Z)^\prime = Y^\prime \cup Z^\prime$


![[SetTheory.png]]

18/01/25
#### Prodotto Cartesiano

Se  $X$ e $Y$ sono due insiemi non vuoti si definisce un terzo insieme $X \times Y$ che si chiama *prodotto cartesiano di $X$ per $Y$*, il quale è composto dalle coppie ordinate costituire al primo posto da un elemento di $X$ ed al secondo da un elemento di $Y$, per esempio:
$$X \times Y = \lbrace (x,y):x \in X, y \in Y \rbrace$$

>[!Warning] Attenzione
$X \times Y \ne Y \times X$ in quanto il prodotto cartesiano richiede coppie ordinate con gli elementi del primo insieme al primo posto e quelli del secondo insieme al secondo posto.


Il prodotto cartesiano di $X \times X$ si denota con $X^2$ e si dice *quadrato cartesiano* e in generale con il simbolo $X^n$ denotatiano la n-ma potenza cartesiana di $X$, la quale è il prodotto cartesiano di $n$ coppie dell'insieme $X$. Per esempio:
Se $X = \lbrace 1, 3, 5\rbrace$ allora $X^3 =$ $$ X_1 \times X_2 \times X_3 = (1,3) \times (1,3) \times (1,3) = (1, 1, 1), (1, 1,3), (1 ,3, 1), (1, 3, 3)... \space e \space cosi' \space via$$

>[!note] Osservazione
Se $Y$ e $Z$ sono sottoinisiemi di $X$ anche gli insiemi: 
$Y \cup Z, \space Y \cap Z, \space Y^\prime, \space Z^\prime, \space Y - Z, \space Z - Y$ sono sottoinsiemi di $X$, questo non vale però per il prodotto cartesiano dei due insiemi, questo perchè con il prodotto cartesiano si vengono a creare delle coppie che non esistono nell'insieme $X$, esistono come valori separati ma non come una coppia ordinata chiaramente.

