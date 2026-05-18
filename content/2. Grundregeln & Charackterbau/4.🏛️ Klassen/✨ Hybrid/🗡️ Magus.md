---
system: Pathfinder 2e
kategorie: Klassen
tags:
  - pf2e
  - klassen
  - magus
  - hybrid
verwandte_notizen:
  - Klassen – Übersicht
  - Attribute & Level System
  - Feats & Talente
  - Archetypen & Multiclassing
  - Zauberschulen & Traditionen
quellen:
  - Secrets of Magic (Seite 36 ff.)
erstellt: 2026-05-16
slug: "ruling/klassen/hybrid/magus"
---

# 🗡️ Klasse: Magus

## Was ist der Magus?

Der Magus ist ein **Hybrid-Kämpfer**, der Nahkampf und arkane Magie zu einer einzigen zerstörerischen Technik verschmilzt. Kein reiner Krieger, kein reiner Zauberer – sondern jemand, der einen Zauber buchstäblich in die Klinge lädt und beim nächsten Schlag freisetzt.

Seine Kernmechanik **Spellstrike** erlaubt es, Spellcasting und Strike zu einer 2-Aktionen-Aktion zu kombinieren: Der Zauber wird mit dem Treffer ausgeliefert. Das macht den Magus zu einem der offensivstärksten Einzel-Target-Schadensdealer im Spiel – auf Kosten von Ressourcenmanagement und Komplexität.

> *„Der Zauberer hebt die Hand. Ich hebe die Klinge. Beides kommt gleichzeitig an."*

---

## 📋 Klassen-Eckdaten

| Merkmal | Wert |
|--------|------|
| **Key Ability** | STR oder DEX (für Angriffe) + INT (für Zauber) |
| **HP pro Level** | 8 + CON-Modifier |
| **Perception** | Trained (L1) → Expert (L9) |
| **Saving Throws** | Fortitude: Expert (L1) → Master (L11) → Legendary (L17) |
| | Reflex: Trained (L1) → Expert (L9) → Master (L17) |
| | Will: Trained (L1) → Expert (L9) → Master (L17) |
| **Zaubertradition** | Arcane (Prepared, wie Wizard) |
| **Max. Spell Rank** | 6 (bei Level 19–20) |
| **Quelle** | Secrets of Magic |

> ⭐ Magus braucht **zwei** starke Attribute: STR oder DEX für Angriffe, INT für Zauberstärke und DC. Beim Bau immer beide berücksichtigen – kein Dump möglich.

---

## 🗡️ Waffen & Rüstung

### Waffen-Proficiency

| Waffengruppe | Startstufe | Steigerungen |
|--------------|-----------|--------------|
| Simple Weapons | Trained | Expert (L5) → Master (L13) |
| Martial Weapons | Trained | Expert (L5) → Master (L13) |
| Unarmed Attacks | Trained | Expert (L5) → Master (L13) |
| Advanced Weapons | – | Nur via Archetype |

> Der Magus hat Zugriff auf alle **Martial Weapons** – deutlich mehr Auswahl als z.B. Thaumaturge oder Wizard. Das ist wichtig: die Waffe ist das Trägermedium für Spellstrike.

### Rüstungs-Proficiency

| Rüstungstyp | Startstufe | Steigerungen |
|-------------|-----------|--------------|
| Unarmored | Trained | Expert (L13) → Master (L19) |
| Light Armor | Trained | Expert (L13) → Master (L19) |
| Medium Armor | Trained | Expert (L13) → Master (L19) |
| Heavy Armor | – | Nur via Archetype (z.B. Sentinel) |

> Magus kann Medium Armor tragen – gut für STR-Builds. DEX-Builds bleiben oft in Light Armor oder unarmored für Synergien mit bestimmten Hybrid Studies.

---

## ⚡ Kern-Mechanik: Spellstrike

Das Herzstück jeder Runde des Magus.

### Spellstrike ◆◆ (2 Aktionen)

Du lädst einen Zauber in deine Waffe und führst gleichzeitig einen Strike aus.

**Bedingung**: Spellstrike-„Container" muss geladen sein (startet leer, wird durch Recharge gefüllt).

**Ablauf:**
1. Wähle einen Zauber mit Spell Attack Roll **oder** Ranged Touch Attack
2. Würfle einen Strike mit deiner Waffe gegen die AC des Ziels
3. Bei Treffer: Strike-Schaden + Zauber-Effekt werden ausgeliefert
4. Container ist jetzt leer → muss neu geladen werden

