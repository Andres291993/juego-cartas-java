# juego-cartas-java

- Card game about any subject where the player has 3 starting HP.

- Two players

- Both players draw 1 card. Max stats are 2 defense and 2 attack.

- There's a deck of 20 cards. 10 of them have 1 attack and 1 def, the rest have 2 and 2. (Cards should be an array, so they can be used at random)

- If one player has a card with 2 attack and 2 def, attacks the other with a card of 1 attack and 1 def. The second player looses that card and gets 1 dmg to HP. 

- If both have cards on ground of 2attack and 2 def, that's a tie and both looses the card because of retaliation. In that case, they don't loose hp.

-The 1 attack and 1 def cards can be sacrificed to get 1 HP. 

-Only one action can be made per turn, both players start the game with full deck, but it's hidden, they get cards at random and start with 2 cards. ( sacrificing a card can be made 1 time per turn and it doesn't count as an action. So a player can sacrifice one card and put other on the ground or attack)

-When HP reaches 0 or a player has no cards, game ends and the other player wins.



---Value           
----Attack  
----Defense

---Mode
----Defense mode
----Attack mode
----Sacrifice for HP
