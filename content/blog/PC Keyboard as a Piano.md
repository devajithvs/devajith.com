---
title: Play Piano on a PC Keyboard
description: An idea/WIP that allows people to play (any) instruments on their laptop/pc
author: "Devajith"
tags:
    - "Music"
    - "Software"
    - "PC Keyboard"
date: 2022-01-02 12:12:39
---

Interesting idea, but this is still a work in progress.
## Motivation

So, picture this: I'm a broke university student who loves singing and playing instruments, but can't afford a piano or a guitar. But fear not! I've got a computer with a keyboard, and I'm a coding enthusiast.

So I thought, why not combine my love for music and coding? And thus, the idea was born to play piano with a computer keyboard! But of course, it's still a work in progress, so bear with me here.

Now, I did some serious analysis, mostly on pianos. Did you know a classical piano has 88 keys, but a regular computer keyboard has 101 keys? Talk about a close match! But wait, some laptop keyboards have fewer keys, and we can't mess with those function keys, or we risk wrecking our computer settings. 


## What is a way to play piano with fewer keyboard keys?

So, what's the solution? Well, we've got 26 character keys, 10 numbers, and 10 special keys to work with. And the cool thing about computer keyboards is that we can use combinations, like using <kbd>Shift</kbd> for added options. With some clever mapping, we can cover the entire piano keyboard with just 44 characters!

## Limitations

But of course, there's a catch. Musicians often need to play two tones concurrently, which can get tricky with non-one-to-one mapping. Like, try playing <kbd>c</kbd> and <kbd>Shift</kbd> + <kbd>c</kbd> at the same time, it's like attempting to walk in two opposite directions with each foot - an impossible feet (pun intended) that defies the laws of physics.

But fret not, I've got a plan! I'll assign the shorter black keys (sharps) to <kbd>Shift</kbd> + character combinations, since they're less commonly used. And after some thorough Googling, turns out a chord with both flats and sharps is pretty uncommon, so it's all good for our use case!

## Implementation ideas

Now, onto the implementation ideas. I'm thinking of making this software run anywhere, and I've got a soft spot for the Rust programming language. But hey, I'm not sure how portable that'll be, so I might consider making a web app with web assembly.

Oh, and here's the best part! I've got plans to gamify this whole thing, taking inspiration from a popular app/game called "Piano Tiles". Imagine black tiles pouring down the screen, and you gotta tap them at the right time to play sweet tunes! 🎶🎮 But unlike "Piano Tiles", you'll be playing real music, not just wasting time! 🎵

If I move along with this idea, I plan to release it under an open-source license.

Of course, with all the university placements, assignments, and part-time work, time might be a challenge, but hey, where there's a will, there's a way!

## Update

Good news (or bad?), everyone! I've been able to save up some money thanks to my internship as a compiler engineer, and I finally bought a real piano! So, I might have to scrap my "keyboard piano" project after all. Turns out, playing on an actual piano is a whole different ballgame. But hey, at least I won't be limited to just 44 keys anymore! Can't wait to unleash my musical talents on those real piano keys. Who knows, maybe I'll even learn to play a chord with both flats and sharps - take that, limitations! Cheers to chasing dreams.