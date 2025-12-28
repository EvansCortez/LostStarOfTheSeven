# 🎮 Lost Star of the Seven

**Text-Based RPG | Python Prototype → Java (OOP Refactor)**
*A nameless protagonist awakens in Hongcho with no memories, drawn into a war against the Abyss threatening all seven nations.*

![Status](https://img.shields.io/badge/Status-In%20Development-brightgreen)
![Python](https://img.shields.io/badge/Python-Prototype-blue)
![Java](https://img.shields.io/badge/Java-SE%20Refactor-orange)
![Genre](https://img.shields.io/badge/Genre-Text%20RPG-purple)

---

## 📌 Overview

**Lost Star of the Seven** is a **console-based, turn-based RPG** focused on narrative, exploration, and elemental combat.
The project is developed in **Python** as a rapid prototype, then **refactored into Java** using object-oriented design for a Software Engineering course.

**Core Gameplay Loop:**
**Explore → Fight → Choose → Level Up**

---

## 🌍 World & Nations

Seven nations stand divided as the **Abyss** spreads through dimensional rifts.

| Nation            | Inspiration | Key Traits              | Story Role    |
| ----------------- | ----------- | ----------------------- | ------------- |
| **Hongcho**       | Korea       | Frontline defenders     | **Chapter 1** |
| **Xuening**       | China       | Ancient magic, scholars | Chapter 2+    |
| **Sakurmika**     | Japan       | Island warriors         | Chapter 3+    |
| **Sandovalla**    | Scandinavia | Frozen raiders          | Chapter 4+    |
| **Elysium**       | Greece      | Lost ruins, myths       | Chapter 5+    |
| **Gian Minh**     | Vietnam     | Jungle warfare          | Chapter 6+    |
| **Federal Union** | USA / EU    | Advanced technology     | Chapter 7+    |

---

## ⚔️ Element System

Elemental interactions influence combat outcomes.

| Element      | Strong Against  | Weak Against  |
| ------------ | --------------- | ------------- |
| **Quantum**  | Havoc, Spectrum | Water, Ice    |
| **Water**    | Fire, Ice       | Wind, Quantum |
| **Fire**     | Ice, Wind       | Water         |
| **Wind**     | Water, Fire     | Ice           |
| **Ice**      | Wind            | Fire, Quantum |
| **Havoc**    | Quantum         | Spectrum      |
| **Spectrum** | Ice             | Havoc         |

**Damage Rules**

* Advantage: **+50% damage**
* Disadvantage: **−50% damage**

> The player begins with **no element**, which is revealed later through story progression.

---

## 👥 Characters

### Protagonist

* **Player** – Unknown origin, awakens near Hongcho’s Great Gate with no memories.

### Hongcho Allies

* **Jungmin** – Frontline warrior who finds the player
* **Seowon** – Temple healer and spiritual guide
* **Youngseo** – Strategist coordinating Hongcho’s defense

### Future Allies

* **Kazumi** (Sakurmika) – Swordmaster
* **Fu Yibao** (Xuening) – Mage scholar
* **Suren** (Xuening) – Military commander
* **Jiahao** (Xuening) – Engineer
* **Thomas** (Federal Union) – Tech agent

---

## 📖 Story Premise

The player awakens outside **Hongcho’s Great Gate** as war horns echo through the city.
Abyss creatures emerge from dimensional rifts, overwhelming the nation’s defenses.

> *“Ancient seals are breaking. We need every fighter.”* — Jungmin

As the war escalates, the player begins to feel a strange connection to the Abyss—hinting at a forgotten past.

**Main Quest Path:**
**Defend Hongcho → Unite the Seven Nations → Seal the Abyss → Discover the Truth**

---

## 🗺️ Chapter 1: Hongcho Map

```
     [Temple] (Seowon)
        ↑
[Barracks] ← [Square] (Youngseo) → [Market]
     ↑              ↓
[Gate] ← [Abyss Rift] (Boss)
(Jungmin)    (Final Battle)
```

**Key Locations**

1. **Great Gate** – Starting point
2. **Central Square** – First combat encounter
3. **Barracks** – Weapon acquisition
4. **Temple** – Healing and lore
5. **Abyss Rift** – Chapter 1 boss fight

---

## ⚙️ Game Systems

* **Player Stats:** `HP(100) | ATK(10) | DEF(5) | Element(None)`
* **Combat:** Turn-based (Attack / Item / Run)
* **Inventory:** Potions, weapons, nation emblems
* **Progression:** Level-ups, stat growth, story choices

---

## 🛠️ Development Roadmap

```
Phase 1 – Python Prototype (Weeks 1–2)
├── Player, Enemy, Room classes
├── Hongcho map & navigation
├── Basic combat system
└── Chapter 1 completion

Phase 2 – Java Refactor (Weeks 3–4)
├── OOP redesign (Inheritance & Polymorphism)
├── HashMap-based world structure
├── JUnit testing
└── Save/Load system

Phase 3 – Expansion & Polish
├── Elemental combat modifiers
├── Dialogue trees & branching choices
└── Multiple endings
```

---

## 📁 Repository Structure

```
LostStarOfTheSeven/
├── README.md
├── DESIGN.md
├── python-prototype/
│   ├── player.py
│   ├── enemy.py
│   ├── rooms.py
│   └── main.py
├── java-version/
│   ├── src/
│   ├── tests/
│   └── docs/
└── assets/
```

---

## 🚀 Running the Python Prototype

```bash
git clone https://github.com/EvansCortez/LostStarOfTheSeven.git
cd python-prototype
python main.py
```
