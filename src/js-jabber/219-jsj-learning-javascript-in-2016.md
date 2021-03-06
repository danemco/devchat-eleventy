---
layout: layouts/post.njk
title: >
  219 JSJ Learning JavaScript in 2016
date: 2016-07-06 07:00:04
episode_number: 219
duration: 54:49
audio_url: https://media.devchat.tv/js-jabber/JSJ219Learning.mp3
podcast: js-jabber
tags:
  - js_jabber
  - podcast
---

## Check out [Newbie Remote Conf](https://allremoteconfs.com/newbie-2016)!

&nbsp;02:44 - What it Takes to Learn JavaScript in 201604:03 - Resources: Then vs Now09:42 - Are there prerequisites? Should you have experience?20:34 - Choosing What to Learn

- [The iPhreaks Show Episode #153: Using Mobile Devices to Manage Diabetes with Scott Hanselman](https://devchat.tv/iphreaks/153-ips-using-mobile-devices-to-manage-diabetes-with-scott-hanselman)
  28:19 - Deciding What to Learn Next 31:19 - Keeping Up: Obligations As a Developer34:22 - Deciding What to Learn Next (Cont’d)42:01 - Recommendations
- [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [gulp.js](https://gulpjs.com/)
- [webpack](https://webpack.github.io/)
- [The Little Schemer](https://mitpress.mit.edu/books/little-schemer)
- [Designing Data-Intensive Applications by Martin Kleppmann](https://dataintensive.net/)
  &nbsp;Picks
- [accidentally nonblocking](https://www.tedunangst.com/flak/post/accidentally-nonblocking) (Jamison)
- [choo](https://github.com/yoshuawuyts/choo) (Jamison)
- [Web Rebels](https://www.webrebels.org/) (Jamison)
- [React Rally](https://www.reactrally.com/) (Jamison)
- [Grab The Gold](https://grabthegold.com/) (Aimee)
- [node-for-beginners](https://github.com/rockbot/node-for-beginners) (Aimee)
- [Procrastinate On Purpose by Rory Vaden](https://www.procrastinateonpurpose.com/) (Chuck)
- [Newbie Remote Conf](https://allremoteconfs.com/newbie-2016) (Chuck)
- [Get A Coder Job](https://getacoderjob.com/) (Chuck)

### Transcript

**JAMISON:&nbsp;** He's not actively stabbing me. What a nice guy.

**_[This episode is sponsored by Front End Masters. They have a terrific lineup of live courses you can attend either online or in person. They also have a terrific backlog of courses you can watch including JavaScript the Good Parts, Build Web Applications with Node.js, AngularJS In-Depth, and Advanced JavaScript. You can go check them out at FrontEndMasters.com.]_**

**_[This episode is sponsored by Hired.com. Every week on Hired, they run an auction where over a thousand tech companies in San Francisco, New York, and L.A. bid on JavaScript developers, providing them with salary and equity upfront. The average JavaScript developer gets an average of 5 to 15 introductory offers and an average salary offer of $130,000 a year. Users can either accept an offer and go right into interviewing with the company or deny them without any continuing obligations. It’s totally free for users. And when you’re hired, they also give you a $1,000 bonus as a thank you for using them. But if you use the JavaScript Jabber link, you’ll get a $2,000 bonus instead. Finally, if you’re not looking for a job but know someone who is, you can refer them to Hired and get a $1,337 bonus if they accept the job. Go sign up at Hired.com/JavaScriptJabber.]_**

**_[Let's face it. Bookkeeping is hard and it's not really what you're good at anyway. Bench.co is the online bookkeeping service that pairs you with a team of dedicated bookkeepers who use simple, elegant software to do your bookkeeping for you. Check it out at Bench.co/JavaScriptJabber for 20% off today. They focus on what matters most and that's why they're there. Once again that's Bench.co/JavaScriptJabber.]_**

**_[This episode is sponsored by Rangle.io. Rangle has been working with Angular 2 for a long time, and they are now putting together an 8-hour, 2-day course designed to help Angular developers, learn how to write apps in Angular 2. If you're looking to level-up your JavaScript and Angular 2 skills, go to Rangle.io/Training and click on the link for Angular 2 training. If you're looking for other training in React or JavaScript, they also have that in Rangle.io/Training.]_**

**CHUCK:&nbsp;** Hey, everybody and welcome to Episode 219 of the JavaScript Jabber Show. This week on a panel we have Jamison Dance.

**JAMISON:&nbsp;** Hello, friends.

**CHUCK:&nbsp;** Aimee Knight.

**AIMEE:&nbsp;** Hello.

**CHUCK:&nbsp;** I'm Charles Max Wood from DevChat.TV. Quick shout-out about Newbie's Remote Conf coming up July 13th through 15th. You can get tickets. It's online. You can attend from anywhere.

**AIMEE:&nbsp;** Woohoo!

**CHUCK:&nbsp;** Aimee, are you speaking at that?

**AIMEE:&nbsp;** I am. I checked the website last week, and I'm really excited about the other people speaking.

**CHUCK:&nbsp;** Yeah, it's a really solid lineup. I'm really excited. So, this week, we're going to talk about what it takes to learn JavaScript in 2016.

**JAMISON:&nbsp;** Yes, and maybe some context for why. I think this topic is interesting. I learned JavaScript not in 2016. It wasn't super long ago, but it was several years ago. I feel like when I learned it, there were a lot fewer things to learn about JavaScript. Just the language itself and also fewer things to learn about the ecosystem around JavaScript. Like Node wasn't a thing. It was basically like jQuery, and that was kind of it.

Nowadays, the language itself was more complex. There's a lot more features, and then there's this whole gigantic pile of other stuff like you have to learn a framework. You have to learn all the frameworks because you have to be able to pick one and know which one is right and you have to learn Node and then, you can run it on hardware and then, there's all this transpolation stuff, all these tooling around it and it just feels like it's way larger than when I learned it.

I don't know what that experience is like for someone who is brand new to it, but I assume that it's kind of intimidating because there's so much stuff. Whereas before, you could just kind of learn the semantics and syntax of the language, and then the rest of it will get added over time as the community evolved. Does that make sense?

**CHUCK:&nbsp;** Yeah. The other thing that I want to just pile on with is that the resources for learning JavaScript back when I was learning it were also different. I mean, I was learning it pre-Node.js so I was just doing web development with it, and it wasn't this major platform. It was just something that you kind of tacked on to your server side stuff and then as it grew into something else, it's "Okay, pick up this, pick up that." All kind of came out as opposed to somebody now coming in and like you said, Jamison, now you have to pick up all this other stuff.

But beyond that, we have people coming in from boot camps. We have people coming in even from CS degrees where they may or may not teach them JavaScript. We've got people coming in learning off of like Code School or Khan Academy or something like that. Then basically, joining the field and joining the workforce without any real regimented training, or if they have it, may be a boot camp for a few months instead of college for a few years.

**AIMEE:&nbsp;** So how I would chime into on top of all this, I feel like there are so many resources and there are so many things to learn. But when you're new, if you're learning JavaScript, not just learning it, but as your first language, you probably don't have the context to understand why the things you're learning are there and why they're important. I feel like a huge struggle is without that, like things don't stick. So you're just kind of like copying and pasting and gluing things together without a bigger understanding.

**CHUCK:&nbsp;** So when you are picking it up, what are you gluing together? Are you building little sort of basic projects? Are you picking up a framework and saying, "Well, I'm just going to make this work, and learn what I can in the context of Angular or React," and then moving ahead? I mean, what are people doing today?

**AIMEE:&nbsp;** I feel like the advice that I see out there is pick something. The advice I give people is pick something because it sounds interesting to you. But then, people will pull numbers off of Google or something like that which can be misleading, and pick what they're going to learn based on that.

But still, there is no clear black and white answer of how you get the experience to get the context to know 'why are you using what you're using'. I don't know where you get it from, other than just experience and struggling through it. And you're just building - to answer your question - even in just like Node or Express or something, like a basic to-do app that hooks up to Mongo, or hooks up the Firebase and render some stuff on a page, and maybe you have some animations. But until you get to a big project, it's really hard to see why you're doing what you're doing.

**CHUCK:&nbsp;** Yeah, that is one thing that I think is the same from when I learned JavaScript and when people are learning now, is that I had it recommended to me over and over again to pick a project and build something interesting and I think that's still relevant today just from the standpoint of I have this outcome that I'm trying to work toward, and I'm going to use the resources that I have, be it a class that I'm sitting through or a course I'm taking online or Stack Overflow or calling my friend up so that they can help me get through whatever it is that I need to get through in order to get the outcome I'm building toward.

**AIMEE:&nbsp;** I know, a little bit ago, before we started, Jamison and I were talking and I wonder as you're more advanced if when you're reading these things you can pick them up more quickly not just because you have experience learning things but because you already have context that maybe you forget you've gotten.

**JAMISON:&nbsp;** When you say 'you're reading these things', what do you mean? Like what kind of things?

**AIMEE:&nbsp;** Like you're talking about reading a new Generator spec or something like that. You have an understanding of like a time in the past where you’ve needed something like this.

**JAMISON:&nbsp;** When you say spec, I think you over estimate the extent by learning capabilities. I do not read the spec to learn these things.

**CHUCK:&nbsp;** Jamison reads the comic book version.

**JAMISON:&nbsp;** I wait for someone smarter than me to read the spec and then write in understandable blog post. I think that gets back to the thing you're talking about with context which is it's just way easier like when Generators came out, I had been writing callback code in Node.js for years. So, it's pretty clear when the way I came to them as a way of writing better asynchronous code that you can use for a lot of other stuff. But it was really clear like, "Oh, this will make my life better in this one particular way," so I had a concrete motivation for why I wanted to learn them and understand them. That helped a lot.

I had also seen stuff like there are things kind of like Generators in other languages, like Python. I'm not a Python programmer but I think I've just Googled enough to see something that kind of looks like that. It was easier because of that context, but it was also easier because I had just the context of knowing JavaScript in general. Like if someone is new to programming or new to JavaScript, and they're trying to learn Generators, I think it's a lot harder because like there's all this example code, right? And all the example code is supposed to be really easy to understand, except the Generator part and the example code illustrates how Generators work.

But if you don't understand that "easy part" of the example code because it's all new to you then, it's easy to get distracted by that stuff. Does that make sense?

**AIMEE:&nbsp;** In your opinion, are there certain pre-requisites before you learn a framework or before you learn some of the new ES6 features?

**JAMISON:&nbsp;** That is a good question. I was about to say, yes. But then, I was like, "Wait. I'm just saying yes because that's how I did it." That's how you have to do it. After I [inaudible] JavaScript, so of course, I learned all that stuff after I learned JavaScript.

**CHUCK:&nbsp;** It's such an easy bias to fall into though, right? It's, "Oh well, my thought process goes immediately to how I did it or how I do it or how I think about it."

**JAMISON:&nbsp;** Yeah, that's my point. Prototypes are a huge hang up for a lot of people, and like the class stuff, I think it's still built on Prototypes. But it kind of hides them from you. So, maybe that's an example of where there are people that just don't need to learn Prototypes ever or quite so early. That's maybe one way of the path to learning, it could actually be simplified by new features in the language. So, maybe.

I think to understand Generators, you probably want to understand Promises. There's definitely a path. To understand why they're helpful, I think it's helpful to understand callbacks for asynchronous stuff. So I think there is kind of a path to that specific thing but I don't think that applies to every feature or every framework or tool or whatever.

**AIMEE:&nbsp;** I'm not going to able to like, [inaudible] a question a little bit here too.

**JAMISON:&nbsp;** Please do.

**AIMEE:&nbsp;** I get this question a lot as well. Speaking to newer developers, I feel like a lot of them are in a big hurry. I don’t know. Again, I'm speaking from my personal experience but I would say not to rush the process because I just feel like if you're rushing, you might miss important things. And if you're just like in it to hurry up and get a job, make sure you're not just like in it because you need to pay bills and get a job, that you're really enjoying what you're doing, and enjoying the process of learning because this field is all about that.

**CHUCK:&nbsp;** Yeah, but does that answer the question of should you use or learn a framework or not first?

**AIMEE:&nbsp;** Yes, my answer to that is I do feel like it's important to understand some basics before you start with the framework. When I was trying to learn Rails, that was the same question, do I learn Ruby or do I learn Rails? The people who gave me advice said, "Learn Ruby first. Don't worry about Rails yet."

**JAMISON:&nbsp;** I think that's a very personal thing though. I think some people are much more driven by seeing stuff on their screen and just getting stuff done, and they're more comfortable with some magic that they don't understand going on. So those people that just like dive into Rails and take Rails is new and make stuff happen and have no idea what's going on until they learn the framework by building stuff with it, instead of learning all the building blocks.

**AIMEE:&nbsp;** Yeah, you're totally right.

**CHUCK:&nbsp;** Well, in my experience, when I was learning Ruby on Rails and Ruby, I learned Rails first. I was building stuff in Rails and then I started to learn, "Oh well, this particular feature in Rails is an outgrowth of this functionality in Ruby," and that's kind of the way that I came around to it.

JavaScript is a little bit different for me because, as I said before, I was mostly focused on building web applications and I had kind of hodgepodge learned all kinds of different stuff about JavaScript by the time I got around to using a framework in it. But I kind of understood certain aspects of JavaScript before I learned a framework.

That being said, I don't know if one is necessarily better than the other. I think some people have to know how all of the little pieces work and how they all fit together. Those people are going to want to learn the language first then the framework next. Then there are other people that, as Jamison said, they want to see something on the screen. They want to have that to-do app up there and then they can learn as they go, as they change things in it. Those people are probably better off learning the framework and kind of getting the reward. I call it a success fix because that's what it was for me, is I had something working, I had something running, I had something that I could show off. And my reward was, "Oh, it works!" Then, I move on to something else. Then, I come back and I change it to something else that was a little bit more helpful, functional, or interesting, and move ahead from there.

So, in those cases, then I was Googling the web and lurking on mailing lists and things like that.

**JAMISON:&nbsp;** Trolling as in like the fishing trolling, not the --

**CHUCK:&nbsp;** Yes.

**JAMISON:&nbsp;** You should go die trolling.

**CHUCK:&nbsp;** Yeah.

**JAMISON:&nbsp;** I don't think you do that other kind of trolling, Chuck. I can't see it.

**CHUCK:&nbsp;** Nope. Not of my personality. But that was the way that I approached it. So everything that I learned about Ruby and everything that I learned about Rails was to a large extent for me to be able to achieve that next thing.

**JAMISON:&nbsp;** I also think it's fair to say that those approaches have different tradeoffs. I want to know hoe every underlying thing works and sometimes that's cool because I'll just run into some weird thing that some people don't understand, and I can learn it. Sometimes it makes it really hard to learn new things because I just do a depth first search of the language and then I get down to some like nitty-gritty, totally esoteric corner case that has no bearing on my ability to get stuff done. But I'm like, "What does this line do? What does this line do? What does this line do?" And keep diving down the stack trace until I end up somewhere that's not super useful.

**CHUCK:&nbsp;** Jamison reads by codes, just so you know.

**JAMISON:&nbsp;** Yeah, that's how I end up in weird places on Wikipedia when I just like to follow links instead of trying to learn. The things that I'm capable of learning right now and recognizing that understanding will come over time, I guess.

**CHUCK:&nbsp;** The thing that I find that's interesting though, is that there are a lot of courses that are also tailored around that. Some of the courses start you at basic Ruby and then build you up to where you building a Rails app, and others of them they're like, "Look, a lot of this is magic and we'll get to it later," and they start at the top with Rails and work their way down. It's just interesting the different approaches that people take.

**JAMISON:&nbsp;** That reminds me of learning Math in school. Like they all start with the thing beneath the abstraction, like when you learn Calculus to make you do it. The slow and crappy way till no one does it.

**CHUCK:&nbsp;** Yeah, with summations.

**JAMISON:&nbsp;** Yeah, and then they're like, "Now that you know how it works, here's how you actually do it."

**CHUCK:&nbsp;**"Here's how you do a derivative."

**JAMISON:&nbsp;** Yeah. It's like building up from principles which I don't know if that motivates me that much in Calculus. It's funny that it motivates me that way in programming.

**CHUCK:&nbsp;** Yeah, and I have to say that in Calculus, I don't even get why we were doing what we were doing until after I had mastered the top level concept that they were trying to build this up to. And then it was like, "Oh! Oh, that's what they were doing. Oh, that all makes sense now!" It was poorly explained. This is just a natural extension of this other thing.

**JAMISON:&nbsp;** Yeah, it's like the context thing Aimee was talking about.

**AIMEE:&nbsp;** Yeah, like when I was in college, I did not pay that much attention to my Math courses. And now as a developer, I'm actually really interested in going back and taking some of them because I feel like I have the context to know why certain things are important.

**CHUCK:&nbsp;** Well, that's the difference too between the new people and the experienced people. I think this is something that you've been driving at, Aimee, is that as experienced people, we kind of can immediately -- without even really knowing why we can drive to the center of something and go. Yet, this is the core of what's important and these other things are interesting details that may or may not be interesting depending on what problem I'm solving. With newer people, they don't have the experience necessarily to recognize those patterns yet.

**JAMISON:&nbsp;** I can, though. I think that can cut both ways. I've seen and this has happened to me personally too, I've seen people who are experienced who they see something that kind of looks like a thing they had experience with before, and they hated the thing they used before. So, they see this new thing and they're like, "Oh, it sucks because it reminds me of this old thing that I hated."

When React first came out, everyone hated the JSX syntax because it reminded them of XML, and then people had bad associations with XML and Java. There's just this collective shutter. Then, the same thing with like onclick handlers and React components or Angular or something, it reminds people of the bad old days of just sticking those in your HTML in the web. Because of those associations of the experience people had, it took them, I think for some people, it took them longer to recognize, "No this is actually different, it's better because of these reasons," because experience led them to have this knee-jerk reaction.

So experience can help you evaluate things but it can also make it harder because you can, like you said Chuck, you can look at something and see this is the core of it, it's what's important. But you can also be wrong when you're doing that. And you said the core of React is this weird XML syntax that I hate so React sucks. Then you miss something that's cool. I mean, that same thing applies to every tool or framework.

**CHUCK:&nbsp;** That's true. I think one other example is when I moved from Ruby to doing a little bit more JavaScript. I expected prototypes to act more or less, like classes. They more or less don't. They kind of do in some ways but the differences were nuanced enough to where it really threw me for a loop when it wasn't what I expected it to be.

**JAMISON:&nbsp;** Yeah, because you learned. To me, insane Ruby class system because I don't understand it that well, but it just looks Byzantine and complex and frightening but that was comfortable to use. So Prototypes, you expected to work like that. Is that what you're saying?

**CHUCK:&nbsp;** Yeah, and so it definitely sometimes experience is a curse, just in the sense of you continue to beat your head against the wall, trying to make it fit your expectations, instead of realizing that it's not going to fit your expectations because it's really different.

**JAMISON:&nbsp;** Yes, it's like you hear this kind of tired startup mythology sometimes about how back when we first started this company, we didn't know what was impossible and so we did it, whereas if we knew everything we need today, and maybe we would have never started it. That gets trotted out a lot. But I think it does apply to programming stuff, too. Sometimes having fresh eyes can be a benefit, I guess, and you can get those fresh eyes through, either just not having experience or you can also put yourself in that place as an experienced developer which seems like a good way to approach things, I guess.

**CHUCK:&nbsp;** Yeah.

**AIMEE:&nbsp;** So another question I have for you guys is because you're more experienced, how do you choose what you want to learn? Did you just base it off of what you're really interested in? Do you pull job in a hurry and try to see or maybe just advice to other people like trying to get a job? What would you say should be their criteria for what they'll learn?

**CHUCK:&nbsp;** I'll let Jamison go first on this.

**JAMISON:&nbsp;** Listen, I'm an early adopter. I had a Linkin Park CD before [inaudible] growing up in middle school.

**CHUCK:&nbsp;** That's the ultimate example, right there - the Linkin Park CD.

**JAMISON:&nbsp;** Yeah, that's my resume.

**AIMEE:&nbsp;** So then, building on that question like I've heard multiple people say, "Do not learn Elm as a newer developer." You're big fan of Elm, so what is your take on that?

**JAMISON:&nbsp;** I say learn what you're interested in.

**AIMEE:** &nbsp; Cool.

**JAMISON:** &nbsp; Elm is a fine thing to learn as a new developer. You would then probably eventually come to learn JavaScript and like pull your hair out at complexities of the language because Elm is pretty ruthless about eliminating those. But I don't think that's a bad thing.

**CHUCK:&nbsp;** I can no longer bite my tongue because this is a conversation that I have with people a lot where they go to a boot camp to learn Ruby, for example, and then they're saying, "Well, I looked at all these numbers and it looks like the percentage of programmers out there doing Ruby is declining, and the percentage of programmers out there doing JavaScript is growing." And so relative to each other, JavaScript is becoming more and more popular, more quickly than Ruby, is what I'm reading into it.

But the ultimate truth is that if I go look in the Ruby community, I find that that community is growing as well. It's just relative to the number of programmers coming into the field, not as many of them are picking Ruby as the technology stack that they're going to work in. They're like, "But I really like Ruby and there are some things about JavaScript I can't stand," and then there are others that are obviously saying the other thing. It's like, "JavaScript is just so fascinating. Why would anyone learn anything else?" I want to echo what Jamison said and just learn what you're interested in, because with most of these technologies, especially if they ever have been popular, there's plenty of work out there. So if your primary concern is, "Can I get a job doing this," the answer is probably.

Then what it comes down to is 'what's the next most important thing to you'. In a lot of cases, that’s 'this technology makes me happy'. In other cases it's 'I want to work on these kinds of social causes. I want to work on some of these other areas of concern'. Because of that, you want to pick your technology or pick whatever it is you're going to go into based on whatever those fulfillment factors are for you.

So if Ruby makes you happy, then do Ruby. If JavaScript makes you happy, do JavaScript. If Erlang makes you happy, do Erlang. If Haskell is it, do Haskell. Lisp, whatever. Some of these languages, I don't know very many companies that use Lisp in production, but there are a lot of them who use Clojure. And if you want some close, Clojure is close and interesting.

You see, you have all of these options. Would you tell people to learn Elm? Well, if that's what they wanted to do, I agree with Jamison. Yeah, go learn Elm. Because there are companies out there using it, and there's plenty of work out there for people who understand the way that Elm works. Anyway, there's my rant.

**JAMISON:&nbsp;** You said one thing there that was 'learn what you're interested in'. I think that's a good way to do it if you have enough of a context to have an interest especially for people that are brand new to programming. They just know that they're interested in the field or just programming in general. From what I've seen, they don't really have the context to say, "I'm interested in Ruby," because they don't know what makes Ruby different from everything else.

**CHUCK:&nbsp;** That's fair. But I think a lot of times too we tend to forget that programmers are also people. So Ruby or programming in general isn't the only thing I'm interested in. I really enjoy soccer. I really enjoy coaching. I really enjoy having this impact on other people where they are able to make their lives better in some way or make the world better in some way. In fact I feel very strongly that a lot of the ways that our world has evolved over the last 10 to 15 years have been directly driven by technology. That could be because we're more connected over social networks, it could be because we all have phones in our pockets that can permit us to do all kinds of things, same with tablets. I think there are a lot of things that go into what makes this world the way it is that derive directly from the way that we build code, whether it's our idea or somebody else's idea. So it doesn't necessarily even have to be a technology.

If you've been working in the financial industry for 20 years and you want to disrupt that, and you have some idea to do it, then learn how to build it. If you're looking at something else where you feel like if people could do a particular function for themselves on their phone, then go out and build it. There are so many interesting and just amazing technologies.

One of them that I'll just bring up and this kind of comes down to something that I really care about and is core to why I do the podcasts, that is that we can ultimately shape our world. We had an episode that we did on iPhreaks with Scott Hanselman. And we talked to Scott and I don't know if you know this, but Scott's a type 1 diabetic. We had a long talk about basically systems, and he's built and experimented with several, that allow a diabetic to control their insulin intake. Some of these systems get fairly close to making it automatic. Obviously, you still have to monitor and things and we talked about the shortfalls and everything like that. But can you imagine if you were able to, on a Raspberry Pi or somebody's phone, make it so that they could live their life without ever having to worry about sticking a needle in themselves again, or only having to maintain the system but not actually have to give themselves a shot or play with their pump every few minutes.

You know, there are so many ways that we can make a difference here. And so if you can't decide JavaScript or Ruby or Python or whatever, then go find where the motion is where you do care about, and then figure out what technology they're using and learn that. For the people that aren't going to gravitate to a particular technology and are just looking to get a job in programming because it's lucrative, and that's a totally valid and fine reason for doing this, go find that other thing that you care about and do that.

**JAMISON:&nbsp;** Honestly, two things. The first thing is you feel like you don't have the context to decide what technology is inherently interesting to you. I think a really good way to pick is the community because you're going to be interacting with them. You're going to have questions and a good community that answers questions that are always encouraging can make the difference between continuing or giving up. I've actually said it might be one of the most important things is how friendly and open and welcoming is the community.

**CHUCK:&nbsp;** That's true. I'll also add that some communities have a stronger component of people willing to help new people than others, so you may also want to look at that aspect of community.

**JAMISON:&nbsp;** Yep. The other thing is I want to make sure we're answering Aimee's actual question. We kind of got into the topic of, "How you decide what to learn at the very beginning when you're first learning how to program?" Is that the question you're asking, Aimee? Or did you mean more like how do you pick what to learn next?

**AIMEE:&nbsp;** At the beginning. But then too, I'm also interested to know as you advance, how do you pick? Do you [inaudible]? What interests you, drive it? Do you feel obligated to spend some time outside of work, say you get a new job? As an older developer, someone more experienced or what's coming out in ES6, ES7? Is there a responsibility on your part to take some time outside of your 40 hours a week to learn some of that? If so, how do you approach that?

**JAMISON:&nbsp;** That is a great question. So you said 'is there responsibility' and I honestly don't think there is. I think lots of people could be content to just learn on the job and learn in the work that they do. And if there's a new project that worked, then they learned a new thing. Otherwise, you just keep using the old thing or not old thing, the thing that they're currently using. And that's totally fine. Sometimes, I think we talk a lot about passion and fail to recognize that. To some people, this is a job and then let them go home and live their life. But if you are really into it and want to do it outside of work, that can benefit you greatly. I just don't think you should have to feel like you need to do that to work as a programmer.

Aimee, you talked about people looking at Google Trends and I don't know anyone in real life that does that. I only see that come up in blog posts.

**AIMEE:&nbsp;** I know. I feel like [inaudible] in blog posts. At least you should learn this because…

**JAMISON:&nbsp;** Yeah, you find the trend that supports your blog posts and then you write a blog post about how popular that thing is. I don't know, that's just seems like such a cold mechanical way to take and get to do it to your life.

**AIMEE:&nbsp;** It's because we're programmers. We need numbers to do that.

**JAMISON:&nbsp;** Yeah, that's true.

**CHUCK:&nbsp;** The other thing is that there are a lot of people too that have other things that kind of drive what they're living for and what they're doing. I found this a lot with the remote conferences. There were a lot of people that have emailed me over the last year, and have said, "I really appreciate the remote conferences because I can't travel." You know, that's something that I sort of just took for granted because I can travel.

But they have life circumstances with their significant other or a parent or a child that they can't leave at home with somebody else and they have to take care of them. So in a lot of cases, are they obligated to keep up even though they have all of these other responsibilities at home that other people don't? The answer is obviously no. I think really it just comes down to what people want to get out of their programming. And if it's a paycheck, then it's a paycheck. If it's, "Hey, I really want to understand these other things," then go learn it. If it hits your passion, then great, and if not, then go do what you're passionate about in your spare time. That can be anything you want it to be.

**JAMISON:&nbsp;** We talked about the first part a little bit about kind of what's your obligation as a developer to keep up and I feel like Chuck and I both kind of fell on the same page. But I want to hear what you have to say about that, Aimee. Maybe we can talk about the second part about how do you figure out what to learn next as an experienced developer?

**AIMEE:&nbsp;** Like for me, as somebody coming in, I do feel like maybe I'm comfortable saying this because I do enjoy doing it a little bit on my own. Maybe a little bit is an understatement.

**JAMISON:&nbsp;** You're pretty fanatical about it, I see. I think that's not an understatement.

**AIMEE:&nbsp;** Like I do enjoy digging into the stuff on my own, so maybe that biases me into being comfortable of saying this but I do feel like it's your responsibility to do some stuff out of work. I think I also say that because when you are a junior and you're getting a job, you have nothing to prove. People are gambling on you. It's my personality but I also feel like a sense of obligation to take some time on my own, to dig into whatever technologies are used at my job. So, I do feel like it's an obligation. Maybe that obligation goes away as you get more advanced, in my opinion again. Maybe that's not the case at all.

**JAMISON:&nbsp;** That's interesting.

**CHUCK:&nbsp;** I definitely agree in some ways with you, Aimee. In the first place, basically if you're new and somebody is taking a chance on you, I don't know that that obligates you necessarily to spend the extra time. But if that's what you have to do in order to be able to do your job then I think that's what obligates you because they are paying you to provide them with a certain outcome. If you can't provide them with that certain outcome, then you're not being fair to them as an employer.

**AIMEE:&nbsp;** Yeah, maybe that's more of the gist of it.

**CHUCK:&nbsp;** But the other part of it is that if you're not doing it and you're able to do your job without putting in the extra work, then I think the next thing you have to consider is that there are tradeoffs. I mean, people want people with a certain level of experience and they want people that have a certain – I mean, if I have the option of hiring the passionate person or the not passionate person, I'm going to hire the passionate person and then there's just no way around it. So if you're not excited about coding and you're not consistently pushing yourself to learn and I see somebody else who is doing that, then I'm probably going to hire them even if they aren't at the level that you are.

So, there's a certain tradeoff to it as well, and I think as long as people recognize that and they're okay with it, then some people are just going to do the bare minimum to keep them 9 to 5, and some people aren't, and some people are going to be excited about it. That's a tradeoff that people have to understand is there.

I definitely agree with Aimee on the point of if I'm paying you to do X, Y, and Z and I know that you can do X and Y, and I'm counting on you to get to the point where you can do Z in a reasonable amount of time, then you should be doing whatever you have to do in order to get point where you can do Z.

**JAMISON:&nbsp;** I want to talk about the second part of Aimee's question which is, how do you decide what to learn next? Given that you already have kind of a basic knowledge and I was thinking about this. I think I have two axes that I evaluate stuff on. I've never really defined it as [inaudible] but thinking about it is I see this in common with all the tech I've learned.

One is does it have something interesting to teach me technically, like am I excited about the stuff that I can learn by running this thing? Then the other one is I don't do that Google Trends thing at all, I don't formally evaluate stuff. But I am attracted to things that are new but that I think have the potential to become popular. So I have a little bit of a hipster, like there's a tiny man in suspenders and a beard hiding on my shoulder. That's like, "Hit the thing that's cool that no one else is using." And to some extent, I do follow that a little bit. But I usually pick things that even if they're cool and no one else is using, that hopefully someone will be using them someday in the future.

So, instead of like, I don't know [inaudible] or some random esoteric programming language like Elm is super hipster, super new, not that many people are using it, but I think it has potential to become much more widely used and it's also interesting to me technically. And fun is basically like the combination of those two things for me. Fun isn't like a separate thing that I evaluate on. It's fun if it's interesting technically and I think it's like new but has the potential to grow.

**CHUCK:&nbsp;** Yeah. For me, I definitely get you on the part of what am I going to learn from this. Like how is this going to challenge me? How is this going to push me and make me grow? How am I going to benefit from knowing this? Not even necessarily from the standpoint of 'can I get a better job' or 'can I get further down the road in my career'. But even just how does this expand my mind? Am I going to enjoy learning the lessons it has to teach me? That's a lot in common with what you were talking about, Jamison.

The other part of it, for me though, is what can I do with this? I really like outcomes and I really like winning. So if I can learn a technology, say, some mobile technology like NativeScript or React Native or Swift, then now I can build cool mobile apps. Or whether it's Angular and then I can build single page apps, or I can build better web-enabled apps, or this could make my website five times faster and that would be way cool. I have this outcome that I can get from it that I kind of aspire too, that also drives me in the technology that I learn. But I have almost never learned a technology where I learned it thinking, "Yeah, this is going to help me get my next job."

**JAMISON:&nbsp;** Yeah, I haven't used that. I've been lucky enough that the things that I picked to learn have turned out to be helpful for getting a job or using at work. But I haven't picked stuff because of the future earning potential of that directly. I feel like if it's something I'm interested in and it teaches me stuff, then the earning potential kind of comes from that.

Aimee, I feel like you discount your experience a lot like you always [inaudible] with, "Oh, I'm so new." You're not that new. You've been programming for years now. So I think you have interesting stuff to say about this, too. How do you pick interesting stuff to learn next?

**AIMEE:&nbsp;** I am a little bit like you. Like you say, I really like to deep dive into things, and I'm always just, maybe it's because I'm traditional in the sense that I really enjoy education and things like that. I am always just really interested in trying to dig into Computer Science concepts or looking at RFCs. Yes, a lot of times I read them and there's a lot of stuff that I could just go down a huge rabbit hole. But Jamison, I know we've talked about this a little bit in the past, but there's people who kind of like to just play around with things and actually like just write ton of code. For me, I'm like someone who likes to read, and explore, and do that. So that's what drives me.

Then too, I feel like it's not like a pressure from anyone else, but it's like a personal pressure - maybe pressure isn't even the right word. But the more I dig into things, the more I've been realizing since I've focused so much on JavaScript and Ruby for a while, there are so many aspects of programming that I haven't experienced yet, and so I'm just at the point where I still really, really enjoy JavaScript but I'm really interested in digging into other programming languages, whether it be just Elm for now, to explore more functional concepts. But I don't know, there's a lot of concepts and I'm really been interested in lately. That's where I am.

**JAMISON:&nbsp;** Cool. I think that makes a lot of sense. It turns out, we've had some like broad things that seems like we agree on, but we also seem to have some nuances that [inaudible] our personalities. Again, there's not really a one-size, fits-all answer. It depends a lot on your personal style.

**CHUCK:&nbsp;** Unless you're all doing it wrong.

**JAMISON:&nbsp;** Yeah, that's true. Unless your personal style is different from mine in which you are just suffering.

**CHUCK:&nbsp;** Yeah, I think that goes back again to the discussion we had before where my experience colors the way that I advise other people to do this. And I think in a lot of ways, there is some introspection that has to happen so that people can figure out what is going to do this for them, which technologies are going to challenge you if that's what you're looking for or allow you to pursue the outcomes that you want, if that's what you're looking for, or whether or not it pushes you whatever direction you want to go. Whatever it is that makes you work, I don't know how you figure that out. Maybe the two of you have some ideas there.

I also think that with some of this comes some experience as well, where you try a few things and you're like, "Yeah, that didn't inspire me," and then you try something else and, "That didn't inspire me." You try something else and you're like, "Oh, this really inspired me." And then you can start to figure out, "This inspired me because I felt like I could do it or I felt like I was learning or I felt like I was progressing in this way or that way," or whatever it is that makes you tick.

So even then, if you just have no context whatsoever for what to learn next, try a few things, and then see which of them kind of click. I can also talk to other people and get some ideas from them too. I tried these three things. Well, we all have this in common, why don't you try this that doesn't have that particular aspect to it, and see if that kind of is what your thing is.

**JAMISON:&nbsp;** I think that's a good point you made Chuck about, "You might bounce off some stuff." That happens to me a lot. I probably try large things, like languages or technologies before I find one that really sticks. So I depend a little bit to a lot of things and then find one that sticks. I don't think you have to just like pick one thing and force yourself if you're not enjoying it. So, I appreciate you saying that.

**AIMEE:&nbsp;** I was going to add to what Chuck was saying that there is definitely like a fine line there. I feel like this, especially from newer developers, like friends that I talk to and stuff. At some point, you have to put some blinders on and say, "No, I am going to buckle down and only do this for a couple months and the other stuff can wait."

**JAMISON:&nbsp;** Yeah, that's true.

**AIMEE:&nbsp;** Yeah, otherwise, you just like get everything at a surface level, and there's so much you missed out by not digging deeper into things.

**JAMISON:&nbsp;** Sure. We've been really kind of abstract at high level here. It feels like this is kind of drawing to a close, and I think it'd be cool if we all went out on a limb and suggest at one concrete thing that people should look at. And this isn't like, "You have to learn this, or you're not cool," but just one thing from each of us that we think we would recommend someone else to check out. Does that sound okay?

**AIMEE:&nbsp;** Sounds good to me.

**CHUCK:&nbsp;** No!

**JAMISON:&nbsp;** Okay, I'll just hang up then. I suggest this but I don't have a thing. Does anyone else have? I need to think for a second. Does anyone else have something they want to share first?

**AIMEE:&nbsp;** I have a thing.

**JAMISON:** &nbsp; Okay.

**AIMEE:** &nbsp; Again, let's go back to my experience and what I enjoy, but because I like to do things more foundation first, the book series by Kyle Simpson, You-Dont-Know-JS. I just think that that is prerequisite to - maybe you don't read every single book, front to back, but I would at least start with the first three or four. And I do feel like that is a prerequisite that you complete those before you try to find a job or try to really start digging into a framework, more than just like a "Hello World" tutorial.

**CHUCK:&nbsp;** We're also talking to Kyle next week, so it's a good idea for that, too.

**JAMISON:&nbsp;** So you have to say that?

**AIMEE:&nbsp;** And he did not send me anything to say that. Those books are amazing.

**CHUCK:&nbsp;** Yeah, I will tell you that if you're picking technologies, I tend to also like to pick technologies that look a little bit strange to me. Like why would anybody ever do that? Then, you start to learn more about it. I also like the technologies that tend to have a wider range of use.

For this show, some of the tools that I've looked into after checking them out are, for example, gulp. I'm not an expert in gulp by any means but I have fiddled with it quite a bit. I mean, just from coming to a tool that it looks at least on the surface similar to rake which is a tool that I use in Ruby, just learning the nuances and differences in the way that they think about those problems has been very fascinating.

Then another one that I haven't looked into as much but I have been looking into some, that just seems like a really messy and overloaded system that as I got into it, I'm like, "Okay. I can kind of see why they do some of these things," is webpack. So, if you're picking specific technologies to look into and this being a JavaScript show, go dig into those, and see where the limits are. Try and understand where people are coming from, and why they would put together a tool like that because people who put those things together, generally have a problem they're trying to solve. And even if they don't articulate well what that problem is, if you get in there you can really start to get glimpses of what's there and why you're picking them. So anyway, if I could pick two technologies in JavaScript that you have to go dig into and figure out, try some of those.

**JAMISON:&nbsp;** Okay. I feel bad because mine isn't JavaScript related now.

**CHUCK:&nbsp;** Should I pick a non-JavaScript one?

**JAMISON:&nbsp;** No, there are no constraints. You could pick like the Greek alphabet.

**CHUCK:&nbsp;** There's a book that I'm going to recommend then. Sorry to cut you off, Jamison.

**JAMISON:&nbsp;** No, sure.

**CHUCK:&nbsp;** Go pick up The Little Schemer, and then go do some programming in Scheme, if you want to bring [inaudible]. That one is fun.

**JAMISON:&nbsp;** Cool. My career has been kind of split evenly between frontend and backend. And I feel like most of the backend stuff I've learned has been through the oral tradition, just knowledge passed on from the elders by word of mouth, but never any real intense study on the right way to do stuff. It's all kind of just fumbling around in the dark and asking people that are smarter than I am what to do.

There's this book called Designing Data-Intensive Applications which is a pretty boring title but it's maybe one of the best technical books I've ever read because it dives really deep into how databases work at the systems level. Like, here in the system calls, then like, here is the block structure on this that they use, here is the architectural pattern of this one, NoSQL database compared to this other SQL database and why they have these different tradeoffs. It kind of starts at the very low systems level and then works its way up through distributed systems and different consistency and correctness, tradeoffs you can make, and it's just like an eye-opening look at what goes into building these really high performance backend systems.

I don't work at the scale where the stuff is required, honestly. This is for [inaudible] scale. A lot of this stuff is where these tradeoffs become really important. But it was just so eye-opening to see the "why" behind the "how" of a lot of technologies.

So, yeah, that expanded my brain in a pretty big way - Designing Data-Intensive Applications. That's my recommendation for a technology-related thing to look up.

**AIMEE:&nbsp;** It's also on my list of things to do.

**JAMISON:&nbsp;** It's so good.

**AIMEE:&nbsp;** It sounds so awesome.

**JAMISON:&nbsp;** It's really [inaudible]. The guy who wrote it, I think, he was one of the developers of Kafka. He's got some affiliations, I think.

**CHUCK:&nbsp;** You don't know DBs.

**JAMISON:&nbsp;** Yeah.

**CHUCK:&nbsp;** All right. With that, should we get to picks?

**AIMEE:&nbsp;** Sounds good to me.

**JAMISON:&nbsp;** Sure.

**CHUCK:&nbsp;** All right, Jamison. What are your picks?

**JAMISON:&nbsp;** I have four. So, my first pick is a blog post called accidentally nonblocking. This is kind of a low-level systems blog post. I don't know a ton about this stuff, and it's so far below the abstraction layers that I normally work. I think it's interesting to read the stuff. It's about just as detailed - it's kind of like a detective story into how this one chunk of a program works. I love these kinds of technical write-ups. It's about this person using this really kind of intense systems tool to inspect what their programmer's doing. There's one quote which is pretty rad. So, I'm going to read it. "I really like using ktrace to inspect programs. It’s somewhat primitive, to be sure, but unlike source review, it can be difficult to understand the programmer’s intentions. However, my CPU doesn’t execute intentions; it executes instructions." So, it's just like using this thing to figure out what the CPU is doing when it runs these programs. It's a cool read.

My other pick is a framework called choo. It's by this guy I met at Web Rebels last week, I think his name is Yoshua. And it's basically a port of the Elm architecture to JavaScript and this has been done in other ways but this is kind of a much more direct port of it than things like Redux which are pretty inspired by it, but not a one-to-one port of it. This is a cool experiment to see how you can take cool ideas from Elm and Python to JavaScript.

Then my third pick is just the Web Rebels Conference. It's a JavaScript and kind of web development related conference in Oslo. I was there last weekend, it was amazing. It had such good talks, like some of the best talks that I've ever seen. One of my favorites was by a woman named Mariko Kosaka, and she talks about the history of typography and used it as a lens to look at the history of computing. It turns out a ton of stuff in computing happened because people were trying to figure out how to make fonts render well on computers. That might have been my favorite talk I've ever seen. It was really good.

My last pick is just [inaudible] React Rally. It's a conference about React in Salt Lake City in August. We have our speaker lineup announced and I'm really excited for them. I am genuinely excited for every single talk. If you Google 'React Rally', you'll go to ReactRally.com and you'll see the lineup and be able to buy tickets. I'd love to see you there. Those are my picks.

**CHUCK:&nbsp;** Awesome. Aimee, what are your picks?

**AIMEE:&nbsp;** I have two. It's been a while since I have a new bar that I was excited about. So, that's my first pick. They are made in Tennessee because I'm from the South, they're especially awesome. They’re called Grab The Gold, and they taste really, really, really good.

**JAMISON:&nbsp;** Oh, you mean food bar?

**AIMEE:&nbsp;** Yeah, not bar like that.

**JAMISON:** Got it. It makes sense now.

**AIMEE:** &nbsp; How can I do that when I'm such a health nut? These are so good. I always say that every time but these are really good. Anyway, programming pick. I was kind of reaching through all of these different things that I have in my list, and this one felt really fitting for today. But it is a GitHub repo by rockbot. It's called node-for-beginners. I think like one cool thing that sets this one apart from a lot of the other repos that are just like here are a million tutorials, she has this one, there's a column there that ranks it by level of difficulty. So I think this is very valuable because a lot of times, I feel like I'll invest a night or something starting a book, and you're like either way too deep or this is like way not deep enough. So maybe that would be valuable for someone. And that is it for me.

**CHUCK:&nbsp;** All right. I've got a couple of picks. The first one is a book. It is by Rory Vaden It's called Procrastinate on Purpose.

**JAMISON:&nbsp;** I like it already.

**CHUCK:&nbsp;** It's all about prioritization and doing the right things at the right times. A lot of people asked me regarding freelancing and entrepreneurship about balance, and he basically calls out 'balance is a myth'. And then he talks about why and he has a really great metaphor for how you take time from one bucket and put it in another. Anyway, it's super good so far. I'm not finished with it yet, but I am really enjoying it. I've heard a couple of interviews that he's done on podcasts, and they have been terrific, so I'm definitely going to pick it. The idea behind it in a lot of cases is that you put some things off so that you can take care of what's important now. And then you can reprioritize, then you put some things off in that area of life to prioritize another area of life. Anyway, I really, really have liked the book.

I'm also going to pick a couple of self-serving picks. If you're a new person, Newbie's Remote Conf like I said before, coming up in July 13th through 15th. I'm also writing a book on how to find a programming job. It's called Get A Coder Job. You can find that it at GetACoderJob.com.

I'm actually putting together webinar series where I talk about a lot of the content in the book but it's going to be personalized and I'm also going to be doing some - I don't know what to call them. I guess they're live coaching sessions where I'll have some people who are trying to find their first programming job, come in, and I will coach them in front of everybody else who's on the call. But I'm hoping that they'll ask some of the questions that a lot of other folks have, and that a lot of the advice that I give will be directly related to where people are at. So if any of that interests you, you can go to GetACoderJob.com and you can actually sign up for that. The seats are going to be fairly limited. I don't want s huge group. I'm looking at like 20 or 30 people, and 10 of those are going to be people who apply for the one-on-one coaching.

I'm not sure when this goes out relative to when the deadline is for those applications. So if you miss the applications then just go ahead and buy a ticket. But yeah, it's going to be fairly limited numbers, just so that I can make sure that I can serve everybody who shows up. Anyway, if you're interested in either of those, then definitely go check those out. Yeah, those are my picks.

I'm also thinking about whether or not I can go to React Rally, so check that out too.

**AIMEE:&nbsp;** I'll be there.

**CHUCK:&nbsp;** Yey! We'll have to have a JavaScript Jabber party.

**JAMISON:&nbsp;** Yeah.

**CHUCK:&nbsp;** All right. Well, let's go ahead and wrap this one up. Thank you both for all of your input. I think this is a really interesting discussion. Catch everyone next week.

**_[Bandwidth for this segment is provided by CacheFly, the world’s fastest CDN. Deliver your content fast with CacheFly. Visit CacheFly.com to learn more.]_**

**_[Do you wish you could be part of the discussion on JavaScript Jabber? Do you have a burning question for one of our guests? Now you can join the action at our membership forum. You can sign up at JavaScriptJabber.com/Jabber and there you can join discussions with the regular panelists and our guests.]_**
