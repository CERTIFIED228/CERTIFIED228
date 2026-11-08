# Hi, I'm Mateusz

Cybersecurity is what I'm most passionate about, especially the side of it that deals with scams: how they fool people, and how to catch them before anyone loses money or has an account taken over. I like pulling apart something that looks harmless to see what it's really doing, then building a tool that spots it automatically.

## Why I build these

I grew up with phones and computers, so when a text says my parcel is waiting or my bank account has been locked, I can usually tell something's off. A lot of older people never had that. They didn't grow up in a generation built around technology like mine did, and the technology they did learn has changed massively since they last used it. Parcels get "rearranged" through links in texts, banks send messages instead of letters, and a fake website can copy the real one right down to the logo and the padlock next to the address. Scammers know all of this, and they go after the people who are least likely to notice.

That's why I made these projects. I wanted tools that do the noticing for you and say in plain words what's wrong, so you don't have to be an expert to stay safe online.

## Projects

### [lookalike-watch](https://github.com/CERTIFIED228/lookalike-watch)

A browser extension for Chrome and Edge that warns you when the website you're on is a fake copy of a real one: paypa1.com instead of paypal.com, a fake Royal Mail redelivery page, an HMRC "tax refund" site. It also checks every site against about 390,000 known phishing sites. Everything is checked on your own computer, and nothing you browse is ever sent anywhere.

It comes with a scanner for the other side of the problem, so a company can find fake versions of its own website as soon as they're registered.

[Download and try it](https://github.com/CERTIFIED228/lookalike-watch#download-and-try-it) · Python, JavaScript, Chrome extension, DNS

### [pkg-sentry](https://github.com/CERTIFIED228/pkg-sentry)

The apps people rely on every day, from banking to messaging, are built out of thousands of free code packages written by other developers. Attackers publish malware disguised as those packages, and if one gets in, it can end up inside the app too. pkg-sentry checks a Python or JavaScript package for signs of malware before a developer installs it, without ever running it. Tested on real malware it had never seen before, it caught about two thirds of it, while flagging around 2% of popular, safe packages.

[Download and try it](https://github.com/CERTIFIED228/pkg-sentry#download-and-try-it) · Python, static analysis, supply-chain security

## What I work with

Python, JavaScript, Chrome extensions, DNS, Git, GitHub Actions, pytest
