# Game Design Document (GDD) for "Blockchainia: CardBrawl"

## 1. Game Overview

### Title
Blockchainia: CardBrawl

### Concept
Blockchainia: CardBrawl is a fully on chain game in which Cards are minted for a complex Collect, Craft, and Compete Card game. Each card features a different Monster, Boss, NPC or Playable Character from the Blockchainia Lore. Blockchainia: CardBrawl is a mini-game to our wider gaming ecosystem. The game mixes and adapts from the mechanics of many  well known games, from the capturing based on score (Dominoes, Triple Triad, Final Fantasy 8), to complex battles (Magic the Gathering, Tetra Master, Final Fantasy 9). We implement a combination of Rank (Face Values), Genetics, and Battle Classes to create a strategic hybrid-deterministic battle system. CardBrawl players compete with their genetically unique Cards to collect Resources with allow players to alter their Cards attributes and genetics, as wlel as Forge new Weapons and Armor to each card. Legendary and Mythical Weapons and Armor will grant specific Perks in the battle mathematics.

 Players can invest an entry fee, or "Ante-up", to join matches against NPCs of varying difficulty or their friends. The Ante-up system will allow players to play without needing to have minted cards ahead of time. The winner is allowed to "Clone" one perishable copy of a card they have captured from their opponents hand. The game will feature returns in the form of Resources: Ingredients, Materials, and magical Essences, which must be obtained through playing AI NPCs. Crafting together Formulas of these Resources results in more powerful equipment and spells which can be Forged to cards to increase its "Face Values" and "Genetics".  

### Platform
PC/Mobile

### Genre
Card Game

## 2. Gameplay

### Game Overview
Blockchainia: Cards is a card game that combines crafting with a complex battle system. Players compete against AI NPCs to mine Resources to enhance their genetically unique cards, driving players to level up to enable higher stakes games. Players Ante-Up a small fee to play against AI NPCs, all of which drop valuable Resources needed to engage with the crafting system. Cards can be acquired through minting Card Packs, while ingredients, materials, and essence must be won through playing Card games through the ante-up system. 

Blockchainia: CryptoCards is played on a three-by-three (3x3) square grid of blank spaces where cards will be placed as the game progresses. Each card has four numbers, one in each Cardinal Direction, representing its strength in that direction. These numbers range from one to ten, ten being represented by the letter 'A'. These numbers are called "Face Values". Cards can have elemental alignments that affect the game play if there are elemental icons on the game board (i.e., the Elemental Rule is in effect).

In a basic game each player has five cards. A coin-flip decides who begins. The player who wins the coin toss may choose a card to play anywhere on the grid. After the first card is played, the opposing player may play a card on any unoccupied space on the board. The game continues with players' turns alternating.

To win, a majority of the total ten cards played (including the one card that is not placed on the board) must be of the player's card color. To do this, the player must capture cards by placing a card (referred to as the "Active" card) adjacent to an opponent's card (referred to as the "Resting" card) whereupon the 'Face Values' of the sides where the two cards touch will be compared in what is referred to as a "Face Off". If the Face Value of the Resting card is higher than the Active card's, the Active card will be captured and turned into the opponent's color. If the Active card's Face Value is higher, the Resting card will be captured and changed into the player's color instead. Capturing can only occur during that player's turn, and no other opponent card can capture a card during said turn. That is to say, there is only one "Face Off" per turn. 

A scenario where an Active card is placed adjacent to two or more opponent Resting cards, and the attacking card does not win a "Face Off" in any direction, but the adjacent cards have the same values facing each other, a resulting "Card Brawl" takes place. The Brawl Direction is selected by the player placing the attacking card. The winner of the brawl will take all cards adjacent to the Active card in directions in which the Active Card's face values are higher than its adjacent opponent's Resting Cards. If the Active card shares values with Resting cards in multiple directions, multiple card brawls may take place towards the final outcome, until all potential cards have been captured. The player placing the attacking card chooses the initial direction to take, and continues until all Brawls have completed. In this scenario, cards may be captured and lost multiple times before the final outcome of the turn is reached. 

Cards have different levels. Common level cards have low Face Values, like 1's and 2's and 3's, while Epic and Legendary level cards have 8's, 9's, and A's. Some cards are considered "Mythical". Mythical cards have unique perks derived from their Forged Weapon and Armor. 

### Game Setup
1. **Card Ranks and Genetics:** As stated, Cards have four Ranks, one in each Cardinal direction, as well as unique genetics that are used in the Brawl Mathematics through each Genetic attributes value. The cards also feature 0 through 4 arrows, one possible in each of the four ordinal directions. A Card's Ranks and Genetics can be enhanced via Forging Equipment and Magic to the card. 


1. **Deck Construction:** Players construct a deck of cards from cards they own, or may borrow up to 5 cards, Common through Rare, from a pool of cards made available for each game. The cost of borrowing cards is included in the "ante-up" fee. Players are unable to keep their borrowed cards, although their Opponent may Clone any of the captured borrowed Cards upon winning a match. 
  
2. **Game Board:** Blockchainia: Cards is played on a 3x3 grid board. Each square on the grid can hold one card. 

5. **Face Values:** Each card has four numbers, one in each Cardinal Direction, representing its strength in that direction. These numbers range from one to ten, ten being represented by the letter 'A'.

