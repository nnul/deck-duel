# Deck Duel (v0.2.7)

Deck Duel is a two player card game played with a single deck of cards and a set of dice or other counters. It could be considered an extension of the card game [War](https://en.wikipedia.org/wiki/War_%28card_game%29). Each player flips over the top card of their deck and the high card wins. Ties are resolved during the next round.

However, unlike War, each player maintains a health counter and points for performing actions. The deck consists of only a single suit and face cards have special abilities when played.

## Requirements

- A standard 52-card deck of playing cards
- 2 - 12-sided dice (or another method of tracking health)
- 2 - 4-sided dice (or 6 *will* counters)
- 4 - 6-sided dice
- 1 - penny for tracking initiative (or any small object)

## Object

The object of the game is to be the last player standing at the end of the duel.

## Setup

Each player starts with 13 cards and a set of dice.

### Cards

Divide a standard 52-card deck of playing cards into four groups by suit. Each player chooses a single suit of cards as their playing deck. Shuffle your cards and place them face down in front of you.

### Dice

Each player will need a health tracker (12-sided die), three *will* counters (4-sided die), and two 6-sided dice for managing *aggression* and *guard* points. When using a die for tracking, set the current point value face up on the die.

### Counter

A counter can be any small object used for number tracking. Counters can be used in-place of a die for all health and point tracking if it is more convenient.

A single, shared counter or token is required to keep track of which player currently has initiative. A penny is suggested.

### Layout

<*INSERT IMAGE OF A SETUP PLAYSPACE*>

---

## Playing

### Start

Each player rolls a 6-sided die to determine who has initiative. Initiative indicates which player will go first when spending *will*. After each round initiative passes to the player who last won the combat phase.

Shuffle your cards and place them face down in front of you. Your opponent is given the option to cut your deck after every reshuffle. Players start at 10 health and 3 *will*.

### Phases

There are two phases during each round of the duel. The Prep Phase and the Combat Phase.

#### Prep Phase

Before combat, each player can concentrate their *will* into one of two areas *aggression* or *guard*. Aggression increases the damage dealt on a success in combat and guard is used to evade incoming damage during a loss in combat. Only a single *will* can be spent per turn in this way. The maximum total in either area can never exceed +3. See the section on **concentration** for more details.

The player with initiative spends there *will* first or can choose to not spend any. The other player can then spend their will in response.

#### Combat Phase

Each player flips over the top card of their deck and places it face up in play. The highest card wins this turn of combat. The available outcomes from a win are dependent on the winning card. All cards give the winning player the option to deal +1 damage to their opponent or increase their *will* by one. In addition the Ace and all face cards have additional behaviours. In the case of a tie both players increase their concentration in *aggression* by +1 and the combat phase is resolved.

##### Face Cards

1. King (**K**)
   - The King allows you to gain *focus*. This gives a special meaning and value to the Ace turning it from the worst card in the deck (**A**) into the best card in the deck (**A\***). To gain *focus* you take the **K** and place it sideways next to your discrd pile. This is the only action you take this turn if choosen.
2. Queen (**Q**)
   - The Queen grants you health. You can choose to gain +1 health when **Q** is the winning card. Additionally, a single *will* point can be spent to gain another +1, resulting in +2 health this turn. Only 1 *will* can be spent in this manner. This can be done for a maximum total health of 12. No further health can be gained beyond 12.
3. Jack (**J**)
   - The Jack grants you foresight. You can choose to peak at the top card of your deck, with the option to immediately discard it. Additionaly, a single *will* point can be spent to peak at another card. Only 1 *will* can be spent in this manner. Both cards can be viewed, but the order cannot be changed and only the top card can be discarded.
4. Ace (**A**)
   - The Ace is the worst card in the deck and results in a loss in combat, a complete loss of *concentration*, and the players deck being reshuffled. See **reshuffling** for more detail on this step. This is only true when you do not currently have *focus*. See **A\*** for more on this.
5. Focused Ace (**A\***)
   - The *focused* Ace is the best card in the deck. When the **K** is used to gain *focus* the **A** becomes an **A\*** and gains special attributes. It deals +2 damage this round instead of +1. The deck is always reshuffled on an Ace, but on an **A\*** there is no loss in concentration. See *concentration* for more details on this step.

### Concentration

*Will* points are spent in the prep phase to gain concentration in two areas: *aggression* and *guard*. No more than +3 can ever be gained in a single area. When gaining concentration place a die face up with the current value on the concentration section for the specific area.

Concentration points are used during the combat phase to impact the outcome. Each *aggression* point spent during a successful combat grants +1 damage this turn, for a maximum of +3 damage. Each *guard* point spent during a loss in combat reduces damage by -1 this turn, for a maximum of -3.

Aggression can only be maintained as long as a player takes no damage. Accumulated *aggression* points are lost if during a loss in combat the player also loses health. Aggression is not lost on a losing combat phase if the opponent does not attack or if all incoming damage is evaded by using *guard* points.

All concentration is lost when an unfocused **A** is played. This is immediate and occurs **before** damage is dealt in the combat phase, allowing the winning player to inflict all damage reguardless of how much guard existed before combat started.

### Reshuffling

Whenever any Ace is played that player will end their turn by reshuffling their deck and starting a new round. At the beginning of every round that players *will* points are reset to 3. If an unfocused **A** was played all concentraion points are removed. If an **A\*** was played any existing concentration is carried into the next round.

### Winning

To win, be the first player to reduce their opponents health below 1.

---

## Basic Ruleset

For a quicker and simpler verison of the game, there are a set of basic rules available in the Basic directory of this repository.

---

## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

Deck Duel © 2020 by Keith W. Thompson

Deck Duel is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.
