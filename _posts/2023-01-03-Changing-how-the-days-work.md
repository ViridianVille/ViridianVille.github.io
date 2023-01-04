---
layout: single
title: "Changing how the days work"
date: 2023-01-03 23:59:59 +0100
categories: project_viridian viridian_changes day_cycle
author: Tifa Zabat
---
We're changing how the day works. Seriously. We're changing it.

## From 6 to 1

In the current *Legend of the Green Dragon* code, there are 6 game-days in 1 real-day, with 1 game-day being 4 hours long. This means that some of the descriptions such as "PLAYER did ACTION in 28 days!" make it sound a lot longer than it actually is. We're changing this to 1 game-day in 1 real-day, with 1 game-day being 24 hours long. This means that the descriptions will be more accurate, and it will be easier to keep track of how long things have been happening for. It will also improve roleplaying, as rather than having characters saying "Good Morning" at 9pm in the game, they'll be saying it at more appropriate in-game times.

## Agreeing on a standard

Of course, setting the game day to match real time comes with it's own obstacales, as we're not all in the same timezone. We're going to be using UTC (Coordinated Universal Time) as our standard time, as it's the same time for everyone, and it's the time that the game server is set to. This means that if you're in the UK, you'll be 1 hour ahead of the game time during the Summer, and if you're in the US, you'll be 5 hours behind. This is a bit of a pain, but it's the best way to make sure that everyone is on the same page.

### Technical note

The game will be set in accordance with Zulu Time, which matches UTC and GMT 0. Any discrepencies between Zulu Time and UTC/GMT 0 will be too minor to pose technical problems.

## What does this mean for me?

We know that users will often wait for a new game day to revive if they've been defeated in battle or in the forest, to make up for this, we're going to change a few of the current 'daily' actions to be every 4 hours at 00:00Z, 04:00Z, 08:00Z, 12:00Z, 16:00Z, and 20:00Z. This means that you will still be able to revive every 4 real-time hours. Some of the 'daily' actions, will be kept as daily actions, in effect slowing to every 24 hours, this will apply to actions such as the Lottery Draws.

## Making Game Time clearer

As well as changing how the day works, we're also going to make the current In-Game Time easier to see, with it being added to the top-bar on PC/Tablet, and the side-menu on mobile. This will make it easier to see what time it is in-game, we'll also be adding a 'Speaking Clock' command to some roleplay areas, that will announce the current in-game time in that space. 

## What about the current game?

We are not rolling this change out to the current codebase. This change will only be available once Project Viridian launches.

## Questions or Feedback

Our Developers are actively seeking Player Feedback for this change, so if you've got any questions or comments, please join in the discussion in #the-rewrite channel on our Discord server. Thanks!