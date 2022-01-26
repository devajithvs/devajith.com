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

I love singing and playing instruments. But currently, I am a broke university student who cannot afford a piano or a guitar. On the bright side, I love coding and have a computer with a keyboard.

The idea struck me and ergo I did an analysis, mostly on pianos. A classical piano has 88 keys. A regular computer keyboard (US) has 101 keys. It is possible to do a one-to-one mapping of the keys. But some laptop keyboards have fewer keys. Also, we must refrain from using some function keys as it might wreck the computer settings.

## What is a way to play piano with fewer keyboard keys?

Let's assume that we only have the character keys (26), numbers (10), and special keys (10) at our disposal. The good thing about a computer keyboard is that we can use combinations instead of just having one key typed at a time. We can cover the entire keyboard with precisely 44 characters by taking other keys like <kbd>Shift</kbd> for combinations.

## Limitations

There's a catch though. A musician might need two tones played concurrently, which is difficult if it is not a one-to-one mapping. For instance, it will be impossible to play the tones corresponding to the characters <kbd>c</kbd> and <kbd>Shift</kbd> + <kbd>c</kbd> simultaneously.

The best solution for this problem is to have the shorter black keys (sharps) have <kbd>Shift</kbd> + character combination as it's less used than other Normal flat tones. Upon further googling, I figured that a chord with both flats and sharps is uncommon and thus acceptable for our use case.

## Implementation ideas

The current plan is to make software that would run anywhere. I would love to do it in the programming language Rust. But, I am not sure how portable I can make it. So, I might consider making a web app with web assembly.

I have plans to gamify this. I borrowed the idea from a popular app/game called "Piano tiles". There are black tiles that come pouring down the screen. All you have to do is tap when it is the right time and it plays sweet tones.

"Piano Tiles" is an exceptional idea for an app. It is possible to blend some of that into this project; analyzing popular songs, ordering them based on difficulty, and then gamifying them. Unlike "Piano Tiles" the cool thing is that a person can play "real" music on this app instead of just wasting time playing.

If I move along with this idea, I plan to release it under an open-source license.

I hope I will find enough time to complete this project despite all the placement, assignments, and part-time workload.
