# Diablo IV :: Sorcerer Build Path

Main Object: Chain Lightning

## Claude Sonnet 4.5 AI Guide

---

## Class Sorcerer

```json
{
  "level": "Paragon 116",
  "difficulty": "Torment 1",
  "character_name": "Satanaah"
}
```

## Stats & Materials

- Attack Power: 2.776
- Armor: 1.322
- Life: 2.752
- Strength: 249
- Intelligence: 1.336
- Willpower: 351
- Dexterity: 313

## Gem Classification

### Available Gems (In Stash)

| Gem Type       | Quantity | Weapon                     | Armor                   | Jewelry                          |
|----------------|----------|----------------------------|-------------------------|----------------------------------|
| Royal Amethyst | 5        | +32.0% Damage Over Time    | +8.0 Barrier Generation | +40.0% Shadow Resistance         |
| Royal Emerald  | 5        | +48.0% Critical Strike Dmg | +40 Dexterity           | +40.0% Poison Resistance         |
| Royal Ruby     | 5        | +60.0% Overpower Dmg       | +40 Strength            | +40.0% Fire Resistance           |
| Royal Diamond  | 6        | +40.0% Ultimate Dmg        | +13 All Stats           | +8.0% Resistance to All Elements |
| Royal Topaz    | 1        | +40.0% Basic Dmg           | +40 Intelligence        | +40.0% Lightning Resistance      |
| Royal Skull    | 3        | +16 Life On Kill           | +10.0 Healing Received  | +160.0% Armor                    |

## Runes (Stash)

```json
{
  "runes_stash": {
    "invocation": [
      {
        "name": "KRY",
        "type": "Magic Rune of Invocation",
        "effect": "Requires 300 Offering, Invokes the Spiritborn's Vortex Skill, dealing damage and Pulling in enemies",
        "sockets": null,
        "status": null,
        "offering": 300,
        "quantity": 1
      },
      {
        "name": "LAC",
        "type": "Magic Rune of Invocation",
        "effect": "Requires 400 Offering, Invokes the Barbarian's Challenging Shout Skill, tauting enemies and reducing your damage taken for 3 seconds",
        "sockets": null,
        "status": null,
        "offering": 400,
        "quantity": 1
      },
      {
        "name": "QUE",
        "type": "Magic Rune of Invocation",
        "effect": "Requires 300 Offering, Invoke the Druid's Earth Bulwark Skill for 3 second, granting yourself a Barrier",
        "sockets": null,
        "status": null,
        "offering": 300,
        "quantity": 1
      },
      {
        "name": "QUA",
        "type": "Magic Rune of Invocation",
        "effect": "Gain 10% Movement Speed for 5 seconds, up to 50%",
        "sockets": null,
        "status": null,
        "offering": 50,
        "quantity": 1
      },
      {
        "name": "LUM",
        "type": "Magic Rune of Invocation",
        "effect": "Restore 3.5 Primary Resource",
        "sockets": null,
        "status": null,
        "offering": 5,
        "quantity": 4
      },
      {
        "name": "GAR",
        "type": "Magic Rune of Invocation",
        "effect": "+2.5% Crit per stack, up to 25%",
        "sockets": null,
        "status": null,
        "offering": 25,
        "quantity": 8
      },
      {
        "name": "TEC",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Barbarian's Earthquake",
        "sockets": null,
        "status": null,
        "offering": 50,
        "quantity": 3
      },
      {
        "name": "CEH",
        "type": "Magic Rune of Invocation",
        "effect": "Summon a Spirit Wolf Companion to attack enemies for 8s",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 6
      },
      {
        "name": "TEB",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Necromancer's Abhorrent Iron Maiden skill",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 5
      },
      {
        "name": "TON",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke Sorcerer's Meteorites dealing damage to enemies",
        "sockets": null,
        "status": null,
        "offering": 20,
        "quantity": 5
      },
      {
        "name": "TUN",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Rogue's Stun Grenades, Stunning and dealing damage to enemies",
        "sockets": null,
        "status": null,
        "offering": 20,
        "quantity": 6
      },
      {
        "name": "TAL",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Spiritborn's Pestilent Swarm, dealing damage to enemies",
        "sockets": null,
        "status": null,
        "offering": 30,
        "quantity": 5
      },
      {
        "name": "WAT",
        "type": "Magic Rune of Invocation",
        "effect": "Invoke the Necromancer's Horrid Decrepify Skill, slowing enenimes reducing their damage, and letting you execute them",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 4
      }
    ],
    "ritual": [
      {
        "name": "FEO",
        "type": "Magic Rune of Ritual",
        "effect": "Gain 1000 Offering, become Injured or Crowd Controlled",
        "sockets": null,
        "status": null,
        "offering": 1000,
        "quantity": 1
      },
      {
        "name": "NOC",
        "type": "Magic Rune of Ritual",
        "effect": "Gain 5 Offering, Inflict a Crowd Control, gain double offering if it isn't a Slow or Chill",
        "sockets": null,
        "status": null,
        "offering": 5,
        "quantity": 1
      },
      {
        "name": "MONI",
        "type": "Magic Rune of Ritual",
        "effect": "Gain 100 Offering, cast 2 mobility or macabre skills",
        "sockets": null,
        "status": null,
        "offering": 100,
        "quantity": 7
      },
      {
        "name": "CEM",
        "type": "Magic Rune of Ritual",
        "effect": "Cast Evade",
        "offering": 75,
        "quantity": 5
      },
      {
        "name": "CIR",
        "type": "Magic Rune of Ritual",
        "effect": "Cast 5 skills then become exhausted for 3 seconds",
        "offering": 300,
        "quantity": 6
      },
      {
        "name": "YAX",
        "type": "Magic Rune of Ritual",
        "effect": "Drink a Healing Potion",
        "offering": 200,
        "quantity": 4
      },
      {
        "name": "ZAN",
        "type": "Magic Rune of Ritual",
        "effect": "Cast an Ultimate Skill",
        "offering": 150,
        "quantity": 9
      },
      {
        "name": "QUA",
        "type": "Magic Rune of Invocation",
        "effect": "Gain 10% Movement Speed for 5 seconds, up to 50%",
        "offering": 50,
        "quantity": 2
      }
    ]
  }
}
```

