footer: Write the Docs PDX 2016
slidenumbers: true
build-lists: true
theme: Merriweather

# [fit] Code the Docs

![](images/zork.jpg)

# [fit] Interactive Documentation

---

![](images/timandparis.jpg)

^ PARIS: Hi! We're here to talk about Interactive Code-based Documentation

---

## Tim (unicorn)
##  Paris (not unicorn)
### @parisba and @the_mcjones

![](images/timandparis.jpg)

^ TIM: I'm Tim

^ PARIS: And I'm Paris, you can find us on Twitter if you want!

---

![filtered](images/edna.jpg)
### [fit] We Speak Australian
^ PARIS: We speak Australian. 

^ TIM: Please tell us if we say something you don't understand! 

^ PARIS: We're really excited to be speaking here, and we're thoroughly enjoying this conference so far.

^ TIM: Thanks to everyone who makes it happen. 

^ <TIM MAKES A MARK ON BINGO SHEET> 
    
^ TIM: Thank a volunteer... ok, bingo.

---

## Some things about us...
![](images/timandparis.jpg)

---

## We're academics

![left](images/phd.jpg)

^ PARIS

---

## We're academics and game developers

![left](images/game.jpg)

^ TIM

---

##  We're academics, game developers, and technical authors

![left](images/authors.jpg)

^ PARIS

---


## We're academics, game developers, technical authors, and programming teachers

![left](images/training.jpg)

^ TIM


---

![](images/learningswift.jpg)

^ PARIS: So think a lot about documentation, but mostly we write a lot of books

---

![](images/book1.jpg)

^ TIM: ... A LOT of books.

---

![](images/book2.png)

^ PARIS: ... a really huge amount of books.

---

### [fit] The Situation

![](images/situation.jpg)

^ TIM: and because we also present a lot of programmer training workshops, particularly teaching rapidly changing technologies such as game development, and Apple's developer environment –– Swift, previously Objective-C, and APIs like Cocoa and CocoaTouch for Mac and iPhone development...

^ PARIS: we think a lot about having a closer linkage between our books and the provided code.


---

### [fit] Code + Docs + Notes?!

![](images/docs.png)

^ PARIS: In the last 2 years of teaching these classes, particularly with Swift, Apple's new language, we've noticed that those in the class trying to learn the language have particularly enjoyed one component of the way Apple's frameworks and languages work: Swift Playgrounds.

---

![](images/lost.jpg)

### [fit] People Get Lost

^ TIM: People mess up where they are when moving between the code and documentation.

^ PARIS: They have a disconnect between what they see and what they do.

---

![](images/boring.png)

^ TIM: Interactive Documentation Environments take boring comment-riddled code, which is hard to read and learn from...

---

![](images/notboring.png)

^ PARIS: And turn it into something with attractive formatting, and more documentation than just comments, whilst still being fully interactive.

---

![original](images/docs.png)


^ TIM: it leads back to the idea of code+notes+docs in one. By putting the code you're documenting alongside the documentation, alongside an interactive output from the code, and allowing people to add their own notes and documentation...

---

![original](images/docs.png)

^ PARIS: ... you end up with something quite useful!

---

### [fit] Code + Docs + Notes!

![](images/docs.png)

^ TIM: The more we explored these Interactive Environments –– today we're calling them Interactive Documentation Environments –– the more we thought they were particularly amazing for certain types of technical educational material, teaching, and distributing some types of documentation.

---

## Interactive document environments?

- Swift Playgrounds

- IPython Notebooks

- ... which are now Jupyter Notebooks

- ...and a few others

^ PARIS: There's a bunch of different interactive programming environments like this, including Swift Playgrounds, IPython Notebooks, which are now known as Jupyter Notebooks, and a few others.

---

## Core Features

- live code 
- pretty formatting
- ability to add new notes
- media rich (gifs, videos, etc.)
- real programming, not a special wrapper

^ TIM: Core features of interactive documentation environments...

^ PARIS: Live code, pretty formattting, etc.

---

## We are not experts

![](images/gaston-eggs.jpg)

^ PARIS: We're not experts! We just really like this stuff, and think it's useful.

^ TIM: And want to share!

---

![inline](images/swift.png)

^ TIM: We haven't really got time to go through all three environments we mentioned in detail, so we're going to focus the most on the one we have the most experience with.

^ PARIS: Playgrounds, which are part of Apple's Swift.

---
## Swift 

- Introduced 2 years ago by Apple
- Currently at version 2.2
- Made open source in December 2015[^1]
- Apache License 2.0
- Currently supports OS X and Linux
- Windows support on the way

[^1]: For more information on the Swift project, check out their website: http://swift.org/

^ PARIS: Swift is Apple's new language. And is open source under the Apache License.

^ TIM: We're a bit biased, but we think Swift is the bees knees!

---

## Swift Playgrounds

