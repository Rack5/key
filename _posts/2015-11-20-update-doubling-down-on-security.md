---
layout: post
title: 'Key Update: Doubling Down on Security'
permalink: /double-down-on-security/
---
A couple months ago we started thinking about ways we could make sure Key was more secure. Our challenge was making sure the security didn't get in the way of productivity. 

So we got together, and brainstormed some awesome features to keep you protected. 

Today, we’re really excited to show them to you! Let’s cut straight to it.

### Bouncer
Every so often somebody asks me “What if someone takes my phone?” I was embarrassed responding with: “That person would need to take your computer too?”

While the situation is unlikely, it is possible someone leaves the two on a desk together.

We thought the problem through and through and designed a few solutions. Obviously, we decided to go with the most intuitive one. 

We are calling it “Bouncer”. If you have ever unlocked your iPhone before, you already know how to use it.

When you turn on Bouncer, Key will check your fingerprint or lock screen pin to unlock your Mac. This virtually guarantees that if someone else picks up your phone, they can't log in as you.
Bouncer will always let you out and lock up, but to get back in, you’re gonna need to show some ID!

Enabling it is as simple as going through the “More” menu, and we made up [some docs]({{"/docs/iphone/" | prepend: site.baseurl}}) to help you if you need it.

### Verified Device
Not to scare you, but there are some people out there that like to hack other individuals. There is one kind of attack called a “Man-in-the-Middle Attack”. 

During this attack, someone could <strong>theoretically</strong> collect the data your phone transmits. Then they would relay it later and forcing your computer to unlock... no bueno!

We didn’t like the idea of this being possible. We decided to lock it down with a simple account to verify your phone. Every second, your phone will send out a unique message which your computer uses to verify it. If a hacker steals this message, it won’t be usable the next second.

Logging into your Key account is easy, when you start Key after the update, Key will ask you for your phone number. Key will then send a 6 digit confirmation number via Text that you will use to verify your device.

You’ll only have to do it once, and it will make sure the only people unlocking your computer is you.

### More Info
Apple added extra security measures to their latest operating system “El Capitan”(OS X 10.11). Part of these changes interfered with Key for Mac’s auto updater.

If you are using El Capitan, you’ll have to download Key again from this website. We are really sorry for this. We don’t like giving you extra steps, but we promise it will never happen again!

If you aren’t on El Capitan yet, you have nothing to worry about! Just run the *Check for Update* command and Key will be update faster than you can say 'One Mississippi…'&#42;

*&#42;We haven't quite tested that... but it's probably close.*

### Download Key Today!
If you aren’t a Key user yet, go [download Key]({{"/download/" | prepend: site.baseurl}}) to get started! We've been told its the easiest security software ever used! 

If you have any questions or would like to chat, send an email over to hello@rack5.co! We're quite friendly!
