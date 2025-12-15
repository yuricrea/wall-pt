# PROPOSTA COMPLETA PIANO TERRA
## Wall SpaceTime + Wall Collettive + Automazione Social

*Documento programmatico - Dicembre 2025*

---

## ANTEFATTO

Dopo 13 anni, 1110 eventi, 15+ collettive, il sito di Piano Terra ha bisogno di un ripensamento. Non solo tecnico, ma **concettuale**.

La comunicazione dello spazio non può più essere un'appendice — deve riflettere quello che siamo: **una stratificazione di lotte, incontri, attraversamenti**.

---

## PROBLEMI ATTUALI

### Tecnici
- Sito WordPress datato, template rigido
- Navigazione confusa, pagine vuote ("chi siamo" + "dove siamo")
- Tag inconsistenti (sistematici solo dal 2021)
- Nessuna automazione tra piattaforme

### Organizzativi
- Telegram basso regime, Facebook quasi morto
- Puntello sottoutilizzato
- Pubblicazione frammentata (ogni collettiva per conto suo)
- Dipendenza da chi sa usare strumenti
- Aspettativa magica che post si propaghino da soli

### Culturali
- Pigrizia digitale diffusa (comprensibile ma problematica)
- Analfabetismo digitale (risolvibile)
- **IL PIÙ GRAVE:** lo spazio percepito come "eventificio"

### Il Problema Eventificio

**Piano Terra non è solo eventi.**

Le collettive fanno continuamente:
- Inchieste urbane (Off Topic)
- Escursioni e lotte territoriali (APE Milano)
- Analisi femministe (Ambrosia)
- Hacktivism e tech workshops (A-K-M-E)
- Solidarietà internazionale (Rete Jin)
- Cinema critico e rassegne (CineSenzaForum)
- Improvvisazione musicale (Conserere)
- Lotte per diritti lavoratori (San Precario, Deliverance)

**Ma sul sito vediamo SOLO eventi al PT.**

Il resto — il lavoro quotidiano, le pubblicazioni, le analisi, i report — dove sta?

Sui blog delle singole collettive, invisibili al resto della comunità e a chi cerca PT online.

---




## IL CONCEPT: DUE MURI

### 1. WALL SPACETIME — Archeologia del Passato

> *"Il muro come archeologia del presente.  
> Non timeline lineare ma stratificazione esplorabile.  
> Il tempo non si legge, si attraversa."*

**Cosa è:**
Traduzione digitale del muro fisico dello spazio — ricoperto di sticker, locandine, manifesti accumulati in 13 anni — in interfaccia interattiva navigabile.

**Come funziona:**
- Navigazione orizzontale temporale: 2012 → oggi
- Filtri per categoria: collettive, eventi, campagne, satelliti
- Immagini che **respirano** (pulsano dolcemente, sfalsate)
- Zoom immersivo su click
- Satelliti fluttuanti (realtà impermanenti)
- Densità verticale = intensità periodo (2013: 161 eventi = denso; 2020: 49 eventi = rarefatto)
- Palette: colori Palestina (nero, rosso, verde, bianco)

**Filosofia:**
- Lo spazio autogestito è **vivo**, non museo
- Le lotte non sono passato, sono **presente che pulsa**
- Il respiro è dichiarazione politica
- La memoria è stratificata, non lineare

**Mockup funzionante:**
https://yuricrea.github.io/wall-pt/wall_spacetime_v5.html

NB: sono stati caricati circa 30 eventi+locandine+collettive su 1100. 
il Wall spacetime è molto più stratificato e denso di ciò che vedi, 
pensa stratificato, cospira nel tempo, respira nello spazio, ispira il presente.

---

### 2. WALL COLLETTIVE — Il Respiro del Presente

> *"Il muro vivo. Feed aggregato che mostra chi pubblica, chi è attivo,  
> chi è in stand-by. Effimero, impermanente, fluido."*

**Cosa è:**
Aggregatore automatico di feed RSS e social delle collettive che mostra il ritmo di vita dello spazio **in tempo reale**.

**Come funziona:**

