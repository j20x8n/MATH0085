java c
Asset Pricing in Continuous Time 
MATH0085 
MSc Examination 
2023Problem 1. Consider      a      filtered      probability   space      (Ω   ,   F,   P)   equipped   with   a standard   (P, {Ft   }t≥0)-Brownian   motion   {Wt   }t≥0      starting   at   zero,   where   {Ft   }t≥0   is   the   natural   filtration   generated   by   {Wt   }t≥0   .    We   denote   by   E   the   expectation under   the   measure   P.
(a)    Is   the   process
{9Wt/9}t≥0
a   standard   Brownian   motion   with   respect   to   its   natural   filtration?    Justify   your   answer.                                                                                                                                                                                                                                                                                                   [5]
(b)   Assuming   that   the   process

is   integrable,   argue   whether   it   is   a   martingale   with   respect   to   {Ft   }t≥0      and justify   your   answer.                    [5]
(c)    Suppose   that   T   > 0   is   constant.    Choose   a   partition   Π   with   points   0   = t0    < t1 < t2 < . . . < tn = T, and mesh (longest subinterval) denoted by ||Π|| . Find the first variation of W, given by the limit in probability

Hint:    Use   the fact   that   the    quadratic   variation    (limit   in   probability)   is

Justify   your   answer.                                                                                                                                                                                                                                                                [5]
(d)    Derive   the   stochastic   differential   equation   satisfied   by
{Wt3   }t≥0   .
Using   this,   calculate   E[Wt3],   for   all   t   ≥ 0.                                                                                                                                                          [5]
(e)    Calculate   the   quadratic   variation   of the   process
{Wt3   }t≥0
and   explain   whether   this   is   independent   of the   Brownian   motion’s   path.    [5]
Problem 2. Consider   a   financial   market   defined   on   a   filtered   probability   space (Ω   ,   F, {Ft   }t≥0,   P) with   a   risky   financial   asset   with   price   process   {St   }t≥0      satisfying
dSt      = µStdt   + etStdWt   ,          S0      >   0,                                                                                                 (1)
where   µ   ∈ R,   {Wt   }t≥0    is   a   (P, {Ft   }t≥0)-Brownian   motion,   and   {Bt   }t≥0    is   a   money market   account   satisfying
dBt      = rBtdt,            B0      =   1,
where   r   >   0.    Then,   consider   a   European-type   option   with   payoff 1{ST>K}    at   the expiration   time   T   > 0, with   K   > 0   and 1{·}      denoting   the   indicator   function.
(a)   Derive   the   solution   {St   }t≥0    to   the   stochastic   differential   equation   (1).                [4]
(b)    Derive   the   risk-neutral   stochastic   differential   equation   of   the   price   process {St   }t≥0   .   Explain   in   detail   all   steps.                                           [6]
(c)   Derive   the   explicit   formula   for   the   risk-neutral   price   V   (t,   St   )   of   the   option at   any   time   t   ∈   [0,   T].   Explain   in   detail   all   steps.               [10]
(d)    Construct   a   hedging   portfolio   for   the   option   and   derive   the   explicit   expres-   sions   of   the   hedging   positions   at   any   time   t   ∈   [0,   T].      Explain   in   detail   all   steps.                                                                     [5]Problem 3. Consider      a   filtered   probability    代 写MATH0085 Asset Pricing in Continuous Time MSc Examination 2023R
代做程序编程语言  space   (Ω   ,   F, {Ft   }t≥0,   P)   equipped with   a   standard   (P, {Ft   }t≥0)-Brownian   motion   {Wt   }t≥0    and   the   stochastic   integral process   {Bt   }t≥0    given   by
where

Throughout   this   question, you   may   use   without   proof   that   all   stochastic   integrals against   W   are   martingales.
(a)   Is   the   process   {Bt   }t≥0         a   standard      (P, {Ft   }t≥0)-Brownian   motion?       Justify your   answer.                                                           [5]
(b)   What   is   the   stochastic   differential   equation   satisfied   by   the   process   {BtWt   }t≥0?   As   a   consequence,   calculate   its   expected   value.   Justify   your   answers.                   [5]
(c)   What is the stochastic differential equation satisfied by the process {BtWt2   }t≥0?   As   a   consequence,   calculate   its   expected   value.   Justify   your   answers.                   [9]
(d)   Are   the   processes   {Bt   }t≥0    and   {Wt   }t≥0
(i)   correlated?
(ii)   independent?
Justify   your   answers.                                                                                                                                                                                                                                                                [6]
Problem 4. Consider   a   financial   market   defined   on   a   risk-neutral   filtered   prob-   ability   space   (Ω   ,   F, {Ft   }t≥0,   Q) with   a   risky   asset   with   price   process   {St   }t≥0      satis-fying
dSt      = rtStdt   + σStdWt(1)   ,          S0    > 0,                            (2)
where   σ   >   0,   {Wt(1)   }t≥0    is   a   standard   (Q, {Ft   }t≥0)-Brownian   motion   and   {rt   }t≥0   is   the   interest   rate   process.Consider   a   long   position   in   a   forward   contract   with   expiration   time   T   >   0,   when the   investor   pays   the   forward   price   F0,T       and   receives   the   aforementioned   asset.   Recall   that,   F0,T      is   F0-measurable   (i.e.   known   at   time   t   = 0).
Suppose   that   the   interest   rate   is   constant   rt    = r   > 0   for   all   t   ∈   [0,   T].
(a)   Using a replicating portfolio, derive the explicit expression of   the no-arbitrage   value   of the   forward   price   F0,T .       [5]
(b)   What   is   the   risk-neutral   value   of   the   aforementioned   forward   contract   at   any intermediate   time   t   ∈   [0,   T]?   Justify   your   answer.           [5]
Suppose   for   the   remainder   of   this   question   that   the   interest   rate   {rt   }t≥0    satisfies drt      =   (a − rt   )dt   + bdWt(2)   ,          r0      ∈   R,
where   a,b    >      0   and   {Wt(2)   }t≥0       is   a   standard      (Q, {Ft   }t≥0)-Brownian   motion.       A   zero-coupon   bond   which   pays   1   at   its   maturity   time   T   has   value   B0(*),T    at   time   0.
(c)    Derive   the   explicit   expression   of the   no-arbitrage   value   of the   forward   price F0,T    in   terms   of B0(*),T      and   S0   .    Explain   in   detail   all   steps.                           [7]
Finally,   consider   a   long   position   in   a   futures   contract   with   maturity   time   T   >   0.   This   is   an   agreement   to   receive   as   a   cash   flow   the   changes   in   the   futures   price
ft,T    = EQ   [ST   |Ft]                   (under   no-arbitrage) 
of the   asset   during   the   times   t   ∈   [0,   T]. 
(d)    Derive an explicit expression for the forward–futures spread   in terms   of   B0(*),T   .
Based   on   that,   give   an   example   of a   positive   spread   and   another   example   of   a   zero   spread.                                    [8]







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
