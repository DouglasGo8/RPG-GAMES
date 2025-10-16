# Diablo IV :: Sorcerer Build Path

Main Object:  Chain Lightning

## Claude Sonnet 4.5 AI Guide

---

## Class Sorcerer

- Level: 32
- Character Name: Satanaah
- Difficult Level: Hard

## Gem Classification

### Available Gems (In Stash)

| Gem Type         | Quantity | Weapon                        | Armor                  | Jewelry                          |
|------------------|----------|-------------------------------|------------------------|----------------------------------|
| Chipped Ruby     | 30       | +15 Overpower Damage          | +10 Strength           | +10.0 Fire Resistance            |
| Chipped Amethyst | 32       | +8.0 Damage Over Time         | +2.0% Barrier Gen      | +10.0 Shadow Resistance          |
| Chipped Diamond  | 30       | +10 Ultimate Damage           | +4 All Stats           | +2.0% All Resistance             |
| Chipped Emerald  | 44       | +12.0% Critical Strike Damage | +10 Dexterity          | +10.0% Poison Resist             |
| Chipped Sapphire | 34       | +9.0% Vulnerable Dmg          | +10 Willpower          | +10.0% Cold Resistance           |
| Chipped Topaz    | 31       | +10.0% Basic Damage           | +10 Intelligence       | +10.0% Lighting Resistance       |
| Chipped Skull    | 30       | +2 Life on Kill               | +4.0% Healing Received | +40 Armor                        |
| Sapphire         | 2        | +18.0% Vulnerable Dmg         | +20 Willpower          | +20.0% Cold Resistance           |
| Amethyst         | 2        | +16.0 Damage Over Time        | +4.0% Barrier Gen      | +20.0 Shadow Resistance          |
| Emerald          | 1        | +18.0% Vulnerable Dmg         | +20 Willpower          | +20.0% Cold Resistance           |
| Ruby             | 1        | +30.0% Overpower Dmg          | +20 Strength           | +20.0% Fire Resistance           |
| Diamond          | 2        | +20.0% Ultimate Dmg           | +7 All Stats           | +4.0% Resistance to All Elements |
|                  |          |                               |                        |                                  |

## Body Armor

```json
{
  "body_armor": [
    {
      "body": "Head",
      "armor_name": "Undying Adventurer's Helm",
      "class": "Legendary Helm",
      "power": 330,
      "armor": 53,
      "intelligence": 20,
      "maximum_life": 6,
      "life_per_secs": "6 per 5s",
      "gem_slots": {
        "total": 2,
        "slots": [
          {
            "name": "Chipped Topaz",
            "intelligence": "10"
          },
          {
            "name": "Chipped Topaz",
            "intelligence": "10"
          }
        ]
      },
      "legendary_power": {
        "name": "Unwavering",
        "effect": "When you cast a Skill, you heal for 1.1% life. Double this bonus while below 50% life"
      }
    },
    {
      "body": "Torso",
      "armor_name": "Bone Barrier",
      "class": "Rare Chest Armor",
      "power": 306,
      "armor": 85,
      "intelligence": 19,
      "life": "+6 Maximum Life",
      "gem_slots": {
        "total": 2,
        "slots": [
          {
            "name": "Chipped Topaz",
            "intelligence": "10"
          },
          {
            "name": "Chipped Topaz",
            "intelligence": "10"
          }
        ]
      }
    },
    {
      "body": "Hands",
      "armor_name": "Boneweave Gauntlets of Shared Misery",
      "class": "Legendary Gloves",
      "power": 335,
      "armor": 27,
      "intelligence": 21,
      "maximum_life": 7,
      "lucky_hit": null,
      "gem_slots": null,
      "legendary_power": {
        "name": "Imprinted: Lucky Hit",
        "effect": "When you hit a Crowd Controlled enemy, there is up to a 35% chance for that Crowd Control effect to spread to another unaffected enemy"
      }
    },
    {
      "body": "Legs",
      "armor_name": "Protecting Exceptional Leggings",
      "class": "Legendary Pants",
      "power": 368,
      "armor": 74,
      "intelligence": 23,
      "thorns": 4,
      "dodge_change": "2.1%",
      "gem_slots": {
        "total": 2,
        "slots": [
          {
            "name": "Topaz",
            "intelligence": "20"
          },
          {
            "name": "Chipped Topaz",
            "intelligence": "10"
          }
        ]
      },
      "legendary_power": {
        "effect": "When hit while not Healthy, you from a protective bubble that grants all Players inside immune. The bubble lasts for 2.5 seconds and can only form once every 90 seconds"
      }
    },
    {
      "body": "Feet",
      "armor_name": "Boneweave Treads of Slaughter",
      "class": "Legendary Boots",
      "power": 350,
      "armor": 28,
      "intelligence": 22,
      "maximum_life": 7,
      "movement_speed": "11.6%",
      "additional_effect": "Evade Grants 75% Movement Speed for 1.5 seconds",
      "gem_slots": null,
      "legendary_power": {
        "name": null,
        "effect": "You Gain 20% movement speed, lose this bonus for 3.5 seconds after taking a damage from a close enemy"
      }
    },
    {
      "body": "Two-Handed",
      "armor_name": "Focused Rough Staff of The Wise",
      "class": "Magic Staff",
      "power": 267,
      "armor": 49,
      "stats": {
        "damage_per_hit": "39-59",
        "attacks_per_second": "1.00",
        "damage_over_time": "10.6%"
      },
      "intelligence": 37,
      "critical_strike_damage": 36,
      "gem_slots": {
        "total": 2,
        "slots": [
          {
            "name": "Sapphire",
            "vulnerable_damage": "18"
          },
          {
            "name": "Sapphire",
            "vulnerable_damage": "18"
          }
        ]
      }
    }
  ]
}
```