#### Input automatici:
- Feed blog: Off Topic, APE Milano, Ambrosia, A-K-M-E, Rete Jin, GAS Maltrainsema, SuSaMi...
- Canali social: Telegram, Mastodon, Instagram
- Ogni nuova pubblicazione appare automaticamente sul muro














#### Visualizzazione:
```
╔═══════════════════════════════════════════╗
║  WALL COLLETTIVE - IL RESPIRO PRESENTE    ║
╠═══════════════════════════════════════════╣
║                                           ║
║  [OffTopic]  [OffTopic]  [AKME]         ║
║    ████████  ████████    ████            ║ ← Molto attivi
║                                           ║
║  [APE]     [Ambrosia]                    ║
║    ████       ██                          ║ ← Mediamente attivi
║                                           ║
║  [GAS Maltrainsema]                      ║
║    ░                                      ║ ← Poco attivi/stand-by
║                                           ║
╚═══════════════════════════════════════════╝
```

#### Logica:
- Chi pubblica molto = **denso** (tanti elementi sovrapposti, colori saturi)
- Chi pubblica poco = **rarefatto** (pochi elementi sparsi)
- Chi non pubblica da tempo = **trasparente/grigio** (stand-by visibile)
- Dopo 30-60 giorni = **scompare** (è flusso presente, non archivio permanente)

#### Cosa rivela:

**NON è solo aggregatore RSS.**  
**È STRUMENTO DI COSCIENZA COLLETTIVA:**

- Rende visibile chi è attivo/in stand-by
- Mostra il ritmo di ogni collettiva
- Evidenzia periodi intensi (molte pubblicazioni simultanee)
- Segnala silenzi prolungati (nessuna attività)
- Crea pressione sociale positiva: "Il muro è vuoto? Pubblichiamo qualcosa!"
- Fa emergere intersezioni: due collettive lavorano sullo stesso tema? Il muro lo mostra

**Filosofia:**
- Stratificazione di feed che si aggiornano in tempo reale
- Effimero e impermanente (come la vita dello spazio)
- Tutto è fluido, cambia, respira

---





















## SOLUZIONI PROPOSTE

### 1. RESTYLING SITO

#### Homepage: Manifesto + Due Muri
```
┌─────────────────────────────────────────┐
│  HEADER: Logo PT + Menu + Free Palestine│
├─────────────────────────────────────────┤
│  MANIFESTO: Chi siamo (2-3 paragrafi)  │
│  Antifascista, anticapitalista,         │
│  autogestito dal 2012                   │
├─────────────────────────────────────────┤
│  TAB 1: WALL SPACETIME                 │
│  [2012 → Oggi] Archeologia passato     │
│  → Navigazione orizzontale temporale   │
├─────────────────────────────────────────┤
│  TAB 2: WALL COLLETTIVE                │
│  [Adesso] Il respiro del presente      │
│  → Feed aggregato RSS/social           │
├─────────────────────────────────────────┤
│  FOOTER: Link collettive + social +    │
│          Puntello + contatti            │
└─────────────────────────────────────────┘
```

#### Quick wins:
- [ ] Accorpare "chi siamo" + "dove siamo" (due pagine vuote → una completa)
- [ ] Aggiornare pagina collettive (link, contatti, descrizioni brevi)
- [ ] Logo + mail nel menu
- [ ] Togliere link Nebbia (non più attivo)
- [ ] Calendario: aggiungere "Ci trovi anche su Puntello"

---

### 2. SISTEMA TAG INTELLIGENTE

#### Problema attuale:
- Tag usati in modo inconsistente
- Ogni collettiva tagga a modo suo
- Impossibile cercare per tema trasversale (es. "tutti gli eventi su Palestina")
- Difficile per automazione social (Mastodon/IG usano hashtag)

#### Soluzione: Tassonomia Stratificata

**LIVELLO 1 — CATEGORIA BASE (obbligatoria)**
- `collettiva`: Off Topic Lab, A-K-M-E, Ambrosia, APE Milano, Rete Jin, San Precario, CineSenzaForum, Conserere, Deliverance, GAS Maltrainsema, SuSaMi, Burlexotan
- `evento`: presentazione, dibattito, proiezione, concerto, festa, assemblea
- `campagna`: NoExpo, NoOlimpiadi, Free Palestine, Kurdistan
- `satellite`: yoga, teatro, palestra popolare, jam session, assemblee temporanee

