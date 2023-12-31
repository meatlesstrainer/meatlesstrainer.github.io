---
title: 🎄🐰 Advent of Code 2023 in Hare
date: 2023-12-01
---

I'm learning a new language this year, like I usually do when I do AoC. This year it's [Hare](https://harelang.org), since I like its vibes and [its author.](https://drewdevault.com/)

Right now, I'm mostly focusing on getting my head around the language. Once I get a little free time, I'm going to go back and optimize/clean my code.

Spoilers for the entire thing, obviously!

## Day 1

[Solution source.](https://git.sr.ht/~sverona/advent-2023/tree/master/item/day1.ha)

Okay, well, it came out swinging this year.

There's an edge case in the problem statement that I was *going* to say I didn't believe was clearly stated, but in retrospect I absolutely blew my skirt on. I was going to say that the first and last occurrences of a "digit" shouldn't overlap, but then I looked at the test case again and realized that part 1 absolutely did exactly that --- the first and last digits are the same `7`. You got me; I wrote bad, incorrect code on day 1, because I didn't read the problem statement closely enough. You could even say I cheated by looking at Reddit. Yowza.

For the record, my approach today was to (for part 1) pull out every numeric character into an array, and use the first and last members of that array. Notably, I didn't bother parsing it backwards, which was the correct approach, although it makes me go, *ugh, no, I really don't wanna do that.* Even though it's more elegant, too! This is what you get for being lazy.

It was a subtle bug, but it was indeed a bug. I was wrong. I learned a lesson. Oh, goodness me, this is going to be an interesting one.