| Strike-Ergebnis | Zauber-Effekt |
|----------------|---------------|
| **Kritischer Treffer** | Zauber gilt als **kritischer Erfolg** |
| **Treffer** | Zauber gilt als **Erfolg** |
| **Fehlschlag** | Zauber gilt als **Fehlschlag** (Hälfte bei save-basierten Zaubern) |
| **Krit. Fehlschlag** | Zauber gilt als **kritischer Fehlschlag** |

> ⭐ Das ist der entscheidende Unterschied: Spellstrike **ersetzt** den Spell-Attack-Roll durch den Strike-Roll. Der Magus trifft (oder nicht) mit seiner Waffe – und der Zauber folgt automatisch mit demselben Ergebnis.

### Spellstrike aufladen (Recharge)

Nach jedem Spellstrike ist der Container leer. Neu laden durch eine der folgenden Aktionen:

| Methode | Aktion |
|---------|--------|
| **Cantrip zaubern** | ◆◆ (normales Zaubern) |
| **Arcane Cascade eintreten** | ◆ (Stance-Aktion) |
| **Konflikt-Zauber wirken** | Jeder Spell der 1+ Aktion kostet lädt automatisch neu |

---

## 🌀 Arcane Cascade ◆

Nach Spellstrike oder einem Zauber-Cast kannst du als 1-Aktion in die Arcane Cascade Stance wechseln. Sie lädt den Spellstrike-Container neu **und** gewährt passive Vorteile.

- Stance verlässt sich bei Kampfbeginn oder wenn ein anderer Stance betreten wird
- Genaue Bonus abhängig von der gewählten **Hybrid Study**
- Allgemein: +2 Schaden auf Strikes während der Stance (Schadenstyp abhängig vom letzten Zauber oder Study)

---

## 📚 Hybrid Studies (Wahl bei Level 1)

Die Hybrid Study ist die Spezialisierung des Magus. Sie bestimmt Playstyle, bevorzugte Waffen und Arcane-Cascade-Bonus.

---

### 🔩 Inexorable Iron

**Thema**: Zweihandspezialist, unerbittlicher Schlächter

| | Effekt |
|-|--------|
| **Arcane Cascade** | Wenn du die Stance betrittst oder den Stance hältst und einen Strike machst: +2 Schaden (kann mit Bludgeoning/Slashing/Piercing übereinstimmen je nach Waffe). Zusätzlich: nächste Strike nach Spellstrike bekommt +INT-Modifier Schaden. |
| **Waffenfokus** | Empfohlen: d10–d12 Zweihandwaffen (Greatsword, Maul, Glaive) |
| **Key Ability** | STR bevorzugt |

**Gut für**: Spieler die maximalen Burst-Schaden mit Zwei-Hand-Waffen wollen. Die INT-Bonus-Schaden-Reaktion nach Spellstrike macht jeden Folge-Strike brutal.

---

### 👤 Laughing Shadow

**Thema**: Mobiler Duellant, Teleportation, DEX-Magus

| | Effekt |
|-|--------|
| **Arcane Cascade** | +5 Fuß Bewegungsgeschwindigkeit. Wenn du eine Waffe mit Finesse oder Agile trägst: +1 Statusbonus auf Reflex Saves. |
| **Spellstrike-Bonus** | Kannst während Spellstrike einen 5-Fuß-Step machen |
| **Waffenfokus** | Rapier, Shortsword, Finesse-Waffen |
| **Key Ability** | DEX + INT |

**Gut für**: DEX-Magus-Builds, Charaktere die mobil kämpfen und gegnerischen Angriffen ausweichen wollen. Synergiert gut mit Teleportations- und Bewegungszaubern.

---

### 🛡️ Sparkling Targe

**Thema**: Defensiver Magus, Schild + Magie

| | Effekt |
|-|--------|
| **Arcane Cascade** | Wähle beim Eintreten einen Schadenstyp (z.B. Fire, Cold, Lightning). Du erhältst **Resistance 2** gegen diesen Typ. Skaliert auf Resistance 3 bei Level 7, 4 bei Level 15. |
| **Voraussetzung** | Ein Schild muss gehalten werden |
| **Waffenfokus** | Einhändige Waffen + Schild |
| **Key Ability** | STR oder DEX |

**Gut für**: Defensivere Builds, Frontliner die Treffer einstecken müssen. Resistance gegen häufige Elementarschäden macht den Magus robuster.

---

### 🏹 Sprawling Shot

**Thema**: Fernkampf-Magus, Druck aus der Distanz

