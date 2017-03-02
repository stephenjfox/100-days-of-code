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



### Day 6: January 19, Thursday

**Today's Progress**: Completed the Portfolio Project at Free Code Camp

**Thoughts**: No, you read that date right, I've been gone for three days. I'm a people pleaser and couldn't say "no" to a few people. 

**Links**: It's really late at the time of writing this, so just check the [blog post](https://medium.com/@sjf96/day-6-100daysofcode-7928550e40af#.jrucvkows) for them.




### Day 7: January 20, Friday

**Today's Progress**: Random Quote Machine progress, applying the principles from [Web Design in 4 Minutes](http://jgthms.com/web-design-in-4-minutes/). Reading on [OOCSS](https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/), [BEM CSS](https://css-tricks.com/bem-101/), and ["Why BEM?"](https://blog.decaf.de/2015/06/24/why-bem-in-a-nutshell/).

**Thoughts**: I've wanted to adopt on of these principles-based approaches to building out CSS, but haven't had a decent playground to exercise them. Had a typo-based bug in the Quote Machine ("innerHtml" -> "innerHMTL", which is correct) that was hard to discern. Industry practices are tough when it comes to CSS, especially when I'm a lone developer trying to find which standards adhere to my personal tastes. I'll talk more about it in the blog.

**Links**: 

