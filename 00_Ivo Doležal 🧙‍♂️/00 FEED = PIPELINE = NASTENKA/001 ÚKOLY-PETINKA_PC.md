
- [ ] 1. V OBSIDIANU [[PRÁCE S DATAVIEW]]
- [ ] 2. 
- [x] Pokračování v chatugpt . (ADHD Work Plan) ## 4. **Sjednocení v Microsoft To Do a OneDrive**

# Roadmapa na základě dnešní diskuze

## 1. Organizace v Obsidianu
- [x] **Zkontrolovat strukturu P.A.R.A.**
  - 00 Já: Nástěnka, collector, přehled.
  - 10 Projekty: Lean Mobilo, kurz Python, kurz SQL.
  - 20 Oblasti: Práce, osobní rozvoj, učení.
  - 30 Zdroje: Poznámky, návody, nápady.
  - 40 Archiv: Dokončené věci.

- [x] **Přidat odkazy mezi poznámkami**
  - Na konec poznámek přidat sekci **Související poznámky**.
  - Používat `[[Název poznámky]]` pro propojení.
  -     ---
    Datum vytvoření: 2025-01-19
    ---

- [x] **Začít používat denní poznámky**
  - [[Šablona Daily pages]]:
    ```markdown
    # Deník – {{date}}
    ## Úkoly
    - [ ] 
    ## Co jsem udělal
    - 
    ## Reflexe
    - 
    ## Nápady
    - 
    ```

- [ ] **Vkládání dat do poznámek**
  - Přidat datum vytvoření do poznámek jako metadata:
    ```markdown
    ---
    Datum vytvoření: 2025-01-19
    ---
    ```
  - Používat tagy `#2025`, `#leden2025` pro rychlé filtrování.

---

## 2. Pluginy v Obsidianu
- [ ] **Nastavit plugin Dataview**
  - Zobrazit seznam úkolů:
    ```dataview
    table file.name as "Poznámka", text as "Úkol"
    from "folder_name"
    where !completed
    sort file.name
    ```
  - Zobrazit poznámky podle tagu:
    ```dataview
    list from #tag
    sort file.name
    ```

- [ ] **Nastavit plugin Calendar**
  - Přidat denní poznámky přes kalendář.
  - Vyzkoušet propojení s šablonami (viz výše).
table file.name as "Poznámka", text as "Úkol"
    from "folder_name"
    where !completed
    sort file.name

---

## 3. Git a GitHub
- [ ] **Nainstalovat Git a Git Bash**
  - Stáhnout z [https://git-scm.com/](https://git-scm.com/).

- [ ] **Nastavit repozitář na GitHubu**
  - Vytvořit nový repozitář (např. `ObsidianVault`).
  - Připojit repozitář k Vaultu:
    ```bash
    cd cesta/k/Vaultu
    git init
    git remote add origin https://github.com/tvoje-jméno/ObsidianVault.git
    ```

- [ ] **První synchronizace Vaultu**
  - Přidat a nahrát soubory:
    ```bash
    git add .
    git commit -m "První záloha Vaultu"
    git push -u origin main
    ```

---

## 4. Lean Mobilo projekt
- [ ] **Dokončit mapování procesů**
  - Vytvořit mapu hodnotového toku.
  - Identifikovat úzká místa v procesech.

- [ ] **Připravit standardizaci**
  - Vytvořit SOP pro knihy jízd.
  - Vytvořit SOP pro servisní záznamy.

- [ ] **Připravit se na meeting**
  - Shrnutí aktuálního stavu projektu.
  - Prezentace pro vedoucího a účetní.

---

## 5. Další kroky
- [ ] **Zkoušet propojení Pythonu a Obsidianu**
  - Automatizace poznámek.
  - Export dat do kalendáře nebo jiných nástrojů.

- [ ] **Záloha Vaultu na OneDrive**
  - Nastavit synchronizaci Vaultu s OneDrive.

- [ ] **Pokračovat v kurzu Python a SQL**
  - Připravit si poznámky k jednotlivým tématům.
  - Použít tagy pro rychlé třídění.

---

Tahle roadmapa ti pomůže projít všechny kroky a zároveň si postupně organizovat informace. Dej vědět, jestli chceš něco upravit nebo rozšířit. 😊