- an interactive Swift coding environment
- each statement is evaluated and displayed
- designed for prototyping, experimentation, and learning
- can be paginated
- supports Markdown (yay?!) and HTML

^ TIM: Playgrounds, which we're talking about here, are not open source ... yet. 

^ PARIS: But the Swift REPL, which is the bulk of Playgrounds, is open source.

^ TIM: everything you see in Playgrounds with us today is part of Apple's Xcode, which is free for Macs.

^ PARIS: Playgrounds have all the features we mentioned earlier, as part of a documentation environment.

---

## Markup in Playgrounds

![inline](images/markdown_playground.png)

^ PARIS: <Comment on Erik's opinions on markdown>

^ TIM: These are still new. And we think it will get support for more later, Apple already uses Sphinx..

---

## IPython Notebooks

- Interactive Python coding environment
- works pretty much the same as Swift Playgrounds
- designed for academic and scientific documentation
- Supports text, equations, and graphs

^ PARIS: been around for a while

^ TIM: rarely used to teach

---

![inline](images/jupyter.png)

---

## Project Jupyter

- Successor to IPython
- Started in 2014
- Supports multiple languages
- Otherwise the same as IPython Notebooks
- Used by O'Reilly Media for "Oriole"

^ TIM: successor to IPYthon... <talk about them>
	
---

## Demo-Gods I Summon Thee!

![fit right](images/paul.jpg)

^ Paris: time to be gutsy

^ TIM: that's pjf, a super nice guy 

^ TIM: Just in case our demos don't work, we've also got videos, which we hopefully won't have to fall back on. ANYWAY!

---

![](images/playground.jpg)

## Swift Playgrounds

^ Let's take a more detailed look at Swift playgrounds, our favourite example of this sort of thing!

^ we think this basically because they are more or less designed for it

---

## Live Demo!

![filtered](images/bird.jpg)

^ DEMO: Creating new documentation for something (maths)

^ put a bird on it

---

## [fit] Live Demo!

![right fit](images/fine.jpg)

^ DEMO: Newton's Cradle

^ this is a demo playground provided by apple

---

![](videos/playground_intro.mov)

---

![](images/jupiter.png)

## [fit] Project Jupyter

---

# [fit] O'Reilly Oriole

![right](images/tarsier.jpg)


---

## [fit] Live Demo!

![left fit](images/dog.jpg)

^ our favourite example is ORMs regex golf video

---

![](videos/orm_regex.mov)

^ DEMO: This is a quick run through of a live browser training course talking about regex

^ http://www.oreilly.com/oriole/

^ Its based on an XKCD comic

^ so we go through running each miniscript

^ we can run the regex to see it fails

^ meh who cares about fremont

^ lets see if it works if we add trump in!

---

### [fit] Strengths

![](images/gaston.jpg)

^ PARIS: So, what's the point of all this?

---

## Strengths

- Code and Docs __literally__ together
- ... also notes by the person reading the docs	
- Can change things on the fly
- Mixed Media

^ TIM: in theory we've had all this for a while but people have only really started using it

---

![filtered](images/paper.jpg)

# [fit] You can mix notes, live code, and docs

^ this was sort of a suprise to us
^ but we've found people REALLY like being able to do this

---

> I find the documentation and my own notes living alongside the code to be incredibly handy. It means I don't get lost learning this language and APIs.
-- feedback from Swift training in Melbourne, May 2016

^ PARIS: we are pretty aggressive about asking for feedback, it mostly works

---

### [fit] Weaknesses

![filtered](images/weaknesses.jpg)

---

## Weaknesses 

- Only Markdown(ish) and HTML(ish)
- Kinda crashy...
- Limited language/framework support
- Doesn't hook into docs tools
- Only really works for narratives

^ PARIS: for example playgrounds only support markdown and HTML

---

## What's next?

- Boffins will fix the tech
- Be easier to add in new languages & projects
- This will replace/become books & articles
- Better support for non-narrative documentation
- More integration with video and screensharing

^ TIM: chime in here

---

## Where to learn more...


- On a Mac? Download Xcode from the App Store
    - Then play in Playgrounds.
- On something else? Download Jupyter Notebook
	- The process is complex
	- The docs for this are bad...
	- or go to: https://try.jupyter.org

^ best way to learn is to mess around with it

---

## O'Reilly Oriole

- Try Regex Golf:
    - oreilly.com/learning/regex-golf-with-peter-norvig
- Learn more about Oriole:
    - oreilly.com/ideas/oreilly-oriole-learn-alongside-innovators-thought-by-thought-in-context

---

![](images/timandparis2.jpg)

---

![](images/timandparis2.jpg)

## Thanks!

- Questions? Find us up the front..
- .. or find us on Twitter!
    - @the_mcjones (horse)
	- @parisba (not horse)
- Slides and notes will be online at:
    - http://lonely.coffee and 
    - http://blog.paris.id.au