## Runes (Stash)

```json
{
  "runes_stash": {
    "invocation": [
      {
        "name": "GAR",
        "type": "Magic Rune of Invocation",
        "effect": "+2.5% Crit per stack, up to 25%",
        "sockets": null,
        "status": null,
        "offering": 25,
        "quantity": 1
      },
      {
        "name": "TEC",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Barbarian's Earthquake",
        "sockets": null,
        "status": null,
        "offering": 50,
        "quantity": 2
      },
      {
        "name": "CEH",
        "type": "Magic Rune of Invocation",
        "effect": "Summon a Spirit Wolf Companion to attack enemies for 8s",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 1
      },
      {
        "name": "TEB",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Necromancer's Abhorrent Iron Maiden skill",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 1
      },
      {
        "name": "TON",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke Sorcerer's Meteorites dealing damage to enemies",
        "sockets": null,
        "status": null,
        "offering": 20,
        "quantity": 2
      }
    ],
    "ritual": [
      {
        "name": "MONI",
        "type": "Magic Rune of Ritual",
        "effect": "Gain 100 Offering, cast 2 mobility or macabre skills",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 1
      },
      {
        "name": "CEM",
        "type": "Magic Rune of Ritual",
        "effect": "Cast Evade",
        "offering": 75,
        "quantity": 2
      }
    ]
  }
}
```

## Rings and Amulets

```json
{
  "rings_and_amulets": [
    {
      "name": "Glyph Badge",
      "equipped": true,
      "rarity": "Rare Amulet",
      "item_power": 294,
      "items": {
        "resistance_to_all_elements": "11.1%"
      },
      "stats": {
        "movement_speed": "12.3%",
        "resource_cost_reduction": "2.2%"
      },
      "gem_slots": {
        "Chipped Skull": "40% Armor"
      }
    },
    {
      "name": "Smiting Ensorcelled Ring",
      "equipped": true,
      "rarity": "Legendary Ring",
      "item_power": 193,
      "items": {
        "resistance to all elements": "3.1%",
        "poison_resistance": "3.1%"
      },
      "stats": {
        "intelligence": 13,
        "maximum_life": 4,
        "damage": "5.5%"
      },
      "gem_slots": {
        "Skull": "80% Armor"
      },
      "legendary_power": {
        "name": "You have 13% increase Critical Strike, Change against enemies injured enemies",
        "effect": "While you are healthy, you gain 26% increased Crowd Control Duration"
      }
    },
    {
      "name": "Glamour Nexus",
      "equipped": true,
      "rarity": "Rare Ring",
      "item_power": 306,
      "items": {
        "resistance_to_all_elements": "4.0%",
        "poison_resistance": "4.0%"
      },
      "stats": {
        "intelligence": 20,
        "mana_on_kill": 1,
        "vulnerable_damage": "18.5%"
      },
      "gem_slots": {
        "Chipped Skull": "40% Armor"
      }
    }
  ]
}
```

## Stats & Material

- Life: 101
- Armor: 501
- Attack Power: 92
- Strength: 106
- Intelligence: 353
- Willpower: 107
- Dexterity: 106

## Legendary Items (Stash)

