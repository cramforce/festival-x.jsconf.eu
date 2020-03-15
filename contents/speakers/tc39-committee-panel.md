----

# THIS FILE WAS GENERATED AUTOMATICALLY.
# CHANGES MADE HERE WILL BE OVERWRITTEN.

template: pages/speaker.html.njk
title: 'TC39 Committee: Panel'
data:
  published: true
  reviewed: true
  order: null
  firstname: TC39
  lastname: Committee
  talkTitle: Panel
  coSpeakers: null
  twitterHandle: 'https://twitter.com/tc39'
  githubHandle: 'https://github.com/tc39'
  homepage: 'https://tc39.github.io'
  potraitImageUrl: 'https://avatars3.githubusercontent.com/u/1725583?s=400&v=4'
  caption: "TC39 Committee Panel\r\n>> Hello! Wake up after lunch my name's Rachel White. I'm going to be your emcee for the next three-ish hours or so. \r\n>> I am the developer experience lead at American Express. We are hiring, if you're into that. Talk to me later. The next panel that we have today is going to be the TC39 committee panel, and I'm going to let them handle their intros. Thanks. \r\n>> Hello, everyone. Welcome to the third and final, for the time being, TC39 panel we are doing at JSConf. It's always a pleasure to come back. We will introduce ourselves as we speak. We collected your questions in the last couple of weeks. A little bit differently, we are going to ask questions from the past years, so, that's how the panel's going to work. Let's give a round of applause for the panel members. [Applause]. As we get started, not everyone knows how the committee works or what the committee is. There was a question that was asked in person at one of our prep events that seemed quite obvious, but it is a great question to start with: what is the organisation behind TC39 in ? \r\n>> Hi, I'm Aki, part of the chair group for TC39. I work for PayPal in Braintree. TC39 is the 39th technical committee by the name of a committee called Ecma International, a standards body, like ISO, or that sort of thing, and they publish the standard that we work on as a committee. That's the organisation behind TC39. The committee itself is made up of people who are sent by member organisations that are companies and non-profits who are part of Ecma. We are considered delegates. We either work for or are associated with these companies that are part of Ecma International. We work together and collaborate on what goes into the spec, and how we are going to be able to make improvements and changes, and support all these different ways that JavaScript is used. \r\n>> Thank you, Aki. And the next question that we are going to do to set up the stage what TC 39 is and does is how does a proposal move through the committee. We have Jase here on stage who did a wonderful talk about his Rust engine in JavaScript, and he's been doing more work with the TC39, specifically, he's been getting a proposal through called All Settled. Can you tell us about getting a proposal through such a committee? \r\n>> Yeah, I was quite lucky to meet a lot of people on the committee last year in London. I felt a lot started off with a conversation, and talking to various members of the committee, if there was an appetite for such a proposal. It turns out there was. That was a good thing. Daniel, he has been helpful in putting me in contact with the right people. Not only that, but people who come from different backgrounds as well. That really helped. It started off by a \"straw person proposal\" which is a state zero which is a GIT repo with identifying the problem space. Then we managed to get a champion here, Matthias, V8 - and stage one is identifying what is the problem here? What is the limitation and you  and how we can fix it. It's not too important to have a solution at this point. We managed to craft something up that worked. We had a small proposal that went through - Matthias championed it. For stage 2, myself and Rob from Bloomberg both worked together on some of the specification, and also getting more ideas from people as well. Also, another good thing is after stage 1, we had implementation from Babel which is really good which helps as well when you get feedback. Stage 3 is getting even more feedback and thinking about a candidate release, and luckily, I don't think there were too many sort of rejections or limitations, and most people seemed happy with it, and very recently, we made stage 3 as well, and so now, I think it's just getting some implementations in browsers, and people can try it in Chrome and Canary, and nightly. Yes, hopefully stage 4. \r\n>> You made this proposal not as a member of the committee but as an independent contributor, right? \r\n>> Yes, absolutely. I was become at the BBC at the time. It was a limitation for me as a JavaScript developer, and I thought if it's a limitation for me, how many other people have this limitation? One of those ways of working that out was going to npm seeing how many people download these packages, others languages have this natively. Can we do it in JavaScript? Everyone here was friendly. I had a conversation with members of the panel, and they were very happy to champion it, and we went from there. \r\n>> And I'm going to ask you to introduce yourself? \r\n>> Yes, Jason Williams, software engineer at Bloomberg. \r\n>> So, another question that we get sometimes is we've got this whole proposal structure, but how do we know it's implemented correctly in browsers? What is going on there? I'm going to hand this over to Valerie, and, if you could introduce yourself, and how we do that? \r\n>> I'm an open-web engineer. I'm also the editor - the extension to JavaScript called Ecma 402, the object that does pluralisation and daytime formatting. I help to maintain the test 262 test suite which is ECMAScript implementations. The test suite is about 35,000 tests which test the individual tests, which test JavaScript. Each test is a test file which has some metadata about what line it tests in ECMAScript itself. Each test is run twice. There are really 70,000 tests, once in strict and this is non-strict mode. This report is showing how well the tests are doing on all of the four four JavaScript engines, and the tests are each in individual tests files, so this is a directory structure which shows the test structure that you can find, and, if you want to look at the source, you can drill down and look at individual tests and whether or not they're passing, and see the source code on the page of this website. Or you can go to our GitHub, TC39/test 2662, and to get a standard in ECMAScript or a new proposal in Ecma script, the last test is to add to test 662 as well as the browser implementation. There are tests beak contributed, and all the browsers can make sure they're in compliance and passing the same tests. It's a fun project. [Applause]. \r\n>> Thank you, Valerie. \r\n>> If I could add to that. This is actually really an awesome resource. Jason talked about implementing a JavaScript engine, but for our major JavaScript engines having something like this to be able to say very easily when are we not being spec-conformant is such an immense resource. \r\n>> And can you introduce yourself? \r\n>> Oh, yes, I'm Ross Kersling and I work at PlayStation on our WebKit team. \r\n>> Thank you. So, this sort of rounds off our introduction to how TC39 works, and we're going to be moving on with community questions that you folks asked, and we will start with one from last year, asked by Sam Basson. He asked, \"I notice the committee's very heavily dominated by Americans and American companies, particularly Google. Do you have any plans to become more representative of the world, and only give certain companies so much power?\" \r\n>> We're looking at how individual companies and specifically individual spaces where we get together in person are impacting those contributions, and Ecma International, which is the organisation we're part of, in fact, is currently put an effort into helping us find a way to be more inclusive internationally in future years. The 2019 meetings are already scheduled, but 2020 is being scheduled right now, and we are going to work on finding a way of being more inclusive. \r\n>> Thank you. That was a nice answer. \r\n>> Hi, I'm Daniel Aaronberg, I work in our compiler's team. I think there is a real issue of this particular kind of bias, that was identified, but I just also want to point out there is heavy European involvement in the development of the JavaScript specification, both from people in Munich V8 office, V8 from Bloomberg, and my company based in Spain, and several others also. We can build on that success, of course. Julia based in Germany. \r\n>> I'm based in Germany and Berlin, so, if you have any complaints, you know where to find me! Thanks for that answer. Moving along into more specific questions about the standard, we have had several questions about how long it takes to standardise things and when do things come out? Like how long does it take for a proposal to go from stage zero to stage four? \r\n>> I will take that one. It can take a very long time. The simple answer is years. If you were to essentially - essentially, you wouldn't really expecting to through our staging process more than one per meeting, and we do meet every other month, but, you know, there's a lot to do in that time frame. Implementing in Babel may take time, for instance. The problem space you're addressing might be quite clear but the solution may not be. Maybe you need to revise that ultimate times. Decorators might be a great example. Finally, at the end of it all, before we can say that we are all said and done, we need this to be implemented - and shipping - in at least two of the major engines, and you, unless you want to implement that yourself, might not have control over that time frame. It can take a very lock time, and discussions can get very heated, and so unless you have a very simple, very uncontroversial proposal, it will probably take on the order of years. \r\n>> The next question we have is about when are we going to get a standard library for JavaScript? \r\n>> So, from the way I see it, we already have a standard library in JavaScript. We have a bunch of functions, map, JSON, array, a map set. JavaScript has a pretty - well, I was going to say a pretty big standard library but that's not true. That's what this question is really getting at, is can we have a bigger and more standard things in the library for JavaScript? Should we put the standard library in modules instead of where we are currently putting it which is in globals? And these are pretty interesting questions, and I'm definitely supportive of exploring them. I've been working on them myself partially from the website. I am Dominic from the Chrome Team at Google. Thank you. And I want to mention our colleagues at Apple have focused, adding these new standard library features as built-in modules rather than built-in globals. \r\n>> We're looking into several concrete proposals in TC39 about features to add to the standard library. You heard in Tara's talk earlier today about recent additions like object from entries, and there are other things that we are considering putting in maybe built-in modules, or maybe in the traditional way as properties of objects that are connected to the global. We're looking into Temporal which is a date-time library which could make it so that you don't need to use moment, looking into possibly new ID standard library, or a library for iterator helper methods, as well as methods on set and math. I think we are missing a bunch of things that would be useful to have in the standard library, so it would be great to have more help from contributors about this. \r\n>> Yes, I want to mention that some of these library-type features have been some of the most successful proposals in getting through the process more quickly, so I mentioned that features can take years, but we've also had years that take six months or eight months, because they're kind of just, oh, yes, everybody agrees we should have a finally method on promise, that kind of thing. When we talk about the JavaScript standard library, it's important to look at things that are available across the ecosystem and that ship with JavaScript run times everywhere, and that include things like URL and text browser which are in Node and other run times if they wish to implement them. There are a bunch of examples like that. \r\n>> You will hear more about the integration of URL and texting coder and browser web API s in a talk later today. We are trying to break down the barriers of different standards groups and make sure we can all work together to build a good JavaScript-centred library. [Applause]. \r\n>> Thank you, Dominic and Dan. Moving on to our next question. we have a question that's been given to us anonymously, asking: often we are having discussion that are related to proposals and larger questions than TC39. Yet Discuss is not being used. Is there any plan to improve this? \r\n>> Funny you should mention! We are currently working on having a new discourse instance. It gives us an opportunity to be able to figure out what people really are talking about so that delegates who have limited time - and we also have day jobs, we do this in addition - can really engage with what the community wants to talk about, and it will give us the ability to have those conversations in public, and hopefully be less of a black box to people, because we really do want to engage with people. It's just hard to find each other when what we talk about can be so esoteric. \r\n>> Actually, we have another slide here. If you want to check that out, here's a QR code, and you can go to that directly. I will leave that on for a second. Thank you, Aki. Moving on to the next question, and we have had this the last two years, which is on the pattern-matching proposal.: I've not seen any movement on the pattern-matching proposal. Is it in an idle state? If it lands as a statement, what will be the heuristics to decide when using it or a chain of if-else? Do you think having pattern-matching as an expression would be more beneficial? \r\n>> That's a big question. I'm Cat and one of the co-champions and co-authors of the pattern-matching proposal. The proposal has stalled right now. These things take a lot of time right now. Sometimes, what is hot right now - what is at right now, it's waiting to be proposed for a stage 2. As soon as I get lead to show up for a meeting and - get is ready for a stage 2. As far as the statement versus expression thing, that's a much harder problem. We have Dan, actually, proposed a really interesting solution to the statement and expression problem. For those of you who don't know, like the pattern-matching proposal currently is only a statement, so it doesn't allow you to directly assign from the pattern-matching theme because it was  it has ergonomics that are more spectacular to other things like if, and else, and that stuff. \r\n>> It's hard to evolve the grammar of JavaScript. There's a lot of things in it already, and there are a lot of things that sort of happen implicitly so, to sort of work through this, there are various different solutions, and that's sort of why a lot of these proposals take time at TC39 because, for a big proposal like pattern-matching, we need to consider a lot of different alternatives to work through these kind of technical issues, and find something that's really going to be good again. \r\n>> We have a second question about this from last year. Leonard Koch asks what are your thoughts on reducing the capabilities of the pattern-matching proposal expression to statement in favour of cohesion? \r\n>> So, I guess I kind of answered this already, didn't I? \r\n>> You might have. Sorry. \r\n>> I think I might have answered this already. You know, the idea is I don't like the idea that it's a statement. I want to get something out there because I would rather have a statement than no pattern-matching at all, and my hope is that once we have it as a statement, we can use that as justification to bring more conditionals into expressions, so that maybe we can start discussing, say, bringing if-else into bringing an expression, and then the trouble it's like the semantics in the language don't make it particularly easy to say what the result of a statement-like thing will be if used in an expression position. And kind of like there's one proposal that is out there answering those questions, and I kind of wanted that proposal at least to start exploring that before giving us a solid answer. That's an expressions proposal, whether or not it's required to wrap it with \"do\" is up to the future, but we need to answer the same problem regardless of these. \r\n>> Next yes, moving right along into questions regarding language design. We had a question from Marvin. This is also from last year: are there any long-term goals? What is the bigger picture for JavaScript in the next five years? \r\n>> Hi, I'm Shu, I work at Bloomberg. So, JavaScript is many things to many people, including all of you in the community here. That is the same for us in committee. It's many things to many of us in committee. We have different personal visions and aesthetics to what we want the language to be, and perhaps we are also constrained by what our companies would like the language to be for its use case. It is a committee language, so it's not a one-author language where it's much easier to kind of exercise your singular vision for better or for worse. So, the answer is it's really hard to say what the five-year picture, or what the big picture of what JavaScript is right now. It's we are trying to work out a consensus between the many different visions that people bring to committee, and I want to - the usual response to this when you hear this is it's going to be a mess, and it's going to be full of compromises, going to be full of things that people don't like. But I think in practice, JavaScript is eminently useful, it keeps getting more and more popular, used basically everywhere on the front-end and the back-end. We've done a decent job, and I would hope that we can do a better job the a bringing more cohesion, but there's going to be no singular vision going forward. It's going to be difficult to get that but I hope to have consensus on practicality, and what is most important thing at the time. \r\n>> Thank you. The next question we have is about how transpiling impacts JavaScript, and specific questions are foals: JavaScript has become the target of many compilers. How does this fact influence your work on the language in general? \r\n>> I work on Babel. I think it is what it is being able to use features before they're implemented, an opportunity for all in the community to work out involved, testing them out in the early stages, although we warn against doing that in production, and just being able to be a part of - you don't have to be on the committee, but being able to be involved - yeah. \r\n>> Thank you. And moving on to the next one from Soran: when writing new features, where do you look most for inspiration? Other languages? Which ones, in that case? Or is it mostly driven by requests from the community? \r\n>> Very quickly, again was the answer is many things to many people, but for me personally, I've always very much wanted to bring new capabilities to the language on the web that it could not do before, like what we have done with shared array buffers to bring shared memory programming to the web, and as we hope to do soon, ... \r\n>> I want to second what Shu said, but from my perspective, as somebody who represents the Chrome team, we're interested in what makes programming on the web easier, and so when we think about new features, we're like, what are people commonly doing? What shows up popular - what is a popular pattern for writing websites that is hard because of JavaScript today? An example proposal which I kind of started but never really followed through on is something called blocks where it's we want it to be easier for people to write web workers inline in JavaScript because we think concurrency is important on the web. Things like that is one motivating factor that at least one member of the committee tries to use to govern this process. \r\n>> Thank you for that answer, Dominic. The next question is from Mark, with the new operations and features being added to JavaScript, is there a risk that the language will have too cryptic a syntax for new developers. Web development being approachable is a big boon. \r\n>> I will try to answer this as quickly as possible. We do this strongly with each proposal. We have a notion of a syntax budget which simplifies the idea that there is only so much syntax you can take before being overwhelmed in using a language, so we want that to be comfortable. We don't want to overshoot that, but we do want to make use of new syntax where it really is worthwhile. \r\n>> We will have a couple of quick back-and-forths. \r\n>> Sometimes, adding just a little bit of new syntax can make programming easier. Like a lot of programmers are exciting about the optional chaining proposal where you use question mark dot. Even if it is undefined, it still works. Adding new syntax can make things easier to programme. We consider this as a trade-off, not an absolute. \r\n>> Thank you. So thank you very much to everyone who is on the panel, and thank you all for being such a wonderful audience. As always, we are looking for different ways to help people participate in the process and also help us get the best data. One thing that we are doing right now is an experiment that's currently running. I forgot that side was there. We currently have an experiment running. If you want to participate in it, here, this is very finicky, here is -- please feel free to go to the URL and take the survey. It will help us whether or not experimental data works for the committee process. That's all for our panel. Thank you so much, everyone. [Applause]. Oh, one last thing: anyone who has further questions and didn't manage to get their questions in, we will be in the corner over there taking more questions if you want to talk to us directly. "
  name: TC39 Committee
  image:
    filename: tc39-committee-73aae273.png
    filename_500: tc39-committee-73aae273-500.jpg
    filename_1000: tc39-committee-73aae273-1000.jpg
    filename_square_1000: tc39-committee-73aae273-1000-square.jpg
    filename_square_500: tc39-committee-73aae273-500-square.jpg
    filename_square_200: tc39-committee-73aae273-200-square.jpg
    width: 400
    height: 400
    originalType: png
  web:
    twitter:
      handle: tc39
      url: 'https://twitter.com/tc39'
    github:
      handle: tc39
      url: 'https://github.com/tc39'
    homepage:
      handle: tc39.github.io
      url: 'https://tc39.github.io'