6. **Face Off:** The name for a battle in which two adjacent cards Face Values in their shared directions are considered. 

5. **Genetics** Each card has a genetic value that influence which card will win a Card Brawl. The Power, Brawl Class, Physical Defense, and Magical Defense are shown on the face of each card. These values can be increased through properly forging weapons, armor, and accessories to each card. Genetics give each card a unique base attributes and elemental compatibility. 

6. **Card Brawls** When two cards are placed adjacent to each other with the same "Face Value", a Card Brawl ensues. The Card Brawl mathematics are described below. A single card placement may result in multiple card brawls. The player who places the card decides which brawl occurs first. 

8. **Equipment and Spells** The primary objective of the card game is to craft Legendary Equipment. Card types are uncommon, common, rare, epic, and legendary. Only Legendary Equipment can be used to upgrade a Card to Mythical status. Mythical cards can be obtained by Forging Legendary Spells and Equipment to a card. 

9.  **Collection and Crafting:** The basic resources of the game are ingredients, materials, and elemental essence of magic.  Players create spells and Equipment via the Resources gathered by winning games against AI NPCs. 
    - **Alchemy, Synthesis, and Forging:** Visit the NPC-owned Alchemy and Synthesis shops to craft resources into Spells and Equipment. Equipment can be Forged to a card to alter the cards Face Values and Genetics to upgrade cards to Legendary and Mythical status. 
    - **Card Brawls:** It is possible to increase a cards Brawl Class from P or M to D or A through engaging the card in Card Brawls. 
    - **Vending:** Visit the Vending Machine to mint new card packs. 
    - **Elemental Advantage:** Adds strategic depth with elemental bonuses during a Card Brawl.
    - **Perks:** Introduce conditional skill activation for dynamic gameplay. Perks are derived from Legendary and Mythical Weapons

10. **Resource Types:**
    - **Ingredients:** Used to craft and upgrade Equipment and Spells. 
    - **Materials:** Used to craft and upgrade Equipment and Spells.  
    - **Essence:** Used to craft and upgrade Equipment and Spells. 

5. **Starting Hands:** Players draw a starting hand of cards from their deck. If the player does not own enough cards to fill a hand, they can choose up to five basic cards through the "ante up" system, essentially renting the remaining cards needed to start the game.

6. **Coin Flip:** Each player has five cards, neither knowing the other player's hand. A coin-flip decides which of the two players shall begin.
 
7. **Cloning Cards** The winner of each match is allowed to Clone one perishable copy of a card of their opponents selected from the pool of cards they captured throughout the match. 

### A card is played

Once the game is set up, the starting player may play their first card at any unoccupied grid square on the board. After the first card is played, the opposition may play a card, and the game continues with player turns alternating in this fashion.

### Neutral card play

If a card is placed next to another card, they may interact. Should neither of the cards be placed adjacent in the cardinal directions, there is no interaction. This is a neutral card play.

### Card capture

A Card Brawl occurs only if the Active and Resting cards possess equal Face Values in their adjacent direction, and the Active Card could not win a Face Off in any direction. A Card captured through comparing Rank as adjacent cards is considered to be captured "on the Face Off."

#### Card Brawls

##### Genetic Attributes: 

Every card has four Genetic Attributes. Three are hexadecimal values, and the final is a Brawl Class. An example card may have the Attribute values: P-3-3-3-X-9-2-9-4. Each Genetic Attribute relates to the card's competitive strength. The first value (P in the example) is always an alphabetical value from the set [P,S,D,A], while the next three genetics increase on a hexadecimal range, meaning they can range from 0-9, then through letters A-F.

   - The first value is the Brawl Class of the card. 
   - The second value is for the power genetic of the card. (3 or above)
   - The third value is for the physical defense genetic of the card. (6 above)
   - The fourth value is for the magical defense genetic of the card. (0 above)
   - The fifth value is always an X and is not a part of the genetic. 
   - The final four values are four hexadecimal numbers creating 65,536 unique Genetic values that will assign the elemental compatibility of the Card. 
   - Each of the genetics for power, physical defense and magical defense increases on a hexadecimal scale, with 0 being the weakest and F being the strongest.

The power and defense genetics represents a range of possible attack or defense points. 0 will take values from 0-15, while F will take values from 240-255. 

The card genetics are used in the following situations:

The first two values are used for the Attacking card.
The last two values are used for the Resting card.

#### Power genetic

The first value on the card is the power genetic. This is the card's offensive value. The example card has a power genetic of 3, which means its actual value is a random number chosen between 48 - 63 HP.

**Brawl class genetic:**
The second value on the card is the brawl class genetic. This value is not based on the hexadecimal scale like its other genetics, but instead is one of four classes. This genetic is represented by the letters P, S, D, and A. The card's brawl class determines how the values are assessed in card brawls.

- P is a Physical brawl class
- S is a Spell brawl class
- D is a Defensive brawl class
- A is an Ace or Weapon brawl class

The brawl class affects which genetic the attacking card attacks. P will attack the Physical Defense genetic, while S will attack the Magical Defense genetic. The other two have more obscure effects as they are rarer. D attack sthe lower of the two defenses and A attacks the lowest value on the card. It is possible to increase a cards Brawl class to D or A if it contains certain genetics.  

