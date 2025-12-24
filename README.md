# vrhovni-zalba

Repo sadrži nacrt podneska (prijedlog za dopuštenje revizije) te prateće AI analize, prijedloge dorada i evaluacije.

## Sadržaj repo-a

- **`revizija-samo-text.txt`**: izvorni tekst podneska (prijedlog za dopuštenje revizije) u “plain text” formatu.
- **`ocjena-gpt_5_2.md`**: ocjena i usporedba dokumenata iz `analiza-3/` (evaluator: GPT‑5.2).

### `analiza-1/` — uredničko‑pravne analize izvornog podneska (po modelima)

- **`analiza-1/analiza_revizije_1_gpt_5.md`**: uredničko‑pravna analiza strukture/kvalitete podneska + preporuke za doradu (GPT).
- **`analiza-1/analiza_revizije_1_gemini.md`**: ista vrsta analize (Gemini).
- **`analiza-1/analiza_revizije_1_sonnet.md`**: ista vrsta analize (Sonnet).
- **`analiza-1/*.pages`**: Apple Pages izvozi/varijante navedenih analiza.

### `analiza-2/` — reference + ton/stil (meta-analize)

- **`analiza-2/analiza_referenci_gpt_5_2.md`**: analiza referenci navedenih u `revizija-samo-text.txt` (što je citirano i koliko je provjerljivo/dostupno) — GPT‑5.2.
- **`analiza-2/analiza_referenci_gemini.md`**: analiza referenci — Gemini.
- **`analiza-2/analiza-referenci_claude-opus-4.md`**: analiza referenci — Claude Opus 4.
- **`analiza-2/emocionalni-tonovi-i-karakterizacije.md`**: izdvojene rečenice/odlomci iz izvornika s emocionalnim tonom i karakterizacijama (uz reference na linije).
- **`analiza-2/tipfeleri-i-jezicne-nedosljednosti_emocionalni-tonovi-i-karakterizacije.md`**: popis tipfelera i jezičnih nedosljednosti u prethodnom dokumentu (bez izmjene izvornika).

### `analiza-3/` — novi nacrti podneska + evaluacije

- **`analiza-3/novi-prijedlog-gpt_5_2.md`**: novi, restrukturirani nacrt prijedloga (GPT‑5.2).
- **`analiza-3/novi-prijedlog-opus.md`**: novi nacrt prijedloga (Opus).
- **`analiza-3/novi-prijedlog-gemini.md`**: novi nacrt prijedloga (Gemini).
- **`analiza-3/ocjena-sonnet.md`**: evaluacija triju varijanti iz `analiza-3/` (evaluator: Claude Sonnet 4.5).
- **`analiza-3/ocjena-gemini-3-pro-preview.md`**: evaluacija triju varijanti iz `analiza-3/` (evaluator: Gemini 3 Pro Preview).

## Konverzija

- **`.md` → `.docx`**: `https://cloudconvert.com/md-to-docx`
