---
title: Tweedisc, a twitter integration bot
description: An application to use Twitter without leaving the comfort of Discord
author: "Devajith"
tags:
    - Twitter
    - Discord
    - Integration
    - Tweet
date: 2022-01-20 12:57:39
---

## What is Tweedisc?

Tweedisc is an application that allows people to post tweet links on their community discord servers and like, share or retweet each other's Twitter posts without leaving Discord.

## Usecase and Target Audience

Tweedisc turned out to be a handy tool for people, businesses, projects, and pretty much everyone else that has a community on Discord. The tool helps discord communities engage with stuff happening on Twitter and also boosts engagement for small communities by interacting with each other. The linking process only takes a few clicks. This tool saves time for users of having to log in or switch accounts just to Retweet/Like a Tweet.

## Profits and Expenses

My friend helped me ship the product to the target audience. In 10 days, we had 20 people signed up. It runs on a spare google cloud server that I have (basically free, google has an "always free" VPS instance that I use to run small applications).

Currently (as of 26th Jan 2022), the project has one paying customer (5$/month) and 51 users. The cost to run the server is zero, making the net revenue 5$.

## Development Sprint

The working prototype was built in 2 days (new year sprint). This was my development process:

1) I jumped straight into the API Documentations for Twitter and Discord to see if the project is viable.

2) Started coding a Discord bot using the python library - discordpy. The bot will react to Twitter links with a like and retweet reaction. Whenever a user reacts to the message, the bot gets notified.

3) Signed up for a Twitter developer account to access the Twitter API. API is rate limited but more than enough for an initial prototype.

4) Implemented a linking system linking a user's Twitter account with their Discord utilizing Oauth2 authentication for Discord and Twitter.

5) The bot makes a request to the Twitter API on behalf of the user with the corresponding reaction whenever a user reacts to a Twitter link.

6) If the user is not registered, the bot deletes the reaction and message the user with a URL to link their Discord account.

## Other Contributions

While building the prototype, the python API library for Twitter - "Tweepy"  had a feature missing for which I made a pull request, but it did not get merged as the maintainer eventually pushed an update as there were some changes that the maintainer needed to do.

## Oauth2

I spent some time with Oauth2. I learned how authentication works and enjoyed implementing the system.

## Reflection

I learned that if you code and you love to do it. You can build amazing things that people use. That is a joy.
