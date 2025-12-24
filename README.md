# vrhovni-zalba

Repo sadrži nacrt podneska (prijedlog za dopuštenje revizije) te prateće AI analize, prijedloge dorada i evaluacije.

📁 **GitHub Repository:** [github.com/abarisic86/vrhovni-sud-revizija](https://github.com/abarisic86/vrhovni-sud-revizija)

## Sadržaj repo-a

### Osnovni dokumenti

- **[`revizija-samo-text.txt`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/revizija-samo-text.txt)**: izvorni tekst podneska (prijedlog za dopuštenje revizije) u "plain text" formatu.
- **[`novi-prijedlog-opus.docx`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/novi-prijedlog-opus.docx)**: Word verzija dorađenog prijedloga (Opus).

### Dodatne pravne analize

- **[`dodatni-izvori-pravna-praksa.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/dodatni-izvori-pravna-praksa.md)**: detaljna analiza dodatnih web izvora i sudske prakse ESLJP-a, VSRH i USUD-a relevantnih za predmet (70+ stranica).
- **[`sazetak-dodatnih-izvora.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/sazetak-dodatnih-izvora.md)**: sažetak ključnih nalaza iz web analize sa preporukama za daljnje korake.

### [`analiza-1/`](https://github.com/abarisic86/vrhovni-sud-revizija/tree/main/analiza-1) — uredničko‑pravne analize izvornog podneska (po modelima)

- **[`analiza_revizije_1_gpt_5.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-1/analiza_revizije_1_gpt_5.md)**: uredničko‑pravna analiza strukture/kvalitete podneska + preporuke za doradu (GPT).
- **[`analiza_revizije_1_gemini.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-1/analiza_revizije_1_gemini.md)**: ista vrsta analize (Gemini).
- **[`analiza_revizije_1_sonnet.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-1/analiza_revizije_1_sonnet.md)**: ista vrsta analize (Sonnet).
- **`*.pages`**: Apple Pages izvozi/varijante navedenih analiza.

### [`analiza-2/`](https://github.com/abarisic86/vrhovni-sud-revizija/tree/main/analiza-2) — reference + ton/stil (meta-analize)

- **[`analiza_referenci_gpt_5_2.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-2/analiza_referenci_gpt_5_2.md)**: analiza referenci navedenih u `revizija-samo-text.txt` (što je citirano i koliko je provjerljivo/dostupno) — GPT‑5.2.
- **[`analiza_referenci_gemini.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-2/analiza_referenci_gemini.md)**: analiza referenci — Gemini.
- **[`analiza-referenci_claude-opus-4.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-2/analiza-referenci_claude-opus-4.md)**: analiza referenci — Claude Opus 4.
- **[`emocionalni-tonovi-i-karakterizacije.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-2/emocionalni-tonovi-i-karakterizacije.md)**: izdvojene rečenice/odlomci iz izvornika s emocionalnim tonom i karakterizacijama (uz reference na linije).
- **[`tipfeleri-i-jezicne-nedosljednosti_emocionalni-tonovi-i-karakterizacije.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-2/tipfeleri-i-jezicne-nedosljednosti_emocionalni-tonovi-i-karakterizacije.md)**: popis tipfelera i jezičnih nedosljednosti u prethodnom dokumentu (bez izmjene izvornika).

### [`analiza-3/`](https://github.com/abarisic86/vrhovni-sud-revizija/tree/main/analiza-3) — novi nacrti podneska + evaluacije

- **[`novi-prijedlog-gpt_5_2.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-3/novi-prijedlog-gpt_5_2.md)**: novi, restrukturirani nacrt prijedloga (GPT‑5.2).
- **[`novi-prijedlog-opus.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-3/novi-prijedlog-opus.md)**: novi nacrt prijedloga (Opus).
- **[`novi-prijedlog-gemini.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-3/novi-prijedlog-gemini.md)**: novi nacrt prijedloga (Gemini).
- **[`ocjena-sonnet.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-3/ocjena-sonnet.md)**: evaluacija triju varijanti iz `analiza-3/` (evaluator: Claude Sonnet 4.5).
- **[`ocjena-gpt_5_2.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-3/ocjena-gpt_5_2.md)**: evaluacija triju varijanti (evaluator: GPT‑5.2).
- **[`ocjena-gemini-3-pro-preview.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/analiza-3/ocjena-gemini-3-pro-preview.md)**: evaluacija triju varijanti (evaluator: Gemini 3 Pro Preview).

## Korisni alati i reference

### Konverzija dokumenata

- **`.md` → `.docx`**: [cloudconvert.com/md-to-docx](https://cloudconvert.com/md-to-docx)

### Pravne baze (iz dodatnih analiza)

- **HUDOC baza ESLJP-a**: [hudoc.echr.coe.int](https://hudoc.echr.coe.int) - pretraživanje presuda Europskog suda za ljudska prava
- **IUS-INFO**: [iusinfo.hr](https://www.iusinfo.hr) - hrvatska pravna baza s odlukama VSRH i USUD-a (pretplatnička usluga)
- **Ured zastupnika RH pred ESLJP-om**: [uredzastupnika.gov.hr](https://uredzastupnika.gov.hr)

### Ključne presude ESLJP-a (iz analize)

Detaljne informacije o sljedećim presudama dostupne su u [`dodatni-izvori-pravna-praksa.md`](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/dodatni-izvori-pravna-praksa.md):

- **Elsholz v. Germany** (2000) - obveza provođenja vještačenja
- **Sommerfeld v. Germany** (2003) - odbijanje stručnih preporuka
- **Sahin v. Germany** (2003) - kašnjenje u obiteljskim predmetima
- **Hokkanen v. Finland** (1994) - provedba odluka o kontaktu
- **Zawadka v. Poland** (2005) - otpor roditelja
- **Bochan v. Ukraine** (2007) - arbitrarnost u odlučivanju

---

**Napomena:** Za kompletnu analizu dodatnih pravnih izvora pogledajte:
- 📄 [Detaljna analiza (70+ str)](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/dodatni-izvori-pravna-praksa.md)
- 📋 [Sažetak i preporuke](https://github.com/abarisic86/vrhovni-sud-revizija/blob/main/sazetak-dodatnih-izvora.md)
