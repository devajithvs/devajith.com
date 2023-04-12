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

Tweedisc is an application that changes the way people engage with Twitter on Discord. It allows users to effortlessly post tweet links on their community Discord servers, and like, share, or retweet each other's tweets without ever leaving Discord.

## Usecase and Target Audience

Tweedisc has quickly become an indispensable tool for a wide range of users, including individuals, businesses, projects, and communities on Discord. It simplifies the process of interacting with tweets on Twitter and boosts engagement for small communities by facilitating interactions within Discord. With just a few clicks, users can easily link their Twitter accounts and start liking, sharing, and retweeting tweets, saving time and effort.

## Profits and Expenses

My friend helped me ship the product to the target audience. In 10 days, we had 20 people signed up. It runs on a spare google cloud server that I have (basically free, google has an "always free" VPS instance that I use to run small applications).

Currently (as of 26th Jan 2022), the project has one paying customer (5$/month) and 51 users. The cost to run the server is zero, making the net revenue 5$.

**UPDATE**: Tweedisc started gaining traction quickly, and within a few months, it reached a milestone of $400 in Monthly Recurring Revenue (MRR). This was a significant achievement for me, it proved that I can make money online and work for myself. With a lot of paying users, Tweedisc was able to generate decent revenue.

**UPDATE2**: Despite the initial success, Tweedisc faced a setback when Twitter stopped providing API access. This decision affected the functionality of the tool, as it heavily relied on the Twitter API to interact with tweets. As a result, the project had to be discontinued, and the revenue generation came to a halt.

## Development Sprint

The journey of Tweedisc started with an ambitious development sprint that spanned just two days during the New Year. Here's a brief overview of the development process:

1) Extensive research and understanding of the API documentations for Twitter and Discord to determine the project's feasibility.

2) Coding of a Discord bot using the powerful Python library, discordpy. The bot is designed to react to Twitter links with like and retweet reactions, with notifications sent to the bot whenever a user reacts to a tweet.

3) Signing up for a Twitter developer account to gain access to the Twitter API, which is rate-limited but more than sufficient for a prototype.

4) Implementation of a seamless linking system that connects a user's Twitter account with their Discord account using OAuth2 authentication for both Discord and Twitter.

5) Integration of the bot with the Twitter API, allowing it to make requests on behalf of users and perform corresponding reactions to tweets whenever a user reacts to a tweet on Discord.

6) Creation of a user-friendly system that prompts unregistered users to link their Discord account with a URL, and deletes reactions and sends messages accordingly.
    
## Other Contributions

In addition to the successful development of Tweedisc, I also made significant contributions to the Python API library for Twitter, called "Tweepy." I submitted a pull request to address a missing feature, although it did not get merged as the maintainer had already pushed an update. Nevertheless, this experience allowed me to further enhance my coding skills and gain valuable insights into open-source collaboration.

## Oauth2

The implementation of OAuth2 for Tweedisc was a challenging yet rewarding experience. It provided me with a deep understanding of how authentication works and allowed me to hone my technical skills in this area.

## Reflection

Tweedisc was a successful project that earned $5672 in revenue to date and had a significant number of paying users. However, due to Twitter's decision to stop providing API access (made it very expensive), the project had to be discontinued. Tweedisc was my first successful startup.