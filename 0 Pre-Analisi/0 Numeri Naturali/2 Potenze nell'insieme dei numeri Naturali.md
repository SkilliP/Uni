Per potenza di un numero di intende un numero che fa da *base* $a \in \mathbb{N}$ e un numero $b \in \mathbb{N}$ che fa da *esponenente* e si indica con:
$$a^b$$ 
dove noi moltiplichiamo $a$ per se stesso $b$ volte, per esempio:
prendiamo come base $2$ e come esponente $3$, quindi si scriverà come $2^3$ e si svolgerà in questo modo:
$$2^3 = 2 * 2 * 2 = 4 * 2 = 8$$
quindi *due alla terza* fa otto, ogni potenza viene chiamata seguendo la formula "base alla esponente", per esempio:
$$3^{234}$$ si leggerà come "tre alla duecentotrentaquattresima".

>[!Note] Ogni numero ha per esponente 1 anche se non si scrive.
#### Casi Particolari

- La potenza $a^1 = a$

- La potenza $a^0 = 1$ con $\space a \ne 0$ 

- La potenza $0^0 = non \space definito$   

#### Proprietà delle Potenze

  >[!Danger] Non sono dimostrazioni gli esempi seguenti all'enunciazione delle proprietà delle potenze
  >>[!Attention] In futuro potremo dimostrare anche queste semplici proprietà grazie a metodi come la dimostrazione per assurdo o la dimostrazione per induzione

##### Stessa base

- ==Prodotto==: $a^n * a^m = a^{n + m}$ 
  Esempio: $2^3 * 2 ^ 2 = 2^5$ 

- ==Divisione==: $a^n : a^m = a^{n-m}$ con $n,m \in \mathbb{N}, n > m$ 
  Esempio: $2^3 : 2^2 = 2^1$ 

- ==Potenza di Potenza==: $(a^n)^m = a^{n * m}$ 
  Esempio: $(2^2)^3 = 2^{2 * 3} = 2 ^6$ 

##### Stesso Esponente

- ==Prodotto con lo stesso esponente==: $a^n * b^n = (a *b)^n$
  Esempio: $2^3 * 3 ^3 = (2 * 3)^3$

- ==Divisione con lo stesso esponente==: $a^n : b^n = (a : b)^n$
  Esempio: $2^3 : 3 ^3 = (2 : 3)^3$
  
##### Basi Diverse

- ==Prodotto di più fattori allo stesso esponente==: $(a * b * c)^n = a^n * b^n * c^n$
  Esempio: $(3 * 2)^2 = 3^2 * 2^2$  

- ==Divisione di più fattori allo stesso esponente==: $(a : b)^n = a^n : b^n$ con $b \ne 0$
  Esempio: $(3 : 2)^2 = 3^2 : 2^2$  

>[!Note] Nota Bene
Possiamo dimostrare ora perchè $a^0 = 1$ usando le proprietà delle potenze. Infatti possiamo notare come $1 = a^n : a^n$ in quanto un numero diviso se stesso da come risultato $1$ ma se $1 = a^n : a^n$ e $a^n : a^n = a^{n-n}$  abbiamo che $n - n = 0$ e quindi abbiamo che: $1 = a^n : a^n = a^{n - n} = a^0$ per cui abbiamo che $1 = a^0$ come volevamo dimostrare.

##### Basi ed Esponenti diversi

Non ha proprietà, idem somma e sottrazione tra potenze.