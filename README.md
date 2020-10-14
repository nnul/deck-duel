# Deck Duel (v0.2.8)

Deck Duel is a two player card game played with a single deck of cards and a set of dice. It could be considered an extension of the card game [War](https://en.wikipedia.org/wiki/War_%28card_game%29). Each player flips over the top card of their deck and the high card wins. Ties are resolved during the next turn.

However, unlike War, each player maintains a health counter and points for performing actions. The deck consists of only a single card suit and face cards have special abilities when played.

## Requirements

- A standard 52-card deck of playing cards
- 2 - 12-sided dice
- 2 - 4-sided dice
- 4 - 6-sided dice
- A small token object. A penny is suggested.

## Object

The object of the game is to be the last player standing at the end of the duel.

## Setup

Divide a standard 52-card deck of playing cards into four groups by suit.
Each player will need:

- A single card suit as their playing deck
- A 12-sided die for Health points
- A 4-sided die for Energy points
- Two 6-sided die for Attack and Defense points

### Layout

<*INSERT IMAGE OF A SETUP PLAYSPACE*>

---

## Playing

### Start

To determine who goes first, each player rolls a 6-sided die. Highest number wins. The winner will spend their Energy points first during the Prep Phase. This player has *initiatve*. Use the token object to indicate which player currently has *initiative*. At the end of each turn initiative passes to the player who last won the combat phase. This player will spend their Energy points first on the next turn.

Players shuffle their cards and place them face down in front of them, giving their opponent the option to cut the deck. A player is given this option after every reshuffle.

Players start with 10 Health points and 3 Energy points.

### Phases

There are two phases during each turn of the duel. The Prep Phase and the Combat Phase.

#### Prep Phase

Before combat, each player can spend 1 Energy point to increase their *concentration* on Attack or Defense by +1. Only a single Energy point can be spent in this way. The maximum total in either area can never exceed +3. See the section on **concentration** for more details.

The player with initiative spends their Energy point first. The other player then spends their Energy point in response. Players can choose not to spend any Energy points on a turn.

#### Combat Phase

Each player flips over the top card of their deck and places it face up in play. The highest value card wins this turn of combat.

##### Win

The winner of combat chooses one of the following actions to perform:

1. Deal attack damage
   - The player may deal damage to their opponent. Add together the card damage (+1 or +2 for **A\***) and any Attack points for the total attack damage. All used Attack points are then removed from play. The maximum possible damage in a turn is 5 (**A\*** + Attack = 2 + 3 = 5).
2. Gain +1 Energy
   - The player may increase their Energy by +1. This can only done if Energy is currently below 3.
3. Use a face card ability
   - See **face cards** for more details.

##### Loss

The loser of combat can respond by using Defense points to reduce incoming damage. Any damage not reduced in this way is removed from that players health. If a player takes damage while they have Attack points, those points are lost and must be removed from play.

##### Tie

When both players flip over the same value card it results in a tie and both players Attack increases. Add +1 to each players Attack points. If the Attack counter is not already in play then place it next to the Action die and set its value to 1.

#### Face Cards

Face cards give players additional options in combat. However, these options are only available when a combat phase is won. If a player loses combat with a face card it provides not advantage. This is also true in the case of a tie, where neither player can use these abilities.

##### King (**K**)

The **K** allows a player to gain *focus*. This gives special meaning to the Ace by turning it from the lowest value card in the deck (**A**) into the highest value card in the deck (**A\***). To gain *focus* a player takes the **K** and places it sideways next to the discard pile. This is the only action taken this turn if choosen.

##### Queen (**Q**)

The **Q** gives a player health. The player may choose to gain +1 health this turn. Additionally, a single Energy point can be spent to gain another +1 health, resulting in +2 health this turn. Only 1 Energy point can be spent in this way. This can be done for a maximum total health of 12. No further health can be gained beyond 12.

##### Jack (**J**)

The **J** gives a player *foresight*. The player may choose to peak at the top card of their deck, with the option to immediately discard it. Additionaly, a single Energy point can be spent to peak at another card. Only 1 Energy point can be spent in this manner. Both cards can be viewed, but the order cannot be changed and only the top card can be discarded.

##### Ace (**A**)

The **A** is the lowest value card in the deck. It results in a complete loss of *concentration* and the player's deck being reshuffled. See **reshuffling** and **concentration** for more details.

##### Ace with focus (**A\***)

The **A\*** is the highest value card in the deck. When the **K** is used to gain *focus* it causes the **A** to become the **A\***. The card now deals +2 attack damage when played instead of +1 and the player's deck is reshuffled. The deck is always reshuffled on any Ace, but on an **A\*** there is no loss in *concentration*. See **reshuffling** and **concentration** for more details.

### Concentration

Energy points are spent in the Prep Phase to increase *concentration* on either Attack or Defense. No more than +3 can be gained in either category. When adding Attack or Defense points, place a die face up with the current value in that section of the *concentration* zone.

<*INSERT IMAGE OF CENCENTRATION HERE*>

A player may spend Attack and Defense points during the combat phase. Each Attack point spent during a successful combat grants +1 damage this turn, for a maximum of +3 damage. Each Defense point spent during a loss in combat reduces damage by -1 this turn, for a maximum of -3. All spent points are removed from play this turn.

Unspent Attack points are kept only if a player takes no damage during a loss in combat. When a player takes damage all remaining Attack points are lost. Attack points are not lost if all incoming attack damage is reduced to 0 using Defense points.

All *concentration* is lost when an unfocused **A** is played. The player must remove all Attack and Defense points from play immediately. This occurs **before** damage is dealt in the combat phase. The winning player is then able deal their full amount of attack damage this turn.

### Reshuffling

When an Ace is played that player ends their turn by reshuffling their deck and starting a new round. At the beginning of a new round the player resets their Energy points to 3. If an unfocused **A** was played all Attack and Defense points are also removed. If an **A\*** was played any existing Attack and Defense points are carried into the next round.

Only the player who played an Ace reshuffles their cards. The other player continues until the Ace in their deck is played.

### Winning

The first player to reduce their opponents health below 1 wins.

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
