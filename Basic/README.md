# Deck Duel Basic (v0.1.10)

Deck Duel is a two player card game played with a single deck of cards and a set of dice or counters. It could be considered an extension of the card game [War](https://en.wikipedia.org/wiki/War_%28card_game%29). Each player flips over the top card of their deck and the high card wins. Ties are resolved during the next round.

However, unlike War, each player maintains a health counter and points for performing actions. The deck consists of only a single card suit and face cards have special abilities when played.

NOTE: This is a simplified version of the core ruleset. Some mechanics have been changed for simplicity.

## Requirements

- A standard 52-card deck of playing cards
- 2 - 12-sided dice (or another method of tracking health)
- 4 - 6-sided dice (or 12 counters)

## Object

The object of the game is to be the last player standing at the end of the duel.

## Setup

Divide a standard 52-card deck of playing cards into four groups by suit.
Each player will need:

- A single card suit as their playing deck
- A 12-sided die for Health points
- Two 6-sided die for Action points and Rage points

---

## Playing

### Start

Shuffle your cards and place them face down in front of you. Your opponent is given the option to cut your deck. This option is given every time it's shuffled. Place a 12-side die next to your deck. This is your Health counter and starts with an inital value of 10. Place a 6-sided die next the Health counter. This is your Action counter and starts with an initial value os 2. Place the extra six-sided to the side for later use.

### Turns

At the start of a turn each player may choose to use 1 Action point to boost the next attack by +1. This is called Rage. Place the Rage die in play next to the Action die. If it is already in play then increase its value by +1. You may only risk a single Action point in this way per turn.

Each player flips over the top card of their deck and places it face up in front of them. The highest value card wins this turn of combat.

#### Win

The winner of combat deals +1 attack damage to their opponent. Any *Rage* points are added to the total attack damage and the *Rage* die is removed from the board. The total attack damage is always dealt to the opponent. If the winning card is a face card it has an additional effect. See **face cards** for more details.

#### Loss

The loser of combat reduces their health by the amount of attack damage they recieved. A player can spend 1 Action point to reduce incoming damage by -1. Only 1 Action point can be spent in this way. The player removes the amount of damage they received from their health counter. If this value goes below 1 the game is over. Any *Rage* the player has is removed from the board at this time.

#### Tie

When both players flip over the same value card it results in a tie and *Rage* increases. Both players add +1 to their *Rage* counter. If the *Rage* counter is not already in play then place it next to the Action die and set its value to 1.

### Face Cards

Face cards have an additional effect when combat is won. This only occurs when combat is won. No additional effect is applied when combat is lost or tied. All winning face cards give you the option to use an ability or gain an Action point.

#### King (**K**)

The **K** gives you *focus* or +1 Action points.

*Focus* gives special meaning to the Ace by turning it from the lowest value card in the deck (**A**) into the highest value card in the deck (**A\***). To gain *focus* you take the **K** and place it sideways next to your discard pile.

#### Queen (**Q**)

The **Q** gives you +1 health or +1 Action points.

Increase your Health counter by +1 if you choose. The maximum total health can never be greater than 12.

#### Jack (**J**)

The **J** gives you *foresight* or +1 Action points.

*Foresight* allows you to look at the top card of your deck and choose to keep it or discrad it. It is discraded immediately or put back onto the top of the deck.

#### Ace (**A**)

The **A** is the lowest value card in the deck. It results in a loss (or tie) and the player's deck is reshuffled. See **reshuffling** for more details.

#### Ace with focus (**A\***)

The **A\*** is the highest value card in the deck and deals +2 damage.

When the **K** is used to gain *focus* it causes the **A** to become the **A\***. It deals +2 damage this turn (instead of +1) and the player's deck is reshuffled. See **reshuffling** for more details.

### Rage

*Rage* increases the amount of damage dealt in combat. The *Rage* counter is increased whenever a tie occurs in combat or when a player spends an Action point before combat. *Rage* can never be greater than 3. When dealing damage add up all the Rage points plus card damge for the total attack damage. The maximum possible damage in a turn is 5 (**A\*** + *Rage* = 2 + 3 = 5). All *Rage* is removed from the board at the end of any turn that is not a tie.

### Reshuffling

When an Ace is played that player will end their turn by reshuffling their deck and starting a new round. At the start of a new round the player sets their Actions points to 2.

### Winning

To win, be the first player to reduce their opponents health below 1.

## Copyright

Deck Duel (Basic) © 2020 by Keith W. Thompson

Deck Duel (Basic) is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.