#### Physical Brawl
If the challenging card has a brawl class genetic of P (Physical), the power value of this card challenges the physical defense of the resting card. 

#### Spell Brawl

If the challenging card has a brawl class genetic of S (Spell), the power value of this card challenges the magical defense of the resting card. 

#### Defensive Struggle

If the challenging card has a brawl class genetic of D (Defense), the power value of this card challenges the weaker of the two defense genetics of the resting card.

#### Ace Brawl

If the challenging card has a brawl class genetic of A (Ace), the strongest of all three values on this card challenges the weakest of all three values of the resting card.

#### Battle Mathematics
     Additional Card Attributes:
     
     Element: Each card has an elemental attribute (e.g., Fire, Water, Earth, Air).
     Skill: Each card has a special skill that can be activated under certain conditions.

     Battle Phases

     Phase 1: Attribute and Range Determination
     
     Power and Defense Values:

     The challenging card's power value is randomly chosen within its stat range.
     The defending card's defense value is randomly chosen within its stat range, based on the battle class (physical or magical).
     Example:
     Card A: Power = 85 (stat 5 = range 80-95)
     Card B: Defense = 23 (stat 2 = range 16-31)
     Elemental Advantage:

     If the challenging card's element has an advantage over the defending card's element, add a bonus to the challenging card's power.
     Elemental relationships: Fire > Air > Earth > Water > Fire
     Example:
     Card A (Fire) vs. Card B (Earth): Fire has an advantage over Earth.
     Card A: Power = 85 + 10 (bonus) = 95

     Phase 2: Skill Activation and Score Calculation

     Skill Activation:

     Each card can activate its weapon and armor [Perk] if a specific condition is met.
     Example Skills:
     "Weapon": Increase power by 20 if the random attack score is above 50.
     "Armor": Reduce damage taken by 15 if the defense score is below 10.
     Score Calculation:

     Randomly select the actual attack and defense scores within the chosen power and defense values.
     Example:
     Card A: Attack score = Random(0, 95) = 71
     Card B: Defense score = Random(0, 23) = 3
     Apply skills if conditions are met:
     If Card A's [Perk] activates (since 71 > 50), new attack score = 71 + 20 = 91
     If Card B's [Perk] activates (since 3 < 10), new defense score = 3 - 15 = -12 (minimum 0)
     
     Phase 3: Final Score and Outcome Determination

     Score Adjustment:

     Subtract the scores from Phase 2 from the initial stat values in Phase 1.
     Example:
     Card A: 
     95
     −
     91
     =
     4
     95−91=4
     Card B: 
     23
     −
     0
     =
     23
     23−0=23
     Outcome Determination:

     Compare the final scores to determine the winner.
     The card with the highest difference wins the battle.
     Example:
     Card A: 4
     Card B: 23
     Card B wins the battle.

     Final Scores: Final scores reflect the impact of skills and elemental bonuses, determining the battle outcome.

## Design Considerations
- **Strategic Placement:** Players must consider card placement, equipped items, and magical effects.
  
- **Balance:** Ensure cards contain a balance of Face Values in each direction. When various rules are in effect, more consideration is needed to create the optimal deck for success. 
  
- **Variety:** Include a wide range of cards to encourage diverse strategies.
  
- **Customization:** Allow players to customize their decks of cards through crafting to suit their play style.

## Essence Effectiveness Table

| **Essence \ Target** | Earth | Water | Fire | Wind | Light | Darkness | Moon | Nature |
|----------------------|-------|-------|------|------|-------|----------|------|--------|
| **Earth**            | Normal| Normal| Strong| Weak | Normal| Normal   | Normal| Normal |
| **Water**            | Normal| Normal| Weak | Strong   | Normal| Normal   | Normal| Strong     |
| **Fire**             | Weak  | Strong    | Normal| Normal| Normal| Normal   | Normal| Strong    |
| **Wind**             | Strong    | Weak  | Normal| Normal| Normal| Normal   | Normal| Normal|
| **Light**            | Normal| Normal| Normal| Normal| Weak  | Strong       | Normal| Normal|
| **Darkness**         | Normal| Normal| Normal| Normal| Strong    | Weak     | Normal| Normal|
| **Moon**             | Normal| Normal| Normal| Normal| Normal| Normal   | Normal| Normal|
| **Nature**           | Normal| Weak  | Normal| Strong| Weak| Normal   | Normal| Normal|

## Resource list

