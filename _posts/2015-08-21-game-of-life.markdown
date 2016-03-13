---
layout: post
title:  "Conway's Game of Life"
date:   2015-08-21 11:55:00
categories: blog
meta: project
---

This blog post is about my recent fascination with [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life). A simple implementation of the game I made can be found [here](/game-of-life).

>Are we biology or God or something higher? 
I know my heart beats and I listen to it. The beat is biology, but what is the song? -- James Frey

I initially stumbled across Conway's Game of Life through an entry in the book ["This Will Make You Smarter"](https://www.goodreads.com/book/show/13035774-this-will-make-you-smarter) (a *very* good read, 11/10), in which it was presented as a scientific concept that would improve everyone's cognitive toolkit. Developed by John Horton Conway in the 1970s, the Game of Life is a cellular automaton—a model consisting of "cells" spread over a grid that change their states depending on the state of their surrounding "neighborhood." The name of this model can be very misleading as the Game of Life is not a game in the traditional sense. For starters, there are no players, only an omnipotent hand that bestows life upon this little 2D pond in the initial state. 

Like everything else in this world, cells in the Game of Life can only be one of two things: alive or dead. The first generation of live cells--as I mentioned--is bestowed by an omnipotent hand, after which the game progresses under the rules of cells behaving like [social introverts](http://nymag.com/scienceofus/2015/06/apparently-there-are-four-kinds-of-introversion.html). For instance, a live cell with fewer than two live neighbours dies, as if by the perils of solitude (a gas pipe leaked and you didn't have neighbours to check on you, gg); whereas a live cell with more than three live neighbours also dies, as if by being overwhelmed by a large crowd. A live cell with two or three live neighbours continues to live on, perfectly content with the size of its social circle. A dead cell with exactly three live neighbours becomes resurrected, as if by reproduction (for the sake of moving on, let's not question how reproduction works in a fictitious universe).

These rules lead to some fairly interesting results with bacteria-like pixels crawling across the screen:

![Life Animation](http://www.diga.me.uk/LifeAnimation.gif){: .center-image }

After some iterations of the game, the unfortunate blobs that were only meant to be works-of-progress are eliminated by the rules of this universe while other life forms become stable and are able to survive. Two notable categories of life forms that can be easily spotted are still lifes and oscillators. In the above image, the 2 by 2 squares and circular objects scattered across the grid mostly undisturbed are still lifes, while the blinking lines are oscillators that move in consistent patterns. Game of Life hobbyists on the Internet have been diligently recording, naming, and organizing these life forms in the spirit of biologists. Here are some examples of known "creatures" that were given very endearing names (my favorite is loaf):

![Life Forms](http://mathworld.wolfram.com/images/eps-gif/StillLifes_1000.gif){: .center-image}

The most magical part about this model is that so much complexity is borne out of such simple, trivial-sounding rules. After the initial seeding, the game seems to take on a mind of its own and starts behaving in unpredictable ways. This is why Conway named the game "Life," after the most seemingly complex and unpredictable thing in our world. In a BBC documentary, Conway made the witty remark that "mathematics is the simple bit. It's the stuff we can understand. It's cats that are complicated." Some of the world's greatest mysteries indeed lie within cats, and of course, ourselves. 

In a meta sense, the Game of Life has taken on its own life and made quite a ripple in the world. With a simple google search, you can now find tonnes of softwares simulating the game and websites chronicling the patterns of life forms. I urge you to explore these resources and even build an implementation of your own, as it is a rewarding and humbling experience. 

