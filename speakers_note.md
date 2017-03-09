# step 1

I will talk about "Mental Poker".
This slide was made when I was in university.
And I presented in COINS LT.
COINS means COlledeg of INformaiton Sience,
It is course name I was major in.

This talk does not require knowledges about computer science,
but if you know about cryptography, I think it is more interesting.

# step 2

Do you know about Mental Poker?
If you know about this, raise your hand.

# step 3

Mental Poker is proposed in 1981,
by these three mens.
Do you know these guys?

# step 4

I want to remember you these initials S, R and A.

# step 5

Do you remember these guys, about Public key cryptosystems,
and their initials R, S, A.
So they are creaters RSA cryptosystem, which is the one of the
most popular public key cryptography.

They also invented Mental Poker.

# step 6

Mental Poker's abstact is can you play fair game of poker over the phone?
Or over the internet.

# step 7

So without any third-party, who is trusted by everyone.

# step 8

Yes, we can.
When I created this slide, this phrase was popular.

# step 9

How do we play Mental Poker?
But in order to simplify the explanation,
we use the phisical cards and boxes instead of phone or the internet.

# step 10

First, we need 52 cards and 52 boxes.
Since the player put a card into the box, 
We can not distingish what card in the box from outside.

# step 11

Then we prepare 52 padlocks, which is in Japanese "Nankinjo".

# step 12

A player can put a card into a box,
get a card from a box, but the box is not locked and
lock a box by his pandlock.
Players can lock the locked box with their pandlock.


# step 13

A player can unlock his padlock.

# step 14

But a player can not put a card into box locked by the other player,
and get a card, unlock the box.

# step 15

I will introduce the protocol of Mental Poker.
We consider that three operation which are required by playing poker.
They are shuffling, drawing and opening cards.

# step 16

First, I explain shuffing cards.
Player A, who we call Alice, puts all each cards into each boxes and
locks them by her padlocks.

# step 17

And Alice sends locked boxes to player B, who we called Bob.

# step 18

Bob shuffles the boxes and locks them by his padlocks.
In this time, these boxes are locked by both Alice and Bob.

Next we need to draw some cards.

# step 19

Bob sends the boxes to Alice.

# step 20

Alice selects 5 boxes and sends them to Bob.
This five boxes will be her hands.

# step 21

Bob unlock his padlocks of 5 boxes,
which are sent from Alice.
But these boxes are locked by Alice's pandlock,
so Bob can't look the card in the box.

Bob sends the 5 boxes to Alice.

# step 22

Alice unlocks her padlocks of 5 boxes, and
get 5 cards in the boxes.

# step 23

Likewise.
However, this protocol is very hard to play.

# step 24

So we want to play Mental Poker on the computer, 
instead of phisical cards and boxes.

# step 25

If we use Cryptography to play poker,
we can detect cheats with very high probability.
In Mental Poker using phisical cards and boxes,
we have no choice but to open master key and
unlock all box to detect cheats.
But it also opens player's game strategy.

# step 26

If you want to give more information,
you should read this article.

# step 27

Thank you for your listing!