`## Body Armor`

```json
{
  "body_armor": [
    {
      "body": "Head",
      "armor_name": "Exceptional Helm of Concentration",
      "class": "Legendary Helm",
      "power": 750,
      "armor": 120,
      "stats": {
        "intelligence": 90,
        "maximum_life": 266,
        "armor": 157
      },
      "runes": {
        "CenTon": "Acrobatic Inferno",
        "Ability": "Cast Evade",
        "Power": "Invoke the Sorcerer's Meteorites, dealing damage to enemies"
      },
      "tempering": "+9.0% Total Armor",
      "gem_slots": null,
      "imprinted_aspect": {
        "effect": "Casting a Conjuration Skill grants you 17.0% Damage Reduction for 5 seconds"
      }
    },
    {
      "body": "Torso",
      "armor_name": "Everliving Sovereign Mail",
      "class": "Legendary Chest Armor",
      "power": 750,
      "armor": 210,
      "stats": {
        "intelligence": 99,
        "maximum_life": 261,
        "life_per_5_seconds": 193
      },
      "tempering": "+39 Maximum Life",
      "gem_slots": null,
      "runes": {
        "CirCeh": "Lethargic Absolute Zero",
        "Ability": "Cast 5 Skills then become exhausted for 3 seconds. (1 time)",
        "Power": "Invoke the Sorcerer's Mystical Frost Nova Skill, inflicting Freeze and Vulnerable onto enemies"
      },
      "imprinted_aspect": {
        "effect": "You take 25% less damage from Crowd Controlled or Vulnerable enemies"
      }
    },
    {
      "body": "Hands",
      "armor_name": "Wardlord Gauntlets of Elemental Constellation",
      "class": "Legendary Gloves",
      "power": 750,
      "armor": 60,
      "stats": {
        "intelligence": 92,
        "armor": 159,
        "damage_over_time": "36.0%"
      },
      "tempering": "95.0% Crackling Energy Damage",
      "gem_slots": null,
      "imprinted_aspect": {
        "effect": "Casting Pyromancy, Shock or Frost Skill conjures a matching Elemental Dagger around you that pierces through enemies dealing 1,490 damage after 3 seconds. The damage increases by 100% per matching Elemental Skill you cast."
      }
    },
    {
      "body": "Legs",
      "armor_name": "IceHeart Brais",
      "class": "Unique Pants",
      "power": 750,
      "armor": 150,
      "masterwork": "6/8",
      "stats": {
        "maximum_life": 574,
        "frost_nova_size": "85.0%",
        "cold_resistance": "78.8%",
        "shatters_damage_echo": "5.6%"
      },
      "tempering": null,
      "gem_slots": {
        "total": 2,
        "slots": [
          {
            "name": "Royal Topaz",
            "intelligence": 40
          },
          {
            "name": "Flawless Topaz",
            "intelligence": 30
          }
        ]
      },
      "imprint_aspect": {
        "effect": "Enemies that die while Frozen have a 32% chance to unleash a Frost Nova"
      }
    },
    {
      "body": "Feet",
      "armor_name": "Penitent Greaves",
      "class": "Unique Boots",
      "power": 709,
      "armor": 57,
      "masterwork": "6/8",
      "stats": {
        "evade_grants": {
          "item_1": "+75% Movement Speed for 2.0 seconds",
          "item_2": " Unhindered for 2.0"
        },
        "movement_speed": "+16.5%",
        "critical_strike_chance_against_chilled_enemies": "5.2%",
        "chill_slow_potency": "+58.1%",
        "cold_resistance": "51.2%"
      },
      "tempering": null,
      "gem_slots": null,
      "imprinted_aspect": {
        "effect": "You leave behind a trail of frost that chills enemies. You deal 15% more damage to chilled enemies"
      }
    },
    {
      "body": "Two-Handed",
      "armor_name": "SoulBurst Staff of Abundant Energy",
      "class": "Legendary Staff",
      "power": 750,
      "damage_per_second": 524,
      "stats": {
        "damage_per_hit": "419-629",
        "attacks_per_second": "1.00",
        "damage_over_time": "66.0%",
        "intelligence": 194,
        "maximum_life": 522,
        "damage": "60.0%"
      },
      "tempering": "70.0% Lightning damage",
      "imprinted_aspect": {
        "effect": "Crackling Energy has a 92% chance to deal 40% increased damage and chain to an additional enemy"
      },
      "gem_slots": {
        "total": 2,
        "slots": [
          {
            "name": "Royal Sapphire",
            "vulnerable_damage": 36
          },
          {
            "name": "Flawless Sapphire",
            "vulnerable_damage": 24
          }
        ]
      }
    }
  ]
}
```

