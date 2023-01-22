---
title: Integrating Mastodon with Discord
date: 2023-01-22
tags: [Mastodon, RSS]
categories: [Mastodon, Gezel]
---
## There's something special about Mastodon
I don't know how to put it, it's just amazing. It takes Twitter but siphons out all the BS.Imagine a world where you can just join a social network without knowing the *meta* or anything like that. You follow what you're interested in, and you only see that (and what those users **boost**).

If you don't know what Mastodon is, it's basically that, but here's the layman terms:

"Mastodon is free and open-source software for running self-hosted social networking services. It has microblogging features similar to Twitter, which are offered by a large number of independently run nodes, known as instances, each with its own code of conduct, terms of service, privacy policy, privacy options, and content moderation policies." - Thank you, [Wikipedia](https://wikipedia.org)!

### But what about Discord? Where does that tie in?
So if you aren't aware, Discord is a messaging app basically, made up of "servers", or just private DMs with friends. Inside these servers, admins add bots to their servers to give additional functionality, such as moderation, roles, announcements, etc. [Gezel Bot](https://bot.gezel.io) has all that, and more.
I don't want to write this like an "advertisement" as I want it to be informative, but I do want to point out that I am the founder of [Gezel](https://gezel.io) and have written the frontend for Gezel Bot.

Why did we create this, you ask? It's simple. So many Discord bots are paid, or lock a LOT of features behind a paywall. Basically my idea was "lets make the best Discord bot imaginable that's free, and I'll eat the server costs for as long as possible". I know this won't be sustainable, but I'm willing to host it for free as long as possible. When a time comes where the bot is making me bankrupt, we can look into ways to making some money to help pay for costs.

### So where does Mastodon come on?
Simple. You can find many Discord bots that offer ways to auto post Twitter feeds to Discord, but the same can't be said for Mastodon sadly. So we began investigating.

It turns out that Mastodon uses RSS, so building this was quite simple. Basically when you add a URL to [Gezel Bot](https://bot.gezel.io) we'll automatically apply the `.rss` URL, and update your Discord with the information. If you add my account (`https://mas.to/@tommerty/`) we'll basically apply the URL to be `https://mas.to/@tommerty.rss`. From that point, anything I post will be added to your Discord, in whatever `room` you'd like!

This also works the same for hashtags on the platform too, as they have the same `.rss` feature! This way you can have your Discord auto-populate with posts following specific topics, which may be very useful, depending on your use case!

### Want to see what it's all about?
Feel free to add [Gezel Bot](https://bot.gezel.io) to your Discord server for free! 😊