# 🌲 Forestral — Fișă Descriere Silvică

Aplicație mobilă PWA pentru completarea fișelor de descriere silvică în teren, cu sau fără internet.

---

## 📱 Funcționalități

- **Import din AS2007** — încarcă fișierele XLS exportate (OSxxxxA.XLS și OSxxxxS.XLS) și completează automat fișa
- **Completare manuală** — toate câmpurile standardului silvic românesc
- **Export formular** — generează fișa vizuală gata de printat (HTML)
- **Salvare JSON** — salvează și reîncarcă date între sesiuni
- **Salvare automată** — datele se păstrează în browser
- **Funcționare offline** — după prima deschidere nu mai ai nevoie de internet

---

## 🗂️ Secțiuni

| Tab | Conținut |
|-----|----------|
| Import DB | Încarcă fișierele XLS din AS2007 |
| Identificare | ISJ, OS, UP, UA, suprafețe, categorii funcționale |
| Relief & Sol | Relief, expunere, înclinare, sol, tip stațiune, tip pădure |
| Arboret | Vârste, urgențe, compoziție tel, subarboret |
| Semințiș | Specii și proporții semințiș utilizabil |
| Elemente | Date dendrometrice pe elemente (ELM) |
| Export | Export formular vizual, salvare/încărcare JSON |

---

## 🚀 Instalare ca aplicație

1. Deschide link-ul în **Safari (iPhone)** sau **Chrome (Android)**
2. **iPhone:** butonul Share → *Add to Home Screen*
3. **Android:** meniu (⋮) → *Add to Home Screen*

Aplicația se instalează cu iconița Forestral și funcționează complet offline.

---

## 📁 Fișiere

```
index.html      — aplicația principală
manifest.json   — configurație PWA
sw.js           — service worker (cache offline)
icon-192.png    — icoană 192×192
icon-512.png    — icoană 512×512
```

---

## 🛠️ Tehnologii

- HTML / CSS / JavaScript vanilla
- SheetJS (XLSX) pentru import fișiere Excel
- PWA cu Service Worker pentru funcționare offline
- localStorage pentru salvare automată

---

*Dezvoltat pentru uz intern silvic — România 🇷🇴*