| | Effekt |
|-|--------|
| **Arcane Cascade** | Gegner die du mit Spellstrike oder einem Zauber triffst bekommen **Off-Guard** bis zum Ende des nächsten Zuges (nur gegen dich). |
| **Spellstrike-Reichweite** | Spellstrike funktioniert mit Fernkampfwaffen (bis 30 Fuß) |
| **Waffenfokus** | Crossbow, shortbow, sling |
| **Key Ability** | DEX + INT |

**Gut für**: Spieler die nicht in Nahkampf gehen wollen. Off-Guard-Druck aus der Distanz gibt dem Magus und Verbündeten Vorteile.

---

### ✨ Starlit Span

**Thema**: Bogenschütze-Magus, Fernkampf-Spellstrike über Distanz

| | Effekt |
|-|--------|
| **Arcane Cascade** | +1 Statusbonus auf Angriffswürfe gegen Ziele in 30+ Fuß Distanz |
| **Spellstrike-Reichweite** | Spellstrike mit Fernkampfwaffe nutzt die volle Waffenreichweite (kein 30-Fuß-Limit) |
| **Waffenfokus** | Longbow, Crossbow |
| **Key Ability** | DEX + INT |

**Gut für**: Klassen-fantasie des arkanen Bogenschützen. Einzige Study die Spellstrike wirklich auf Distanz ohne Reichweitenbegrenzung ermöglicht.

---

### 🪄 Twisting Tree

**Thema**: Quarterstaff-Spezialist, Reichweite, Versatilität

| | Effekt |
|-|--------|
| **Arcane Cascade** | Dein Quarterstaff erhält **Reach** (verlängerte Reichweite um 5 Fuß) während du in der Stance bist |
| **Waffenfokus** | Quarterstaff (pflichtend – alle Fähigkeiten beziehen sich darauf) |
| **Key Ability** | STR oder DEX |

**Gut für**: Spieler die thematisch den klassischen „Zauberstab als Kampfstab"-Archetyp wollen. Reach-Stance ermöglicht Spellstrike von 10 Fuß Distanz – nützlich gegen Flächeneffekte.

---

## 📖 Zauberslots & Spellcasting

Magus ist ein **Prepared Caster** (wie Wizard) – Zauber werden täglich vorbereitet. Spell-Tradition: **Arcane**.

### Zauberslot-Progression

| Level | Cantrips | Rank 1 | Rank 2 | Rank 3 | Rank 4 | Rank 5 | Rank 6 |
|-------|----------|--------|--------|--------|--------|--------|--------|
| 1 | 5 | 1 | – | – | – | – | – |
| 2 | 5 | 2 | – | – | – | – | – |
| 3 | 5 | 2 | 1 | – | – | – | – |
| 4 | 5 | 2 | 2 | – | – | – | – |
| 5 | 5 | 2 | 2 | 1 | – | – | – |
| 6 | 5 | 2 | 2 | 2 | – | – | – |
| 7 | 5 | 2 | 2 | 2 | 1 | – | – |
| 8 | 5 | 2 | 2 | 2 | 2 | – | – |
| 9 | 5 | 2 | 2 | 2 | 2 | 1 | – |
| 10 | 5 | 2 | 2 | 2 | 2 | 2 | – |
| 11–12 | 5 | 2 | 2 | 2 | 2 | 2 | 1 |
| 13–20 | 5 | 2 | 2 | 2 | 2 | 2 | 2 |

> ⭐ Magus ist kein vollständiger Caster – er hat **weniger Slots** als Wizard. Jeder Slot ist wertvoll, die meisten werden für Spellstrike verwendet. Cantrips sind daher sehr wichtig als Schadensquelle.

### Gute Zauber für Spellstrike

| Zauber | Rank | Warum |
|--------|------|-------|
| **Gouging Claw** | Cantrip | Melee Touch + Bleed, perfekt für Spellstrike |
| **Produce Flame** | Cantrip | Melee oder Ranged Touch |
| **True Strike** | 1 | +1 Würfel auf nächsten Angriff – vor Spellstrike wirken! |
| **Shocking Grasp** / **Ignition** | 1 | Direkt-Schaden Melee Touch |
| **Force Barrage** | 1 | Automatischer Treffer – Spellstrike umgeht aber ohnehin Miss |
| **Haste** | 3 | Selbst-Buff: Extra Strike pro Runde |
| **Invisibility** | 2 | Positioning + Off-Guard für nächsten Spellstrike |
| **Mirror Image** | 2 | Defensiv-Buff |

> **Wichtig**: Für Spellstrike braucht der Zauber einen **Spell Attack Roll** oder einen Melee/Ranged Touch. Zauber die nur Saving Throws verlangen (z.B. Fireball) funktionieren erst mit dem Class Feat **Expansive Spellstrike**.

---