| **Ingredient**   | **Category**    | **Description**                                      |
|------------------|-----------------|------------------------------------------------------|
| Wax              | Ingredient      | Used for sealing and waterproofing                   |
| Water            | Ingredient      | Essential liquid, often used as a solvent            |
| Vinegar          | Ingredient      | Acidic liquid used in various concoctions            |
| Root             | Ingredient      | Plant-based ingredient, often used for its properties|
| Oil              | Ingredient      | Used for lubrication and combustion                  |
| Mushroom         | Ingredient      | Fungal ingredient with various effects               |
| Mud              | Ingredient      | Earthy mixture, often used for grounding spells      |
| Limestone        | Ingredient      | Calcium-rich mineral used in various mixtures        |
| Iron             | Ingredient      | Metal used for strengthening concoctions             |
| Gunpowder        | Ingredient      | Explosive mixture used for powerful effects          |
| Grease           | Ingredient      | Lubricant often used in mechanical concoctions       |
| Feather          | Ingredient      | Light and airy, used for levitation spells           |
| Ethanol          | Ingredient      | Alcohol used as a solvent and for combustion         |
| Dry Ice          | Ingredient      | Solid carbon dioxide used for freezing effects       |
| Clay             | Ingredient      | Earthy material used for crafting and grounding      |
| Bone             | Ingredient      | Used for necromancy and strengthening spells         |
| Ash              | Ingredient      | Remnants of combustion, used in various spells       |
| Mythril          | Ingredient      | Rare metal used for crafting powerful items          |
| Adamantite       | Ingredient      | Extremely hard metal used for ultimate weapons       |
| Lunar Curtain    | Ingredient      | Creates a barrier, often used for protection         |
| Phoenix Feather  | Ingredient      | Revives the fallen, symbolizes rebirth               |
| Dragon Fang      | Ingredient      | Rare and powerful, used for high-level concoctions   |
| Magicite Shard   | Ingredient      | Fragment of a magic crystal, used for spell casting  |
| Echo Screen      | Ingredient      | Cures silence, allowing spells to be cast            |
| Ether            | Ingredient      | Restores magical energy                              |
| Dreamstone       | Ingredient      | Rare stone, used for crafting powerful artifacts     |
| Rainbow Shell    | Ingredient      | Used to create ultimate weapons and armor            |
| Luminite         | Ingredient      | Luminescent material, used for light-based items     |
| Aquanix          | Essence         | Water spirit, grants water-based magic               |
| Terralon         | Essence         | Earth spirit, grants earth-based magic               |
| Aerion           | Essence         | Wind spirit, grants wind-based magic                  |
| Pyron            | Essence         | Fire spirit, grants fire-based magic                 |
| Nocturne         | Essence         | Void-Darkness spirit, grants dark-based magic             |
| Radiance         | Essence         | Void-Light spirit, grants light-based magic               |
| Selene           | Essence         | Void-Moon spirit, grants lunar-based magic                |
| Verdant          | Essence         | Void-Life spirit, grants nature-based magic               |
| Iron             | Material        | A common and sturdy metal used for basic weaponry and armor. |
| Steel            | Material        | An alloy of iron, stronger and more durable, ideal for high-quality weapons and armor. |
| Mithril          | Material        | A lightweight, silver metal known for its exceptional strength and magical properties. |
| Adamantine       | Material        | A rare and nearly indestructible metal, perfect for legendary weapons and armor. |
| Obsidian         | Material        | A volcanic glass that can be sharpened to a razor edge, though brittle and best for slicing weapons. |
| Dragonbone       | Material        | Bones from ancient dragons, incredibly strong and imbued with magical energy. |
| Crystal          | Material        | Mystical crystals that can channel magical energies, used in crafting magical weapons. |
| Darkwood         | Material        | A rare and sturdy wood with dark coloration, used for crafting bows and staves. |
| Orichalcum       | Material        | A mythical metal with a golden hue, known for its durability and enchantment capabilities. |
| Moonstone        | Material        | A pale, luminescent stone with magical properties, often used in crafting magical jewelry and weapons. |
| Dwarven Steel    | Material        | Superior steel forged by dwarven smiths, known for its exceptional quality and strength. |
| Elven Silver     | Material        | A fine and elegant metal used by elves, light and strong with magical properties. |
| Froststeel       | Material        | Steel imbued with the essence of ice, causing weapons to have a chilling effect. |
| Bloodstone       | Material        | A dark, crimson stone that can enhance the power of blood magic in weapons. |
| Star Metal       | Material        | Metal forged from meteorite fragments, possessing unique otherworldly properties. |
| Voidsteel        | Material        | A dark, shadowy metal that absorbs light, used in forging weapons with void or dark magic. |
| Living Wood      | Material        | Enchanted wood that retains the essence of life, used for crafting living weapons and armor. |
| Thunderstone     | Material        | A rare stone that can store electrical energy, used to forge weapons with thunderous power. |
| Phoenix Feather  | Material        | Feathers from the mythical phoenix, used to craft weapons with regenerative and fiery properties. |
| Shadowglass      | Material        | A dark, reflective glass that can absorb and manipulate shadows, used in stealth weapons. |


## Crafting through Synthesis and Alchemy to Create Legendary Weapons

### Synthesis Formulas for Equipment
These items may be "forged" to a card to alter it's values in Blockchainia: CryptoCards. 

#### Common Weapons and Armor Formulas

