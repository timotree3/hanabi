# Selfish Conventions
* This is an instruction how you should respond to a _Selfish Color Clue_ while playing a 2-player game.

<br/>

## Table of Contents
1. [Selfish Conventions](#selfish-conventions)
2. [Interpretations](#interpretations)

## Selfish Conventions
* Here are some conventions related to _Selfish Color Clues_ you might use in the games:

### Selfish Chop Move
* If the player gives a _Selfish Color Clue_ touching **only** one card and the card is not on chop.
* It is a signal as a _Chop Move_, and the clue receiver should chop move their cards to the right of the clued card.
* For example:
  * Alice gives a blue clue touching a blue 1 on Bob's slot 3.
  * Instead of playing his blue 1, Bob gives a blue clue touching a blue 2 on Alice's slot 4 (which is one-away-from-chop).
  * This is quite strange, since Bob can just get the blue 2 after playing his blue 1. If the blue card is on chop, it is reasonable, for Alice is going to discard a playable card. However, it is not on chop.
  * Imagine the situation where Alice has a critical card on chop, and Bob sees Alice has nothing to do in her turn. If he saves the critical card on chop, the team might lose a playable card, which is quite bad. That's how this convention works.
  * Now, it's Alice's turn, she is surprised that Bob didn't play his blue 1 and gave a blue clue to her. It is not a Selfish Focus Inversion, since it only touches one blue card.
  * Then she realizes her blue card is exactly a blue 2 and also Chop Moves her slot 5 as a _Selfish Chop Move_.

### Selfish Focus Inversion
* See [here](https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md#selfish-focus-inversion-sfi--sfi).

<br/>

## Interpretations
* Case A: The clue only touches one card.
* Case B: The clue touches multiple cards.

### Case A1: The clued card is on chop 
* Interpretation: **_Normal Play Clue_**
* Explanation: Your teammate is going to discard the playable card.

### Case A2: The clued card is one-away-from-chop
* Interpretation: **_Selfish Chop Move_**
* Explanation: Your teammate has a critical card on chop.
* Notes: Why do your teammate have a critical card on chop? The most common situation is you just discarded another copy of the card and made your teammate's chop become critical.

### Case A3: The clued card is two-away-from-chop
* Interpretation: **_Selfish (Double) Chop Move_**
* Explanation: Your teammate has two critical cards on chop.

### Case B1: One of the cards is on chop
* Interpretation: _**Normal Play Clue** (Chop Focus)_
* Explanation: Your teammate is going to discard the playable card.

### Case B2: None of the cards is on chop and one of the cards is one-away-from-chop 
* Interpretation: _**Normal Play Clue** (Focus on the leftmost)_
* Explanation: If you don't do it this turn, and if your teammate discards after you play the card, the team loses the focus.
* Example:
  * Alice has a known blue 1. Bob has a blue 2 on slot 2 and a blue 4 on slot 4.
  * If Alice doesn't give a blue clue to Bob this turn and play the blue 1, and if Bob has nothing to do and discards his chop.
  * Then, Alice is not able to give a 2-for-1 blue clue since it turns out to be a _Chop Focus_ clue and the focus is no longer on the blue 2.

### Case B3: None of the cards is on chop and none of the cards is one-away-from-chop 
* Interpretation: _**Selfish Focus Inversion**_
* Explanation: It follows the current convention "Selfish Focus Inversion".

<br/>