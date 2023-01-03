---
title: My experience running a Mastodon Instance
date: 2023-01-03
tags: [Mastodon, self hosting, Ubuntu, Fediverse]
categories: [Personal]
---
Let get something out of the way first... This was complicated. I was hoping for a easy-to-use Docker experience, and that's not what I found.
Even using something like [CapRover](https://caprover.com/) I faced issues. Want to use something other than Ubuntu or Debian? Yeah... Have fun.
As someone who mainly uses Fedora Server, I had problem after problem getting it to work. I did eventually get it working, but it took about 5 hours of tinkering over multiple days with a friend who is better than I on Ubuntu to get up and going.
But after all this, we finally got [iCreate.Social](https://iCreate.Social) off the ground!

## Upon migrating. 
Migrating was actually quite simple, a lot easier than I anticipated. I even made a simple step-by-step guide on the [Gezel Wiki](https://wiki.gezel.io) that I'll outline here in case you're curious:
```
1. Create an account on iCreate.social

2. Head over and log into to your existing Mastodon account, and head over to `/settings/migration` and fill in your iCreate username and your password for your current instance.

3. Export any data you want from `/settings/export` in your current Mastodon server

4. Head over to https://icreate.social/settings/aliases and fill in your existing Mastodon server

5. Head over to https://icreate.social/settings/import and import your data that you exported.
```

## What it's like running an instance.
Quiet, very quiet. Unless you got a bunch of folk ready to join your instance, you're going to be lonely. It was just me and Trent from Gezel, and it still currently is. I understand that with anything, getting users to your services is always the hardest part, and it's not like I've promoted it a tonne, but it is still disheartening. But some people set up instances just for themselves, and that I'm perfectly ok with! But this instance in particular wasn't supposed to be that way, but I digress.

You actually get a lot of control with it, and can do loads of things and see a lot which is quite interesting! I was worried it was going to be a different dashboard to track everything but with most apps I use (Tusky and Fedilab) you can actually view everything from there which is really nice! A lot better than I expected.

### Customizing
This part was fun, especially as someone who classes themselves as a `web developer`. Here's a screenshot of iCreate:
![iCreate.Social](https://i.imgur.com/4XGLfZH.png)
I had a lot of fun making CSS changes which is quite easy if you understand CSS. We styled this basically in tune with our other services like [Gezel Bot](https://bot.gezel.io) and such.

### Response
We opted for very low caching rules to try help the server not end up with 0 storage, but what that does mean that if you're loading the instance for the first time in a few hours, it's slow, really slow. And I have this running on a 8 core, 16gb server with SSD storage. So there is a fine balance you need to find with that alright.

## Going forward, will I keep it?
Won't lie, probably not. This was more of a test of 'how easy is it' rather than a need. I miss the local tab on Fosstodon. But I don't know, maybe if more people start using it I can justify the need. I'm not looking forward to when it comes time to update Mastodon, I imagine it's going to break for some reason, so that'll be fun..

What are your thoughts on Mastodon? Join me on my [Discord](https://gezel.io/discord) and let me know! 