# Simulatore LMI–GMI

Simulatore del modello di scoring del *Questionario e Modello di Valutazione Lean & Green* (UNIFI–ENEA, bozza rev9).

Si inseriscono le risposte di un'azienda di prova; la pagina calcola passo per passo:

- **Lean Maturity Index (LMI)**: domande 13 (media tra 13 e 14), 15, 16 e 17;
- **Green Maturity Index (GMI)**: domande 18 (media di Energia Elettrica e Gas Naturale), 20 e 21;
- **profilo** restituito all'azienda (anello debole = minimo tra LMI e GMI), con la segnalazione di squilibrio quando la differenza è almeno 1,5.

Sono applicate anche la logica di salto (settore servizi, Lean non conosciuta) e la regola sui dati mancanti (LMI con almeno 3 risposte su 4, GMI con almeno 2 su 3).

Pagina unica (`index.html`), senza dipendenze esterne: nessun dato lascia il browser.