| **Item**           | **Formula**                           | **Category** | **Description**                                                 |
|--------------------|---------------------------------------|--------------|-----------------------------------------------------------------|
| Fire Sword         | Pyron + Iron + Feather                | Weapon       | A sword imbued with the power of fire, dealing extra fire damage. |
| Ice Dagger         | Aquanix + Mithril + Dry Ice           | Weapon       | A dagger that freezes enemies upon contact.                     |
| Lightning Axe      | Aerion + Steel + Thunderstone         | Weapon       | An axe that crackles with electricity, stunning enemies.        |
| Earth Hammer       | Terralon + Iron + Mud                 | Weapon       | A hammer that causes small earthquakes on impact.               |
| Shadow Blade       | Nocturne + Voidsteel + Shadowglass    | Weapon       | A blade that deals additional darkness damage.                  |
| Light Mace         | Radiance + Mithril + Luminite         | Weapon       | A mace that emits a blinding light, damaging and blinding enemies. |
| Moon Spear         | Selene + Orichalcum + Moonstone       | Weapon       | A spear that glows with lunar energy, increasing precision and power. |
| Nature Bow         | Verdant + Darkwood + Root             | Weapon       | A bow that enhances arrows with nature's power, causing additional damage. |
| Firearm (Pistol)   | Iron + Grease + Gunpowder             | Weapon       | A basic firearm that is reliable and effective at short range.  |
| Firearm (Rifle)    | Steel + Luminite + Gunpowder          | Weapon       | A rifle with enhanced aiming capabilities for long-range attacks. |
| Crossbow           | Darkwood + Iron + Grease              | Weapon       | A crossbow that fires bolts with precision and power.           |
| Elemental Crossbow | Crystal + Darkwood + Etherstone       | Weapon       | A crossbow that can fire elemental bolts.                       |
| Regenerative Armor | Phoenix Feather + Mithril + Bone      | Armor        | Armor that grants the wearer regenerative abilities.            |
| Elemental Shield   | Aquanix + Pyron + Iron                | Armor        | A shield that provides resistance to elemental damage.          |
| Stealth Suit       | Grease + Clay + Nocturne              | Armor        | Armor that enhances the wearer's stealth abilities.             |
| Scale Armor        | Dragonbone + Dwarven Steel + Crystal  | Armor        | Armor made from dragon scales, offering unmatched protection.   |
| Invisibility Cloak | Etherstone + Moonstone + Elven Silver | Armor        | A cloak that provides invisibility and enhances magical abilities. |
| Cosmic Helm        | Star Metal + Orichalcum + Mithril     | Armor        | A helmet that grants the wearer cosmic awareness and protection. |
| Frost Gauntlets    | Froststeel + Silver + Etherstone      | Armor        | Gauntlets that grant the wearer control over ice and cold.      |
| Nature Boots       | Verdant + Living Wood + Leather       | Armor        | Boots that enhance the wearer's connection to nature, boosting speed and agility. |


### Synthesis Formulas for Legendary Weapons, Armor, and Accessories
Legendary Weapons, Armor, and Accessories can be created by synthesizing Precious Stones with other Materials, Essences, and Ingredients to an existing Weapon, Armor, or Accessory. The Stone and Weapon chosen alter the final genetics of the Legendary Weapon produced. 


#### Synthesizing Precious Stones
Precious stones can be used to craft Legendary Weapons to Forge to cards . They can also be used for the summoning of powerful allies in the Blockchainia: OpenWorlds and Blockchainia: CryptoBrawl. 

| **Precious Stone**    | **Formula**                         | **Name**       | **Description**                                                       |
|-----------------------|-------------------------------------|----------------|-----------------------------------------------------------------------|
| Aqua Gem              | Aquanix + Crystal + Moonstone       | Poseidon       | Summons Poseidon, god of the sea, to command water and marine creatures. |
| Earth Crystal           | Terralon + Dragonbone + Orichalcum  | Gaia           | Summons Gaia, the Earth Mother, to protect and nurture the land.       |
| Flame Ruby            | Pyron + Obsidian + Bloodstone       | Hephaestus     | Summons Hephaestus, god of fire and forge, to wield flames and craft.  |
| Shadow Onyx           | Nocturne + Voidsteel + Shadowglass Shard | Hades       | Summons Hades, lord of the underworld, to command darkness and the dead. |
| Light Diamond         | Radiance + Luminite + Elven Silver  | Apollo         | Summons Apollo, god of light and music, to heal and inspire.           |
| Lunar Pearl           | Selene + Moonstone + Froststeel     | Artemis        | Summons Artemis, goddess of the moon and hunt, to guide and protect.   |
| Nature Emerald        | Verdant + Living Wood Heart + Dwarven Steel | Cernunnos | Summons Cernunnos, the horned god, to oversee nature and wildlife.     |
| Volcanic Garnet       | Pyron + Terralon + Adamantine       | Surtr          | Summons Surtr, the fire giant, to unleash volcanic fury.               |
| Storm Topaz           | Aerion + Thunderstone + Steel       | Thor           | Summons Thor, god of thunder, to wield his mighty hammer and storm.    |
| Mystic Amethyst       | Radiance + Etherstone + Crystal     | Amaterasu      | Summons Amaterasu, goddess of the sun, to illuminate and purify.       |
| Warrior's Bloodstone  | Pyron + Dragonbone + Bloodstone     | Ares           | Summons Ares, god of war, to lead in battle and inspire warriors.      |
| Ocean's Heart         | Aquanix + Sapphire + Luminite       | Ryujin         | Summons Ryujin, the dragon god of the sea, to control tides and marine life. |
| Frost Crystal         | Aquanix + Froststeel + Mithril      | Yuki-Onna      | Summons Yuki-Onna, the snow woman, to command ice and cold.            |
| Phoenix Feather       | Pyron + Phoenix Feather + Obsidian  | Phoenix        | Summons the Phoenix, a mythical bird, to revive and incinerate foes.   |
| Chaos Ruby            | Nocturne + Bloodstone + Voidsteel   | Loki           | Summons Loki, the trickster god, to cause chaos and deceive enemies.   |
| Celestial Moonstone   | Selene + Star Metal + Moonstone     | Selene         | Summons Selene, the moon goddess, to bless with lunar magic and protection. |