```json
  {
  "legendary_stash": [
    {
      "name": "RootFist Of Frozen Orbit",
      "type": "",
      "rarity": "Legendary",
      "item_power": 127,
      "stats": {
        "intelligence": 10,
        "maximum_life": 3
      },
      "damage": {
        "dps": 13,
        "damage_per_hit": "10-14",
        "overpower_damage": 6.2
      },
      "legendary_power": {
        "name": "Frozen Orb Enhancement",
        "effect": "+52% Frozen Orb Damage"
      },
      "gem_slots": 0,
      "notes": "First legendary drop - guardado para possível Frozen Orb build"
    },
    {
      "name": "Elder Shiv of Engulfing Flames",
      "type": "",
      "rarity": "Legendary",
      "item_power": 227,
      "stats": {
        "maximum_life": 5,
        "damage": "+5.0%",
        "vulnerable_damage": "+16.5"
      },
      "damage": {
        "dps": 19,
        "damage_per_hit": "13-19",
        "attacks per second": 1.20,
        "damage_to_close_enemies": "+4.7%"
      },
      "legendary_power": {
        "name": "Increased Burning damage to Enemies for each second",
        "effect": "Burning up to 45% after 5 seconds, additionally 10% increased burn damage that are not healthy"
      },
      "gem_slots": 0,
      "notes": ""
    },
    {
      "name": "Battle Caster's Ender Shiv",
      "type": "",
      "rarity": "Legendary",
      "item_power": 280,
      "stats": {
        "maximum_life": 6,
        "intelligence": 17,
        "vulnerable_damage": "+18.0%"
      },
      "damage": {
        "dps": 25,
        "damage_per_hit": "17-25",
        "attacks per second": 1.20,
        "damage_to_close_enemies": "+5.5%"
      },
      "legendary_power": {
        "name": "When you Conjuration Skills hit you have up to a 31% change to gain +1 Rank to your Conjuration skill for 12 seconds",
        "effect": "This can stack up to 10 times"
      },
      "gem_slots": 1,
      "notes": ""
    }
  ]
}

```

## Skill Tree

```json
{
  "skill_tree": {
    "basic": [
      {
        "name": "Spark",
        "rank": "1/5",
        "completed": false,
        "upgrades": [
          {
            "name": "Enhanced Spark",
            "completed": true
          }
        ]
      }
    ],
    "core": [
      {
        "name": "Chain Lightning",
        "rank": "5/5",
        "completed": true,
        "upgrades": [
          {
            "name": "Enhanced Chain Lightning",
            "completed": true
          },
          {
            "name": "Greater Chain Lightning",
            "completed": true
          }
        ]
      }
    ],
    "defensive": [
      {
        "name": "Teleport",
        "rank": "5/5",
        "completed": true,
        "upgrades": [
          {
            "name": "Enhanced Teleport",
            "completed": true
          },
          {
            "name": "Shimmering Teleport",
            "completed": true
          }
        ]
      },
      {
        "name": "Ice Armor",
        "rank": "5/5",
        "completed": true,
        "upgrades": [
          {
            "name": "Enhanced Ice Armor",
            "completed": true
          },
          {
            "name": "Mystical Ice Armor",
            "completed": true
          }
        ]
      }
    ],
    "passives": [
      {
        "name": "Devastation",
        "rank": "3/3",
        "completed": true
      },
      {
        "name": "Glass Canon",
        "rank": "3/3",
        "completed": true
      },
      {
        "name": "Elemental Attunement",
        "rank": "3/3",
        "completed": true
      },
      {
        "name": "Icy Veil",
        "rank": "2/3",
        "completed": false
      }
    ],
    "mastery": [
      {
        "name": "Ball Lightning",
        "rank": "5/5",
        "completed": true,
        "upgrades": [
          {
            "name": "Enhanced Ball Lightning",
            "completed": true
          },
          {
            "name": "Wizard's Ball Lightning",
            "completed": true
          }
        ]
      }
    ],
    "ultimate": [
      {
        "name": "Unstable Currents",
        "rank": "1/5",
        "completed": false,
        "upgrades": [
          {
            "name": "Prime Unstable Currents",
            "completed": true
          }
        ]
      }
    ]
  }
}
```

## Enchantments

```json
{
  "enchantments": {
    "slot_1": {
      "name": "Ball Lightning",
      "effect": "Casting Teleport automatically casts Ball Lightning"
    },
    "slot_2": {
      "name": "Ice Armor",
      "effect": "Upon getting hit, you automatically cast Ice Armor"
    }
  }
}
```

