
## Some intro notes

Unix has a culture
Unix has a distinctive art of programming
Unix carries a powerful design philosophy

Understanding these traditions will help you build better software

Unix was born in 1969, and has been in continuous production use ever since. That is older than the PC, Microprocessors, video display terminals, and contemporaneous with the first semiconductor memories.

It was on more machines than any other OS. It has seen more architectures and more odd hardware than any other OS.

Machines have increased a thousandfold in power, languages have mutated, born and died, industry practice has gone through multiple revolutions, and unix hangs in there.

## Is it all good?

Maybe it will never achieve the popularity on the business-desktop market dominated by Microsoft.

Outsiders say it's an academic toy, a hacker's sandbox.

Some say it will be forever a perpetual niche. To useful to die, but to akward to break out of the back room.

## Some of it really is. Most of it.

#### Open Source Software
A term invented in 1998, but peer review intesive development of freely shared source code was a key feature of the Unix Culture from day one.

#### Cross platform portability and Open Standards

#### The Internet and the Web
The TCP/IP standards, on which the internet is based, are closed related to UNIX. In such a way that atempts to make them work on other operating systems have benn bedeviled by incompatibilities and bugs. Even the URL is a child to the idea of a uniform namescpace everywhere. More: you can't be an Internet expert, withiout a deep understanding of UNIX.

#### Flexibility
Many operating systems touted as more modern or user friendly than Unix achieve their surface hlossiness by locking users AND developers into one interface policy. Narrow, rigid. Tasks the designers have anticipated are very easy, but the rest is often impossible or at least extremely painful.

The beautiful thing about unix is its fliexibility. The ways that its simple programs can be combined to produce useful effects that not even its designers anticipated.

#### Unix is fun to hack

#### The lessons of unix can be applied elsewhere

## The unix philosophy

**Ken Thompson** started by thinking on how to design a small but capable operating sustem with a clean service interface. It's not theological or theoretical. It's bottom up, not top down. It's based on experience. It's pragmatic.

**Doug McIlroy**, the inventor of Unix pipes had this to say:

1. Make each program do one thing well. If you need to do a new job build afresh rather than complicate the old.
2. Expect the output of every program to become the input to another, as yet unknown, program. Don't clutter the output. Don't insist on interactive input.
3. Design and build software to be tried early.

In a summary: Write programs that do one thing and do it well. Write programs that work together. Write programs to handle text streams because that's a universal interface.

Some more rules:

1. Rule of modularity: Write simple parts connected by clean interfaces.
2. Rule of clarity: Clarity is better than cleverness.
3. Rule of composition: Design programs to be connected to other programs.
4. Rule of separation: Separate policy from mechanism; separate interfaces from engines.
5. Rule of simplicity: Design for simplicity; add complexity only where you must.
6. Rule of Parsimony: Write a big program only when it is clear by demonstration that nothing else will do.
7. Rule of transparency: Design for visibility to make inspection and debugging easier.
8. Rule of robustness: Robustness is the childof transparency and simplicity.
9. Rule of representation: fold knowledge into data, so program logic can be stupid and robust.
10. Rule of Least Surprise: In interface design, always do the least surprising thing.
11. Rule of silence: When a program has nothing surprising to say, it should say nothing.
12. Rule of repair: When you must fail, fail noisily and as soon as possible.
13. Rule of economy: Programmer time is expensive; conserve it in preference to machine time.
14. Rule of Generation: Avoid hand-hacking
15. Rule of Optimization: Get it working before you optimize it.
16. Rule of diversity: distrust all claims for "one true way"
17. Rule of extensibility: Design for the future, because it will be here sooner than you think

## Attitude Matters

To do the unix philosophy right, you have to be loyal to excellence. You have to believe that software design is a craft worth all the intelligence, creativitym and passion you can muster. Otherwise you'll never look past the easy, stereotyped ways of approaching design and implementations. You'll rush into coding when you should be thinking. You have to value your time. If someone has already solved a problem once, don't let pride or politics suck you into solving it a second time instead of re-using. Never work arder than you have to; work smarter instead. And save the extre effort for when you need it. Software development should be a joyous art, a kind of high-level play. If this attitude seems proposterous or ambarassing, stop and think. Why this? You need to care. You need to play. You need to be willing to explore.


## History

The original unix was a third system. Its grandfather was the small and simple Compatible Time-Sharing System (CTSS), either the first or second timesharing system ever deployed. Its father was the pioneering multics project. Multics did collapse of its own weight.

#### 1969 - 1971

It wwas born at Bell Labs, by Ken Thompson. The first speculation on timesharing machines was uttered ten years earlier by computer scientist John McCarthy (lisp, AI). The most powerful machines of the day had less than a megabyte of storage and ram combined. Video display terminals would not appear for another six years. The standard interactive device was the ASR-33 teletype. Slow, noisy, uppercase only on big rolls of yellow paper. Part of the reason of the unix tradition for terse commands and sparse responses was this.