**LIVELLO 2 — TEMA (opzionale, multiplo)**
- `lavoro`: precariato, riders, sfruttamento, sindacato, diritti
- `territorio`: diritto alla città, urbanistica, grandi opere, gentrificazione
- `genere`: femminismo, queer, patriarcato, violenza di genere, LGBTQIA+
- `internazionale`: Palestina, Kurdistan, migrazioni, solidarietà internazionale
- `cultura`: cinema, musica, arte, letteratura, fumetti
- `tech`: hacktivism, privacy, sorveglianza, autodeterminazione digitale
- `ecologia`: ambiente, climate crisis, decrescita
- `altro`: tutto ciò che non rientra sopra

**LIVELLO 3 — HASHTAG LIBERI (opzionale)**
```
#gaza #apartheid #riders #gentrificazione #freePalestine 
#jinJiyanAzadi #noexpo #noolimpiadi #antifa #anticap
```

#### Automazione tag:

**Plugin WordPress suggerisce automaticamente:**
- Evento con "Gaza" nel titolo → auto-suggerisce `#palestina` + tema `internazionale`
- Organizzatore è A-K-M-E → auto-tag `collettiva: AKME`
- Tipo evento "presentazione libro" → auto-tag `evento: presentazione` + `cultura`
- Contenuto parla di "riders" → auto-suggerisce tema `lavoro` + `#riders`

**Benefici:**
- Ricerca trasversale funziona
- Integrazione social nativa (Mastodon/IG usano hashtag)
- Meno lavoro manuale (suggerimenti intelligenti)
- Coerenza aumenta nel tempo

---

### 3. AUTOMAZIONE SOCIAL — "Pubblica una volta, propaga ovunque"

#### Il problema:
> "Bisogna imparare Zapier/IFTTT"

#### La soluzione: Setup Iniziale + Manutenzione Zero

**FASE 1: Hacknight Setup (una volta sola, 4-6 ore)**
- nerd + appassionati + A-K-M-E + chi vuole partecipare
- Config tutto in UNA sessione
- Documentare passo-passo live ? (guide + screenshot)

**FASE 2: Funziona da Solo (per sempre)**
- Workflow automatico gira in background
- Chi pubblica su WordPress **non deve sapere nulla**
- Se qualcosa si rompe → guida troubleshooting

#### Architettura:

```
        ┌─────────────────────────────────────┐
        │  WORDPRESS (fonte unica)            │
        │  Evento/Post con immagine + tag     │
        └───────────────┬─────────────────────┘
                        │
                        ▼
              ┌───────────────────────┐
              │   AUTOMAZIONE         │
              │ (IFTTT o n8n o zapier)│
              └────────┬──────────────┘
                       │
        ┌──────────────┼──────────────┬──────────────┐
        ▼              ▼              ▼              ▼
   ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐
   │Telegram │   │Mastodon │   │Instagram│   │Puntello │
   │ Canale  │   │         │   │(+ FB)   │   │  (?)    │
   └─────────┘   └─────────┘   └─────────┘   └─────────┘
```


**Risultato:**
1. Pubblichi evento su WordPress
2. Premi "Pubblica"
3. Automaticamente appare su: Telegram, Mastodon, Instagram, Facebook, Puntello (se integrabile)

**Chi pubblica non deve fare altro.**

#### Tool Consigliati (scala difficoltà)

**LIVELLO 1 — Facilissimo (Telegram)**
- **RSS Bot Telegram** (@RobotRSS_bot)
- Setup: 5 minuti, zero codice
- Costo: free
- Limiti: solo Telegram

**LIVELLO 2 — Facile (Mastodon)**
- **Plugin WP "Mastodon Autopost"**
- Setup: 10 minuti, interfaccia WordPress
- Costo: free
- Limiti: solo Mastodon

