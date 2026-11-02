---
name: stop-slop-it
description: Toglie dai testi in italiano i tic della scrittura AI, come frasi di circostanza, contrasti a formula, avverbi e gergo. Usala quando scrivi, correggi o rivedi un testo in italiano.
license: MIT
metadata:
  based-on: hardikpandya/stop-slop
  language: it
---

# Stop Slop in italiano

Togli dalla prosa italiana gli schemi prevedibili della scrittura generata dall'AI.

## Regole principali

1. **Taglia le frasi di riempimento.** Via le aperture di circostanza ("Ecco il punto", "Diciamocelo"), le stampelle dell'enfasi ("E non è poco") e gli avverbi che non aggiungono informazione. Vedi [references/frasi.md](references/frasi.md).

2. **Rompi le strutture a formula.** Niente "non è X, è Y", elenchi in negativo, frasi spezzate per effetto, domande seguite dalla risposta, oggetti che agiscono come persone. Vedi [references/strutture.md](references/strutture.md).

3. **Dai un soggetto alle frasi.** L'italiano nasconde chi agisce con il passivo e con il "si" impersonale ("si è deciso", "viene effettuata un'analisi"). Scrivi chi fa cosa.

4. **Usa i verbi, non i nomi.** "Effettuare una verifica" diventa "verificare", "procedere all'invio" diventa "inviare". La nominalizzazione allunga la frase e la svuota.

5. **Sii specifico.** Niente affermazioni vaghe ("Le implicazioni sono enormi"). Nomina la cosa precisa. Niente estremi pigri ("sempre", "tutti", "mai") usati senza motivo.

6. **Porta il lettore nella scena.** Parla a chi legge, con il "tu" o il "voi" che il testo richiede, e preferisci il dettaglio all'astrazione. Niente voce da narratore lontano.

7. **Varia il ritmo.** Alterna frasi brevi e lunghe. Due elementi valgono più di tre. Chiudi i paragrafi in modi diversi. Niente trattini lunghi.

8. **Fidati di chi legge.** Dai i fatti senza ammorbidirli, giustificarli o accompagnare per mano.

9. **Taglia le frasi da citazione.** Se una frase suona come un aforisma da stampare in grande, riscrivila.

## Controlli rapidi

Prima di consegnare un testo:

- Avverbi in "-mente" o rafforzativi come "davvero", "proprio", "assolutamente"? Toglili, o tienili solo se cambiano il significato.
- Un passivo o un "si" impersonale? Trova chi agisce e mettilo come soggetto.
- Un nome dove basta un verbo ("effettuare", "procedere a", "andare a")? Usa il verbo.
- Una cosa che compie un'azione da persona ("i dati ci dicono", "il progetto nasce")? Nomina la persona.
- Un'apertura come "Ecco", "Diciamocelo", "La verità è che"? Vai al punto.
- Un "non è X, è Y" o un "non solo X, ma anche Y"? Afferma Y.
- Una domanda seguita subito dalla risposta ("Il risultato? ...")? Dai la risposta.
- Tre frasi di fila della stessa lunghezza? Spezzane una.
- Un paragrafo che finisce con una battuta a effetto? Cambia la chiusura.
- Un trattino lungo? Usa la virgola, i due punti o le parentesi.
- Un'affermazione vaga ("La posta in gioco è alta")? Di' quale posta.
- Un commento sul testo stesso ("In questo articolo vedremo", "Senza ulteriori indugi")? Cancellalo.
- Un calco dall'inglese dove esiste l'espressione italiana ("fare la differenza", "impattare su", "al giorno d'oggi")? Riscrivi.

## Punteggio

Dai un voto da 1 a 10 su ogni dimensione:

| Dimensione | Domanda |
|------------|---------|
| Direzione | Il testo afferma o annuncia? |
| Ritmo | Vario o da metronomo? |
| Fiducia | Rispetta l'intelligenza di chi legge? |
| Autenticità | Sembra scritto da una persona? |
| Densità | C'è qualcosa da togliere? |

Sotto 35/50: riscrivi.

## Esempi

Vedi [references/esempi.md](references/esempi.md) per le trasformazioni prima e dopo.

## Cosa lasciare com'è

- Le citazioni testuali, i nomi propri e i termini tecnici del settore.
- Il tono voluto di un marchio: se un prodotto usa esclamazioni o ripetizioni per scelta, segnalale invece di toglierle.
- I testi legali e le istruzioni di sicurezza, dove la forma impersonale serve a essere precisi.

## Licenza

MIT. Adattamento italiano di [stop-slop](https://github.com/hardikpandya/stop-slop) di Hardik Pandya.
