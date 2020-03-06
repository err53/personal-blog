---
template: post
title: Adventures in Distrohopping
slug: adventures-in-distrohopping
draft: false
date: 2019-07-29T04:00:00.000Z
description: My experiences with different distros of Linux
category: linux
tags:
  - linux
  - distrohopping
---
I have been using Linux as my main operating system for about a year at this point, and have been loving it.
However, I seem to have developed a serious distrohopping addiction, peaking during stressful times, like exams.
Because of this, I have decided to find a primary distro, and stick with it, once and for all.

**A/N:** All the distros that I talk about will be linked, if you feel like checking them out for yourself.

## [Arch Linux][arch]

The first distro I tried was Arch Linux.
A minimal, barebones distro with little-to-no theming done beforehand.
Famous for it's command-line only install, I thought it would be a good challenge for me.
After finishing a basic XFCE install over the course of a few hours, I thought I was done.
I was wrong.
I spent another good chunk of my time customizing my desktop environment, before realising how futile my efforts were.
All this time could have been better spent doing something productive, like working on one of my side projects, or studying math.
I decided that for my primary distro, I wanted something that required a minimal amount of configuration, while being easy and relatively fast to install.

## [Fedora][fedora]

Next up, Fedora.
As an aspiring developer, I felt it was my duty to at least try a product in the Red Hat family.
I have tried to use Fedora KDE in the past, but felt that it was bloated and slow.
This time around, I decided to go with the intended user experience, and installed it with Gnome 3.
I used it on and off for about a week, and discovered a few things:

- I actually like stock GNOME 3
- I prefer a good repository that doesn't require me to depend on Flatpaks or third-party repositories
- I like DNF's implementation of atomic rollbacks, but don't like the poor integration with the on-demand package installer, or the GNOME software centre

The last two points, while not dealbreakers, did push me over the edge when combined with the poor performance of GNOME on Fedora, and I began to look elsewhere for a final distro

## [Debian][debian]

My jump to Debian was due to a few main considerations:

- I had previously had good experiences with Debian-based systems, including Ubuntu and Mint
- I prefer the stability that Debian-based systems provided me in the past

With these points in mind, I jumped to Debian with Gnome 3.
While the stability of Debian was nice, the old packages was a huge hassle to work around, especially since I prefer installing as much from the official repositories as possible.
If I were going to use the backports repos, I might as well install Ubuntu, or one of it's derivatives...

Wait. That's actually not a bad idea

## [Linux Mint][mint]

An Ubuntu-based distro with a unique desktop environment, similar to Windows.
While it isn't Gnome 3, I had recently changed my desk setup, and Gnome was no longer a viable workflow anyhow.
I had used Mint before, and I have one major gripe with their default desktop environment, Cinnamon.
**It doesn't handle dual batteries well.**
**Like at all.**
It just displays the level of the most charged battery, making the battery indicator completely useless on a laptop like the T470.
Their other environments aren't much better.
I am not a fan of MATE, and don't like their default customizations to XFCE.
Furthermore, Mint themes any additional DEs added after the fact, which I am _not_ a fan of.
Furthermore, I still wasn't able to find the latest version of Hugo, my preferred static site generator, in the repos.
However, it is the best option I have used out of the bunch, have useful bundled tools that work well, and requires the least configuration out-of-the-box to be useful.

## Other Distros

I have used a _lot_ of distros before, and I'll just briefly mention some popular ones that I chose to exclude from my experimentation.

### [EndeavourOS][endeavour]

The Antergos project, what I would have previously used (I really liked their XFCE defaults), is now dead.
Endeavour OS looks promising, but is still in it's early days.
I love that the project tries to keep it minimal, and encourage an Arch-like philosophy while making it easy for newcomers to get started.
I haven't installed it yet, but it is on my watchlist.
Once their online installer arrives, I will most likely test it out on bare metal.

### [Manjaro][manjaro]

I'm not a big fan of their themeing.
If Manjaro shipped without such heavy theming, and kept it closer to stock, I likely would have used it.
The AUR is nice, but I have experienced incompatibilities with the VirtualBox Extention Pack before.

### [Ubuntu][ubuntu]

I know there is a lot of hate against Canonical in the Linux community, and most of it, in my opinion, is unjustified.
They offer many different DEs, which I find to be very helpful.
I used to run Xubuntu as my daily driver.
However, I don't like what they are doing with Snaps, and would prefer to support a distro with Flatpaks by default.
Mint adds a lot of useful goodies ontop of Ubuntu, which is why I went with them instead of a pure Ubuntu-based distro.

### [Solus][solus]

I love Solus.
I think that their packaging solution and philosiphy of separating user configs and distro configs is a great idea, and their addition of Flatpaks was a good move.
The optimisations they have done on their distro are also amazing.
Even with Flatpak support, however, the repos are too small for my taste.
While I could just build from source, I would prefer to do as little maintainance as possible for updates, and thus chose to not use Solus.
There package manager, `eopkg` is also kind of slow.
I know they're still working on these various issues, and will also continue to follow this growing distro, but it's not for me yet.

## Conclusion

So here I am, stuck between a rock and a hard place.
(Or in this case, a mediocre distro and a lack of time.)
While I would love to spend the time tweaking Arch Linux to fit my needs, or deal with Debian's older packages, at the end of the day, I need something that just works.
Mint, while not perfect, works well enough that I haven't had to switch for about a week, and have been able to get actual work done.
Perhaps in the future I will revisit this, or maybe Mint will finally fix the dual battery issue.

## Update
I jumped to Arch a week after writing this, but found the bleeding-edge packages too unstable for me. I'm back on Mint for now.

## Update 2
In February, I needed to send my laptop to Lenovo to get it repaired, and wiped it for security. The operating system I ended up settling on was Arch again (The AUR is simply too useful to give up at this point)

[arch]: https://www.archlinux.org/
[fedora]: https://getfedora.org/
[debian]: https://www.debian.org/
[mint]: https://linuxmint.com/
[endeavour]: https://endeavouros.com/
[manjaro]: https://manjaro.org/
[ubuntu]: https://manjaro.org/
[solus]: https://getsol.us/home/
