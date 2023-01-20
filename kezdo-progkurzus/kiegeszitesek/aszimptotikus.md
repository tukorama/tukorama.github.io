{% include head.html %}

---
title: "Függvények aszimptotikus viselkedése"
permalink: /kezdo-progkurzus/kiegeszitesek/aszimptotikus
---

# Függvények aszimptotikus viselkedése

Függvények aszimptotikus viselkedését szeretnénk jellemezni a továbbiakban.

## $\Theta$-jelölés

### Definíció:
$\Theta(g(n)) = \{ f(n) : \exist c_1, c_2, n_0 \in \N, c_1, c_2, n_0 > 0  \text{, hogy }  \forall n > n_0 \text{-ra } 0 \leqslant c_1 g(n) \leqslant f(n) \leqslant c_2 g(n)  \}$