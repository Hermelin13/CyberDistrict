# 🌆 CyberDistrict  
Strategická správa futuristického města

## 📌 Základní informace

**Název hry:** CyberDistrict  
**Žánr:** 2D strategická simulace (real-time)  
**Engine:** Godot 4.6.1
**Platforma:** PC  

---

# 💡 1. Hlavní myšlenka hry

CyberDistrict je strategická hra zaměřená na správu futuristické městské čtvrti v cyberpunkovém světě. Podobá se SimCity.  

Hráč přebírá roli správce nové městské zóny a jeho cílem je:

- budovat infrastrukturu,
- řídit ekonomiku,
- udržovat stabilní energetickou síť,
- kontrolovat kriminalitu,
- zajišťovat spokojenost obyvatel.

Klíčovým prvkem hry je provázanost jednotlivých herních systémů, které se navzájem ovlivňují.

---

# 🌃 2. Herní prostředí

Hra se odehrává ve futuristickém městě inspirovaném cyberpunkovou estetikou:

- neonové osvětlení
- vysoké obytné bloky
- technologicky pokročilé budovy
- digitální infrastruktura

Hráč buduje město na mapě rozdělené do mřížky (TileMap).

---

# ⚙️ 3. Hlavní herní systémy

## 💰 3.1 Ekonomický systém

Ekonomika je založena na:

- daních z obyvatel
- údržbě budov
- investicích do infrastruktury

Vyšší daně zvyšují příjem, ale snižují spokojenost obyvatel atd.

---

## ⚡ 3.2 Energetický systém

Každá budova:

- spotřebovává energii,
- některé budovy energii produkují.

Při nedostatku energie dochází k výpadkům (blackout), které negativně ovlivňují:

- spokojenost,
- příjem města,
- stabilitu systému.

---

## 😊 3.3 Systém spokojenosti obyvatel

Spokojenost je ovlivněna:

- výší daní,
- dostupností energie,
- přítomností parků,
- úrovní kriminality.

Nízká spokojenost vede k:

- poklesu příjmů,
- růstu kriminality,
- riziku nepokojů.

---

## 🚓 3.4 Bezpečnostní systém

Kriminalita roste při:

- nízké spokojenosti,
- vysoké hustotě obyvatel.

Policejní stanice kriminalitu snižují, ale zvyšují náklady na údržbu.

---

## 🏗 3.5 Stavební systém

Hráč může stavět:

- obytné bloky (zvyšují populaci),
- elektrárny (zvyšují produkci energie),
- policejní stanice (snižují kriminalitu),
- parky (zvyšují spokojenost),
- obchodní centra (zvyšují příjem).

Každá budova má:

- pořizovací cenu,
- náklady na údržbu,
- konkrétní efekt na herní systémy.

---

# 🧠 4. Strategická hloubka

Hra je založena na rovnováze mezi systémy.

Například:

- Zvýšení daní → vyšší příjem → nižší spokojenost → vyšší kriminalita → nižší efektivita ekonomiky.
- Nedostatek energie → pokles spokojenosti → pokles příjmu → finanční problémy.

Hráč musí neustále optimalizovat rozhodnutí a strategicky se starat o město s ohledem na budoucí vývoj.

---

# 🏆 5. Cíl hry

### ✅ Výhra:
- Dosáhnout 1000 obyvatel,
- Udržet spokojenost nad 70 %,
- Zachovat kladný rozpočet po určitou dobu.

### ❌ Prohra:
- Bankrot (finance pod 0),
- Spokojenost pod kritickou hranicí,
- Kolaps městské infrastruktury.

Vítězství může být relativní → hra počítá skóre (obyvatele), to znamená čím více obyvatel tím lepší hráč.

---

# 🚀 6. Možná budoucí rozšíření

- Strom technologií
- Náhodné události (protesty, hackerské útoky)
- Denní/noční cyklus
- Pokročilé AI řízení obyvatel
- Multiplayer režim - podpora jiných měst
- Mobilní verze

---

# 📖 Shrnutí

CyberDistrict je strategická hra zaměřená na řízení komplexního městského systému.  
Hlavním cílem je vytvořit stabilní a prosperující futuristickou čtvrť pomocí vyváženého řízení ekonomiky, energie a spokojenosti obyvatel.
