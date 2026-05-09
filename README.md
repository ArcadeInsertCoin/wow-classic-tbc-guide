# World of Warcraft – The Burning Crusade Classic (Patch 2.5.x)
## PvE Komplettguide · Alliance
### Retribution Paladin · Elemental Shaman

---

# 🛡️ PALADIN
_Retribution PvE Guide_

---

## 📊 Stat-Caps & Prioritäten

### Retribution
- Hit Cap: **9 %**
- Expertise: sehr stark
- Prio:
  - Hit
  - Weapon Damage
  - Strength
  - Crit
  - Haste

---

## ⚔️ Core Skills

- Seal of Blood / Command
- Crusader Strike
- Judgement
- Consecration
- Exorcism (nur Dämonen / Untote)
- Avenging Wrath

---

## 🚫 Nicht benutzen

- Seal of Crusader
- Holy Light als DPS-Heal
- Consecration Spam bei Mana-Problemen
- Exorcism auf normale Ziele

---

## 🔁 Rotation

### Solo
- Seal → Judgement → Crusader Strike
- Consecration optional

### Dungeon
- Judgement → Crusader Strike → Consecration

### Raid
- Crusader Strike
- Judgement
- Consecration bei genug Mana
- Wings + Trinkets zusammen

---

## 🔔 Auren

### Solo
- Retribution Aura

### Dungeon
- Sanctity Aura

### Raid
- Sanctity Aura
- situativ Devotion Aura

---

## 🧱 Gear-Pfad

### P1 (Karazhan)
- Hellreaver
- Lionheart Champion
- Crystalforged Sword

### P2 (SSC / TK)
- Gorehowl
- Cataclysm Edge
- Dragonspine Trophy

### P3–5
- T5 → T6
- Black Temple
- Sunwell Plateau

---

## 🍖 Consumables

### Food
- Roasted Clefthoof

### Flask
- Flask of Relentless Assault

### Potions
- Haste Potion
- Super Mana Potion

### Trinkets
- Dragonspine Trophy
- Bloodlust Brooch
- Madness of the Betrayer

---

## 🔧 Berufe

### Optimal
- Blacksmithing + Jewelcrafting

### Alternativen
- Engineering
- Enchanting

---

## 🐉 Raid-Aufgaben

### Karazhan
- Blessings aktiv halten
- Utility helfen
- Interrupts nutzen

### SSC / TK
- Burst auf Prioritätsziele
- Cleave kontrollieren

### Hyjal
- Consecration Cleave
- Adds kontrollieren

### Black Temple
- Cooldowns sauber rotieren
- Aggro kontrollieren

### Sunwell
- Fehlerfrei spielen
- maximale Uptime

---

## ⚔️ Retribution Macros

### Crusader Strike

```lua
#showtooltip Crusader Strike
/startattack
/cast Crusader Strike
```

### Judgement

```lua
#showtooltip Judgement
/startattack
/cast Judgement
```

### Wings Burst

```lua
#showtooltip Avenging Wrath
/use 13
/use 14
/cast Avenging Wrath
```

---

# ⚡ SHAMAN
_Elemental PvE Guide_

---

## 📊 Stat-Caps & Prioritäten

### Elemental
- Hit Cap:
  - mit Talenten reduziert
- Prio:
  - Spell Hit
  - Spell Damage
  - Haste
  - Crit
  - Intellect

---

## ⚔️ Core Skills

- Lightning Bolt
- Chain Lightning
- Totem of Wrath
- Wrath of Air Totem
- Mana Spring Totem
- Elemental Mastery
- Earth Shock
- Bloodlust / Heroism
- Lightning Shield

---

## 🚫 Nicht benutzen

- Flame Shock Spam
- Earth Shock als reine DPS Rotation
- Zu viele Totems neu setzen
- Chain Lightning bei Mana-Problemen spammen

---

## 🔁 Rotation

