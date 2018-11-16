---
layout: post
title: Is it possible to live 100%  in a linux shell??
---

 Yay!  The answer is "Yes"
 
 ![linuxx](/images/linuxx.png)
 
Here, I would to share a little one day story of Bryan Lunduke, who is a writer and works as the Social Media Marketing Manager of SUSE. He once took a challenge to use nothing but a Linux terminal for 30 days. First Day experience , Here is what he wrote about his Day 1:

The day started as I expected it to. I fired up a terminal window and made it full screen and launched tmux—a terminal multiplexer. (I'm keeping a traditional desktop environment running in the background for a few days as a safety net while I get things working just right.)

For those new to the concept of a terminal multiplexer, think of it like a tiled window manager (multiple windows arranged in a non-overlapping fashion)—only just for terminals. That way you can have multiple shell sessions (and multiple applications) running at the same time within the same terminal.

Luckily I’ve used tmux enough in the past to know the basics (Ctrl-B tells tmux that you're about to issue it a command, Ctrl-" and Ctrl-% splits the current shell session into two, and arrow keys move between shells). Still, it took me a few hours before I was fully comfortable navigating around.

I’m not going to lie. After a full day of using tmux, it feels a little cumbersome. Not confusing. Not hard. Just a tad awkward. As I continue, this it might be worth trying out other multiplexers (like GNU Screen) to see which one feels the most comfortable for me.

## Email

Before I could go much further, I needed to get a few essentials taken care of. I started with email.

I played around with a few options, including "mutt" and "notmuch." Both seem like excellent text-based email clients. But I opted to go with alpine for the moment. The interface just made more sense to me right out of the gate, and alpine keeps the essential commands (like "R" for Reply) on screen most of the time. Eventually I'm sure I won't need any of those little helpers, but they're nice to have while I'm getting comfortable.

No real problems here at all. Configuring alpine for IMAP to fetch my email proved to be just as easy as configuring a graphical client like Thunderbird. And using it was pretty doggone straightforward. It's an email client.

## Instant messaging

With email taken care of, I turned my attention to instant messaging. What I found completely caught me by surprise: Instant messaging from the terminal is totally sweet.

First is "finch." The ncurses (text)-based interface for the libraries power Pidgin. That means I now have a powerful, multi-protocol, multi-account instant messaging client right here in terminal land. It's fast and, while a little quirky, very usable. Color me impressed.

The other instant messaging client that rather impressed me was "hangups." The only thing this client does is connect to Google Hangouts, but it does so quite well. It has a nice, simple tabbed interface, it shows all of your recent conversations (just like you'd see in a Hangouts app), and it shows the full history (including offline messages). Being as nearly every Linux developer and nerd I know uses Hangouts, so must I—at least until I can persuade everyone to move off onto a different service (which I have, so far, failed at). So, having a quality terminal client really is a pleasant surprise.

## Web browsing

With email and instant messaging out of the way, I turned my attentions to web browsing.

I started off assuming I was simply going to be using "lynx," the traditional grand-daddy of text-based web browsers. I was pleasantly surprised that other (rather good) options were available.

First up, "w3m". It is probably the most pleasant on the eye of all the text-based browsers I've tried. The rendering really is enjoyable to read (usually). Then I tried "ELinks." It supposedly sports some support for JavaScript (though I haven't actually tested that part out yet), which is both surprising and damned impressive.

During the afternoon I jumped back and forth between all three browsers. I'm honestly not sure which one I'll end up using more often. But for right now, I'm just tickled pink that I even have options.

## Word processing

Now that I could effectively communicate with the world (in the most basic ways), I needed to figure out how to actually get some work done. I needed a word processor.

And I found a fun one: WordGrinder.

It’s fast, is easy to use, has a nice, simple menu system (hit Escape and then either use the arrow keys or hot keys), and supports .odt and HTML (and a few other formats). I rather dig it—quite a lot. I’m using it right now to write these very words.

(How meta—I’m in a word processor writing words about writing words in that word processor.)

The only downside is that it doesn’t support turning text into a hyperlink, which is kind of important and something that, if all goes according to plan, you’ll see in this article. So, how do I do that?

I write the article (without any links) in WordGrinder. Then export to HTML, open that in a text editor (in this case, Nano) and add the links by hand.

Only one problem: I then have an HTML file. I’m used to storing all of my documents in OpenDocument (.odt) format, and I’d prefer to be able to send something like that to my editor for publishing.

Pandoc to the rescue! This puppy converts just about every document format I can imagine (including ePub, .docs, .odt and HTML). I’m not sure how well it works on complex documents (images, tables and the like) just yet. But for articles with hyperlinks, it seems to work like a charm.

## What scares me?

So far, so good. Day 1 is complete, and I was actually able to get real work done. But as I continue researching ways to accomplish various tasks, there are a few challenges looming on the horizon that I simply don’t have solutions for. Yet.

* How on Earth am I going to edit an image? I’m in a freaking text-based terminal.
* I already miss YouTube. I wonder if there’s some way to stream YouTube clips, translated to ASCII somehow. It sounds ridiculous, I know, but it seems possible.
* I have solutions for most social media (more on that tomorrow as I fine-tune things), but using GooglePlus via w3m or lynx is downright painful. I need to find a better way.

But those are problems for the days to come.

For now, I’m going to enjoy the fact that I was able to actually get all of my work done without jumping back to a graphical desktop. And I actually rather enjoyed myself while doing it.
