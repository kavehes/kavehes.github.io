---
layout: default
modal-id: 0
date: 2017-09-26
img: handfull.png
alt: image-alt
project-date: December 2017
category: Game Jam - Solo
description: Ludum Dare 40
---
A hand full of Blocks is a card game made during the Ludum Dare 40 done as a solo developper. It is a two player game where you are given 20 life point, a 20 cards' deck and must use it to make your opponent's life drop to 0, but you must be careful as at the end of each turn you lose life equals to your hand's size and "Block" card aren't discardable.
  
The Jam version is pretty rough and need a lot of work, and i'll probably work on it at some point to add deckbuilding and a proper versus mode when i find the time.
<br><br>
#### Art for the Cards
![Cards]({{ "/img/handfull/cardlist.png" | #}})

<br><br>
#### Cards effect
**Heal** : You gain life equals to the number of cards in your hand  
**Recycle** : Discard one of your cards then draw a card  
**Steal** : Steal one of your opponent's card, Steal turns into a Block  
**Transfert** : Transfer exactly two of your blocks to your opponent  
**Breaker** : Break all Blocks from your hand  
**Turn** : Turn one card from your opponent's hand of your choice into a Block  
**Damage** : Deal damage to your opponent equal to your hand size  
**Draw** : Make your opponent draws two cards  
**Block** : Cannot be discarded at the end of your turn  
<br><br>
#### Rules Summary

Each player starts with a hand of 3 cards, 20 life points and 20 cards  
  
First you draw a card.  
Then you may play one card from your hand, using it's effect.  
Then once that card's effect resolve you may discard any card in your hand except "Block" cards.  
Finally you take damage equals to the number of cards in your hand and your opponent starts their turn.  
  
Once one of the players' life drops to 0 or they can't draw a card, that player loses the game.  
<br><br>
#### The Game
<iframe frameborder="0" src="https://itch.io/embed/200832" width="552" height="167"></iframe>
If the displayed link is incorrect, please head **[here](https://kavehes.itch.io/a-hand-full-of-cards)**