**LIVELLO 3 — Medio (Multi-piattaforma)**
- **IFTTT** (If This Then That)
- Setup: 30 min per piattaforma, interfaccia visuale
- Costo: €3-5/mese per illimitato (free: 2 applet)
- Pro: no codice, manutenibile da chiunque

**LIVELLO 4 — Avanzato (Self-hosted, etico)**
- **n8n** (open source, self-hosted)
- Setup: A-K-M-E lo installa su loro server
- Costo: €0 (solo server, che A-K-M-E ha già)
- Pro: controllo totale, etico, illimitato
- Contro: richiede conoscenza base server

#### Strategia Consigliata:

**START SIMPLE:**
1. **Ora (5 min):** RSS Bot Telegram → funziona subito
2. **Hacknight (2 ore):** Mastodon plugin + IFTTT base
3. **Dopo 3 mesi:** Se funziona, A-K-M-E migra tutto su n8n (controllo totale)

---

### 4. MANIFESTO FISICO SPAZIO

**Cosa:** Poster A3/A2 da affiggere all'ingresso e nel sottoterra

**Contenuto:**
- **Cos'è Piano Terra:** Centro sociale autogestito, occupato 2012, 15+ collettive
- **Valori:** Antifascista, anticapitalista, solidarietà internazionale, femminista, queer-friendly
- **Pratiche:** Autogestione, assemblea, mutualismo, cultura critica
- **Cosa NON è:** Non un locale della movida, non un bar, non uno spazio neutro
- **Cura e responsabilità:** Come comportarsi, safer space, consent

**Ispirazione:** Progetto Criss Cross (Serpica) — rigenerazione spazi  
Link: https://crisscrossproject.org/it/

**Motivazione:**  
Il quartiere Isola è molto cambiato. PT viene spesso scambiato per locale movida.  
Un manifesto visivo aiuta a comunicare identità immediatamente.

**Design:**  
- Palette Palestina (nero, rosso, verde, bianco)
- Font: Space Mono + Archivo Black
- Estetica: grunge, stratificata, non patinata
- Multilingue? IT + EN almeno

---

## MOCKUP FUNZIONANTI

### Wall SpaceTime v5
**URL:** https://yuricrea.github.io/wall-pt/wall_spacetime_v5.html

**Caratteristiche implementate:**
- ✅ Navigazione orizzontale temporale (2012 → 2025)
- ✅ Respiro animato 6-10% randomizzato
- ✅ Filtri categoria (collettive, eventi, campagne, satelliti)
- ✅ Satelliti con animazione fluttuante
- ✅ Zoom immersivo su click
- ✅ Timeline sincronizzata
- ✅ Anni chiave evidenziati (2012, 2015, 2020, 2025)
- ✅ Free Palestine banner stile Autistici
- ✅ Responsive base

**Dati:**
- 40+ elementi mappati
- 1110 eventi nel database calendario
- 15+ collettive identificate
- 13 anni storia (2012-2025)

---

### Timeline v2
**URL:** https://yuricrea.github.io/wall-pt/timeline_v2.html

**Caratteristiche:**
- ✅ Timeline verticale classica (zigzag sinistra/destra)
- ✅ Linea centrale gradient colori Palestina
- ✅ Eventi respirano individualmente
- ✅ Year markers con freccia rossa
- ✅ Tags per categoria
- ✅ Noise texture overlay (grunge effect)
- ✅ Mobile responsive

**Quando usarla:**
- **Wall SpaceTime** = esplorazione libera, immersione, densità visiva
- **Timeline v2** = lettura cronologica, dettagli, testo più leggibile

**Sono due lati della stessa medaglia.**

---

## ROADMAP

### FASE 1 — Discussione Collettiva (ora)

**Obiettivo:** Raccogliere feedback, critiche, idee

**Azioni:**
- [ ] Provare mockup (desktop + mobile)
- [ ] Leggere questo documento
- [ ] Dare feedback specifico:
  - Wall SpaceTime: vi piace? troppo complesso? manca qualcosa?
  - Wall Collettive: concept utile? fattibile? come modificarlo?
  - Automazione: quali piattaforme prioritarie? chi può aiutare setup?
  - Tag: sistema proposto sensato? altre idee?
