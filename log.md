# 100 Days Of Code - Log

### Day 0: January 11, 2017

**Today's Progress**: Preping for the 100 days of code.

**Thoughts:** I've got a few programming languages that I want to level up in, so here they are and how I'm going to give them a boost:

  - [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction) by [Brendan Eich](https://brendaneich.com/)
      - [Professor Frisby's Mostly Adequate Guide](https://www.gitbook.com/book/drboolean/mostly-adequate-guide/details)
      - [Programming Javascript Applications](https://www.amazon.com/Programming-JavaScript-Applications-Architecture-Libraries/dp/1491950293/ref=sr_1_1?ie=UTF8&qid=1484205077&sr=8-1&keywords=programming+javascript+applications)
  - [Clojure](https://clojure.org/) by [Rich Hickey](https://www.infoq.com/author/Rich-Hickey)
      - [Programming Clojure](https://www.amazon.com/Programming-Clojure-Stuart-Halloway/dp/1934356867/ref=sr_1_1?ie=UTF8&qid=1484205480&sr=8-1&keywords=programming+clojure)
      - [Functional Programming Patterns in Scala and Clojure](https://www.amazon.com/Functional-Programming-Patterns-Scala-Clojure/dp/1937785475/ref=sr_1_1?ie=UTF8&qid=1484205542&sr=8-1&keywords=functional+patterns+scala+and+clojure)
  - [Dart](https://www.dartlang.org/) by [Google](https://careers.google.com/)
      - [Learning Dart](https://www.amazon.com/Learning-Dart-Second-Ivo-Balbaert/dp/1785287621/ref=pd_sbs_14_3?_encoding=UTF8&pd_rd_i=1785287621&pd_rd_r=HH1RHEQ8RYJAHCR220T6&pd_rd_w=4cH8H&pd_rd_wg=YeqXb&psc=1&refRID=HH1RHEQ8RYJAHCR220T6)
          - Also [Mastering Dart](https://www.amazon.com/Mastering-Dart-Sergey-Akopkokhyants/dp/1783989564/ref=sr_1_1?ie=UTF8&qid=1484205607&sr=8-1&keywords=mastering+dart) when the time comes ;)
      - [Effective Dart](https://www.dartlang.org/guides/language/effective-dart)
      - [Write Web Apps with Dart](https://www.amazon.com/Write-Web-Apps-Dart-Develop-ebook/dp/B0195N89GY/ref=sr_1_1?ie=UTF8&qid=1484205658&sr=8-1&keywords=write+web+apps+with+dart)



I'm expecting to do a TodoMVC in AngularDart, some small concurrency experiments with Clojure. Maybe a library will fall out of these exercises, but I'm more doubtful: both Dart and Clojure have such strong core libraries as it stands. Javascript, on the other hand, is a "require"-party, but I think I'll write my own. Something like a functional programming core library, written in ES6 (all the good ones are &lt;ES5)


**Link to work:** A lot of these will have scratch project repositories, which I will link on GitHub/BitBucket.



### Day 1: January 12, Thursday

**Today's Progress**: Not as much as I wanted. Spent a healthy chunk of time configuring the atom-dart plugin for a faster development cycle than that offered by IntelliJ. Wanted to get to more Javascript today, with Elliott's book, but I'm beat.

**Thoughts**: For some reason, IntelliJ freezes up whenever Pub serves the web page. I think the plugin is doing upload work synchronously. Might make for a good PR.



### Day 2: January 13, Friday

**Today's Progress**: Complete AngularDart [Tour of Heroes](https://webdev.dartlang.org/angular/tutorial) tutorial, up through Part 4. Pretty fun, and gives me grounds for the rest I have planned for the language. Pushed the repository to Github, so there are links now. Stalled on Javascript and Clojure, because of time constraints but I have a new plan: switch-when-stale. Dart hasn't gotten stale, and I've got 98 more days to go, but if I ever get tired of configuring "new" things I'll have plently to chew on.

**Thoughts**:

__Dart__:

Since completing the Tour of Heroes, I want to see more of the reality of completing a full-sized app. There aren't many tutorials online, but the books I have will give me a general direction. I'm also starting to model, on paper, the work that will be needed for the E2E Dart app that I want to build. It's going to use [Flutter](flutter.io) and a web server, all written in Dart.


__Clojure__ and __Javascript__:

Another day where I didn't get to them.


**Link(s) to work**

1. [My Github](https://github.com/stephenjfox)
2. [Tour of Heroes (with Dart)](https://github.com/stephenjfox/dart_tour_of_heroes)




### Day 3: January 14, Saturday

**Today's Progress**: Finished [dart_tour_of_heroes](https://github.com/stephenjfox/dart_tour_of_heroes). A __lot__ of setup for the backend to the mobile app. I need to figure out how to strip my credentials so I can push to GitHub.

**Thoughts**: I typically hate config, but today wasn't bad. (It might just be config on the JVM :P) The list of projects I have hasn't shrunk in the slightest, so it will be exciting to see if I actually start to finish them. Ambition is a great fuel for the flame, but can also set me up for epic disappointment.

On a similar note, I genuinely want to chew through the books I listed. They are _excellent_. The writing styling in all of them is great for different reasons and I could learn so much from them. I seriously need a recommitment to myself to read those books! My current favorites (that I've read in the past) are Frisby's FP book and Programming Clojure. The bits I've read of Learning Dart are thorough and articulate in presentation of new material - I just haven't gotten to the feature rich applications yet.

I don't want to "code in the closet", so if I find that all this configuration is taking me away from the code-y bits, I'll do something simple in a public space (here on GitHub). I've noticed that I haven't been sharing the links to my project work as we're required to do. For tomorrow!

Onto the languages:

__Dart__ and __Javascript__: Started the backend for the mobile app that I semi-ranted on. Can't deploy the Dart web server to the Azure environment I'm setting up, so I switched to Javascript. Bums me out just a little. I might still make it in Dart, after deploying a VM to my personal website.

__Clojure__: The neglected, redheaded stepchild. :{ Soon, dear LISP. Soon. I stated it in a [blog post](https://medium.com/@sjf96/the-top-back-end-programming-languages-4528795fd9ba#.nmu4nkhrr), LISP was the most fun I've had programming in a while. There's no reason to be this negligent when I love the language so much!


**Links to work**: Pending. __Will__ return.



### Day 4: January 15, Sunday

**Today's Progress**: ToH is basically done. There's more CRUD functionality that the tutorial wants, but I think I'll do that on my own. I want to be comfortable with async programming, not just "guided". No Clojure work yet, though I've found a project that matches my (syntactic) skill level. Javascript server-side project is a bit of a moonshot; might not even be technically possible. But that's why we have simple projects too!

**Thoughts**: Clojure is calling me - the spirit is willing, but the flesh is weak. Javascript hasn't been getting its just stay in my life; Dart is just so new! It's been around for 5-ish years, but the language is just so capable at expressing what I want from my programs, how could I __not__ use it?!!

I'm disappointed in what little I got done today, but life happens. I barely met an hour and 15 minutes, and that's if you squint at the work I did. Way too much hand holding tutorial junk. I know what I can do, so it's time to do it.

I think this log will be more like a short review, where the blog post will be a bit more long winded. Hopefully my writing will improve as time goes on .

**Links**: See the [blog post](https://medium.com/@sjf96/100daysofcode-day-4-c91f80152ae#.yv29cc2q0). Any links would be found there.



### Day 5: January 16, Monday

**Today's Progress**: Started to go above and beyond completion criteria for ToH. I want a single-screen, master-detail view a lot like [this](http://chancancode.github.io/hn-reader/about). Coded a simple foundation for an [address book](https://github.com/stephenjfox/js-address-book) and did some serious reading through the [awesome resources](https://github.com/sindresorhus/awesome)!

**Thoughts**: I wasn't "in the mood" to code, which is weird because my mind is always itching to implement the next crazy idea. Outside life has been distracting me from doing things I enjoy, and I need to stop compromising my integrity over those things. 

I've begun to appreciate the hesitation to adopt Dart as a main-stay language, but it genuinely has all the tools it needs at its disposal. Technically, even more, because of the JavaScript interop it offers. Dart can be do it, and probably a lot more simply than you'd expect.

I've thrown a lot of excuses this New Year, and the month of January is flying by. It's really time to nut up or shut up.

Clojure still becomes and, with my [new set of toys](https://github.com/razum2um/awesome-clojure), I'll have loads to unleash. If I comb through SICP and Programming Clojure again, the desire will hit me like a brick.

**Links**: Anything missed will be covered in the [blog post](https://medium.com/@sjf96/100daysofcode-day-5-abf8e12a5ab7#.uip7sfs0u)

