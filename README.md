# ⚔️ WoW Classic TBC PvE Guide
## Alliance | Phase 2 Focus: SSC & TK
### 🧙 Elemental Shaman (70) & 🛡️ Retribution Paladin (70)

Ein kompakter, aber ausführlicher PvE-Guide für TBC Classic mit Fokus auf Phase 2, also Serpentshrine Cavern und Tempest Keep / The Eye [web:9][web:11].

---

## Inhaltsverzeichnis

- [⚡ Elemental Shaman](#-elemental-shaman)
- [🛡️ Retribution Paladin](#-retribution-paladin)
- [🏰 Heroic Dungeons](#-heroic-dungeons)
- [⌨️ Macros](#-macros)
- [🧩 Addons](#-addons)
- [🗡️ Gear Progression](#-gear-progression)
- [🍖 Consumables](#-consumables)
- [✅ Golden Rules](#-golden-rules)

---

<details open>
<summary><strong>⚡ Elemental Shaman</strong></summary>

### Stat Priority

1. Spell Hit
2. Spell Damage
3. Haste
4. Critical Strike
5. Intellect
6. MP5

### Hit Cap

- Ohne Shadow Priest / Boomkin: 16% Spell Hit.
- Mit passiver Hit-Reduktion durch Talente entsprechend weniger.

### Zielwerte

| Stat | Ziel |
|---|---|
| Spell Damage | 1000+ |
| Crit | 20%+ |
| Haste | so viel wie möglich |
| Hit | Cap zuerst |

### Rotation

#### Single Target
```text
Lightning Bolt
Lightning Bolt
Chain Lightning
Lightning Bolt
Lightning Bolt
Chain Lightning
```

#### Priorität
1. Totems aktiv halten.
2. Lightning Shield aktiv halten.
3. Chain Lightning auf Cooldown.
4. Lightning Bolt als Füllzauber.

#### Multi Target
```text
Chain Lightning
Lightning Bolt
Chain Lightning
Fire Nova Totem
```

### Cooldowns

- Elemental Mastery immer mit Bloodlust, Heroism oder Trinket-Procs stacken.
- Nicht auf Trash verschwenden.
- Für Boss-Burst und DPS-Checks aufheben.

### Totems

#### Caster Group
- Earth: Tremor Totem.
- Fire: Totem of Wrath.
- Water: Mana Spring Totem.
- Air: Wrath of Air Totem.

#### Melee Group
- Earth: Strength of Earth Totem.
- Fire: Totem of Wrath.
- Water: Mana Spring Totem.
- Air: Windfury Totem.

#### Hunter + Druide Group
- Earth: Strength of Earth Totem.
- Fire: Totem of Wrath.
- Water: Mana Spring Totem.
- Air: Grace of Air Totem.

### SSC / TK Raid Notes

<details>
<summary><strong>Serpentshrine Cavern</strong></summary>

#### Hydross the Unstable
- Single Target Fight.
- Cooldowns direkt nach Transition.
- Nicht zu früh laufen.

#### The Lurker Below
- Boss-DPS.
- Adds während Submerge.
- Nach erstem Spout planbar burst nutzen.

#### Leotheras the Blind
- Human Form priorisieren.
- Whirlwind meiden.
- In der Demon Form nicht unnötig riskieren.

#### Fathom-Lord Karathress
- Adds zuerst.
- Caribdis und Tidalvess priorisieren.
- Spitfire Totem sofort entfernen.

#### Morogrim Tidewalker
- Chain Lightning bei Murloc-Wellen stark.
- Nach der ersten Welle Burst nutzen.
- Auf Watery Grave und Positionierung achten.

#### Lady Vashj
- Phase 1 kontrolliert spielen.
- Phase 2: Adds, Strider und Tainted Core priorisieren.
- Phase 3: Bloodlust + Trinkets + Full Burn.

</details>

<details>
<summary><strong>Tempest Keep / The Eye</strong></summary>

#### Al'ar
- Platformwechsel beachten.
- Phase 2 ist der wichtigste Burn-Moment.
- Meteor und Flame Patch ausweichen.

#### Void Reaver
- Max Range spielen.
- Ständig bewegen.
- Pure DPS Fight.

#### High Astromancer Solarian
- Add-Wellen schnell töten.
- Wrath of the Astromancer sofort rauslaufen.

#### Kael'thas Sunstrider
- Berater sauber kontrollieren.
- Phase 3 ist der härteste DPS-Check.
- Phase 4 und 5 mit allen Rest-Cooldowns spielen.

</details>

### Addons
- WeakAuras
- Quartz
- DBM
- Details!
- OmniCC
- Leatrix Plus
- TotemTimers

### Macros
```lua
#showtooltip Lightning Bolt
/targetenemy [noharm][dead]
/cast Lightning Bolt
```

```lua
#showtooltip Chain Lightning
/stopcasting
/cast Elemental Mastery
/cast Chain Lightning
```

```lua
#showtooltip Earth Shock
/stopcasting
/cast Earth Shock
```

```lua
#showtooltip Bloodlust
/use 13
/use 14
/cast Bloodlust
```

### Gear Progression

#### Pre-Raid BIS
- Spellstrike Set
- Frozen Shadoweave Set
- Totem of the Void
- Icon of the Silver Crescent

#### Phase 1
- Cyclone Set (T4)
- The Lightning Capacitor
- Icon of the Silver Crescent

#### Phase 2
- T5 Cyclone Set
- Netherstrike Bracers
- Worldfire Chestguard
- Quagmirran's Eye
- Scarab of the Infinite Cycle

#### Phase 3
- T6 Skyshatter
- Skull of Gul'dan
- Hex Shrunken Head

### Consumables
- Flask of Blinding Light
- Blackened Basilisk
- Superior Wizard Oil
- Destruction Potion
- Super Mana Potion
- Dark Rune
- Scroll of Spirit V
- Scroll of Intellect V

### Golden Rules
- Lightning Bolt ist dein Hauptschaden.
- Totems niemals vergessen.
- Cooldowns nur für Bossfenster nutzen.
- Max Range spielen.
- ABC: Always Be Casting.

</details>

---

<details>
<summary><strong>🛡️ Retribution Paladin</strong></summary>

### Stat Priority
1. Hit
2. Strength
3. Weapon Damage
4. Expertise
5. Crit
6. Haste

### Seal Twisting
Seal Twisting ist die wichtigste DPS-Technik für Ret in TBC.

#### Alliance Variante
```text
Seal of Command
↓
Seal of Righteousness
```

### Swing Timer
- Pflicht: WeaponSwingTimer oder Quartz.
- Twist timing: etwa 0.3 bis 0.4 Sekunden vor dem Autoattack.
- Zu früh = DPS-Verlust.
- Zu spät = Twist verpasst.

### Rotation
1. Crusader Strike.
2. Judgement.
3. Seal Twist.
4. Consecration.
5. Exorcism gegen Dämonen oder Untote.

### Cooldowns
- Avenging Wrath auf Pull oder in Bloodlust-Phase.
- Trinkets immer mit Burst kombinieren.
- Haste Potion mit Bloodlust und Avenging Wrath stacken.

### Auras
- Solo: Retribution Aura.
- Raid: Sanctity Aura.
- Situativ: Devotion Aura oder Resist Auras.

### Blessings
- Caster Group: Blessing of Wisdom oder Salvation.
- Melee Group: Blessing of Might.
- Hunter / Feral / Balance passend nach Bedarf.

### SSC / TK Raid Notes

<details>
<summary><strong>Serpentshrine Cavern</strong></summary>

#### Hydross the Unstable
- Nach Transition burstbar.
- Aggro Reset beachten.

#### The Lurker Below
- Spout konsequent bewegen.
- Nach erstem Spout burst nutzen.

#### Leotheras the Blind
- Whirlwind meiden.
- Human Form priorisieren.

#### Fathom-Lord Karathress
- Adds zuerst.
- Totems und Priority Targets sauber spielen.

#### Morogrim Tidewalker
- Murloc-Wellen mit AoE unterstützen.
- Cooldowns nicht zu früh verschwenden.

#### Lady Vashj
- Phase 3 für Full Burn aufheben.
- Bloodlust + Trinkets mitnehmen.

</details>

<details>
<summary><strong>Tempest Keep / The Eye</strong></summary>

#### Al'ar
- Phase 2 ist der Burst-Moment.
- Meteor vermeiden.

#### Void Reaver
- Perfekter Ret-Fight.
- 100% Uptime ist das Ziel.

#### High Astromancer Solarian
- Debuffs sofort rauslaufen.
- Adds priorisieren.

#### Kael'thas Sunstrider
- Phase 3 ist der große DPS-Check.
- Phase 4 und 5 mit Rest-Cooldowns spielen.
- Gravity Lapse sauber mit DPS-Uptime spielen.

</details>

### Gear Progression
#### Phase 1
- Lionheart Champion
- Hellreaver
- Crystalforged Sword
- Bloodlust Brooch
- Abacus of Violent Odds

#### Phase 2
- Gorehowl
- Cataclysm Edge
- Dragonspine Trophy

#### Phase 3
- T6 Set
- Madness of the Betrayer

#### Phase 5
- Apolyon
- Brutallus Gear
- Full BIS

### Consumables
- Flask of Relentless Assault
- Roasted Clefthoof
- Haste Potion
- Super Mana Potion
- Scroll of Strength V
- Scroll of Agility V
- Adamantite Weightstone

### Macros
```lua
#showtooltip Crusader Strike
/startattack
/cast Crusader Strike
```

```lua
#showtooltip Judgement
/startattack
/cast Judgement
```

```lua
#showtooltip Avenging Wrath
/use 13
/use 14
/cast Avenging Wrath
```

### Golden Rules
- Niemals ohne Swing Timer spielen.
- Seal Twisting üben.
- Cooldowns stacken.
- Nicht overaggro gehen.
- Positionierung ist DPS.

</details>

---

## Heroic Dungeons

- Nur laufen, wenn die Daily/Badge-Ziele sinnvoll sind.
- Ret Paladin spielt stark mit konsistentem Uptime-Fokus.
- Elemental Shaman profitiert von sauberer Positionierung und kontrollierten Pulls.

---

## Notes

- Diese Version ist auf GitHub-Rendering optimiert, und `<details>` funktioniert dort gut für einklappbare Bereiche [web:1][web:10].
- Phase 2 in TBC Classic besteht aus SSC und The Eye, daher ist die Guide-Struktur genau darauf ausgelegt [web:9][web:11].
