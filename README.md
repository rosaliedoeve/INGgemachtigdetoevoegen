# ING Zakelijk - Gemachtigde Toevoegen Prototype

## 📋 Overzicht

Dit is een klikbaar HTML prototype dat de **verbeterde flow** demonstreert voor het toevoegen van een gemachtigde zonder particuliere ING rekening.

### Probleem (Oud - 5+ stappen)
❌ Te veel kliks en doorverwijzingen
❌ Formulier moest apart gemaild worden
❌ Frustrerende gebruikerservaring

### Oplossing (Nieuw - 3 stappen)
✅ Directe route naar formulier
✅ Online submitten (geen mailen meer!)
✅ Duidelijke progress indicator
✅ Gestroomlijnde ervaring

---

## 🚀 Hoe te gebruiken

### Het prototype openen:

1. **Open `index.html`** in je browser
   - Dubbelklik op het bestand, OF
   - Rechtermuisklik → "Openen met" → Kies je browser

2. **Navigeer door de flow:**
   - **Screen 1** (index.html): Dashboard met CTA "Gemachtigde zonder ING rekening toevoegen"
   - **Screen 2** (add-gemachtigde.html): Formulier met 4 stappen
   - **Screen 3** (confirmation.html): Bevestigingspagina

---

## 📁 Bestanden

```
ING/
├── index.html              → Screen 1: Dashboard
├── add-gemachtigde.html    → Screen 2: Formulier (4 stappen)
├── confirmation.html       → Screen 3: Bevestiging
├── styles.css              → ING design system
├── script.js               → Interactiviteit & validatie
├── ING_Group_N.V._Logo.svg.png → ING logo
├── PROJECT_BRIEF.md        → Volledige project documentatie
└── README.md               → Deze handleiding
```

---

## 🎨 Design System

### Kleuren
- **ING Orange**: #FF6200 (primaire actie kleur)
- **Wit**: #FFFFFF
- **Donkerblauw**: #003D5C (tekst)
- **Grijs**: #767676 / #E5E5E5

### Componenten
- ING branding consistent met zakelijk platform
- Progress indicator voor multi-step form
- Responsive design (desktop-first)
- Form validatie & error handling
- Success states met feedback

---

## ✨ Features

### Screen 1: Dashboard
- Overzicht bestaande autorisaties
- Primaire CTA voor nieuwe gemachtigde
- Duidelijke messaging over verbeterde flow

### Screen 2: Formulier (4 stappen)
**Stap 1**: Organisatiegegevens
- KvK nummer (auto-format, 8 cijfers)
- Bedrijfsgegevens
- Type organisatie

**Stap 2**: Gemachtigde gegevens
- Persoonsgegevens
- Contactinformatie
- Email validatie

**Stap 3**: Bevoegdheden
- Rekening selectie
- Machtigingen (checkboxes)
- Betalingslimiet (optioneel)
- Geldigheidsduur

**Stap 4**: Bevestiging
- Review alle ingevoerde gegevens
- Voorwaarden akkoord
- Direct indienen (geen mailen!)

### Screen 3: Bevestiging
- Success message met referentienummer
- Volgende stappen uitgelegd
- FAQ sectie
- Print functionaliteit

---

## 🔧 Technisch

### Validatie
- Real-time form validatie
- Required field checks
- Email format validatie
- KvK nummer format (8 cijfers)
- Telefoon nummer auto-formatting

### Navigatie
- Smooth scroll tussen stappen
- Progress indicator update
- Terug/Volgende knoppen
- Enter key support

### Data handling
- FormData opslag tijdens proces
- SessionStorage voor confirmation page
- Form data review voor indienen

---

## 📊 Flow Vergelijking

### OUD (Complex - 5 screens)
1. Dashboard → Klik "Beheer bevoegdheden"
2. Popup → "Kan niet via deze weg"
3. Info pagina 1 → Klik juiste optie
4. Info pagina 2 → Klik weer
5. Formulier → **Moet apart mailen! ❌**

### NIEUW (Simpel - 3 screens)
1. Dashboard → Klik "Gemachtigde toevoegen"
2. Formulier → Vul in (4 substappen met progress bar)
3. Bevestiging → **Direct ingediend! ✅**

**Resultaat**: Van 5+ kliks naar 2 kliks! 🎉

---

## 🧪 Testen

### Test scenario:
1. Open `index.html`
2. Klik op oranje knop "Gemachtigde zonder ING rekening toevoegen"
3. Vul formulier in (alle stappen)
4. Klik "Aanvraag indienen"
5. Zie bevestigingspagina met referentienummer

### Test validatie:
- Probeer door te gaan zonder verplichte velden in te vullen
- Probeer ongeldig email adres
- Probeer KvK nummer met letters
- Test alle checkboxes en radio buttons

---

## 📱 Responsive

Het prototype is desktop-first maar heeft responsive breakpoints voor:
- Tablet (768px)
- Mobile (< 768px)

Sidebar wordt horizontaal op mobile devices.

---

## 🎯 Volgende Stappen (Buiten scope prototype)

Voor productie implementatie:
- [ ] Backend API integratie
- [ ] Database connectie
- [ ] Authenticatie & autorisatie
- [ ] Email notificaties (bevestiging, reminders)
- [ ] Document upload functionaliteit
- [ ] Admin dashboard voor goedkeuring
- [ ] Audit logging
- [ ] WCAG 2.1 accessibility compliance
- [ ] Cross-browser testing
- [ ] Performance optimalisatie

---

## 📞 Contact

Voor vragen over dit prototype:
- Project: ING Gemachtigde Simplified Flow
- Opdrachtgever: ING Bank - Zakelijk
- Datum: 4 februari 2026

---

## 📝 Licentie

Dit is een prototype gemaakt voor WUA - ING Project.
Alle ING branding en design elements zijn eigendom van ING Group N.V.

---

**🧡 Gemaakt met Claude Code**