```json
{
  "chaos_perks": {
    "equipped": {
      "slot_1": {
        "name": "Accelerating Chaos",
        "rank": "2/10",
        "effect": "Damaging an enemy has up to a 10% chance to trigger a Chaotic Burst on the enemy, dealing 88 damage",
        "additional_effect": "Your Chaotic Burst tat hit an enemy reduce a random active Cooldown by 0.5 seconds",
        "next_rank": {
          "damage": 96
        }
      },
      "slot_2": {
        "name": "Erupting Chaos",
        "rank": "1/10",
        "effect": "Chaotic Chaos randomly erupt around you in combat, dealing 80 damage of your highest damage type",
        "additional_effect": "Your chaotic bursts additionally deal 100% of their initial damage over 4 seconds",
        "next_rank": {
          "damage": "88"
        }
      },
      "slot_3": {
        "name": "Power Siphon",
        "rank": "1/10",
        "effect": "Your Core Skills deal 50% increased damage, but also reduce your Maximum Current Resource by 20 by 6 seconds",
        "additional_effect": "This reduction stacks but does not refresh",
        "next_rank": {
          "damage": "55%"
        }
      },
      "prime_slot": {
        "name": null,
        "effect": "Empty - unlocks at higher level"
      }
    },
    "stash": [
      {
        "name": "Invigorating Attacks",
        "rank": "2/10",
        "effect": "Every 5 seconds, you ext Basic Skill generates an additional 55% of your Maximum Primary Resource when cast",
        "additional_effect": "Your Basic skills deal 30% reduced damage",
        "next_rank": {
          "resource_gain": "60%"
        }
      },
      {
        "name": "Explosive Combination",
        "rank": "1/10",
        "effect": "Casting a basic Skill increases your damage by 10% for 5s, stacking up to 3 times",
        "additional_effect": "",
        "next_rank": {
          "damage_increased": "11%"
        }
      }
    ]
  }
}
```

## Upgrade Potion
 
- Light Healing Potion

## Build Goals

### Short Term (Level 18-25) - COMPLETO

- [x] Enhanced Frost Nova → REMOVIDO (respec)
- [x] Max Ice Armor (5/5)
- [x] Reach Level 15 for Ball Lightning
- [x] Ball Lightning (Mastery)
- [x] Reach Level 25 for Unstable Currents

### Mid Term (Level 30-35) - EM PROGRESSO

- [x] Unstable Currents (Ultimate)
- [x] Prime Unstable Currents
- [x] Devastation 3/3
- [x] Glass Canon 3/3
- [x] Elemental Attunement 3/3 ⭐
- [x] Icy Veil 2/3 ⭐
- [x] Reach Level 30 ⭐
- [x] Enchantment Slot 2 (Ice Armor) ⭐
- [ ] Icy Veil 3/3 (Level 33)
- [ ] Farm useful Aspects
- [ ] Consider Veteran difficulty

### Long Term (Endgame)

- [ ] Farm Legendary items (Raiment of the Infinite, Shako)
- [ ] Optimize Paragon Boards (Level 50+)
- [ ] Perfect Aspects setup
- [ ] Veteran/Nightmare difficulty

## Gear Progression Log

### Update - Level 32

**Total Intelligence:** 353

**Major Changes:**

- Difficulty: Normal → Hard
- Head: Undying Adventurer's Helm (Legendary - heal on cast)
- Weapon: Focused Rough Staff (+36% Crit base, +60% total Crit Damage)
- Skills: Removed Frost Nova, added Glass Canon 3/3
- Life: 101 (sustained by Undying power)
- Armor: 501

**Damage Multipliers:**

- Devastation: +9%
- Glass Canon: +18%
- Elemental Attunement: +15% (close), +10% (distant)
- Power Siphon: +50%
- Vulnerable: +37% (weapon +18% + ring +18.5%) ⭐ ATUALIZAR!
- Crit Damage: +60%
- Crit Chance: +13% (vs injured)
- Attack Speed: +25% (Prime only) ⭐ ATUALIZAR! (perdeu ring +3.5%)
- Movement Speed: +43.9% (amulet + boots + legendary) ⭐ ADICIONAR!

**Defense Layers:**
- Ice Armor 5/5 (Manual + Auto-Enchantment)
- Icy Veil 2/3 (+16% Barrier duration)
- Undying Helm (1.1% heal per cast, 2.2% below 50%)
- Protecting Bubble (2.5s immunity, 90s CD)
- Aspect of Control (35% CC spread)
- 501 Armor
- 2.1% Dodge Chance
- 43.9% Movement Speed
