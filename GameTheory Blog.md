# Description

Experiments in rapid improvement in games, explaining the theory (math, psychology, etc.) behind everything. Each game approached in a similar manner, exposing the preparation and analyzing the results. Occasionally some posts about more general strategies.

# Format

Research: Notes before making a post
Initial post: Always contains the following two items

* Get started - all the preparation and equipment necessary to begin your quest
* Get better - how to practice, learning curves to expect
* Key concepts

Reaction: Results from the experiment and reflections on the practice method, etc.

# Posts

## Poker

### Research

* http://www.twoplustwo.com
* http://liquidpoker.com
* Theory of poker
* Let there be range

### Initial post
#### Get started
#### Get better

### Reaction

## Mahjong

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## Bridge

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## Chess

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## Go

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## Backgammon

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## Pinochle

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## AsynchronousAnagrams

### Research

### Initial post
#### Get started
#### Get better

### Reaction

## 吹牛

### Research

No matter how many cards you put down, expected value of # gotten rid of is the same!! (assuming other person calls BS)
But what you really want is expected cards lost
E(L|BS called) = r/p*p - (1-r/p)*t
E(L|BS called) = r - t + rt/p

      0      1       2       3       4      5
--- ----- ------- ------- ------- ------- -----
 1    0      1       -       -       -      -
 2    0    1-.5t     2       -       -      -
 3    0    1-.67t  2-.33t    3       -      -
 4    0    1-.75t  2-.5t   3-.25t    4      -
 5    0    1-.8t   2-.6t   3-.4t    4-.2t   5

Let b = probability of calling BS

Then expected lost is E(L) = b*(r - (1-r/p)*t) + (1-b)*p

Assume b is an increasing function of p?
probably also an increasing function of t

if b is constant sqrt[trb/(1-b)] gives a MINIMUM to E(L), so endpoints are better

obviously some bonus awarded if you really want next person to gain cards => BS less

how to spread out your cards

4 cards

2+1, 2+1
60%*3 + 60%*3*g =
g= chance of getting back around

winning a BS call - very advantageous

I decided to make a risky BS call because I know my opponent would call my BS...

### Initial post
#### Get started
#### Get better

### Reaction

## Traffic

### Research

### Initial post
#### Get started

Unblock Me Free - 1200 puzzles, 600 beginner 600 intermediate/advanced 

#### Get better
#### Key concepts

Forced positions:
long vertical block: must be at bottom
two small vertical blocks: top block must be at top
 
difficulty of modeling with 'temporal element' -- must unblock car in current position, only then can unblock in later position 

### Reaction

many puzzles done without much conscious effort - just try to find a 'non-trivial' move (one that opens more possibilities)
at first, conscious thought sometimes incorrectly deemed something impossible. this got better over time.
 
# General Resources

* Mentat Wiki, "ways to become a better thinker" http://www.ludism.org/mentat/HomePage