#### Synthesizing Legendary Weapons, Armor, and Accessories

| **Item**             | **Formula**                         | **Category** | **Description**                                                 | **Power** |
|----------------------|-------------------------------------|--------------|-----------------------------------------------------------------|-----------|
| Ring of Radiance     | Radiance + Mythril + Feather + [Stone]        | Accessory    | A ring that enhances light-based magic and spells.              | 7 |
| Lunar Amulet         | Selene + Luminite + Ash + [Stone]             | Accessory    | An amulet that boosts lunar-based magic and nighttime abilities. | 8 |
| Gauntlets of Strength| Terralon + Iron + Bone + [Stone]              | Accessory    | Gauntlets that significantly increase the wearer's physical strength. | 7 |
| Titan's Gauntlets    | Adamantine + Iron + Obsidian + [Stone]        | Accessory    | Gauntlets that bestow the strength of the titans to the wearer.  | 9 |
| Crystal Band         | Crystal + Elven Silver + Etherstone + [Stone] | Accessory    | A band that enhances the wearer's magical power and resilience.  | 8 |
| Solar Gauntlets      | Radiance + Gold + Iron + [Stone]              | Accessory    | Gauntlets that boost the wearer's strength and radiate light.    | 7 |
| Void Ring            | Nocturne + Shadowglass + Silver + [Stone]     | Accessory    | A ring that grants the wearer control over shadows and darkness. | 6 |
| Ocean Pendant        | Aquanix + Sapphire + Mithril + [Stone]        | Accessory    | A pendant that allows the wearer to breathe underwater and control water. | 8 |
| Frost Gauntlets      | Froststeel + Silver + Etherstone + [Stone]    | Accessory    | Gauntlets that grant the wearer control over ice and cold.       | 7 |
| Phoenix Armor        | Phoenix Feather + Mythril + Bone + [Stone]    | Armor        | Armor that grants the wearer regenerative abilities.            | 9 |
| Elemental Shield     | Aquanix + Pyron + Iron + [Stone]              | Armor        | A shield that provides resistance to elemental damage.          | 8 |
| Stealth Suit         | Grease + Clay + Nocturne + [Stone]            | Armor        | Armor that enhances the wearer's stealth abilities.             | 7 |
| Dragon Scale Armor   | Dragonbone + Dwarven Steel + Crystal + [Stone]| Armor        | Armor made from dragon scales, offering unmatched protection.    | 9 |
| Ethereal Cloak       | Etherstone + Moonstone + Elven Silver + [Stone]| Armor       | A cloak that provides invisibility and enhances magical abilities. | 8 |
| Phoenix Feather Cape | Phoenix Feather + Living Wood + Bloodstone + [Stone] | Armor  | A cape that provides regeneration and fiery protection.          | 8 |
| Star Metal Helm      | Star Metal + Orichalcum + Mithril + [Stone]   | Armor        | A helmet that grants the wearer cosmic awareness and protection. | 9 |
| Moonlight Robe       | Selene + Silk + Moonstone + [Stone]           | Armor        | A robe that grants the wearer enhanced magical abilities and stealth. | 8 |
| Flame Cloak          | Pyron + Silk + Gold + [Stone]                 | Armor        | A cloak that grants immunity to fire and increases fire magic potency. | 8 |
| Storm Helm           | Thunderstone + Iron + Luminite + [Stone]      | Armor        | A helmet that channels the power of storms, protecting the wearer. | 9 |
| Blazing Sword        | Pyron + Iron + Mythril + [Stone]              | Weapon       | A sword imbued with the Stone of fire, dealing extra fire damage. | 7 |
| Sniper Rifle         | Iron + Grease + Luminite + [Stone]            | Weapon       | A high-precision firearm with enhanced aiming capabilities.     | 8 |
| Energy Sword         | Luminite + Mythril + Grease + [Stone]         | Weapon       | A melee weapon with a blade made of pure energy.                | 9 |
| Grenade Launcher     | Gunpowder + Iron + Grease + [Stone]           | Weapon       | A firearm that launches explosive grenades.                     | 8 |
| Plasma Rifle         | Luminite + Iron + Ethanol + [Stone]           | Weapon       | A futuristic rifle that shoots plasma bolts.                    | 7 |
| Thunder Hammer       | Thunderstone + Iron + Steel + [Stone]         | Weapon       | A powerful hammer that summons thunder with each strike.        | 7 |
| Frost Blade          | Froststeel + Mithril + Obsidian + [Stone]     | Weapon       | A sword that emits a chilling aura, freezing enemies upon contact. | 6 |
| Shadow Dagger        | Shadowglass + Voidsteel + Darkwood + [Stone]  | Weapon       | A dagger that allows the wielder to move through shadows unseen. | 5 |
| Inferno Axe          | Pyron + Iron + Steel + [Stone]                | Weapon       | An axe that ignites upon impact, dealing massive fire damage.    | 8 |
| Glacial Spear        | Froststeel + Mithril + Orichalcum + [Stone]   | Weapon       | A spear that chills the air, freezing enemies it pierces.       | 7 |
| Shadow Bow           | Shadowglass + Darkwood + Luminite + [Stone]   | Weapon       | A bow that fires arrows of pure darkness, confounding enemies.  | 6 |
| Thunder Blade        | Thunderstone + Iron + Etherstone + [Stone]    | Weapon       | A sword that crackles with electricity, stunning foes.          | 7 |
| Mystic Staff         | Crystal + Elven Silver + Moonstone + [Stone]  | Weapon       | A staff that enhances magical abilities, channeling powerful Stones. | 9 |
| Celestial Mace       | Star Metal + Adamantine + Bloodstone + [Stone]| Weapon       | A mace that glows with celestial light, smiting enemies.        | 8 |
| Gale Whip            | Aerion + Mithril + Silk + [Stone]             | Weapon       | A whip that summons gusts of wind, cutting through enemies.     | 6 |
| Venom Dagger         | Verdant + Living Wood + Poison + [Stone]      | Weapon       | A dagger that delivers a deadly poison, weakening enemies.      | 5 |

