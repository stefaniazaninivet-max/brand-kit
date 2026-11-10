# Brand kit Veterinaria Zanini

Versione del 10/11/2026. File: `tokens.json` e `tokens.css` (colori, tipografia, spaziature), `logo/` (PNG trasparenti), `componenti/` (CSS e anteprime HTML), `tono-di-voce.md`, `dati-struttura.md`. I colori hanno un tema chiaro e uno scuro (`data-theme`).

---

Veterinaria Zanini è un ambulatorio di paese con la cura di un centro specialistico. Il marchio deve sembrare moderno, luminoso e vicino: competenza che si dà del tu. Questo kit sostituisce il precedente, tiene il blu del logo e aggiunge più aria, un corallo caldo e un motivo ricorrente, la tessera.

## Principi

- Parti dal bianco e dall'aria. `surface` è lo sfondo di default; `surface-soft` e `surface-tint` servono per staccare le sezioni.
- Il blu è la firma, il corallo è il sorriso. Usa `brand` per ciò che è strutturale (pulsanti, link, titoli in evidenza) e `accent` una sola volta per schermata, sull'azione che vuoi far compiere.
- Forme morbide e modulari. Angoli sempre arrotondati con `radius-md` o `radius-lg`, come le quattro tessere del logo; niente spigoli vivi, niente ombre pesanti.
- Un'immagine vera vale più di dieci decorazioni. Se c'è una foto, lascia che sia lei la protagonista.

## Logo

Il marchio è la griglia 2×2 (croce medica, gatto, cane, coniglio) con la scritta "Veterinaria Zanini". I file in `logo/` hanno lo sfondo trasparente.

- Su `surface`, `surface-soft` e `surface-tint` usa `logo-completo.png`, `simbolo.png` e `scritta.png`.
- Su `notte`, su fotografie scure e sul tema scuro usa `logo-completo-scuro.png` e `scritta-scuro.png`. Il simbolo resta quello normale: le tessere blu si vedono bene anche sul fondo scuro.
- Spazio libero attorno al logo: almeno la larghezza di una tessera. Larghezza minima del logo completo 120 px (30 mm in stampa); sotto, usa solo il simbolo, almeno 32 px.
- Non ruotare, non deformare, non cambiare i colori, non inserire il logo su fondi con disegno o foto affollate. Non aggiungere ombre.
- Il simbolo da solo va bene per profilo social, icona dell'app e timbro. Il logo completo va su carta intestata, sito, insegne e firme email.

## Colore

- Fondo e testo: `surface` con `ink` per il testo, `ink-muted` per le note. Non usare testo `brand` o `azzurro` sul fondo `brand`.
- `brand` per pulsanti principali e link; `brand-deep` per hover e per il testo blu su `surface-tint`.
- `azzurro` e `logo-blu` sono i due toni delle tessere del logo; `notte` è il blu profondo per fasce scure. Servono a disegnare, non a scrivere.
- `accent` (corallo) è per l'azione principale: "Prenota", "Chiama". Il testo sopra è sempre `on-accent`, mai bianco. Non usare `accent` come colore del testo su `surface`.
- `salute` per prevenzione e vaccini; `urgenza` per pronto soccorso e avvisi. Accompagnali sempre con una parola o un'icona: il colore da solo non basta.
- Tema scuro: stessi nomi, valori più chiari. Quando serve un fondo scuro in un documento chiaro, usa `notte` con testo bianco.

## Tipografia

- Titoli in Plus Jakarta Sans (`display`, `titolo-1`, `titolo-2`, `titolo-3`), testo in DM Sans (`testo-lg`, `testo`, `testo-sm`). Sono due caratteri gratuiti di Google Fonts, in licenza libera anche per uso commerciale. Dove non sono disponibili, il sistema ripiega su Montserrat, il carattere del vecchio sito.
- Un solo `display` per pagina. Sotto, scendi di un gradino alla volta e non saltare da `display` a `testo`.
- Testo corrente almeno 16 px sul web e 11 pt in stampa; mai sotto 14 px per le note.
- `etichetta` è per i badge e i sovratitoli: sempre maiuscola, 12 px, spaziatura ampia.
- Frasi brevi, righe non più larghe di circa 70 caratteri.

## Forme e motivo

La firma grafica è la tessera: un quadrato arrotondato diviso lungo la diagonale in due toni, con la metà chiara in alto a destra, come nel logo.

- Costruiscila con `radius-md` o `radius-lg`; la coppia più usata è `azzurro` + `logo-blu`, poi `logo-blu` + `notte`.
- Le tessere si dispongono in griglia modulare con `space-4` di distanza; alcune possono occupare due moduli.
- Una tessera in `accent`, piena, può inserirsi tra le altre come tocco caldo. Non più di una per composizione.
- Usala come sfondo di copertine, intestazioni di documenti, post e icone dei reparti. Non sovrapporla al testo.
- Non usare gradienti. Il solo passaggio di tono ammesso è la diagonale netta della tessera.

## Immagini

- Foto di animali vivi, con luce naturale e sguardo in camera o verso la persona che li cura. Sempre a colori, calde, mai ritoccate in modo pesante.
- Ritaglia con angoli arrotondati `radius-lg`. Una foto per riquadro; niente collage con più di tre immagini.
- Foto dei reparti e dello staff solo con il permesso delle persone. Niente immagini stock di animali che non sono quelli dell'ambulatorio quando se ne possono usare di proprie.
- Icone: sagome piene a un solo colore (`brand` o `ink`), angoli arrotondati, spessore uniforme. Niente emoji come decorazione nei materiali stampati.

## Composizione

- Margini ampi: `space-8` ai lati su schermo ampio, `space-4` su telefono.
- Una schermata o una pagina ha un solo punto di arrivo: un titolo `display` o `titolo-1`, poi una frase, poi l'azione.
- Schede e riquadri: `surface-soft` sul fondo `surface`, bordo `line`, angoli `radius-lg`. L'ombra `shadow-card` compare solo al passaggio del mouse.
- Pulsanti: massimo uno `accent` per vista; gli altri sono `brand` o contorno `outline`.
- Controlla sempre che il testo sia leggibile: 4,5:1 di contrasto nei temi chiaro e scuro, 3:1 per bordi, icone e anello di focus.

## Componenti

`Button`, `Badge` e `ServiceCard` in `components/` mostrano le regole di sopra già applicate; usali come riferimento per sito, app e moduli, e riprendili tali e quali nei materiali stampati.
