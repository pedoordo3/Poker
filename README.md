# Poker
Build a Poker Odds Calculator with these specs:

Card Input: Allow keyboard input using shorthand notation:

Rank: A, K, Q, J, T (10), 9-2
Suit: c (clubs), h (hearts), d (diamonds), s (spades)
Example: "Kc" = King of Clubs, "Ah" = Ace of Hearts
Input should validate and reject invalid entries


Your Position: Add a dropdown or selector where you choose your starting position:

Early, Middle, Late, Button, Small Blind (SB), Big Blind (BB)
Display your selected position on the screen


Card Entry Flow (step-by-step):

First: Enter your 2 hole cards
Then: Enter flop (3 cards)
Then: Enter turn (1 card, optional)
Then: Enter river (1 card, optional)
User should be able to clear/reset at any step


Odds Calculation:

Calculate equity (win %) against a random opponent range
Assume opponent has any two random cards
Display: Win % (and optionally tie %)
Update as cards are added


UI:

Clean, simple interface
Show current cards entered (hole cards, board)
Show your position prominently
Show win % clearly
Able to reset/start over
