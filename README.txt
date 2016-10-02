C64_Very_Basic_3B


2 print".."tab(12)"rocky's dinerR"
10 printchr$(147)chr$(158)
15 tb=9:ac=10
22 print:printtab(tb)".bank account $"ac

25 print"."chr$(159)
30 wh=2:printtab(tb)"wheat bread $"wh
40 ch=2:printtab(tb)"cheese $....."ch
50 ma=1:printtab(tb)"mayonaise $.."ma
60 pi=3:printtab(tb)"pickles $...."pi
70 tt=wh+ch+ma+pi
80 print:printtab(tb)"your total is $"tt

82 ac=ac-tt
85 print:printtab(tb)"Pcash left $"ac
90 print
100 :
110 printtab(tb)".deserts:"chr$(154)
120 print
130 co=4:printtab(tb)"chocolate pie $"co
140 print
150 ifac>=co then print"you added a pie
to the menu"
160 if ac<co then print"...you don't hav
e enough for the pie."
ready.




















break
ready.