1. [The Quote Machine](http://codepen.io/stevemasta34/full/GrWmjJ/)



### Day 8: January 21, Saturday

**Today's Progress**: Random Quote Machine is feature complete, with a simple, flat UI. I've studied more ideas regarding CSS systems, and how to scale with them. I also broke my portfolio site (when adding the Random Quote Machine).

**Thoughts**: Breaking the portfolio site just shows me I need to rewrite it. It's too damn fragile. It genuinely makes me angry that I dove into using some tech I didn't know (SCSS) and expected magic to happen; that's new-coder-entitlement if I ever saw it. It was even mobile-friendly! I'm keeping the color scheme, and tossing everything else.

I have plans for LISP in my future. No more beating around the bush. Sunday will be a day of Clojure (double entendre). If I can ramp up fast enough, I might even try ClojureScript. But, first things first: let's do one thing at a time and actually get a day with Clojure in it.

**Links**:

1. [The (broken) Portfolio](http://codepen.io/stevemasta34/full/GZLydE)
2. [The Random Quote Machine](http://codepen.io/stevemasta34/full/GrWmjJ/)


### Day 9: January 22, Sunday

**Today's Progress**: A new low - only just shy of missing the day. Reviewed my Clojure notes and jogged my memory. No JS. No Dart.

**Thoughts**: I'm glad I took such good notes the last time I studied Clojure (August 2016!!!), in such [a good IDE](lighttable.com). The inline evaluation makes prototyping a sinch. I still haven't tested it for an application, but for the functions I threw together while reading, pushing the language: "Oh I wonder if this will compile... Okay, now does it do what I want it to? ... And corner cases... This language is so awesome."

**Links**:

I know there supposed to be links to prove that we did something, but it was mostly a review and my scratch pad.
(3 minutes later). 

Actually, I do have __something__: [my scratch repo](https://github.com/stephenjfox/clojure_scratch)


### Day 10: January 23, Monday

**Today's Progress**: HUGE progress today. "A Day of Dart" is what I'll call it. Completed the first chapter of "Learning Dart". Reviewed a little Clojure and looked at a more complete dev environment setup.

**Thoughts**: Like I said, I complete the first chapter of "Learning Dart" and I love the book: it's like it was written with me in mind. Sure there are explanations that cover rudimentary concepts, but I __learned__ so much reading through it! It was great. I'm going to ride this out for a little while. For about 20 minutes today, I juggled between hopping to Clojure (because it was on the list) and powering through with the high of coding Dart. Guess which one I chose ;)


**Links**: 

1. [Dart To-Do List](https://github.com/stephenjfox/jubilant-todo)



### Day 11: January 24, Tuesday

**Today's Progress**: Basics of the to-do list are up, with a non-persistent, HTML-orient model right now. Will progress to data-oriented model in the future.

**Thoughts**: I will do more in the future, but I'm really glad today wasn't lost; all this happened because I made it so. Tomorrow, Javascript should get some attention - either the Address Book or the [weather app for FreeCodeCamp](https://www.freecodecamp.com/challenges/show-the-local-weather). When I need more momentum, I can use books for inspiration, so I'm sure that will help tomorrow.

**Links**:

1. [Dart To-Do List](https://github.com/stephenjfox/jubilant-todo) (4-ish new commits)

2. [Blog post](https://medium.com/@sjf96/day-11-of-100days-of-code-69a8ea603d8f)


### Day 12: January 26

**Today's Progress**: Very low. Technical difficulties caused frustration at my first swing at development.

**Thoughts**: Spent the majority of my evening studying the Korean language, so I was actually limited in time I could devote to code. More than necessary, I listened to a friend talk and that took time away from the challenge. I'm tempted to not count this day, only to make up for it on the weekend.


### Day 13: January 27

**Today's Progress**: Address book and package manager cruft. 

**Thoughts**: I spent WAY too long working with yarn and npm to have any substantial progress.
Setup a new working structure, where each segment of the address book will have its own branch. That way, I won't be able to program strange interdependencies.

Paranoid? Most likely. Effective? Definitely.

**Links**:

1. [Address Book in question](https://github.com/stephenjfox/js-address-book)

2. [Blog post](https://medium.com/@sjf96/day-13-of-100daysofcode-d229625a9b2d#.njel3xpgk)


----

I'm going to redo days 12 and 13. I can't recall any serious work from day 12, and it's shameful. Starting Monday - the 30th - with a solid Day 15 is what I want.

This Saturday and Sunday (January 28 and 29, respectively) will be Days 12.1 and __14__, as 13 was a genuine few hours of work, with public commits and all.

After this update, I will have a reposting of Day 12. Then, Sunday, I will continue with 14. Like a normal person. :)

----


### Day 12.1: Saturday, January 28

**Today's Progress**: I learned a lot about the [AngularDart Material Component library](https://www.dartdocs.org/documentation/angular2_components/0.2.2/angular2_components/angular2_components-library.html)
as well as Dart's support for Angular. I completed a code lab. Did some work on a private project; I'm charged with a component to develop. I have permission to use AngularDart, but JavaScript may be wiser for project longevity. But then again, that's why Dart was made. Time will have to tell.

**Thoughts**: Highly illuminating material. Google uses BEM CSS and I've got [proof](https://github.com/dart-lang/one-hour-codelab/blob/master/angular2_components/4-final/lib/lottery_simulator.css#L22). I guess that settles that, if I dream of becoming a Googler some day (it __still__ has its appeal after my first flunked interview).

**Links**:

1. Complete [code lab](https://github.com/stephenjfox/angular2-components-codelab)



### Day 14: Monday, January 30

**Progress**: 
 
 * I cleaned up the Dart To-Do app that I've been working on. It's nothing special so far, but it could be quite respectable very soon.
 
 * More research into CSS methodologies, re-reading some articles that once seemed exhausted of new knowledge grants new insight.

**Thoughts**: There is just so much to CSS. These methodologies are all competing over my mind space. Which will stick! I feel a little disorganized between the blog post and this log, but I think I've given myself a poor structure for a worklog in this fashion. This is __not__ how I do work logs. For the past week, I've been writing these after the blog post itself.

Still, one gets a different look at me here than there. I'm figuring things out, one day at a time.

**Links**:

1. I'll be more thorough in the [blog post](https://medium.com/@sjf96/day-14-100daysofcode-fac14e9a9978#.fiji1bmo6)
2. [To-Do app](https://github.com/stephenjfox/jubilant-todo)
3. [JS Address Book](https://github.com/stephenjfox/js-address-book)


----

Days 15-18 have been elided. There was work done in the veign of technical research, resource aggregation, and coding samples. I've changed my principles to align more with those outlined in Chingu [P1xt](https://medium.com/@P1xt)'s [guide](https://forum.freecodecamp.com/t/computer-guide-computer-science-and-web-development-comprehensive-path/64470), namely:

1. have git commits every week, most of the days of the week
2. Be active in my Chingu Cohort
3. "take notes, on a blog, in markdown, wherever, somewhere - not about what you read, or about what the instructor said - about what you learned"
4. if you build something, document it and test it as appropriate. __I'm expanding on this__: I will report it to Twitter, concistently
5. build projects fully, not some scaled down halfassery

----


The bullet points will be in the blog post from now on. This is just going to be my brain dump...

### Day 19: February 7, 2017

The project I'm working is effectively a specialized component/control for self-run, in-persion, client-oriented businesses. It's going to be beautiful, and it's going to be useful. But I've got work to do, because the component libraries aren't going to code this for me.

There aren’t any __real__ out-of-the-box solutions for this kind of thing, so I need to make a complex component or two. That's fine, as I'll get all the joy of flexing my [TS](http://www.typescriptlang.org/index.html) muscles again.

This day of work has been such a burn: work was mentally boring and trying to recover from that to knock out an awesome project is tough. I just have to found on to my flame - the desire to build excellence - to keep going...

Angular 2 is easy stuff, but things aren't wired the same as AngularDart; I had forgotten because AngularDart is close _enough_, but makes small changes (like importing with the `directives` attribute on the Component annotation object, or the list-literal usage). It's genuinely weird that what was a full-blown HTML Element in AngularDart is just a directive attribute in Angular Material 2. I sincerely like the AngularDart was of doing things more: you can just read the HTML and know that you aren't hacking the hell out of the native stuff. You're just using the native stuff as the atomic building blocks.

Man, my day job left me feeling grouchy. So many processes to fix... (concluded in [blog post](https://medium.com/@sjf96/day-19-of-100daysofcode-4d72f66ea4#.gfna92l9g) )

----

If it's not apparent, Clojure has been dropped for the short term. I've been doing a few practice algorithms in it around once a week, but nothing to bat an eyelash at.

----

## New Book List

- [Site Reliability Engineering](g.co/SREBook) - by SREs (former and current) at Google
- [JavaScript Allongé](https://leanpub.com/javascriptallongesix/read)
  - A broad, blended, and passionately written work covering "programming with functions" with Javascript as a lens.
  - The book starts with "basics" but I have an endorsement from [Eric Elliott](https://twitter.com/_ericelliott) that there's much to learn for anyone who works in JS.
- [Setting Up ES6](https://leanpub.com/setting-up-es6/read)
  - ES6 (sans modules) is basically [supported in all browsers](https://kangax.github.io/compat-table/es6/), but not in Node or most of it's tool
  - Namely, [Gulp](https://css-tricks.com/transpiling-es6/), Grunt, and WebPack 1 don't know what to do with ES6-standard Javascript. So we need to compile it with Babel (because [traceur](https://github.com/google/traceur-compiler) kind of sucks and doesn't get updated).

Everything else I've been reading has been put on hold, because these are books of principles and largely applicable technologies. The others were more directed application of a given language.
I want to be a principled man.


----

### Day 22: February 22, 2017

Omissions addressed in the [blog](https://medium.com/@sjf96).

Dang it CSS is frustrating. I __know__ it, but when I go to execute I'm stopped at the door. Take for example, centering an element horizontally. To the CSS novice, this seems like a complex and mystical thing that should be relatively straight forward (would a style like "align: center" make sense?) and yet aludes one.

Then, they wander into this little nugget `margin: 0 auto; /* centers element */` and you think you're the freaking Wizard of Oz... Has __never__ worked for me in a CodePen, and that's the project requirement for these Free Code Camp challenges.

I'm an engineer, who gets off on making things work. I'll be the first to admit. But when one exercises the enumeration of possible state combinations and none produce the desired result, you find yourself quite agitated. This is what has occurred this evening working with horizontal centering with my cascaded styles.

___Aside___
We should really find another way to write for the web. HTML and CSS were meant for static documents of the 90's. It's almost 2020.
___End Aside___

[10 minutes post rant] I read [this](https://css-tricks.com/centering-css-complete-guide/), so I hope I can execute on that...



### Day 23: February 23, 2017

Typing that is going to feel a little redundant for the rest of the month (the days are the same).

This Local Weather app is giving me a surprising amount of trouble. I have this beautiful vision in my head, and nary the skills to create that from scratch. Haven't been coerced into using libraries for the majority of my career, I've simple short on practice. Very far behind the 10,000-some odd hours to be an expert in something; whereas with Java, that's a different matter...

So here I am, fumbling about. Strong CSS principles and vision in mind. My hand drawing skills are rather bad at getting my imagination onto paper, but I know what I want to app to look like: Material, through and through.

__A Goal__: To have the page color scheme change with the weather. I.e. "Snowy" weather is white, gray, and blues. "Hot" weather is red, tan, orange. etc.

Tonight, I've already recorded almost two hours of work and the page is still, _roughly_ the same ugliness it was last night: a bit of logical over complication and strict adherence to principles slowed me down.

[10 minutes later] BEM. I appreciate the flat approach to everything. It removes dependencies and, as such, allows one to think about things independently of one another. "If I was just working with X, what would I need to do to change it?" That's the idea anyway. So each specialized class has just a few lines that describe exactly what you want to happen and nothing else - because nothing else is effecting the class, is it? Highest specificity wins in the land of CSS selectors.

I'm struggling with how to box the icon for the weather (a mandatory feature). If I house the image in a box, is that unnecessary boxing of HTML primitives? Or should I put the image in a box, style the box, and then further style the image?

You know what? After reading that, it sounds silly to do the latter. Thanks.

Since I'm going for a Material-theme, I want minimal margin with substantial padding. I'm sure [the basics](http://learn.shayhowe.com/html-css/positioning-content/) will help me!

[Another 15 minutes later] I love CSS variables. And color palette pickers like [Material Palette](https://www.materialpalette.com). They help me hone the vision.

Reread [this article](https://medium.freecodecamp.com/3-questions-to-watch-out-for-in-a-javascript-interview-725012834ccb#.m5sanrpyd) to remember JavaScript event delegation patterns, so I don't have runaway Function objects polluting my heap.

Feature completion feels pretty good.


### Day 24: February 24, 2017

I'm starting really late today (it's 11PM), so I'll just be squeezing things in. Flat UI is where I want to go; the "Material" label has been clouding my vision.

I've got my HTML organized fairly well, along with BEM styles to boot. Being sick is making it a huge pain to just sit down in this chair and code.

##### 11:15 PM

So horizontally centering an element is `margin: 0 auto;`, but what's vertical centering? Likewise, it's `margin: auto 0;`. But that's a weird thing to achieve.

After a bunch of fiddling, I've settled on a box height for the main view of 66.5%. This is what works best on my iPhone 7+, so now I'm going to test it elsewhere.
Building mobile first is just that: test on a mobile device, and make sure things scale.

On desktop, this sizing is too much. I think it has to do with my `height` measurements compensating for the CodePen banner.

##### 11:38 PM

Messing with the view port took a view. CodePen magnifies the port significantly. Time to start playing with font sizes (it was on the list anyway).

##### 11:56 PM

Aligning the left side of the text of my "latitude" and "longitude" fields with the "weather content" box's left wall is kind of tough. I'm not certain where the "centering" of text takes place in regards to this

##### 12:06 PM

There is a runaway element styling on my page. The footer isn't receiving any styles, so I'm probably going to ditch it.

##### 12:16 PM

Following the Material Design (I know, I know) rules for pixel sizing, using multiples of 8px and 16px.

##### 12:23 PM

I'll be giving it a rest for the night. My brain will organize my thoughts into clarity while I sleep and I'll have something structured to say for the blog post.

Maybe I should just put the button back, instead of trying to be clever with clicking the temperature units...


### Day 25: February 25, 2017

##### 11:26 PM

I think I'm on a mission to prove to myself that I can jog in CSS circles forever. Between adherence to strict [BEM rules](https://en.bem.info/methodology/key-concepts/) and stateless JavaScript, I'm working overtime on some really simple stuff.

Look here. The Local Weather app is done, in effect. 

- [x] Icon for the weather (free from Apixu)
- [x] Local temperature on page load
- [x] Click-a-thing to toggle Fahrenheit/Celsius.

It's just not good looking. I would think that making a modern, flat UI for such a simple app would be more simple. Obviously mistaken.

I just remembered a border-decoration (or something like that) to use on `button` to get it looking flat. :) Let's see what I can get up to in a few minutes...

##### 11:40 PM

Screw it. I'm using the Material Design visual template and attempting a re-create (almost like [the guide from p1xt](https://forum.freecodecamp.com/t/computer-guide-computer-science-and-web-development-comprehensive-path/64470))

##### 11:53 PM

It's a lot cleaner now, but the UI doesn't match a phone very well. The magnified view from CodePen is totally throwing me off.

At this point, I need to adjust things like `background` and `width` to get the fill color-correct.

##### 12:04 AM (next day)

I've scrapped `margin` and `padding` because they were just playing me in a weird place on the screen. Almost identical to the [material palette](https://www.materialpalette.com/blue-grey/light-blue) sample, but the gratuitous white space needs addressing.

I'm going to blog, then we'll catch up tomorrow.


### Day 26: February 26, 2017

Codes for Jesus (thanks Bro Science)! I'm giving myself an hour to get the view to look decent enough for my tastes. I'm fiddling with the height and verticle-centering, while listening to K-pop, so I can just have this done.

27 minutes. I'm calling it. I'm conceptually stuck at this point, but it looks ok. There's not a ton of content to style around, so I've got limited resources to design. That's an excuse. I'm really just unsure of where to go from here, to ask the right questions.

The CSS that I'm writing isn't giving me the desired result of a "main content" with a fixed size. Instead, the main content block snaps to a new size once its content is hydrated (loaded). It's very upsetting. Maybe I'll have something later.
Making use of blank space is something I need to master, because the next app is a Wikipedia viewer: a small scale search engine, that I'm planning to do a "master-detail" setup for.

On small devices (width &lt;600px) the plan is to use a completely different set of styles, which I think is how it is supposed to always be done. I'm going to Material palette again for the color scheme, but everyone knows Wikipedia is black-white-and-gray-scale.

You know what? I just thought that I could have the cohort (Chingu-Penguins, Gen. 1) peer critique it and help me make it better. I know it's not beautiful. Or maybe I should just keep going, get my cert, then come back for seconds after my skills have improved? Who knows?


### Day 27: February 27, 2017

##### 10:16 PM

This whole blog-once-every-two-days thing is really weird. Why not just get those posts out daily?

Today I spent an hour and change try to coax a "compose" function into life. So far, I've had limited success:

- While I'm able to create a function that composes on two and three inputs, moving to a functional reduce doesn't provide a compliant solution.

Worse yet, I've had the algorithm for at iterative implementation in my head all afternoon. But see, when it comes to being principled, I'm a stictler (and occasional asshole) on the inside.

Hang on a sec. I'm going to try it out. My pride isn't that great.

##### 10:26 PM

Yup. It works. Like a charm. And now I know how to do it with reduce... -\_- Teaching myself is both boring and fascinating sometimes.

##### 10:29 PM

It's just that easy kids. Now I need to handle edge cases, like 0 and 1 functions. Then it's good for a pretty little bow

##### 10:38 PM

Dang it. I knew I was doing something off. Compose consumes right to left, such that the definition is more human readable.

Ex:

```
// just some setup to get you thinking in code again.
const head = (array) => array[0];
const toUpperCase = (string) => string.toUpperCase();
const reverse = (array) => array.reverse(); // imagine Array.prototype.reverse() isn't an in-place operation, for brevity

const last = compose(head, reverse);
```

You can read the definition of "last" as "the head of the reversed list". The way I wrote my compose (consuming left to right) it reads more like "reverse the list, then take its 'head' element".

This reads a lot more like "how" to do something, rather than "what" to do (which is what functional programming is all about).

Lessons learned for the future.


### Day 29: March 1, 2017

##### 10:28 PM

I still haven't finished writing about the machine learning meetup from yesterday. Hopefully, this doesn't spoiler it too much.

That's the __real__ trouble with this challenge: the posting to social media. My life is far removed from social networking, that having a visible commitment on something that I've extracted from my life... It's like going to my ex-girlfriend's for dinner. I might get fed, but it's not very enjoyable.

I love the coding. And I'm definitely getting better at writing by blogging (almost) everyday. It's just a weird problem to have: "I need to say all these things. Online. When I know that I've done them. That all said, having to perform for people does get a different result out of me.
I'm just whining at this point.

##### 10:32 PM

Algorithms. Of the practical variety. I'm implementing a point-free-form "compose" function. The version I had the other day required that you think from the bottom-up, and this version works from the top down.

I personally like the top-down approach, because it's a touch more declarative and reads "matter of fact"-ly. If you want _something_, you state what that something is.

To re-use an earlier example: "I want the last element in a list... What's the 'last' element, you say? Well, I suppose, if we were looking from the other end, it would be the very first one." And, again, telling the computer the how - "spin the list around, then give me the first thing you find" - is practically imperative.

__The bug I've got__ right now is strange: `String.prototype.length` isn't returning its length, but instead is returning itself. I must have misdefined something, so I'm going to type them back out.

##### 10:46 PM

Thanks to the REPL, I figured it out. Then it was just some tweaking. I'm going to leave the variable names length and self-documenting, because it should be that way.

##### 11:06 PM

Done. Chat with y'all tomorrow.
[Proof](https://github.com/stephenjfox/functional-javascript/blob/compose-point-free/compose/compose-test.js)

