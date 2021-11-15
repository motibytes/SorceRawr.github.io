---
layout: post
title: Road to Blockchain Development
permalink: development
picformat: .gif
---

<a href="{{ page.url }}"> ![image](/img/development.gif) </a>

This details how I learned to develop on blockchains. I recommend jumping to [this summary](#jumptome).  

# Part 1 🕵️

Before I was committed to learning how to develop on these platforms, I started out with Crypto Zombies and Eth.Build.

## [Crypto Zombies](https://cryptozombies.io/en/course)

## [Eth.build](https://eth.build/)

While I didn't understand too much of what was going on, what I was doing was familiarizing myself with the Solidity language and seeing how it interacted with the Ethereum blockchain. Austin Griffith's Eth.build gave me a look at how the magic of private and public keys can be used to do all kinds of amazing things. However, I was far from being able to do anything.  

# Part 2 👨‍🚀

At some point I stopped being only mildly interested and decided I wanted to build a project and that I would find out how. I had to dive into the water.

At this stage, I learned primarily by using parts of these two tutorials [There were actually 3, the 3rd one did not make the cut].

What I learned is that there are many working parts and you might as well be familiar with all of them.

## [Deploy an NFT smart contract on Polygon Tutorial](https://medium.com/pinata/how-to-create-layer-2-nfts-with-polygon-and-ipfs-aef998ff8ef2)

## [Deploy an NFT smart contract on Ethereum Tutorial](https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/)

The issues I ran into while doing these forced me to do more research and understand more of what was going on.

I now understood that all of this stuff centers around my sacred Solidity contract and its functions.

I learned how to use **Hardhat**, which is like this barebones rickety spaceship you tweak a bit to get your solidity contract launched out there onto these
blockchain networks, and **Alchemy** was a provider that could handle switching between blockchain networks for me. **Pinata** was the service that would hold my precious data, and **IPFS** was even more magic based on that same sweet sweet hashing technology, long live cryptography. **OpenZeppelin** were the guys writing all the code for ERC-721's, the NFTs I'm interested in, and all you had to do was import their code into your contract and push it out. I also learned that a few javascript scripts were all it took to call the functions I'd created in my contracts.

Now I could get something pushed out and I knew some things that were going on, but I barely understand the logic of smart contracts.
I figured out I could go to Etherscan and look at anyone's contracts I wanted [and that you want to scroll to the very bottom of them first, past all the imports]. Thanks to Crypto Zombies and some hands-on experience my brain was now starting to be able to read the code. These words in the top of functions, "Private" and "Public" and similar words were starting to make sense. But there was no way I could write this stuff.

I wanted more, too. How could I get my code into a website? How could I build a functional project?

# Part 3 👨‍💻

I looked for more resources. I found Solidity by Example and dived in, working through the text and learning from the teacher in the associated video series.

## [Solidity by Example](https://solidity-by-example.org/)

This is what started to give me a true grasp of the language.

Then I found Austin Griffith's ETH Scaffold. An amazing project. This project would set you up with an entire development 'studio', including a live front end [and so much more], and the ability to deploy these live. It made everything easier and was a one-stop solution from start to finish.

## [Ethereum Dev Speed Run](https://medium.com/@austin_48503/%EF%B8%8Fethereum-dev-speed-run-bd72bcba6a4c)

I was able to get this off the ground and finally see a project interact with the front-end website.

# Part 4 🧙

There was just one problem I found. I didn't know React. I didn't understand these systems, and I wanted more control over the production process.
I looked for more development tutorials, and one I found told me again that I should learn React. It recommended this video series, and I couldn't have been more interested.

## [React Tutorial](https://www.youtube.com/watch?v=j942wKiXFu8&list=PLwgC-cD-X2_W-Og-cX-W1lzG3Jppy_Y7k&index=70)

I think it was at this point that I realized, wow. Pretty much all of this live development usually revolves around node.js technology. I spent one long night on a quick refresh of that as well.

## [Node.js course](https://www.youtube.com/watch?v=zb3Qk8SG5Ms&list=PLwgC-cD-X2_W-Og-cX-W1lzG3Jppy_Y7k&index=57)

-

# Part 5 🌞💡

This was the part where I felt like I was beginning to be able to see what might lay over a mountain of information and began to see a horizon in the distance.

I always save the best for last, and now went on to follow Alchemy's excellent How to Create an NFT Tutorial. This is where all of this really started clicking for me. Now, I had seen and done some of this before. I knew how to deploy to hardhat. I had seen how React hooks plugged in functions to a live website. Now I got to see how this technology plugged into Web3.

## [Alchemy NFT Tutorial](https://docs.alchemy.com/alchemy/tutorials/how-to-create-an-nft)

Here I could see that real deployment of a full project would be possible. I also learned a few things. I learned that really, you don't need to worry about the front-end, ever, at all.  For example, as it turns out, they set all this up so that your contract will generate an **ABI** with all your functions and that's what you plug into the front-end website. Easy.

# Part 6 - Now ✨

Now I'm here. I stumbled across a smart contract I wanted to fork and work with and play with. I've been wanting it to click in my mind, how simple this is. How it usually is, is as simple as writing a "get" function to get what I want, and a "set" function to set the state of something.  
Now I've gone back to the eth scaffold, which I may not end up using for my final front end, but I see now is an amazing, amazing tool to automatically and instantly give you access to all of your functions, to play with them and mess with any contract to your heart's content.

I'm at the point now where I can see there are all kinds of fun projects I'm going to be able to build and I'm crazy excited. The amount I can create in a day is rising exponentially as I start to grasp what I'm doing. This seriously becomes a blast.

I still have questions to answer for myself, among some of the tops are,

"How are people standardizing storing arrays of data on IPFS?" [Current assumption: The data is already stored. It has nothing to do with the blockchain.] [Update: Yes]

"How do I generate NFT's with random attributes?" [Current Assumption: ~~A script is called by the front-end, created, hosted on IPFS, and then the metadata for that data is passed in as a variable to the mint function on the contract.~~] [[Update: Not unless you're a psychopath]

# Part 7 - Road to my Mastery of Solidity YouTube Playlist ‍🚀

-

## [YouTube Playlist](https://www.youtube.com/playlist?list=PLwgC-cD-X2_W-Og-cX-W1lzG3Jppy_Y7k)

-

# Part 8 - NEW - The Golden Road - Updated 10/12/2021

If you're like me and you ran headfirst through all these tutorials, hitting walls and barely scraping by, and you survived until now,
congratulations, now you're gonna wanna kill me.

You've probably thought, why isn't any of this information condensed, why can't I find a single resource that has everything I'm looking for in one place?
Well, I finally found it. It's here at [cryptodevhub.io](https://cryptodevhub.io/wiki/ethereum-virtual-machine-tutorials),

^^^^ the resource I've been looking for for countless months.

And the tools! The glorious, glorious tools! [the tools](https://cryptodevhub.io/wiki/ethereum-virtual-machine-tools)
[Update 11/14/2021: Out of that list of tools, I am particularly fond of [eth95.dev](https://eth95.dev/)/ ]

<div id="jumptome"> - </div>

# Part 9 - NEW - A Different Angle - Updated 11/14/2021.

Looking at the journey I took from a different angle, here were the steps.

1. In Part 1, I was pretty much wasting time in the sea of possibility, as in, I was reading about code I might never actually use. This was mostly an advanced form of procrastination.  

2. In Part 2, the most important part of this entire journey, what I was doing was I was proving to myself, giving evidence to my mind that launching an NFT project was possible. I've learned that instead of taking a long journey to get to the end,
make a prototype project. Rush through something like a train with no brakes. This changes the experience so that the end of the project is no longer a possibility that your mind can convince you may never happen. It has already happened because
you have already been there.

3. In part 3, I now wanted to take this more seriously. I had a strong desire to know what I was doing. I had a real reason to learn and read about code that I knew I would use. That's when Solidity By Example was not a boring and dead manuscript,
it was the goldmine of usable practical code I needed to understand. The motivation and energy required to read the boring docs were generated by my previous step in part 2.

4. In parts 4 through 6, I now had a baseline understanding from my own experience of my project, and I was now gaining exposure to the NFT development world and seeing how others were doing things. Most importantly I was not reinventing the wheel,
and I was not using "just any way" to do a part of the project. I was looking for the best ways I could find to do parts of a project. As I explored I found that different template projects out there were better or worse depending on what it was I
wanted to make.

5. At the end of part 6, I was asking the right questions, but the answers were hard to come by. What I was reaching was the information plateau for which I could see no higher. I came to see that most of what I could find [though I had a lot more resources after finding cryptodevhub.io] were existing setups that were highly customized already and language-specific [I now know this is called "opinionated"], and "enterprise-level" tutorials like Alchemy's NFT project, which was mostly great except when it came to how they decided to go about minting an NFT in their front-end logic or providing an explanation to do anything simple. As I spent time at this plateau, I began to see that there were questions and processes I could not find answers to. This was the first time in my life when I realized the information wasn't there. I would not be surprised to learn that many devs in this space might not know how to work with a lot of this tech as it was intentionally designed, because the information is lacking.

6. It was at this point that I was looking for these answers that I came to learn that some information is essentially insider knowledge. At this point, you should talk to people who have done it. [I am probably not that person because I almost certainly am not using your setup.]

Some words of advice from this moment in time, aside from the **actual creation of art** and *learning*, do not create a long workaround to solve a problem if it's going to cost you several days. That is reinventing the wheel. Someone else has done it already, and that means you just need to find out they did it so it can take you a few minutes instead of a few days.

Unfortunately, there is no way around the hardest part of development is getting stuck on errors. There's no way around this. Note that Hardhat breaks often and others have recommended not wasting time on phantom errors in hardhat. Make a new hardhat project and move your contract to it as soon as you get an error as your first troubleshoot every time. With errors, have patience, and if you've been on it for too long, take a walk, get some fresh air and do something else. When programming, having access to games like Tetris or any game or activity that stimulates connections for play is often helpful.

# Part 10 - NEW - NFT Platforms - Updated 11/14/2021

A few of the main 'NFT creation platforms' I've discovered are here, though most I have not used myself.
These will not so much teach you NFT development as they will give you a custom setup for a specific kind of NFT project.

[CryptoPunks](https://github.com/cryptopunksnotdead/programming-cryptopunks)

[HashLips](https://github.com/HashLips)

[Bitbirds 1](https://github.com/nft-fun/generate-bitbirds)

# Additional Advice 🤖💛

It's okay to not know how to do things. Try to do it. If you can't figure it out, if you can't find the answer, move on and try something else. Keep trying things until something works. Play.

All of this is less complicated than it seems on the surface. Once you know what's going on, a lot of this tech is stupidly simple to use.

Don't try to learn. Pick something you want to build, and start building it. I pretty much wasted a lot of time with crypto zombies because I wasn't trying to create something.

Don't rush. No matter how fast you go, your brain is going to have to process the information. It does the majority of this work while you sleep.
If you load it up with too much information, it will laugh at you and discard the entire stack.
Feed your brain with some information each day and allow it to cook. It's like cooking, information cooking. Mmm.

So remember, always cook your brain! 👨‍🍳 🍌

Did this help you in your journey?
Here's the original Twitter post if you want to share it: [twitter.com/BytesTheBlessed/status/1440841630097948672](https://twitter.com/BytesTheBlessed/status/1440841630097948672)

Do you have additional resources you believe are mission-critical to starting out in eth dev? Please share them with me and I will add them.