## 📈 Progression – Magus über alle Level

### Proficiency-Steigerungen

| Level | Verbesserung |
|-------|-------------|
| 5 | Weapons & Unarmed: **Expert** |
| 7 | Spells: **Expert** |
| 9 | Perception: **Expert**, Reflex: **Expert**, Will: **Expert** |
| 11 | Fortitude: **Master** |
| 13 | Weapons & Unarmed: **Master**, Light+Medium+Unarmored: **Expert** |
| 15 | Spells: **Master** |
| 17 | Fortitude: **Legendary**, Reflex: **Master**, Will: **Master** |
| 19 | Spells: **Legendary**, Armor: **Master** |

### Klassen-Features pro Level

| Level | Feature | Beschreibung |
|-------|---------|-------------|
| 1 | **Spellstrike** | Kern-Mechanik: Zauber in Strike laden und gleichzeitig ausliefern |
| 1 | **Arcane Cascade** | Stance nach Zaubern/Spellstrike: Recharge + passive Boni |
| 1 | **Hybrid Study** | Wähle eine der 6 Spezialisierungen – definiert Playstyle |
| 1 | **Spellbook** | Vorbereitetes Zauberbuch wie Wizard (beginnt mit 4 Zaubern Rank 1) |
| 1 | **Magus Feat** | +1 Class Feat |
| 2 | **Magus Feat** | +1 Class Feat |
| 2 | **Skill Feat** | +1 Skill Feat |
| 3 | **General Feat** | +1 General Feat |
| 3 | **Skill Increase** | Eine Fertigkeit um eine Stufe erhöhen |
| 4 | **Magus Feat** | +1 Class Feat |
| 4 | **Skill Feat** | +1 Skill Feat |
| 5 | **Ability Boosts** | +4 Attribut-Boosts |
| 5 | **Ancestry Feat** | +1 Ancestry Feat |
| 5 | **Weapon Expert** | Waffen steigen auf Expert |
| 5 | **Skill Increase** | +1 Skill Increase |
| 6 | **Magus Feat** | +1 Class Feat |
| 6 | **Skill Feat** | +1 Skill Feat |
| 7 | **Alertness** | Perception: Expert |
| 7 | **General Feat** | +1 General Feat |
| 7 | **Skill Increase** | +1 Skill Increase |
| 7 | **Spell Expert** | Arcane Spells auf Expert |
| 7 | **Studious Spells** | Zugang zu zusätzlichen Spells abhängig von Hybrid Study |
| 8 | **Magus Feat** | +1 Class Feat |
| 8 | **Skill Feat** | +1 Skill Feat |
| 9 | **Ancestry Feat** | +1 Ancestry Feat |
| 9 | **Reflex Expert + Will Expert** | Beide Saves auf Expert |
| 9 | **Skill Increase** | +1 Skill Increase |
| 10 | **Ability Boosts** | +4 Attribut-Boosts |
| 10 | **Magus Feat** | +1 Class Feat |
| 10 | **Skill Feat** | +1 Skill Feat |
| 11 | **Fortitude Master** | Fort auf Master |
| 11 | **General Feat** | +1 General Feat |
| 11 | **Skill Increase** | +1 Skill Increase |
| 12 | **Magus Feat** | +1 Class Feat |
| 12 | **Skill Feat** | +1 Skill Feat |
| 13 | **Ancestry Feat** | +1 Ancestry Feat |
| 13 | **Armor Expert** | Light+Medium+Unarmored auf Expert |
| 13 | **Skill Increase** | +1 Skill Increase |
| 13 | **Weapon Master** | Waffen auf Master |
| 14 | **Magus Feat** | +1 Class Feat |
| 14 | **Skill Feat** | +1 Skill Feat |
| 15 | **Ability Boosts** | +4 Attribut-Boosts |
| 15 | **General Feat** | +1 General Feat |
| 15 | **Skill Increase** | +1 Skill Increase |
| 15 | **Spell Master** | Arcane Spells auf Master |
| 16 | **Magus Feat** | +1 Class Feat |
| 16 | **Skill Feat** | +1 Skill Feat |
| 17 | **Ancestry Feat** | +1 Ancestry Feat |
| 17 | **Fort Legendary, Reflex Master, Will Master** | Alle Saves auf Top-Niveau |
| 17 | **Skill Increase** | +1 Skill Increase |
| 18 | **Magus Feat** | +1 Class Feat |
| 18 | **Skill Feat** | +1 Skill Feat |
| 19 | **Armor Master** | Rüstung auf Master |
| 19 | **General Feat** | +1 General Feat |
| 19 | **Skill Increase** | +1 Skill Increase |
| 19 | **Spell Legendary** | Arcane Spells auf Legendary |
| 20 | **Ability Boosts** | +4 Attribut-Boosts |
| 20 | **Magus Feat** | +1 Class Feat |
| 20 | **Skill Feat** | +1 Skill Feat |

