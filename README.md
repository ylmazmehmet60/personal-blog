
=SUM(1/COUNTIF(A2:A100, "*" & TRIM(MID(SUBSTITUTE(A2:A100, ";", REPT(" ", LEN(A2:A100))), (ROW(A2:A100)-ROW(A2)+1)*LEN(A2:A100), LEN(A2:A100)))&"*"))


== HEROKU 

https://radiant-island-87085.herokuapp.com/