## Rings and Amulets

```json
{
  "rings_and_amulets": {
    "rings": [
      {
        "name": "Elementalist's Pareidolic Ring",
        "equipped": true,
        "rarity": "Legendary Ring",
        "item_power": 750,
        "stats": {
          "resistance_to_all_elements": "10.0%",
          "shadow_resistance": "10.0%",
          "intelligence": 98,
          "maximum_life": 261,
          "poison_resistance": "36.6%"
        },
        "tempering": "61.0% Lightning Damage",
        "gem_slots": {
          "Royal Skull": "160 Armor"
        },
        "imprinted_aspect": {
          "effect": "Core Skills cast at or above 100 Mana gain 27.0% increased Strike Chance"
        }
      },
      {
        "name": "Mother's Embrace",
        "equipped": true,
        "rarity": "Unique Ring",
        "item_power": 476,
        "masterwork": "7/8",
        "stats": {
          "resistance_to_all_elements": "5.5%",
          "shadow_resistance": "5.5%",
          "all_stats": 56,
          "attack_speed": "14.0%",
          "critical_strike_chance": "5.8%",
          "lucky_hit_chance": "5.8%"
        },
        "tempering": null,
        "gem_slots": {
          "Royal Skull": "160 Armor"
        },
        "legendary_power": {
          "effect": "If a Core Skill hits 4 or more enemies, 59% of the Resource cost is refunded"
        }
      }
    ],
    "amulets": [
      {
        "name": "Lightning Rod All-Being Chain",
        "equipped": true,
        "rarity": "Legendary Amulet",
        "item_power": 750,
        "stats": {
          "resistance_to_all_elements": "25.0%",
          "intelligence": "+11.1%",
          "maximum_life": 272,
          "lucky_hit_chance": "7.0%"
        },
        "tempering": "73.0% Shock Critical Strike Damage",
        "imprinted_aspect": {
          "effect": "Chain Lightning has a 25% chance to deal 93% increased damage, This chance is double against bosses or crowd controlled enemies and prefers them as targets"
        },
        "gem_slots": {
          "Royal Skull": "160 Armor"
        }
      }
    ]
  }
}
```

