# 🎯 SkillHub – osobní platforma pro správu dovedností

Tento projekt slouží jako učební fullstack aplikace, která postupně roste od jednoduché statické stránky po plnohodnotnou React + Laravel webovku s Tailwindem. Buduje se podle jednotlivých kurzů od Jonase Schmedtmanna.

---

## 🧱 Fáze 1: HTML + CSS (Statický web)

### ✅ Základy
- [ ] Vytvořit `index.html` s hlavičkou, hlavní sekcí a patičkou
- [ ] Přidat hero sekci s CTA tlačítkem
- [ ] Vytvořit sekce: Jak to funguje / Pro koho to je / Kontakt
- [ ] Základní styl pomocí vlastního CSS (bez frameworku)
- [ ] Přidat responzivitu (media queries)

---

## 💻 Fáze 2: JavaScript (Interaktivní web)

### ✅ Funkce
- [ ] Formulář pro zadání dovednosti (název, úroveň, poznámka)
- [ ] Zobrazit seznam dovedností na stránce
- [ ] Možnost označit dovednost jako hotovou / v procesu
- [ ] Smazání dovednosti
- [ ] Uložení do `localStorage` a načítání po reloadu

---

## ⚛️ Fáze 3: React (Přepis do komponent)

### ✅ Komponenty
- [ ] `App`
- [ ] `SkillList`
- [ ] `SkillForm`
- [ ] `SkillItem`
- [ ] `FilterBar`

### ✅ Funkcionalita
- [ ] Stav pomocí `useState`
- [ ] `useEffect` pro localStorage
- [ ] Přidávání, mazání, označení dovednosti
- [ ] Filtrování: Vše / Aktivní / Hotové
- [ ] Routing: `/`, `/moje-dovednosti`, `/cil`, `/poznamky`

---

## 🎨 Fáze 4: Tailwind CSS

- [ ] Instalace Tailwind přes Vite nebo CRA
- [ ] Stylování komponent pomocí utility tříd
- [ ] Temný režim (`dark:` varianty)
- [ ] Responzivní design

---

## 🔧 Fáze 5: Backend v Laravelu

### ✅ API (Laravel + Sanctum)
- [ ] Přihlašování a registrace
- [ ] CRUD pro dovednosti
- [ ] Endpoints pro poznámky a cíle
- [ ] Middleware pro ověření tokenu
- [ ] Testování pomocí Postmanu nebo Laravel tests

---

## 🔄 Fáze 6: Fullstack spojení (React + Laravel API)

- [ ] Přihlášení uživatele a uložení tokenu
- [ ] Volání API přes `fetch` nebo `axios`
- [ ] Zobrazení dat z databáze v komponentách
- [ ] Odesílání změn na server (POST/PUT/DELETE)
- [ ] Oddělené dashboardy pro uživatele a kouče

---

## 📝 Bonus funkce
- [ ] PDF export poznámek nebo dovedností
- [ ] Kalendář učebních plánů
- [ ] Role (uživatel, kouč)
- [ ] Emailové notifikace (Laravel Notifications)
- [ ] Multijazyčný režim (např. EN/CZ)

---

## 📚 Použité technologie

- HTML, CSS, TailwindCSS
- JavaScript (ES6+), React
- Laravel, REST API
- localStorage, axios
- Git, GitHub

---

## ✅ Tip: Jak používat

1. Začni jen s HTML + CSS
2. Po každé větší lekci z kurzu přidej novou funkci
3. Odškrtni si splněné úkoly výše
4. Udělej pravidelný `commit` (např. `git commit -m "přidán formulář pro dovednosti"`)

---

## 🧠 Cíl projektu

Vytvořit komplexní fullstack aplikaci pro osobní růst, která poroste spolu s tvými znalostmi. Výsledkem bude projekt vhodný do portfolia, který ukazuje vše od struktury až po moderní vývoj s API.

