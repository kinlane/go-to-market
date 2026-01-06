---
date: 2026-01-06
title: Setting Up YouTube, Apple, and Spotify Podcasts for Naftiko Capabilities
linkTitle: Setting Up YouTube, Apple, and Spotify Podcasts for Naftiko Capabilities
description: >
  Setting up our media channels as I prepare for launching the Naftiko Capabilities podcast.
author: Kin Lane ([@kinlane](https://github.com/kinlane))
---

I spent a couple of hours setting up the minimum viable channels needed to support the Naftiko Podcast out of the gate. It was interesting to see the difference in user experience between YouTube, Apple, and Spotify. YouTube is definitely the most advanced. I like the Apple one because it is 100% configured by an RSS feed for the podcast, which has it's ups and downs. Spotify was by far the worst experience, with the interface spinning wheel never stopping and every other API call failing behind the scenes.

It will be interesting to stand up a Naftiko capability to manage our podcast across just these three channels. I manage the RSS feed used to power apple via GitHub, but both YouTube and Spotify has an API, but as with any API the devil will be in the details. Spotify is cumbersome to manage, so I look forward to automating. Apple will be the easiest to automate because it is 100% YAML on GitHub, served up as an RSS feed to Apple.

There are services we can use to automate this stuff, but I'd rather define a Naftiko Capability to help us manage. I'd rather breakdown all of the APIs needed, and understand what all the details of each service is. Once I have the podcast running for a few weeks, and I get the capability defined for how I will be automating podcast management, I will explore some other channels we can syndicate to, as well as looking at what some of the aggregator services are doing when it comes to managing podcasts for users. 

I will publish podcasts to these three channels on Tuesday and Thursddays each week. I am guessing after a couple of weeks of manually doing the Spotify work I will be willing to invest more in some automation. I feel like Apple is a minimum viable experience, which makes sense. I feel like Spotify is a textbook entry for enshittification and they just don't care about experience. We'll see, I'll spend some time in there, and then get back to other platforms like SoundCloud, and we'll see how I feel.