# Andra världskriget – studieplanscher & instuderingsfrågor

En liten studiesajt (en enda `index.html`) inför historieprovet i åk 8. Den visar sju planscher med fråga och svar: tidslinje, aktörerna, fyra fördjupningar (Pearl Harbor, Stalingrad, Dagen D, atombomberna) och krigets följder.

## Innehåll i mappen

```
andra-varldskriget/
├── index.html        ← själva sidan (öppna i webbläsare)
├── prompter.md       ← alla 7 FigureLabs-prompter
├── README.md         ← den här filen
└── bilder/           ← de 7 planscherna
    ├── 01-tidslinje.png
    ├── 02-aktorer.png
    ├── 03-pearl-harbor.png
    ├── 04-stalingrad.png
    ├── 05-d-dagen.png
    ├── 06-atombomberna.png
    └── 07-foljder.png
```

## Titta på sidan lokalt

Dubbelklicka på `index.html` — den öppnas i din webbläsare. Vill du byta ut en plansch, spara bara en ny bild med samma filnamn i `bilder/`.

## Publicera på GitHub Pages

### Alternativ A – via webben (enklast, inget program behövs)

1. Gå till github.com och logga in. Klicka **New** för att skapa ett nytt repository, t.ex. `andra-varldskriget`. Välj **Public**.
2. På repo-sidan: klicka **Add file → Upload files**.
3. Dra in **hela innehållet** i den här mappen (både `index.html` och mappen `bilder/`). Klicka **Commit changes**.
4. Gå till **Settings → Pages**.
5. Under **Build and deployment → Source** välj **Deploy from a branch**, välj branch **main** och mapp **/ (root)**. Klicka **Save**.
6. Vänta någon minut. Adressen blir:
   `https://DITT-ANVÄNDARNAMN.github.io/andra-varldskriget/`

### Alternativ B – via git (om du har Git installerat)

```bash
cd andra-varldskriget
git init
git add .
git commit -m "Studiesajt: andra världskriget"
git branch -M main
git remote add origin https://github.com/DITT-ANVÄNDARNAMN/andra-varldskriget.git
git push -u origin main
```

Slå sedan på Pages enligt steg 4–6 ovan.

## Tips

- Sidan är gjord för att fungera lika bra på mobil som utskriven (Ctrl/Cmd + P).
- Varje avsnitt har en hopfällbar ruta längst ner med FigureLabs-prompten, om du vill göra om en plansch.