## Legendary Items (Stash)

```json
{
  "legendary_stash": null
}
```

## Skill Tree

```json
{
  "skill_tree": {
    "basic": {
      "skills": [
        {
          "name": "Spark",
          "rank": "5/5",
          "completed": true,
          "upgrades": [
            {
              "name": "Enhanced Spark",
              "completed": true
            }
          ]
        }
      ],
      "passives": null
    },
    "core": {
      "skills": [
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
      "passives": [
        {
          "name": "Devastation",
          "rank": "3/3",
          "completed": true
        },
        {
          "name": "Elemental Dominance",
          "rank": "2/3",
          "completed": false
        }
      ]
    },
    "defensive": {
      "skills": [
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
          "name": "Elemental Attunement",
          "rank": "3/3",
          "completed": true
        },
        {
          "name": "Glass Canon",
          "rank": "3/3",
          "completed": true
        }
      ]
    },
    "conjuration": {
      "passives": [
        {
          "name": "Align the Elements",
          "rank": "3/3",
          "completed": true
        },
        {
          "name": "Protection",
          "rank": "3/3",
          "completed": false
        }
      ]
    },
    "mastery": {
      "skills": [
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
      "passives": [
        {
          "name": "Icy Veil",
          "rank": "3/3",
          "completed": true
        },
        {
          "name": "Static Discharge",
          "rank": "3/3",
          "completed": true
        }
      ]
    },
    "ultimate": {
      "skills": [
        {
          "name": "Unstable Currents",
          "rank": "5/5",
          "completed": true,
          "upgrades": [
            {
              "name": "Prime Unstable Currents",
              "completed": true
            },
            {
              "name": "Supreme Unstable Currents",
              "completed": true
            }
          ]
        }
      ],
      "passives": [
        {
          "name": "Conduction",
          "rank": "3/3",
          "completed": true
        },
        {
          "name": "Coursing Currents",
          "rank": "3/3",
          "completed": true
        }
      ]
    },
    "key_passives": {
      "key_1": {
        "name": "vry's mastery",
        "active": true
      },
      "key_2": {
        "name": "overflowing energy",
        "active": false
      },
      "key_3": {
        "name": "enlightenment",
        "active": false
      },
      "key_4": {
        "name": "combustion",
        "active": false
      },
      "key_5": {
        "name": "esus's ferocity",
        "active": false
      },
      "key_6": {
        "name": "avalanche",
        "active": false
      },
      "key_7": {
        "name": "shatter",
        "active": false
      }
    }
  }
}
```

## Enchantments

