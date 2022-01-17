# Project Puch

Notifications and chat service to connect streamers and content creators with their community.

Live Stream: [https://www.twitch.tv/iamborto](https://www.twitch.tv/iamborto)

## Introduction

I know, the name of the project is not great, but like most developers, I can't name things - I hope you can help. For now, let's focus on what it is and which problem is trying to solve.
I was looking for a project to work on when I noticed most streamers I was following were using Telegram Channels to interact with their communities - at least in Italy. We'll get on what can be improved later.

For me, it's a good balance between applying current skills and learning new ones. On top of that, the core features are widely understood and independent from each other. This makes the project a good fit for live streaming, something I wanted to do for a while.

## Telegram

Telegram's target audience is not content creators. They are a generic chatting service. For this reason, they do not and never will develop features targeted to a specific niche.

This is somewhat mitigated through bots. However, relying on untrusted and possibly unmaintained 3rd party projects is not ideal. And asking for specific updates or features to bot authors is quite hard at best, to just impossible.

## Proposed Features

* Reply to channel messages
* Telegram integration
  * Post messages on Telegram automatically
* Twitch integration
  * Log in with Twitch account
  * Add users to private channels when they subscribe
  * Send notifications when going live
* Reaction to channel messages
* Unlockable emotes
* Moderators
* Bots

## Technologies

The details on how and why I use the following technologies will be discussed during streams but here's a quick summary:
* Backend
  * C# - .NET 6.0
  * Azure Functions
  * CosmosDB (SQL and Gremlin)
  * SignalR
  * Active Directory B2C
* Frontend
  * Typescript
  * Ionic React
  * Capacitor (iOS, Android, PWA)
  * TailwindCSS

Open Source? Not yet. I am sure of the direction I want to take.

## How to help

I stream most of the development on my Twitch channel. For now, just jump in the stream and say hi!