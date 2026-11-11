# ColdCases.it — prototipo aggiornato

Archivio statico bilingue (italiano/inglese). `index.html` contiene ora i sei record incorporati e funziona anche con doppio clic, senza server locale. `cases.json` resta il file sorgente da aggiornare quando si aggiungono o correggono casi: dopo una modifica, rigenerare la copia incorporata in `index.html` oppure chiedere un nuovo pacchetto aggiornato.

## Pubblicazione gratuita
1. Crea un repository GitHub chiamato `coldcases`.
2. Carica `index.html`, `cases.json` e questo README.
3. In Settings → Pages seleziona Deploy from a branch, branch `main`, folder `/root`.
4. Il sito sarà disponibile su `https://TUO-UTENTE.github.io/coldcases/`.
5. Per usare `ColdCases.it`, registra il dominio e configura i DNS seguendo le istruzioni GitHub Pages.

## Timer
Ogni record specifica `date`, `timer_basis`, `timer_label` e `timer_label_en`. Il timer parte dalla data documentata dell'evento scelto: scomparsa, dirottamento o ritrovamento. Se l'ora esatta non è nota, la mezzanotte locale è una convenzione tecnica, non un dato storico. Per i corpi non identificati il timer parte dal ritrovamento, non dalla data stimata della morte.

## Avvertenza editoriale
I sei casi sono un primo nucleo dimostrativo, non un censimento completo. Prima di pubblicare, verificare periodicamente stato del caso, fonti, date e link. Per i tre casi INTERPOL, la data del timer è quella del ritrovamento; per DE01 la causa della morte non è stata determinata e un reato non è stato escluso, ma non va presentato come omicidio accertato.
