REGOLE:
0) Scaricate l'intera cartella per lavorare

1) Non modificate Header e Footer nella vostra versione, 
se ci sono problemi parliamone prima insieme

2) Cerchiamo di utilizzare il più possibile gli elementi di bootstrap che sono già pronti 
e facili da usare.

3) Quando dovete modificare spaziature, colori, ecc. e state utilizzando degli elementi 
di Bootstrap cercate sulla documentazione se c'è un modo per farlo senza modificare 
le classi.
Per esempio se dovete mettere margin alle card utilizzate le classi di Bootstrap 
me (margin end), ms (margin start), mt (margin top) e mb (margin bottom) negli elementi
che volete cambaire.

4) Se dovete proprio modifcare a mano lo stile di qualcosa di bootstrap cercate 
di modificare le classi e gli id già presenti. Per farlo basta richiamarli nel nostro CSS
e inserire le modifiche così da sovrascriverle (il css è richaimato dopo a quello di 
Bootstrap quindi lo sovrascrive sempre).

INFORMAZIONI:
- Le cartelle sono così strutturate: .idea (cose del browser), Cienrgy (directory 
principale), assets (elementi grafici come immagini e foglio di stile), pages (tutti 
i file html delle pagine)

- Le pagine dentro a pages hanno la stessa struttura con personalizzazioni nella navbar per
far capire in che pagina ci troviamo.