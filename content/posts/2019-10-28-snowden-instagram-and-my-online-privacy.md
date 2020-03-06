---
template: post
title: 'Snowden, Instagram, and my online privacy'
slug: online-privacy
draft: false
date: 2019-10-28T04:00:00.000Z
description: My experience reducing my digital footprint
category: privacy
tags:
  - privacy
socialImage: "/media/surveillance.jpg"
---
**TL;DR: I left (part) of the internet, and cut back on the information I due to privacy reasons.**

I never used to care about privacy.
Many of the people I know still don't care.
I don't blame them, not everyone has the time to research and form an opinion on privacy.
But for those who want to learn more about my story or want to learn more about privacy, read on about why I started caring.

## Middle School

In June of 2013, Edward Snowden released his infamous documents detailing the NSA's invasion into US citizen's privacy.
I was just entering the world of technology at that time and had no idea what this meant for internet security until a few years later.

In my 8th Grade class, as part of a reading/essay assignment, I had to read the book _Digital Fortress_, by Dan Brown.
Of course, being a work of fiction, many of the events and details within the book are unrealistic.
However, this book sparked curiosity within me.

> Is digital surveillance beneficial, or does it do more harm than good?

I don't believe that I can make as good of an argument as others in the field, so I will leave some links here so you can do further research.

- [Safe and Sorry – Terrorism & Mass Surveillance: **Kurzgesagt – In a Nutshell**][kurzgesat]
- [Why privacy matters: **Glenn Greenwald**][greenwald]

My conclusion was that digital surveillance is both harmful to privacy, and provides no benefit.
Furthermore, I found that the digital world has led to indiscriminate surveillance from several parties, including advertisers, governments.

However, I brushed it off as inconsequential.
After all, what do I have to hide?
I'm a teenager living in a freedom-respecting part of the world, with no reason to care!
So, I put off my doubts and continued with my life.

## High School

High schools are a terrible environment for those wishing to protect their privacy.
While people have left Facebook, the alternative they have started using, Instagram, is just as bad.
Combined with the _influencer dream_, many teens have no qualms of putting their entire lives online, with little-to-no control over their data.

When I made my account back in 2017, I didn't care about privacy, people being able to see what I was up to, or companies like Facebook being able to watch my every move.
Hell, before I deleted my account, I had left my profile public for all to see.
So what changed?

## Fall 2018

Through a series of events which I no longer remember, I started getting into cryptography and infosec.
One might think that security and privacy are closely connected, and they are.
Security allows for privacy to exist.
Without technologies like encryption, there can be no privacy on the internet.
But who cares, right? The lock on my browser means my data's encrypted, right?

However, the deeper I looked into how the services I use secure my data, the more concerned I became.
What happens to the disappearing stories I post to Instagram?
What about my Facebook Messenger chats?
Who sees the emails I send?
The family pictures I put on Google Photos?

That encryption I talked about?
Companies still have full, decrypted access to my data.
The only encryption that exists is between my device and the company.

The realization I came to, was that these companies didn't care about my privacy.

**They only care about my data.**

### Company Analytics

The business model of Google, Facebook, and now, Microsoft, revolves around selling data, in one form or another.
Sure, they don't admit it directly.
They claim that what they're selling is an "Advertising Profile", but it just means that the company selling the data has already performed the necessary analysis on the data.
For example, Gmail has admitted to using your email contents to sell advertisements.

Even if companies claim to not search your actual data, the metadata that comes from this analysis is surprisingly thorough.
Whether that's interests, medical problems, or potential purchases, a lot of data that many would consider being personal is being analyzed and sold.

### Governmental Spying

Aside from companies being able to access my data, there is also the threat of governmental analysis.

Are governments actively targeting me right now? Probably not.
Are they passively collecting everything I put online? Definitely.

According to Snowden's leaks, the NSA passively collects an insane amount of both data and metadata of both US and Non-US citizens.
And from his leaks about PRISM, I would assume Canada's NSA equivalent, the CSE, is doing the same thing.