- [ ] Discussione in assemblea PT? Quando?

**Domande aperte:**
- Chi è interessato a partecipare a hacknight implementazione?
- Quali collettive vogliono autonomia pubblicazione su WP?
- Restiamo su Meta (IG/FB) o migriamo completamente?
- Come gestiamo manutenzione nel tempo?

---

### FASE 2 — Setup Base (dopo feedback, 1-2 settimane)

**Obiettivo:** Quick wins + automazione base

**Azioni:**
- [ ] Fix quick sito:
  - Logo + mail nel menu
  - Togliere link Nebbia
  - Accorpare "chi siamo" + "dove siamo"
  - Aggiornare pagina collettive
  - Aggiungere "Ci trovi anche su Puntello" in calendario
- [ ] Setup automazione Telegram (5 min, RSS Bot)
- [ ] Setup plugin Mastodon autopost (10 min)
- [ ] Iniziare test tag system (manuale, poi automatizzare)

**Output:** Sito più pulito + automazione base funzionante

---

### FASE 3 — Implementazione Completa (quando vogliamo, 1 giorno hacknight)

**Obiettivo:** Integrare Wall SpaceTime + Wall Collettive + automazione full

**Formato:** Hacknight (sabato o domenica, 10:00-18:00, PT o da remoto)

---

### FASE 4 — Lancio (dopo hacknight, 1 settimana)

**Obiettivo:** Deploy pubblico + comunicazione

**Azioni:**
- [ ] Deploy finale su pianoterralab.org
- [ ] Post lancio su tutti canali (Telegram, Mastodon, IG, FB, Puntello)
- [ ] Comunicazione esterna (mail collettivi amici, reti territoriali)
- [ ] Formazione base per collettive:
  - Come pubblicare evento con tag corretti
  - Come verificare che automazione funziona
  - Dove trovare guide se qualcosa non va

**Output:**
- Sito nuovo online
- Comunicazione diffusa
- Collettive autonome nella pubblicazione

---

## RISORSE DISPONIBILI

### Repository GitHub
**URL:** https://github.com/yuricrea/wall-pt

**Contiene:**
- Manifesto completo (filosofia + specifiche tecniche)
- Analisi calendario 1110 eventi (2012-2025)
- Codice sorgente mockup v5 e timeline v2
- Proposte automazione social
- Roadmap implementazione
- 56 immagini (loghi, locandine, sticker)

**Contributi benvenuti:**
- Fork repository
- Pull request con miglioramenti
- Issue per segnalare bug o proporre feature
- Open source, copyleft

---

### Siti Collettive PT
- Piano Terra: https://www.pianoterralab.org/
- Off Topic Lab: https://www.offtopiclab.org/
- A-K-M-E: https://akme.vado.li
- APE Milano: https://ape-alveare.it/ape-milano/
- Ambrosia: https://ambrosia.noblogs.org/
- Rete Jin: https://retejin.com/
- GAS Maltrainsema: https://maltrainsema.noblogs.org/
- SuSaMi: https://susami.noblogs.org/

### Tool Automazione
- IFTTT: https://ifttt.com (più semplice)
- n8n: https://n8n.io (self-hosted, etico)
- Zapier: https://zapier.com (alternativa IFTTT)
- Make: https://make.com (ex-Integromat, intermedio)

---

## FILOSOFIA E VALORI

### Archeologia Stratificata del Presente

> *"Il muro come archeologia del presente.  
> Non timeline lineare ma stratificazione esplorabile.  
> Il tempo non si legge, si attraversa."*

Questo non è "un sito figo". È **dichiarazione politica**:
- Lo spazio autogestito è vivo, non museo
- Le lotte non sono passato, sono presente che pulsa
- La memoria è stratificata, non gerarchica
- Il respiro è vita, cospirazione nel senso originale: respirare insieme

### Esclusività Concettuale

Il codice è open source, replicabile.  
Il concept no.

