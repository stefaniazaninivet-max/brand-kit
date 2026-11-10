Scheda per un reparto o un servizio: tessera in alto a sinistra, badge in alto a destra, titolo, due righe di testo e un collegamento. Sta su `surface` con fondo `surface-soft` e bordo `line`; al passaggio del mouse si alza con `shadow-card`.

- Chi usa il componente fornisce: il titolo (`titolo-3`, massimo cinque parole), un testo breve di una o due frasi e la destinazione del collegamento. Il collegamento inizia con un verbo e finisce con la freccia.
- Una tessera per scheda: `zn-tile` (azzurro + blu del logo) è la regola, `zn-tile--notte` per i reparti specialistici, `zn-tile--accent` piena solo per le urgenze o l'azione principale, una sola per riga di schede.
- Disponi le schede in una griglia di 2–3 colonne con `space-4` di distanza.
- Non mettere foto dentro la scheda: per le immagini usa un riquadro a parte con `radius-lg`.
