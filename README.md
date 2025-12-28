# Lost Star of the Seven - **GitHub README.md**

```markdown
# 🎮 Lost Star of the Seven

**Text-based RPG (Console: Python → Java)**  
*A nameless protagonist awakens in Hongcho with no memories, drawn into a war against the Abyss threatening all seven nations.*

[![Python](https://img.shields.io/badge/Python-Prototype-blue)](https://www.python.org/)
[![Java](https://img.shields.io/badge/Java-SE%20Class-orange)](https://www.java.com/)
[![GitHub](https://img.shields.io/badge/Status-In%20Development-brightgreen)](https://github.com/)

---

## 📋 Game Overview

**Title:** Lost Star of the Seven  
**Type:** Text-based RPG (console, Python prototype → Java production)  
**Genre:** Turn-based RPG with elemental combat  
**Platform:** Terminal/Console  
**Core Loop:** Explore → Fight → Choose → Level Up  

**Core Idea:**  
A nameless protagonist wakes up in Hongcho with no memories and becomes involved in a war against the Abyss, a threat that could engulf all seven nations.

---

## 🌍 World & Nations

| Nation | Inspiration | Key Traits | Chapter Role |
|--------|-------------|------------|--------------|
| **Xuening** | China | Vast empire, ancient magic | Chapter 2+ ally |
| **Sakurmika** | Japan | Island warriors | Chapter 2+ ally |
| **Hongcho** | Korea | **Frontline nation** | **Chapter 1** |
| **Sandovalla** | Scandinavia | Frozen warriors | Chapter 3+ |
| **Elysium** | Greece | Ancient ruins | Chapter 4+ |
| **Gian Minh** | Vietnam | Jungle guerrillas | Chapter 3+ |
| **Federal Union** | USA/EU | Modern tech | Chapter 2+ |

---

## ⚔️ Elements System

| Element | Strengths | Weaknesses |
|---------|-----------|------------|
| **Quantum** | Havoc, Spectrum | Water, Ice |
| **Water** | Fire, Ice | Wind, Quantum |
| **Fire** | Ice, Wind | Water |
| **Wind** | Water, Fire | Fire, Ice |
| **Ice** | Wind | Fire, Quantum |
| **Havoc** | Quantum | Spectrum |
| **Spectrum** | Ice | Havoc |

**Rule:** Strength = +50% damage, Weakness = -50% damage

---

## 👥 Main Characters

**Player (Protagonist)** – Unknown origin, wakes in Hongcho  

**Hongcho Allies:**
- **Jungmin** – Warrior who finds player at gate  
- **Seowon** – Healer at temple  
- **Youngseo** – Strategist at central square  

**Future Allies:**
- **Kazumi** (Sakurmika) – Swordmaster  
- **Fu Yibao** (Xuening) – Mage scholar  
- **Suren** (Xuening) – Commander  
- **Jiahao** (Xuening) – Engineer  
- **Thomas** (Federal Union) – Tech agent

---

## 📖 Lore

Player wakes outside **Hongcho's Great Gate** hearing war horns.  
**Hongcho** faces invasion from **Abyss monsters** emerging from rifts.  
**Jungmin** finds player: "Ancient seals are breaking. We need every fighter."  
Player feels strange connection to the battle, hinting at forgotten past.

**Main Quest:** Save Hongcho → Unite nations → Seal Abyss → Discover identity

---

## 🗺️ Chapter 1 Map: Hongcho

```
     [Temple] (Seowon)
        ↑
[Barracks] ← [Square] (Youngseo) → [Market]
     ↑              ↓
[Gate] ← [Abyss Rift] (Boss)
(Jungmin)    (Final Battle)
```

**Locations:**
1. **Great Gate** – Start, meet Jungmin  
2. **Central Square** – First fight, meet Youngseo  
3. **Barracks** – Get weapon  
4. **Temple** – Heal, lore  
5. **Abyss Rift** – Final battle

---

## ⚙️ Game Systems

**Player Stats:** `HP(100) | ATK(10) | DEF(5) | Element(None)`  
**Combat:** Attack / Item / Run  
**Inventory:** Potions, weapons, nation emblems  

---

## 🛠️ Development Plan

```
Phase 1 (Week 1-2): Python Prototype
├── Player class + basic stats
├── 5 Hongcho rooms
├── Simple combat (attack/run)
└── Win Chapter 1

Phase 2 (Week 3-4): Java Refactor (SE Class)
├── OOP: Player, Enemy, Room classes
├── HashMap for world data
├── JUnit tests
├── Save/Load system

Phase 3: Polish + Elements
├── Elemental damage system
├── Character dialogue trees
└── Multiple endings for Ch1
```

---

## 📁 Repository Structure

```
LostStarOfTheSeven/
├── README.md                 # This file
├── DESIGN.md                # Full design doc
├── python-prototype/        # Week 1-2 MVP
│   ├── player.py
│   ├── rooms.py
│   └── main.py
├── java-version/            # SE class refactor
│   ├── src/
│   ├── tests/
│   └── docs/
└── assets/                  # Design images, maps
```

---

## 🚀 Quick Start (Python Prototype)

```
git clone https://github.com/EvansCortez/LostStarOfTheSeven.git
cd python-prototype
python main.py
```

---

**✨ Software Engineering Portfolio Project**  
*Perfect for OOP, Design Patterns, Testing, Version Control classes*

---
**Professional, complete, and ready to impress professors / recruiters!** 

Next: Create `python-prototype/main.py` starter code?
