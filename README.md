# ☀️ Solar ROI Estimator

**Solar ROI Estimator** je interaktivní webová aplikace pro výpočet návratnosti investice do domácí fotovoltaické elektrárny v Česku.  
Uživatel zadá své roční údaje o spotřebě, lokalitu a další volby – a aplikace spočítá, jak rychle se investice vrátí.

---

## 🔧 Použité technologie

- [Next.js](https://nextjs.org/) – React framework pro webovou aplikaci
- [TypeScript](https://www.typescriptlang.org/) – typová kontrola
- [TailwindCSS](https://tailwindcss.com/) – utilitní CSS framework
- [Recharts](https://recharts.org/en-US/) – grafy návratnosti
- [Leaflet](https://leafletjs.com/) – interaktivní mapa pro výběr lokality
- [PVGIS API](https://re.jrc.ec.europa.eu/pvg_tools/en/) – veřejná data o solární irradianci

---

## ✨ Funkce

- Výpočet podle: ⚡️ **spotřeba**, 🌍 **lokalita**, 💰 **tarif**, 🔋 **baterie**, 🚗 **elektromobil**
- Automatické načítání dat o slunečním záření z **PVGIS** dle souřadnic
- Interaktivní graf **návratnosti investice po letech**
- Podpora různých modelů EV s možností ručního zadání spotřeby
- Možnost výběru polohy z mapy (Leaflet)

---

## 🖥️ Ukázka

`coming soon`

---

## 📦 Lokální spuštění

```bash
git clone https://github.com/sar-ilia/solar-roi-estimator.git
cd solar-roi-estimator
npm install
npm run dev
