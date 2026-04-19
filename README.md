# Profesní web na GitHub Pages (hotový základ)

Tahle šablona je jednoduchý moderní one‑page profesní web (HTML/CSS/JS), ideální pro GitHub Pages.

## 1) Rychlé nasazení na GitHub Pages

### Varianta A – „user site“ (doporučeno)
1. Na GitHubu vytvoř nový repozitář pojmenovaný přesně `TVOJE_UZIVATELSKE_JMENO.github.io`.
2. Nahraj do něj obsah této složky (soubor `index.html` a složku `assets/`).
3. V repozitáři otevři **Settings → Pages**.
4. V části **Build and deployment** zvol **Deploy from a branch**, potom vyber branch `main` a potvrď uložením.

GitHub Pages hledá jako vstupní soubor `index.html` (nebo `index.md` / `README.md`).

### Varianta B – „project site“
- Repozitář může mít libovolné jméno a web poběží na `https://TVOJE_UZIVATELSKE_JMENO.github.io/nazev-repa/`.

## 2) Úpravy obsahu
- Texty a sekce upravíš v `index.html`.
- Barvy, layout a responzivitu upravíš v `assets/style.css`.
- Chování (přepínač motivu, rok ve footeru) je v `assets/main.js`.

## 3) Kontakt / formulář
GitHub Pages je statický hosting (bez backendu). Doporučení:
- Nejjednodušší: použij `mailto:` odkaz.
- Alternativa: externí služba formuláře (Formspree apod.).

---

Vytvořeno jako „starter“ pro GitHub Pages.