filename: /tc39-committee/panel.html
yt:
  id: slA06pbTRi4
  url: 'https://youtube.com/watch/slA06pbTRi4'
  title: Panel by TC39 Committee | JSConf EU 2019
  poster: 'https://i.ytimg.com/vi/slA06pbTRi4/maxresdefault.jpg'
  index: 12
  schema:
    '@context': 'https://schema.org'
    '@type': VideoObject
    name: Panel by TC39 Committee | JSConf EU 2019
    duration: PT26M26S
    description: >-
      Join us for the third annual TC39 panel at JSConf EU! TC39 is the
      standards committee that designs the JavaScript language (sometimes called
      ECMAScript). The panel will feature a range of committee members and is
      your chance to ask questions about the past, present and future of
      JavaScript!


      https://2019.jsconf.eu/tc39-committee/panel.html
    thumbnailUrl: 'https://i.ytimg.com/vi/slA06pbTRi4/maxresdefault.jpg'
    uploadDate: '2019-06-12T13:59:10.000Z'
    publisher:
      '@type': Organization
      name: JSConf EU
      logo:
        '@type': ImageObject
        url: 'https://2019.jsconf.eu/android-chrome-512x512.png'
        width: 512
        height: 512
    embedUrl: 'https://www.youtube.com/embed/slA06pbTRi4'
    interactionCount: 4277
    actor:
      name: TC39 Committee
  viewsPerHour: 1.1861884789639876
  websiteUrl: /tc39-committee/panel.html

----

 