```json
{
  "enchantments": {
    "slot_1": {
      "name": "Ball Lightning Enchantment",
      "effect": "Casting Teleport automatically casts Ball Lightning"
    },
    "slot_2": {
      "name": "Ice Armor Enchantment",
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
        "rank": "4/10",
        "effect": "Damaging an enemy has up to a 10% chance to trigger a Chaotic Burst on the enemy, dealing 88 damage",
        "additional_effect": "Your Chaotic Burst tat hit an enemy reduce a random active Cooldown by 0.5 seconds",
        "next_rank": {
          "damage": 96
        }
      },
      "slot_2": {
        "name": "Unstable Power",
        "rank": "3/10",
        "effect": "Chaotic magics erupt from your basic skills, making them guaranteed to Critically Strike and Overpower for 55% increased damage, but the power is unstable, giving them a 3 seconds cooldown",
        "additional_effect": "",
        "next_rank": {
          "damage_increased": "60%"
        }
      },
      "slot_3": {
        "name": "Explosive Combination",
        "rank": "3/10",
        "effect": "Casting a basic Skill increases your damage by 10% for 5s, stacking up to 3 times",
        "additional_effect": "",
        "next_rank": {
          "damage_increased": "11%"
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
        "rank": "3/10",
        "effect": "Every 5 seconds, you ext Basic Skill generates an additional 55% of your Maximum Primary Resource when cast",
        "additional_effect": "Your Basic skills deal 30% reduced damage",
        "next_rank": {
          "resource_gain": "60%"
        }
      },
      {
        "name": "Power Siphon",
        "rank": "1/10",
        "effect": "Your Core Skills deal 50% increased damage, but also reduce your Maximum Current Resource by 20 by 6 seconds",
        "additional_effect": "This reduction stacks but does not refresh",
        "next_rank": {
          "damage": "55%"
        }
      },
      {
        "name": "Erupting Chaos",
        "rank": "1/10",
        "effect": "Chaotic Chaos randomly erupt around you in combat, dealing 80 damage of your highest damage type",
        "additional_effect": "Your chaotic bursts additionally deal 100% of their initial damage over 4 seconds",
        "next_rank": {
          "damage": "88"
        }
      },
      {
        "name": "Alternating Alterations",
        "rank": "1/10",
        "effect": "Casting a Core skill empowers you next Non-Channeled cast of a different Core Skill, refunding 50% of its resource cost and increasing its damage by 40%",
        "additional_effect": "",
        "next_rank": {
          "damage_increased": "42%"
        }
      },
      {
        "name": "Advanced Techniques",
        "rank": "1/10",
        "effect": "Your base Core Skill ranks increased their Mana Cost by 10%, ad further increase their damage by 10%",
        "additional_effect": "",
        "next_rank": {
          "damage_increased": "11%"
        }
      },
      {
        "name": "Marred Guard",
        "rarity": "Legendary Chaos Perk",
        "rank": "1/10",
        "effect": "You can no longer be healed above 50% Life",
        "additional_effect": "You gain 5.0% Maximum Resistance to All elements, 10% Armor, and 50% increased Barrier and Fortify Generation",
        "next_rank": {
          "maximum_resistance": "5.5%",
          "barrier_and_fortify": "55%",
          "armor": "11%"
        }
      },
      {
        "name": "Chaotic Cooldowns",
        "rarity": "Legendary Chaos Perk",
        "rank": "1/10",
        "effect": "Casting a skill with a Cooldown will randomly set its cooldown between 2 seconds and its base cooldown, You no longer benefit from cooldown reduction",
        "additional_effect": "Using a cooldown unleashes a Chaotic Burst, dealing 594 damage of your highest damage type",
        "next_rank": {
          "damage": 634
        }
      },
      {
        "name": "Crazy Brew",
        "rarity": "Legendary Chaos Perk",
        "rank": "1/10",
        "effect": "You Healing Potion is infused with the power of Chaos, grating you 100% Resource Cost Reduction, 40% increased attack speed and 40% incresead movement speed for 5 seconds. Your healing potion has a 15 seconds Cooldown, and you can drink it while at full life",
        "additional_effect": "Using a cooldown unleashes a Chaotic Burst, dealing 594 damage of your highest damage type",
        "next_rank": {
          "attack_speed": "44%",
          "movement_speed": " 44%"
        }
      },
      {
        "name": "Mana-Infused Conjurations",
        "rank": "1/10",
        "effect": {
          "name": "Your Conjurations are empowered and deal 10% increased damage but each one drains 5 Mana per second",
          "ice_blades": "Attacks burst in area around the target",
          "lighting_spears": "hits have a 10% chance to spawn static Ball Lightnings",
          "Familiar": "leaves damaging ground afeter its attacks",
          "Hydra": "periodcally create Firewalls towards its targets"
        },
        "next_rank": {
          "damage_increased": "12%"
        }
      }
    ]
  }
}
```