La differenza tra "un sito cool" e "un'opera di memoria collettiva militante" sta in:
- Cura
- Conoscenza della storia
- Rispetto delle stratificazioni
- Relazione con le persone che abitano lo spazio

**Questo non si copia con un fork su GitHub.**

### Il Respiro Come Resistenza

Le immagini sul Wall respirano — pulsano dolcemente, sfalsate, organiche.

Non è decorazione. È **metafora politica**:
- Spazi autogestiti **respirano** (vivono, cospirano)
- Occupazioni **respirano** (resistono, persistono)
- Collettive **respirano** (lavorano, pubblicano, si fermano, ripartono)

Il respiro è vita. Il respiro è resistenza. Il respiro è sumud.

---

## NOTA CRUCIALE: CURIOSITÀ E RESPONSABILITÀ
Questo progetto richiede:
- Curiosità (cliccare, esplorare, capire)
- Autodeterminazione (imparare, provare, sbagliare)
- Responsabilità collettiva (non delegare sempre alle stesse persone)

**L'autogestione non è solo assemblee.**  
**È capacità di prendersi cura degli strumenti (beni) comuni.**

Chi pubblica eventi deve saper usare WordPress.  
Chi vuole visibilità deve contribuire a comunicazione.  
Chi critica deve proporre alternative.

**Pigrizia digitale è comprensibile.**  
**Mancanza di curiosità è problema politico.**

Usare GitHub come contenitore di questo progetto è scelta **pedagogica**:
- Chi è curioso clicca, legge, impara
- Chi contribuisce usa strumenti collaborativi (fork, pull request, issue)
- Chi non è interessato resta fuori (e va bene così)

**Non tutto è per tutti.**  
**Ma tutto è accessibile a chi vuole accedere.**

---

## COME CONTRIBUIRE

### Se sei collettiva PT:
1. **Prova i mockup** (desktop + mobile)
2. **Dai feedback specifico** (cosa funziona, cosa no, cosa manca)
3. **Partecipa a hacknight** (implementazione collaborativa)
4. **Impara a pubblicare** con tag corretti (formazione post-lancio)
5. **Alimenta Wall Collettive** con le tue pubblicazioni (blog, social)

### Se sei nerd/hacker/designer:
1. **Fork repository** su GitHub
2. **Migliora codice** (pull request benvenute)
3. **Segnala bug** (apri issue)
4. **Proponi feature** (discussion su GitHub)
5. **Partecipa a hacknight** (mani in pasta)

### Se sei curioso/a:
1. **Leggi questo documento**
2. **Esplora mockup**
3. **Condividi con chi potrebbe essere interessato**
4. **Vieni a hacknight** anche solo per imparare

---



## CONTATTI

**Yuri Crea**
- GitHub: https://github.com/yuricrea/wall-pt
- Email: [via Piano Terra mailing list]

**Piano Terra Lab**
- Sito: https://www.pianoterralab.org/
- Indirizzo: Via Confalonieri 3, Milano (Isola)
- Mailing list: lista@pianoterralab.org

---

## CREDITI

**Concept & Design:** Yuri Crea  
**Sviluppo Collaborativo:** Yuri Crea + Claude code


**Sviluppato dalla postazione 36 del Pio Albergo Trivulzio.**  
**Lo scarrafone resiste anche alle radiazioni.** ⚡🪳

---

## APPENDICE: CITAZIONI

> "C'è chi gratta il cielo e chi all'Isola sta al Piano Terra!"

> "Il muro come archeologia del presente. Non timeline lineare ma stratificazione esplorabile. Il tempo non si legge, si attraversa."

> "Le immagini respirano — come il cuore pulsante di uno spazio che vive e cospira."

> "La mancanza di curiosità è deriva verso l'ignoranza e l'oblio delle capacità critiche del presente e del passato, strumenti per comprendere e intercettare flussi spaziotemporali nel futuro senza certezze del mondo di mezzo."

---

*Documento vivo - ultima modifica: 12 dicembre 2024*  
*Repository: https://github.com/yuricrea/wall-pt*  
*License: Copyleft - Fai quello che vuoi, ma cita la fonte*

✊🪳🍉
