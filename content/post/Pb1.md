---
title: Calcul des intégrales \(\textstyle \int_{0}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t\) et \(\textstyle\int_{0}^{+\infty}\frac{\ln(1+t)}{t(1+t)}{\rm d}t\)

date: 2022-07-15
math: true
---

   **Partie I.** 

1. Montrer que l'intégrale $\int_{0}^{1}\frac{\ln t}{1+t}{\rm d}t$ est convergente.
2.
	(a) Montrer que les intégrales $\int_{0}^{1}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t$ et $\int_{1}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t$ sont convergentes.

	(b) Établir que
    $$
\int_{0}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t= 2 \int_{1}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t.
    $$
3. À l'aide d'une intégration par parties bien justifiée, montrer que
  $$
\int_{0}^{1}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t=-2 \int_{0}^{1}\frac{\ln t}{1+t}{\rm d}t.
  $$
  
4. (a) Montrer que pour tout $n\in \mathbb{N}$, l'intégrale $u_{n}=\int_{0}^{1}t^{n}\ln t{\rm d}t$ est convergente.

   (b) Montrer que $\forall n\in \mathbb{N},\quad u_{n}=- \frac{1}{(n+1)^{2}}$.
   
   (c) Vérifier que
    $$ 
	\forall n\in \mathbb{N},\quad \sum\limits_{k=0}^{n}(-1)^{k}u_{k}=\int_{0}^{1}\frac{\ln t}{1+t}{\rm d}t+(-1)^{n}\int_{0}^{1}t^{n+1}\frac{\ln t}{1+t}{\rm d}t.
	$$

  5.  En admettant que $\sum\limits_{n=1}^{+\infty}\frac{(-1)^{n}}{n^{2}}= -\frac{\pi^{2}}{12}$, déduire de ce qui précède les valeurs des intégrales
  $$
\int_{0}^{1}\frac{\ln t}{1+t} {\rm d}t\quad \text{et de}\quad \int_{0}^{+\infty}\left( \frac{\ln t}{1+t} \right)^{2}{\rm d}t.
  $$

**Partie II.**

On considère la fonction $f$ définie sur $[0,+\infty[$ par $f(t)= \frac{\ln(1+t)}{t}$, si $t\ne0$ et $f(0)=1$.

1. Vérifier que $f$ est continue sur $[0,+\infty[$.

  Dans la suite, on considère $F:x\mapsto \int_{0}^{x}f(t){\rm d}t$, pour tout $x\ge0$.
  
2. Montrer que $F(1)=- \int_{0}^{1} \frac{\ln t}{1+t}{\rm d}t$.

2. Montrer que la fonction $t\mapsto \frac{f(t)}{1+t}$ est intégrable sur $[0,+\infty[$.
3. 
   (a) Montrer que $F(x)\underset{x\to +\infty}{=}o(x)$.
   
   (b) En déduire que $t\mapsto \frac{F(t)}{(1+t)^{2}}$ est intégrable sur $[0,+\infty[$, et que
    $$
\int_{0}^{+\infty}\frac{F(t)}{(1+t)^{2}} {\rm d}t= \int_{0}^{+\infty}\frac{f(t)}{1+t} {\rm d}t.
    $$
4. 
   (a) Prouver que
    $$
\int_{0}^{+\infty}\frac{f(t)}{1+t} {\rm d}t= \frac{1}{2} \int_{0}^{+\infty}\frac{F(t)+ F \left( \frac{1}{t} \right)}{(1+t)^{2}} {\rm d}t.
    $$
	(b) Montrer que $\forall x>0,\quad F(x)+ F \left( \frac{1}{x} \right)= \frac{1}{2}(\ln x)^{2}+2F(1)$.
	
5. Déduire de ce qui précède la valeur de $\int_{0}^{+\infty}\frac{f(t)}{1+t} {\rm d}t$.