### Solo
- Lightning Bolt
- Lightning Bolt
- Chain Lightning

#### Loop
LB → LB → CL

---

### Dungeon
- Totems setzen
- LB Spam
- CL auf Cooldown
- Earth Shock Interrupt

---

### Raid
- Lightning Bolt Spam
- Chain Lightning auf CD
- Totems aktiv halten
- Bloodlust timen

---

## 🪵 Totems

### Solo
- Wrath of Air Totem
- Mana Spring Totem
- Searing Totem

### Dungeon (Caster)
- Totem of Wrath
- Mana Spring Totem
- Searing Totem

### Dungeon (Melee)
- Windfury Totem
- Mana Spring Totem
- Searing Totem

### Raid
- Totem of Wrath
- Mana Spring Totem
- situativ Fire Totems

---

## 🧱 Gear-Pfad

### P1 (Karazhan)
- Spellstrike Set
- Totem of the Void
- Icon of the Silver Crescent

### P2 (SSC / TK)
- T5 Set
- Quagmirran’s Eye
- Nexus-Key Gear

### P3–5
- T6
- Black Temple
- Sunwell Gear

---

## 🍖 Consumables

### Food
- Blackened Basilisk

### Flask
- Flask of Blinding Light

### Potions
- Super Mana Potion
- Destruction Potion

### Weapon Buff
- Flametongue Weapon

### Trinkets
- Icon of the Silver Crescent
- Quagmirran’s Eye
- Skull of Gul’dan

---

## 📍 Positioning

### Solo
- mittlere Distanz
- Vorcasten

### Dungeon
- hinter Tank
- Totem Range beachten

### Raid
- feste Position
- wenig Movement
- Totems optimal platzieren

---

## 🔥 Bloodlust / Heroism

### Wann benutzen?
- Boss Pull
- Burst Phasen
- Raid Call folgen

---

## 🐉 Raid-Aufgaben

### Karazhan
- Totems sauber halten
- Interrupts nutzen

### SSC / TK
- Totem Positionierung
- Mana Management

### Hyjal
- CL Cleave sehr stark
- Aggro kontrollieren

### Black Temple
- hoher Burst
- Bloodlust richtig timen

### Sunwell
- Movement + DPS Balance
- Totem Uptime perfekt halten

---

## 🔧 Berufe

### Optimal
- Tailoring + Jewelcrafting

### Alternativen
- Enchanting
- Alchemy

---

## ⚡ Elemental Macros

### Lightning Bolt

```lua
#showtooltip Lightning Bolt
/targetenemy [noharm][dead]
/cast Lightning Bolt
```

### Chain Lightning + Elemental Mastery

```lua
#showtooltip Chain Lightning
/stopcasting
/cast Elemental Mastery
/cast Chain Lightning
```

### Earth Shock Interrupt

```lua
#showtooltip Earth Shock
/stopcasting
/cast Earth Shock
```

### Solo Totem Macro

```lua
#showtooltip Wrath of Air Totem
/castsequence reset=6 Wrath of Air Totem, Mana Spring Totem
```

### Dungeon / Raid Totem Macro

```lua
#showtooltip Totem of Wrath
/castsequence reset=6 Totem of Wrath, Mana Spring Totem
```

### Searing Totem

```lua
#showtooltip Searing Totem
/cast Searing Totem
```

### Bloodlust

```lua
#showtooltip Bloodlust
/use 13
/use 14
/cast Bloodlust
```

---

# 🏆 BESTE ADDONS

## Beide Klassen

- Questie
- Details!
- WeakAuras
- Quartz
- OmniCC
- DBM

---

# 💡 GOLDENE TBC REGELN

## Retribution
- Mana managen
- nicht overaggro gehen
- Cooldowns sinnvoll nutzen

## Elemental
- Totems effizient setzen
- LB Spam = Hauptschaden
- Positioning extrem wichtig
- nicht unnötig bewegen

---
