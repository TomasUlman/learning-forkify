# learning-forkify

> ⚠️ This is a study project based on a Udemy course. It is not intended for production use.  
> The README continues in Czech, as this project is part of my personal learning archive.

---

## 🍳 Forkify – vyhledávání a správa receptů

Forkify je interaktivní aplikace pro vyhledávání receptů, jejich zobrazení, úpravu, uložení do záložek a přidání vlastních receptů. Aplikace komunikuje s veřejným API (`forkify-api.herokuapp.com`) a staví na architektuře MVC.

🔗 **Live demo**: [https://tomasulman-forkify.netlify.app/](https://tomasulman-forkify.netlify.app/)

---

## 💡 Funkce aplikace

- **Vyhledávání receptů** podle klíčového slova
- **Zobrazení detailu receptu** včetně porcí a ingrediencí
- **Přepočet surovin** podle počtu porcí
- **Záložky** – ukládání oblíbených receptů (uloženo v LocalStorage)
- **Přidání vlastního receptu** přes formulář
- **Navigace pomocí URL hash (#id)**
- **Stránkování výsledků**
- **Zobrazování spinnerů, chybových a úspěšných hlášek**

---

## 🧱 Architektura (MVC)

- **Model (`model.js`)**
  - Správa stavu (`state`)
  - Načítání dat z API (AJAX)
  - Validace a zpracování vstupů
- **View (např. `recipeView.js`, `searchView.js`, `paginationView.js`)**
  - Vykreslování UI komponent
  - Správa DOM událostí
- **Controller (`controller.js`)**
  - Propojování modelu a view
  - Centrální bod logiky aplikace

---

## 🛠 Použité technologie

- **HTML / CSS / SCSS**
- **JavaScript (ES6+)**
- **Modulární kód s `import/export`**
- **OOP – třídy pro každou UI komponentu**
- **LocalStorage**
- **Fetch + error handling (AJAX wrapper)**
- **Netlify deploy**

---

## 🧠 Co jsem si na projektu vyzkoušel

- Návrh aplikace v MVC architektuře
- Modulární rozdělení kódu na jednotlivé komponenty
- Práci s asynchronními daty, validací a výjimkami
- Ukládání a obnovu dat ze `localStorage`
- Správu URL (`window.location.hash`) a historii
- Práci s formulářem a vlastní validací vstupních polí
- První deploy na **Netlify**

---

## 🧼 Poznámka

Aplikace je studijním projektem a není určena pro produkční nasazení. API může být limitováno nebo časem nedostupné.