---

## ⭐ Magus-Highlights auf einen Blick

| Level | Meilenstein |
|-------|------------|
| **1** | Spellstrike + Arcane Cascade – Build von L1 funktionsfähig |
| **5** | Weapon Expert – Trefferchance steigt deutlich |
| **7** | Studious Spells – Study-spezifische Bonus-Zauberslots |
| **9** | Expert Reflex + Will – defensive Stabilisierung |
| **13** | Weapon Master + Armor Expert – Magus ist nun ein vollständiger Frontliner |
| **15** | Spell Master – Zauber-DC und Spell Attack steigen |
| **17** | Alle Saves auf Master/Legendary – extrem robust |
| **19** | Spell Legendary + Armor Master – Peak-Performance |

---

## 🎓 Empfohlene Class Feats

| Level | Feat | Nutzen |
|-------|------|--------|
| 1 | **Spellstrike Cantrips** | Cantrips können als Spellstrike verwendet werden – wichtig für Recharge-Effizienz |
| 2 | **Shielded Magus** | Schild-Nutzung ohne Penalty (gut für Sparkling Targe) |
| 4 | **Expansive Spellstrike** | Alle Zauber (auch Save-basierte) können mit Spellstrike kombiniert werden |
| 6 | **Lunging Spellstrike** | +5 Fuß Reichweite bei Spellstrike |
| 8 | **Cascade Countermeasure** | Reaktion in Arcane Cascade: Counterzoubern |
| 10 | **Spellstrike Targets** | Spellstrike trifft mehrere Ziele |
| 12 | **Fused Staff** | Staff als Spellcasting-Fokus – mehr Zauberslots via Stab |

---

## 🆚 Magus im Vergleich

| Aspekt | Magus | Fighter | Wizard |
|--------|-------|---------|--------|
| **Hauptressource** | STR/DEX + INT + Spell Slots | Waffen-Proficiency | INT + Spell Slots |
| **Schaden** | Strike + Zauber-Burst | Viele Strikes, Crits | Zauber-Fläche/-Control |
| **Rüstung** | Medium | Alle bis Legendary | Light oder keine |
| **Waffen** | Simple + Martial | Alle bis Legendary | Simple only |
| **Zauber** | Arcane Prepared (Rank 6 max) | Keine | Arcane Prepared (Rank 10) |
| **Stärke** | Einzelziel-Burst | Konstanter Schaden | Kontrolle + Fläche |
| **Schwäche** | Resourcen-Management, Action-Economy | Magie-Resistenz | Melee-Gefährlichkeit |
| **Komplexität** | Hoch | Niedrig | Mittel-Hoch |

---

## 💡 Wichtige Spielhinweise

**Action-Economy:** Spellstrike kostet ◆◆. In einer Runde mit 3 Aktionen: Spellstrike (◆◆) + Arcane Cascade (◆) = Container neu laden, in Stance. Nächste Runde: Spellstrike (◆◆) + 1 freie Aktion (Move oder Strike ohne Zauber).

**Kontra Multiple Attacks:** Der zweite Angriff in einer Runde hat –5 Penalty. Spellstrike als einziger Angriff pro Runde ist oft besser als zwei normale Strikes.

**INT nicht vernachlässigen:** Spell Attack Roll und Spell DC kommen von INT. Niedrige INT = Zauber verpuffen häufig. Mindest-INT 18 beim Build empfohlen.

**Vorbereitungslogik:** Prepare 1–2 Support-Zauber (True Strike, Haste) + Reste Schaden-Zauber für Spellstrike. Zu viele verschiedene Zauber führen zu Entscheidungsparalyse.

---

## 🔗 Verwandte Themen

- [[1. 📋 Klassen - Übersicht]] – Alle Klassen im Vergleich
- [[1. 📊 Attribute & Level System]] – Ability Boosts, Proficiency-Tabellen
- [[🌀 Zauberschulen & Traditionen]] – Arcane Tradition im Detail
- [[8. 🎯 Dedication Feats#Magus Dedication]] – Als Archetype für andere Klassen
- [[4. ✅ Erfolgsgrade]] – Spellstrike nutzt Strike-Erfolgsgrad für Zauber
- [[6. 📈 Proficiency-System]] – Warum zwei Proficiency-Quellen (Waffe + Zauber) die Komplexität erhöhen