### Alchemy Formulas
#### Alchemy Formulas for Consumable Spells

| **Alchemy Formula**     | **Spell Name**      | **Description**                                                         | **Power** |
|-------------------------|---------------------|-------------------------------------------------------------------------|-----------|
| Terralon + Terralon     | Rockslide           | A massive slide of rocks that crushes enemies.                          | 2         |
| Terralon + Aquanix      | Mudslide            | A torrent of mud that engulfs and slows enemies.                        | 1         |
| Terralon + Pyron        | Lava Burst          | Erupts molten rock that burns and traps enemies.                        | 1         |
| Terralon + Aerion       | Sandstorm           | Whips up a fierce sandstorm that blinds and slices through enemies.     | 1         |
| Terralon + Nocturne     | Voidquake           | A devastating earthquake infused with void energy that disrupts reality. | 2         |
| Aquanix + Aquanix       | Tsunami             | A gigantic wave that washes away everything in its path.                | 2         |
| Aquanix + Pyron         | Steam Blast         | A burst of scalding steam that burns and blinds enemies.                | 1         |
| Aquanix + Aerion        | Hurricane           | A powerful hurricane that drenches and blows away everything in its path.| 1         |
| Aquanix + Nocturne      | Abyssal Tide        | Summons a tide from the abyss that pulls enemies into the void.         | 2         |
| Pyron + Pyron           | Inferno             | An intense blaze that engulfs and incinerates everything.               | 2         |
| Pyron + Aerion          | Flame Cyclone       | A massive cyclone of flames that engulfs and burns everything it touches.| 1         |
| Pyron + Nocturne        | Hellfire            | Summons flames from the void that burn with unholy intensity.           | 2         |
| Aerion + Aerion         | Tornado             | A powerful tornado that tears through everything in its path.           | 2         |
| Aerion + Nocturne       | Ethereal Breeze     | A soothing breeze from the void that heals allies and confounds enemies.| 2         |
| Nocturne + Nocturne     | Annihilation        | A destructive force that obliterates everything it touches.             | 3         |
| Radiance + Radiance     | Divine Light        | Summons a blinding light that purifies and damages all enemies.         | 2         |
| Radiance + Nocturne     | Eclipse             | A combination of light and darkness that causes massive destruction.    | 2         |
| Nocturne + Nocturne     | Shadow Veil         | Envelops the battlefield in darkness, blinding all enemies.             | 1         |
| Selene + Selene         | Lunar Blast         | A powerful beam of lunar energy that devastates enemies.                | 2         |
| Selene + Nocturne       | Nightfall           | Calls down the power of the moon and darkness to crush enemies.         | 2         |
| Verdant + Verdant       | Nature's Wrath      | Summons the fury of nature to entangle and damage enemies.              | 2         |
| Verdant + Aquanix       | Vine Whip           | Conjures water-infused vines that bind and drown enemies.               | 1         |
| Verdant + Pyron         | Wildfire            | Unleashes a wildfire that spreads and incinerates everything.           | 1         |
| Verdant + Aerion        | Leaf Storm          | Summons a storm of razor-sharp leaves that cut through enemies.         | 1         |
| Verdant + Nocturne      | Shadow Grove        | Creates a grove of shadowy trees that ensnare and drain life from enemies.| 2         |


### Alchemy Formulas for Legendary Spells 
Each Legendary spell can progress from its base [Element], to [Element]+, to its [Legendary Spell]. For example, the Earth elemental spell is acquired at level 1. It may to Earth+ between levels 25 and 50, and between 75 and 85 to Gaia's Wrath. Forging a Spell requires the following formula, plus an additional mix of Consumable spells and Essence. All of these will be considered when Forging the Spells unique Genetics. 