While I have no reason to fear the current government, I can't make any guarantees about a future Canada.
Even if I could guarantee Canada to hold the same viewpoints on politics, religion, and other controversial topics, for my entire life, I definitely can't make that guarantee about other countries.

So, I decided to do something about this

## Taking back my privacy

While I try not to share too much of my life online, I, like everyone else, have left digital footprints everywhere.
Whether social media, utilities, or other sites, I have not been careful in obscuring my digital trail.
Since I can't feasibly delete everything about me, or leave the internet without an outlet to express myself, I decided to compromise.

Delete as much unused social media as possible, and switching to federated (read: decentralized) social media that gives me more granular control over my privacy.

### Leaving Social Media

Leaving social media was one of the hardest things I have ever done.

Even though I never liked Instagram, it's messaging feature had made it crucial for communication with most people I know.
However, I didn't have many followers anyway, so I just convinced the people that needed to contact me to find another way.

Facebook, or at least the social media side, was easy. Nobody uses it anyway, so I deleted my entire profile.

Facebook Messenger, however, was (and still is) a sticking point.
Many of my project chats are on there, and it remains one of the only common points of contact with the people I know.
Until Signal, Wire, or another platform becomes more popular, I have to compromise by only using one insecure messaging platform.

I've already cut back from Twitter a lot, but I still keep it to have a public point of contact, and because Twitter blocked Mastodon's bridge feature (I'm still angry about that).

I don't put any private information on Reddit anyway, so I just regularly delete old content.

I don't have WeChat installed on my phone anymore, and don't use it, so I didn't bother doing anything with that account.

### Leaving Gmail

Well, I didn't completely leave Gmail, but I moved my private communications over to Disroot, a privacy-respecting alternative to G-Suite, run by volunteers in Amsterdam.
While they don't use per-user disk encryption, any secure communications should be done via GPG anyway so I won't fault them there.

I would use Tutanota, but their contact sync doesn't integrate as an account in Android, which is a deal breaker for me.
I'll keep my account open for the day when that feature is implemented, and probably switch.2019-10-27

### The future

I am hoping to move more of my life away from giants like Google and Microsoft.
I hope to move away from Android's G-Apps for my primary phone, but since I do some Android development, stripping G-Apps isn't an option at this point.
I also want to move away from G-Suite, but my school is locked into the Google ecosystem, so there's not much I can do there.

## The outcome

I most definitely am less connected with people after cutting out social media.
However, I am still in contact with my closest friends, and strangers have to work a fair bit harder to discover me.
While this does make it more difficult to make connections, I am willing to make this tradeoff for the privacy it brings me.

## Recommendations

While I generally try to keep my opinions and values to myself, I strongly urge those of you who spent the time to read this post to consider the data you put out there.
It certainly doesn't need to be as extreme as deleting some of your social media like me.
Just being mindful of what you post and regularly deleting online data is enough for most.

For those of you who would like to take back their privacy, I would recommend considering your threat model.
You might not care about the government, even though they are spying on you.
You might not care about companies spying on you either.
That's entirely up to you.

If you have decided that you would like to reduce the data that companies and governments can collect about you, I would recommend taking a look at the [EFF's Surveillance Self-Defence][ssd], and to look at either [privacytools.io][ptio], or [PRISM Break][prism] for software recommendations.

## Conclusion

I will probably start posting things that I think are important to privacy, and about what I am doing to protect it.

I will continue to post tech and other related content. (I'm getting a new mechanical keyboard, so you might see a review on that soon!)

No, I will likely not return to Instagram. (Aside from all the privacy issues, the environment on Insta is pretty toxic as well.)

Yes, I might leave other social media if I find reason to.

And yes, I will try to update this blog with what I've been doing.

Leave a comment below on your thoughts if you want, or email me directly via the contact form if you don't trust Disqus.

[kurzgesat]: https://www.youtube.com/watch?v=V9_PjdU3Mpo
[greenwald]: https://www.ted.com/talks/glenn_greenwald_why_privacy_matters
[ssd]: https://ssd.eff.org/
[ptio]: https://www.privacytools.io/
[prism]: https://prism-break.org/
