# Min Budget 💰

En personlig budget-PWA byggd för iPhone. Sparas som webb-app på hemskärmen och fungerar offline.

## Funktioner

- **Budget** — sätt månadsbudget per kategori
- **Logg** — logga faktisk spending per månad, navigera bakåt i tiden
- **Analys** — budget vs. snitt, differens per kategori
- All data lagras lokalt på enheten (localStorage)
- Auto-rensar data äldre än 12 månader

## Installation (iPhone)

1. Öppna URL:en i **Safari**
2. Tryck dela-ikonen → *Lägg till på hemskärmen*

## Deploy med GitHub Pages

1. Skapa ett nytt repo på GitHub
2. Kör följande kommandon i denna mapp:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/DITT-ANVÄNDARNAMN/DITT-REPO.git
git push -u origin main
```

3. Gå till repo → Settings → Pages → Source: `main` / `/ (root)`
4. Din app finns på `https://DITT-ANVÄNDARNAMN.github.io/DITT-REPO/`

## Uppdatera appen

```bash
git add .
git commit -m "Beskrivning av ändringen"
git push
```

GitHub Pages uppdateras automatiskt inom någon minut.

## Versioner

- **v1.0** — Budget + Logg + Analys, PWA-stöd
- **v2.0** — Planerad (se nedan)

## v2.0 — Planerade ändringar

1. Logg: Visa bara kategorier som varierar (ta bort fasta som hyra, CSN, sparande)
2. Transport: Utökas med parkering och böter/avgifter
3. Ny logg-only-kategori: Oförutsedda utgifter
