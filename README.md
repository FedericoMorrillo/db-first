# db first

creazione di una tabella che contiene i dati delle auto usate messe in vendita da un autoconcessionario.

Legenda:
marca: ho usato un varchar per contenere un massimo di 50 caratteri;

modello: ho usato un varchar con un massimo di 100 caratteri;

carburante: ho usato un varchar con 7 caratteri per contenere'diesel o benzina';

cambio: ho usato un varchar con massimo 10 caratteri per inserire le stringhe ' manuale o automatico';

KM percorsi: un valore int per assegnare un valore numerico;

accessori: ho assegnato un text per poter scrivere una descrizione;

anno di immatricolazione: la data impostata in anno-mese-giorno;

classe auto: con tinyint(1) posso assegnare un solo numero;

disponibile: con tinyint(1) posso assegnare solo un numero in questo caso 0 o 1 che verrebbero utilizzati come valore booleano;

descrizione: ho assegnato un text per poter scrivere una descrizione;

prezzo: decimal(6,2) per assegnare una cifra di massimo 6 numeri con altri due numeri dopo la virgola che starebbero per i centesimi;
