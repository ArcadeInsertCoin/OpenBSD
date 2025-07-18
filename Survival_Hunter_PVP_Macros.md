Survival Hunter PvP Makros für WoW Classic (Patch 1.17 Phase 5)
Hier ist das vollständige Markdown-Dokument mit optimierten PvP-Makros speziell für WoW Classic (Patch 1.17 Phase 5), formatiert für GitHub:

# Survival Hunter PvP Makros - WoW Classic (Patch 1.17 Phase 5)

![Hunter PvP](https://i.imgur.com/YjB7d4h.png)

## ⚠️ Wichtig: Classic-spezifische Mechaniken
- **Deterrence existiert nicht** in Classic - verwende stattdessen Aspect of the Monkey
- **Counterattack** ist ein Survival-Talent (erfordert 20 Punkte in Survival)
- Keine "cursor casting"-Funktion für Fallen
- Pet-Management ist kritischer als in späteren Erweiterungen

---

## 🛡️ Defensiv-Makros

### 1. Aspect of the Monkey + Wing Clip (Grundverteidigung)
```lua
#showtooltip
/cast Aspect of the Monkey
/cast Wing Clip

2. Disengage + Frost Trap (Nahkampf-Distanzierung)

#showtooltip Disengage
/cast Disengage
/cast Frost Trap
/petpassive

3. Notfall-Pet-Heilung

#showtooltip Mend Pet
/stopcasting
/cast [@pet,nodead] Mend Pet
/cast [@pet,dead] Revive Pet

⚔️ Offensiv-Makros

#showtooltip Counterattack
/cast Counterattack
/startattack

2. Raptor Strike + Mongoose Bite (Burst-Kombo)

#showtooltip Raptor Strike
/cast Raptor Strike
/cast !Mongoose Bite
/startattack

3. Modifier-Makro (Aspekt/Offensive)

#showtooltip
/cast [mod:shift] Aspect of the Hawk; Counterattack
/startattack [nomod]

🧪 CC & Utility

1. Freezing Trap + Pet-Kontrolle

#showtooltip Freezing Trap
/petpassive
/petfollow
/cast Freezing Trap

2. Scatter Shot + Autoshot

#showtooltip Scatter Shot
/cast Scatter Shot
/stopattack
/cast !Auto Shot

3. Flare + Aspect des Wildtiers (Anti-Stealth)

#showtooltip Flare
/cast Aspect of the Wild
/cast Flare


🔑 Taktische Tastenbelegung
Taste	Makro	Verwendung
F1	Aspect of Monkey + Wing Clip	Grundverteidigung
F2	Disengage + Frost Trap	Distanzierung
F3	Counterattack Combo	Nahkampf
F4	Freezing Trap	CC
Shift+F	Flare + Aspect	Anti-Rogue/Druide


🌟 Talentempfehlung für Phase 5 PvP

graph TD
    A[Survival] --> B[Improved Wing Clip: 3/3]
    A --> C[Counterattack: 1/1]
    A --> D[Deterrence: 3/3]
    E[Marksmanship] --> F[Improved Concussive Shot: 5/5]
    E --> G[Aimed Shot: 1/1]

Core Talents:

Counterattack (Survival)

Deterrence (Survival, +3% Parry)

Aimed Shot (Marksmanship)

Scatter Shot (Marksmanship)

🧠 Erweiterte PvP-Tipps für Classic

Gegen Krieger/Rogues:

Frost Trap vor Counterattack platzieren

Aspect of the Monkey immer aktiv halten

Wing Clip vor Disengage nutzen

Gegen Kaster:

Scatter Shot bei Casts nutzen

Viper Sting für Manaverbrennung

Aspect des Wildtiers gegen Zauber

Pet-Management:

Windspiel für zusätzliches Betäubung

Katze für höheren Schaden

IMMER "/petpassive" vor CC verwenden

Fallen-Rotation:


sequenceDiagram
    Jäger->>Gegner: Concussive Shot
    Gegner->>Jäger: Läuft auf dich zu
    Jäger->>Boden: Frost Trap platzieren
    Gegner->>Frost Trap: Ausgelöst!
    Jäger->>Gegner: Autoshot + Serpent Sting