| **Element** | **Legendary Spell**  | **Formula**                                           | **Description**                                                                 |
|-------------|----------------------|-------------------------------------------------------|---------------------------------------------------------------------------------|
| Earth       | Gaia's Wrath         | Earth Crystal + Earth Hammer                            | Unleashes the fury of the Earth, causing massive earthquakes and upheaval.      |
| Water       | Poseidon's Fury      | Aqua Gem + Ocean's Heart + Glacial Spear              | Summons a colossal tidal wave and torrential rain to devastate enemies.         |
| Fire        | Inferno Blaze        | Flame Ruby + Inferno Axe + Phoenix Feather Cape       | Engulfs the battlefield in intense flames, incinerating everything in sight.    |
| Wind        | Tempest of the Skies | Ocean Pendant + Thunder Blade + Gale Whip              | Conjures a massive storm, with powerful winds and lightning strikes.            |
| Light       | Radiant Judgment     | Light Diamond + Ring of Radiance + Celestial Mace     | Calls down beams of divine light to smite and purify the land.                  |
| Darkness    | Shadow Cataclysm     | Shadow Onyx + Shadow Dagger + Void Ring               | Summons a void of darkness, engulfing enemies and disrupting their senses.      |
| Moon        | Lunar Eclipse        | Lunar Pearl + Moonlight Robe + Ethereal Cloak         | Brings forth an eclipse, casting a shadow over the battlefield and empowering allies. |
| Nature      | Verdant Rebirth      | Nature Emerald + Venom Dagger + Nature Boots          | Revitalizes the land, causing plants to grow rapidly and heal allies.           |


## Forging
Weapons, Armor, Accessories, and Spells can be used to increase a Cards statistics. Forging Weapons, Armor, or Accessories to a card will essentially burn the item embed it to the card of choice, altering the cards genetics and the images shown on the face of the card. 

### Game Progression
- **Match-Based Play:** Players enter matches, competing against both AI and other players. To play against AI, players must "ante-up". 
- **The Iron Price** Upon match end, the winning player may take a perishable copy of one card from the opponents deck. 
- **Crafting and Upgrading:** Post-match, players use collected essences and materials to craft and upgrade spells, weapons, and pets.

- **Items, Relics, and Artifacts:** Collect in game items of various utility in future games. 

## 3. Story and Setting

### World
The game is set in a virtual on-chain realm where the separation of magic and technology has been obfuscated from the public by a shadowy organization. Ancient ruins and mines scatter the landscape, providing rich sources of elemental essence and raw materials. NPC characters inhabit the land, and have littered it with monuments, fountains, as well as various spiritual relics and artifacts revealing a deep but unspoken culture. Their interactions give clues to the history of this strange world, revealed through easter eggs holding the secrets of the beginning of this unique realm, ultimately leading each player on a unique journey to understand the prophecy behind the NPC's very existence.

### Narrative
The realm of Blockchainia exists outside of the concept of time itself, a plane where games of past, present, and future are slowly being connected by an unknown force. This force initially takes the form of a seemingly out-of-place Sword that flies through the sky near the end of a match. 

Players are members of various guilds vying for control over resources and power in a world fractured by misinformation. Each player's actions and alliances will influence the eventual storyline and available resources, as well as the complexity of the various magic and technologies that evolve through each season of game play.

It is initially unknown to the player, but the NPC's despise the powerful invaders that enter through yet-unknown virtual means. From the NPC's views, players play a brutal game for sport, annihilating each other while pillaging their sacred land and destroying their culture, history, and home in the process, while also forcing their leaders to create every more powerful weapons and magic. They yearn for a savior, one who will provide the governance necessary to banish these barbarians from the realm of Blockchainia forever.

Yet, while most NPCs view these invaders as a threat, others have found opportunity, offering "smart contracts" to players for completing certain tasks and rewarding them heavily for their efforts. 

## 4. Art Style

### Visuals



## 5. Technology

- **Engine:** Unity
- **On-chain Competative Gameplay:** 

## 6. Monetization

- **Entry Fees and Rewards:** Players can play without minting by the "ante-up" system, and can pick from a deck of common cards. If the player wins, they can still steal a perishable copy of a card from the opponent. 
- **Microtransactions:** Crafting through Forging, Alchemy, and Synthesis have a small on-chain overhead. 
- **Season Pass:** Enables free entry into games for the season via an NFT.
- **Founders Pass:** Enables free entry for life via an NFT. 

## 7. Development and Marketing

### Team
- Ed Anderson
- Will Chastka

### Milestones
1. Prototype - 2-3 months
2. First Playable Alpha - 3-6 months
3. First Playable Beta - 6-9 months
3. Beta Testing and Feedback - 12 months
4. Launch - 15 months

### Marketing Strategy
- Series of verticle slice trailers showing spoofs of the OpenWorld and CryptoBrawl games
   - Reveal Brand/Narrative and Mechanics as close to gameplay as possible
   - Key interactions:
     - Combat
     - Crafting and Economics
     - Game Interoperabiity
     - Lore/Backstory
   - Frequent releases that communicate to audience the benefits of Early Access to drive Follows and Signups through unique rewards. 
- Promote the CardBrawl as a Companion Application
  - Reveals, Live Streams, and Q&A via Social Media
  - Early Access for feedback and hype building

- Layer Teaser Trailers with popular streamers and influencers to create better brand recognition and recall
- Launch Event
- Recruit charitable organizations that allow players to complete specific game contracts and earn tokens paid to the charity of their choice

## Conclusion

Blockchainia: CardBrawl utilizes a collect, craft, compete loop to create a dynamic and strategic card game, offering players a wealth of options for customization and tactical decision-making.
