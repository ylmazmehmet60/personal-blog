=SUM(1/COUNTIF(FILTERXML("<t><s>" & SUBSTITUTE(A2, ";", "</s><s>") & "</s></t>", "//s"), FILTERXML("<t><s>" & SUBSTITUTE(A2, ";", "</s><s>") & "</s></t>", "//s")))


== HEROKU 

https://radiant-island-87085.herokuapp.com/
