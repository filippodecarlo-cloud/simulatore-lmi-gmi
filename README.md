# Simulatore LMI–GMI

Simulatore del modello di scoring del *Questionario e Modello di Valutazione Lean & Green* (UNIFI–ENEA, bozza rev8).

Si inseriscono le risposte di un'azienda di prova; la pagina calcola passo per passo:

- **Lean Maturity Index (LMI)**: domande 13 (media tra 13 e 13B), 14, 15 e 16;
- **Green Maturity Index (GMI)**: domande 17 (media di Energia Elettrica e Gas Naturale), 19 e 20;
- **profilo** restituito all'azienda (anello debole = minimo tra LMI e GMI), con la segnalazione di squilibrio quando la differenza è almeno 1,5.

Sono applicate anche la logica di salto (settore servizi, Lean non conosciuta) e la regola sui dati mancanti (LMI con almeno 3 risposte su 4, GMI con almeno 2 su 3).
Le regole non ancora presenti nel documento sono marcate come *proposta*.

Pagina unica (`index.html`), senza dipendenze esterne: nessun dato lascia il browser.
