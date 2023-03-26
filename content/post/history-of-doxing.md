---
author: "Code Kisser"
title: "How Internet Celebrities Have Been Doxed"
description: "A collection of anecdotes on various people who have been doxed and how exactly they got doxed."
date: 2023-03-16T03:13:26Z
---

A collection on how various internet celebrities and other individuals have been doxed or hacked.
<!--more-->
I created this so that I and other people can learn from their mistakes + I couldn’t find a list like this online.

Note: I’m not a security expert or anything, nor am I a doxer. I just wanted to document the interesting stuff I found when googling doxing.

## Boogie2988

According to a blog post boogie wrote shortly after his hack, his accounts were stolen because his phone number was hijacked [[1](https://medium.com/internet-creators-guild/getting-hacked-as-an-internet-creator-982d03637e86)].

> The hacker instructed the Verizon representative to change my phone number from my Samsung to his old burner phone. Once the rep had done this, the hacker basically had my cell phone in his hand and the cell phone next to me had become a worthless brick. He used that device to recover and change the password to my email address and once he had that… he had everything. I had used the same email as the recovery address for my YouTube channel and my PayPal.

### Learnings

> He pointed out some big mistakes I had made: using the same email address as the recovery email for everything, and having this be a public email address.

## DreamWasTaken

Dream posted a picture of his kitchen on Twitter, and a fan matched the picture to a public Zillow posting [[2](https://screenrant.com/minecraft-dream-doxxed-face-reveal-speedrun-cheat-controversy/)].

## Ernest Lehmitz: WWII German Spy

The spy would write letters to Germany with secret messages written in invisible ink between lines, but the FBI was able to track him down using the non-invisible decoy contents of the letters (that were framed as innocuous, though fictitious ramblings about life). The ramblings had small shreds of truth about Ernest’s life which the FBI was able to use to build a vivid image of the real Ernest [[3](https://www.silive.com/news/2018/07/staten_island_wwii_espionage_c.html)]. For example, he wrote about his garden and housing troops at his house (which was common at the time). The FBI only needed 12 of these letters.

The reason why I find this particularly interesting is that it’s always been said that the best lies have some truth, as quoted by Benjamin Franklin, Twain, Solon, etc. In an ironic twist, this was exactly the German spy’s downfall.

When I asked my friend how he would defend against doxing, he said he would put false personal information on the internet so doxers would get incorrect details. Admittedly, this was my idea at first, too. Unfortunately, with enough effort, or with Modern tools like (probably, never used it) Maltego, fake information can immediately be seeded out. Best practice will always be to not give out as little information as possible.

## Scott Alexander, Slate Star Codex

Scott is a blogger who caught the eye of a NYT journalist in 2020, and the journalist found Scott's real identity and exposed it in an NYT article [[4](https://slatestarcodex.com/2020/06/22/nyt-is-threatening-my-safety-by-revealing-my-real-name-so-i-am-deleting-the-blog/)] [[5](https://www.nationalreview.com/news/what-a-nyt-reporters-doxxing-threat-says-about-the-papers-standards/)]. The journalist was able to find Scott's real identity because "Scott Alexander" is his real first and middle name, in addition to Scott being public about his occupation and general location. The journalist used all of this to find him on Google.

The reason why this is notable is not because of how he got doxed, but the circumstances surrounding it. The NYT journalist initially reached out to Scott in order to write a "mostly positive" article on Slate Star Codex, but the article would include Scott's full name that the journalist uncovered. Scott requested that his full name not be published and even threatened to delete his blog, but NYT refused and said “it was New York Times policy to include real names, and he couldn’t change that.“ Scott created a public post condemning NYT for planning on publishing his identity against his wishes. In response, NYT allegedly changed the article from "mostly positive" to a negative piece that frames Slate Star Codex as a far-right leaning website, and allegedly used misleading wording to make Scott seem to maintain racist views.

Something I found interesting was how NYT did not seem to support the journalist's initial plan on exposing Scott based off the quotations [5]. Maybe if Scott went to the chief editor, the editor could have ordered the rogue journalist not to dox Scott. For other threats like trolls, Scott would be SOL.

## Scott Cawthon

Scott Cawthon, creator of Five Nights at Freddy's, was cancelled in 2021 for his donations to controversial American politicians [[6](https://www.forbes.com/sites/erikkain/2021/06/18/five-nights-at-freddys-controversy-scott-cawthon-republican-donald-trump-lgbtq-backlash/?sh=10a1d1aa6f8a)]. This eventually led to Scott leaving FNAF production.

Large ($200+) donations are part of the public record. If you use your legal name on social media, people can search your donations rather easily on websites like [opensecrets.org](https://www.opensecrets.org/donor-lookup). The website shows Scott Cawthon donated to Donald Trump and Mitch McConnell, Mark Fischbach (Markiplier) donates to Bernie Sanders, Bill Nye the Science Guy donates to Maria Cantwell (D), Madonna donates to Democrats, and much more.
Even if you never mention your political leaning online, it can potentially be exposed by other people if your real name is known. Furthermore, note how the reverse can be done in order to find your location. If someone knows your real name, a politician you donated to, and the approximate amount you donated, they can find which city and state you live in.

## Japanese Idol

A man claimed that he was able to locate an Idol by looking at the reflection in her eyes in a selfie [[7](https://www.bbc.com/news/world-asia-50000234)]. He allegedly made that up, and was actually able to track her down using geolocation metadata in the photo [? Random Redditors].

No article mentions what specific social media platform she was posting on, but most reputable social media sites strip images and videos of metadata before publishing them. This has not always been reliable as, for example, Twitter leaked users’ exact geolocation for years [[8](https://www.wired.com/story/twitter-location-data-gps-privacy/)].

## Domain Theft

![Man wearing pantyhose mask](https://media.istockphoto.com/id/469958369/photo/dangerous-man.jpg?s=612x612&w=0&k=20&c=4wsAfucv2ssPpJUPtj_rw6SMJAQKC5Y0zU_MBCGliNw=)

A man disguised with sunglasses and a pantyhose mask showed up to another man's home and robbed him at gunpoint... for his domain URL [[9](https://www.theverge.com/2019/12/9/21003858/instagram-polo-rossi-lorathio-adams-ii-sentenced-14-years-domain-name-state-snaps)]. How the home address was uncovered, I don't know. If I had to guess, they probably used the WHOIS registry. You are required to give a name, address, phone number, and other personal identification information in order to legally own a domain on the internet. This information can easily be looked up on [who.is](https://who.is/)


WIP