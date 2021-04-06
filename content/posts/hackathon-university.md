---
title: "Proposal: Hackathon University"
date: 2021-03-24T10:23:35-05:00
draft: false
---

*Disclaimer: I am currently a computer science student in college.*

## The Current System

> What should you do in college to become a [good hacker](http://www.paulgraham.com/gh.html)? There are two main things you can do: become very good at programming, and learn a lot about specific, cool problems. These turn out to be equivalent, because each drives you to do the other.
>
> The way to be good at programming is to work (a) a lot (b) on hard problems. And the way to make yourself work on hard problems is to work on some very engaging project.
>
> Odds are this project won't be a class assignment.
>
> Paul Graham, [Undergraduation](http://www.paulgraham.com/college.html)

Currently, every computer science student in college takes the same basic courses in his first two years - data structures, algorithms, operating systems, etc. For the next two, he will have his choice in which upper division courses to take. Nonetheless, the structure of every class he will take is the same: about 8 or so cookie cutter coding projects stolen from Stanford or Carnegie Mellon and 3 tests that the professor wrote up the night before he administers them.

As far as I can tell, there is shockingly little creativity in how courses are taught across different universities. Administrators decide which classes should be offered based on what courses the prestigious universities are offering. And because the syllabi are public, professors at lower ranked universities just copy the schedule, slides, projects, and reading materials from professors at higher ranked ones. It is entirely possible that some professor at Stanford decides how operating systems is taught to every student in the world.

It could be worse. There could be zero projects, and the courses could be entirely (instead of partly) graded on how well you can memorize superficial details that will be out of date by the time you graduate (or are already out of date). Nonetheless, the current system is definitely not optimal. Every programmer knows that you learn the most by working on challenging projects which you find interesting. Since the student does not get to pick his projects, he is unlikely to find them interesting. And in my experience, the challenging part about most projects is not the concept being implemented but rather just the process of figuring out why your implementation is not compatible with the starter files that the professor (at Stanford) has prepared for you.

**The system does the job it's built to do - signal who the good workers are. If you can go through a codebase making formulaic changes that an authority told you to make under a deadline, you will make an excellent Nth hire for Oracle or Microsoft. But you, my friend, are no** [**hacker**](http://www.paulgraham.com/hp.html)**.**

This is not to say that everyone needs to become a hacker. If all the engineers in the empire start building digital cathedrals, no one will be left to do maintenance on the bridges. Most people who study computer science in college do not have the desire nor the capacity to become a Linus Torvalds or an Aaron Swartz.

And luckily for them, there’s 9,999 colleges in the country which have no intention of turning them into great coders. All I’m asking for is one university which is exclusively focused on training hackers. For such an institution, I offer the following proposal.

## Proposal

What if universities were organized around monthly hackathons? There would be different hackathons going on at the same time, each with a different theme: file systems, ray tracers, neural networks, etc. Students would choose which hackathon they want to participate in every month. They would spend the first two weeks of the month coming up with what they want to build and how they will build it. They would attend relevant lectures, read tutorials and papers, and talk with professors and other students about their ideas. During the final two weeks, they would use everything they have learned to build something new and interesting that fulfills the criteria of the theme.

To make sure that the students are actually building things, the professors could reject submissions that don't show comprehensive mastery of the theme and a creative application of the relevant concepts - try again next month. To make sure that every student is familiar with the fundamental subjects in computer science, colleges could require that all students must complete hackathons on a few select themes like data structures or compilers before they graduate. The rest of the credits can be fulfilled by any hackathon the student chooses.

Assuming four months in a semester, this college could administer 32 month-long hackathons in a four year college career. If this seems excessive, that should tell you about the amount of time that is wasted in a college education. I would guess that students could learn more after a year of doing these kinds hackathons than after four years of a traditional computer science curriculum.

Many modifications to this proposal are possible for colleges to experiment with:

- Sequences of hackathons on the same subject - algorithms 1, algorithms 2, ... - with ever increasing criterion for quality and mastery 
  - The first one will let you get away with implementing an existing algorithm in a slightly new and creative way, but the last one will demand almost a thesis quality new idea or application.
- Overlapping hackathons with offset final weeks
  - I'm not a big fan of this one as it prevents students from single-mindedly exploring a specific problem and disperses their energy. What would happen if we expected founders to start multiple companies at once? You would get completely unexceptional and mediocre results. Too much of college is like the allegory of the man who digs a 100 five foot holes in search of water when all he needed to do to quench his thirst was to dig 25 feet in any single spot. I would like to escape this pattern.
- Team hackathons
- Winners get waived tuition or extra honors or something

### Extrimistan

It could end up being the case that a student learns less by doing an average monthly hackathon than by completing an average programming assignment.

But Toto, I have a feeling we're not in Mediocristan anymore. Maybe every research project Larry Page worked on before PageRank was useless. But fortunes and careers are not created by your average performance. The expected value of your work is dominated by the best thing you ever do - especially in a field like computer science where the reward for your best work can be in the billions of dollars.

Which means you want to increase volatility, even at the risk of doing lots of useless projects. It may be useful to ask how you would optimize for the opposite. For example:

Make every student take the same classes and do the same projects. Don't give students the autonomy to implement these projects in creative and unforeseen ways. Teach students about decades old ideas which have been fully explored. Don't spend too much time on new techniques or open questions. 

### The Untaught Lesson

One of the most common jokes on the Programmer Humor subreddit is the ridiculous amount of experience which recruiters demand on their job board. I have a suspicion that these requirements are put up in order to eliminate recent college graduates who have not learned the softer skills of analyzing problems and generating their own solutions. 

![Developer experience meme](/developer-experience-meme.jpg)

Here is how a programming assignment in college usually work. The professor tells you which problem you need to solve and how you must solve it, and she gives you an autograder which tells you instantly whether your solution worked by comparing it to a prebuilt reference solution.

At no point during this assignment is the student asked to identify what problems should be solved in the first place, nor is he asked to weigh the tradeoffs of different solutions. He is not trained to proactively analyze whether his solution works and how it may be optimized. These activities are largely what actual engineers are expected to do everyday, and yet the current system provides no training for them.

Regular hackathons would make students exercise these skills. The students has to choose a problem to work on, and he has to come up with a solution from scratch instead of being handed starter files and bulleted instructions.

### Punctuated Hysteria

College students like to slack off and explore, and then work intensely for a brief period of time before the deadline. So why not exploit this tendency instead of settling for consistent but mediocre performance? 3 weeks of learning, reading, and being curious followed by 1 week of intense hacking sounds way more fun than a semester of overlapping fill-in-the-blank projects. 

By the way, punctuated hysteria is not simply a vice of college students - this is how human being like to work:

> [N]ormal human work patterns take the form of periodic intense bursts of energy, followed by relaxation, followed by slowly picking up again toward another intense bout. This is what farming is like, for instance: all-hands-on-deck mobilization around planting and harvest, but otherwise, whole seasons taken up largely by minding and mending things, minor projects, and puttering around. But even daily tasks, or projects such as building a house or preparing for a feast, tend to take roughly this form. In other words, the traditional student’s pattern of lackadaisical study leading up to intense cramming before exams and then slacking off again—I like to refer to it as “punctuated hysteria”—is typical of how human beings have always tended to go about necessary tasks if no one forces them to act otherwise.
>
> David Graeber, [Bullshit Jobs](https://www.amazon.com/Bullshit-Jobs-Theory-David-Graeber/dp/150114331X)

### Cheating

Computer science programming assignments are extremely easy to cheat on. Like I mentioned, the projects are often copied directly from Stanford or Carnegie Mellon by dozens of other professors. And these assignments are not significantly updated year to year, meaning thousands of students will have completed the exact same assignment and many dozens of them will have posted their code on Github. Most students try to find code online if they're stuck, and since it's so easy for them to do so, this unfairly punishes the students who don't cheat.

The sad part is that you don't feel guilty for cheating - you're not stuck because you don't understand a concept you should learn before graduating but rather because you don't know where and how the professor wants to modify the starter files.

It is much harder to cheat in hackathons than it is to cheat on normal programming assignments for the same reason that it is much harder to cheat on an essay than it is to cheat on a fill in the blank quiz. In the programming assignment, you are supposed to implement the same thing in the same way, so it's not surprising that your code might resemble someone else's. But if you choose the same idea as someone else for a hackathon, and then you implement it in the same way, you're much easier to catch.

But hackathons do something more important than reducing cheating itself - they eliminate the vicious circumstances which enable cheating in the first place  - mindless, copy-pasted assignments which don't require or reward creativity.

### Mastery

Does anyone believe that you become a great programmer by doing cookie cutter programming assignments? If so, how come I never hear anyone give this advice? How come no great hacker ever says, find all of the coding projects on MIT’s website and work your way through them?

Instead, the advice I have read good programmers give has always been the same: find and work on challenging problems that you find interesting. What if going to university for computer science allowed you to follow that advice? The purpose of the university would be to give you the motivation, mentoring, resources, and structure to work on the problems that you find interesting and to try to implement your ideas.

## Appendix: The Recurse Center

After writing this essay, I remembered that there actually is a place which is very much like Hackathon University. It’s called the [Recurse Center](https://www.recurse.com/). It’s a 12 week self directed educational retreat for programmers of all levels of experience.

Julia Evans [writes](https://jvns.ca/blog/2014/03/10/help/) about her experience at the Recurse Center:

> At Hacker School [aka Recurse Center], people who are new to programming learn incredibly fast. Hacker Schoolers learn Clojure and Scala and Erlang and Python and Ruby and Haskell and web programming and sockets. They write compilers and BitTorrent clients and generate music and create new programming languages and make games. At Hacker School, people get dramatically better at programming. It’s almost a magical environment[.]

The success of the Recurse Center shows that education by hackathon is an extremely effective learning strategy for many students and that it may be possible to scale the structure of The Recurse Center into a full fledged Hackathon University.