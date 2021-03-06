Ten Quick Tips For Teaching Using Participatory Live Coding
----------------------------------------------

Lex Nederbragt, Version 0.1 January 2020.

# Introduction

## What is participatory live coding?

Participatory live coding is a technique where a teacher or instructor does live programming
while the learners simultaneously copy and execute the exact code or commands that are being written.
The instructor reads what is being typed out loud,
explaining the different elements and principles.
Instructor and learners all execute the commands or program,
leading to an immediate evaluation of the results.
Learners thus 'code-along' with the instructor.
There are frequent, often short, exercises,
where learners are asked to solve a small relevant problem on their own.

This approach aims to be an improvement on teaching programming through lecturing showing static code,
or relying on learners reading a textbook or compendium.
What is taught is immediately applied rather than just shown on a slide or on paper.
It also slows the instructor down,
giving learners more time to actively engage with the material before moving on to the next concept.
The thought process behind coding also becomes more apparent when this is observed live.
Learner's questions can immediately be answered and misconceptions corrected by demonstration.
Exercises enable immediate practice using the material.
The participatory, 'code-along' aspect is important to help novices become active practitioners,
rather than passive observers of the programming process.

Crucially,
the technique also allows for teaching handling of mistakes.
Beyond deliberately introducing mistakes during the live coding,
instructors will often make unplanned mistakes.
Novice learners are likely to make many such mistakes themselves,
and diagnosing and solving mistakes is an integral aspect of learning programming.

Participatory live coding for teaching programming should not be confused with Live Coding used to demonstrate software
(for example, at a conference, with an audience passively observing),
Live Streaming programming (doi:10.1145/3059009.3059035),
or used as a form of performing art (e.g. while creating computer music, https://www.cambridge.org/core/journals/organised-sound/article/live-coding-in-laptop-performance/08F42B84BBCA427C345030481A3DDA0D).

A video recording demonstrating the technique can be found here <https://vimeo.com/139316669>.

## Who uses it

Participatory live coding is the main teaching method in workshops organised by the global non-profit called The Carpentries,
the umbrella organisation for Software Carpentry, Data Carpentry and Library Carpentry
(https://carpentries.org, doi:10.12688/f1000research.3-62.v2).
Increasingly,
university courses involving the teaching of programming or related techniques employ the method
(https://lexnederbragt.com/blog/2017-12-17-experiences-with-the-first-edition-of-introduction-to-computational-modelling-for-the-biosciences/, https://jose.theoj.org/papers/1a083e69c49c15011f9404dfab9b1ec8).

There is a limited body of research on the effectiveness of Live coding in programming education.
Most studies focus on non-participatory live coding,
demonstrating the programming process and opposing this to the use of static code on slides
(https://doi.org/10.1145/3279720.3279725 and references therein, as well as https://dl.acm.org/doi/10.1145/3373165.3373182).
So far, the technique show that live-coding is as good as if not better than static code examples.

The ten quick tips described below are aimed at those interested in applying the technique in to their own teaching.
These complement the "Ten quick tips for delivering programming lessons"
https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007433.

## Tip 1. Go slowly.

Say out loud what you are doing while you do it
for every command you type,
every word of code you write,
and every menu item or website button you click,
and then point to the command and its output on the screen and optionally go through it a second time.
This not only slows you down,
it allows learners who are following along to copy what you do,
or to catch up, even when they are looking at their screen while doing it.
If the output of your command or code makes what you just typed disappear from view,
scroll back up so learners can see it again.

*Do not copy-paste code from your lesson script.*
[FIXME: explain why not.]

## Tip 2. Mirror your learner's environment.

Try to create an environment that is as similar as possible to what your learners have to reduce cognitive load.
[FIXME: explain or include reference for "cognitive load".]
You may have personalised your environment with a very simple or rather fancy Unix prompt,
colour schemes for your development environment, keyboard shortcuts, etc.
Your learners usually won't have all of this,
so try to create an environment that mirrors what your learners have.

Similarly, avoid using keyboard shortcuts.
[FIXME: a sentence of explanation.]

Some instructors create a separate 'bare-bone' user (login) account on their laptop
or a separate 'teaching-only' account on the service being taught (e.g., Github).
It could be a benefit if both instructor and learners use the exact same software (termina or IDE),
howevere this may incur som effort to get the software installed on the computers that students use.
Using a cloud-based solution may be an alternative to ensure all involved have the exact same setup.

## Tip 3. Be seen and heard.

If you are physically able to stand up for a couple of hours,
do it while you are teaching.
When you sit down,
you may appear hidden for those sitting in the back rows.
Standing makes the experience more interactive and less monotonous,
and draws the learners' attention away from their screens to you,
which helps getting the point you are making across.

It helps to have a high table/standing desk or lectern.
[FIXME: explain]

Regardless of whether you are standing or sitting,
make sure to move around as much as reasonable.
For example,
you could walk to the screen to point something out or draw something on the whiteboard (see below).

Even though you may have a good voice and know how to use it well,
it may be an advantage to use a microphone,
especially if the room is equipped with one.
Your will tire your voice less,
and you increase the chance of people with hearing difficulties being able to follow the teaching.

## Tip 4. Use the screen(s) wisely.

Use a big font and maximize the window.
A black font on a white background works better than a light font on a dark background.
When the bottom of the projector screen is at the same height or below the heads of the learners,
people in the back won't be able to see the lower parts,
so resize the window(s) you use on your computer (drawing up the bottom) to compensate.

Pay attention to the lighting:
no lights should directly shine on the presenter's screen.

It is even more important than when presenting slides that all learners can see the relevant portions of the screen.
[FIXME: why?]

If you can get a second screen, use it!
It may require its own PC or laptop,
so you may need to ask a helper to control it.
You can use the second screen to show illustrations or the lesson material.

## Tip 5. Avoid being disturbed.

Turn off notifications on your laptop and phone,
such as those from social media, email, etc.
Seeing notifications flash by on the screen distracts you as well as the learners,
and may even result in awkward situations when a message pops up you'd rather not have others see.

## Tip 6. Use illustrations - even better, draw them.

Lesson material often come with illustrations,
and these may help learners to understand the stages of the lesson and to organize the material.
What can work really well is when you as instructor generate the illustrations on the whiteboard as you progress through the material.
This allows you to build up diagrams,
making them increasingly complex in parallel with the material you are teaching.
[FIXME: mention dual coding and the value of presenting complementary information on visual and linguistic channels.]

Diagramming helps learners understand the material,
makes for a more lively workshop (you'll have to move between your computer and the blackboard),
and gathers the learners' attention to you as well.
[FIXME: more detail here?]

## Tip 7. Stick to the lesson material.

Participatory live coding when teaching works best with a well-developed and tested script.
[FIXME: GVW doesn't like the term "script". Worth making the analogy with jazz - there's a score, but you're expected to improvise on top of it?]
It may be tempting to deviate from your material because you would like to show a neat trick
or demonstrate some alternative way of doing something,
but there is always a fair chance you'll run into something unexpected that you then have to explain,
so it is advised not to improvise.
[FIXME: GVW disagrees :-)]

If you really want to use something outside of the material,
try it out thoroughly before teaching it:
run through the lesson as you would during the actual teaching and test the effect of your modification.

Use printouts of the lesson material during teaching,
or alternatively use a second device (tablet or laptop) on which you can view your notes.
[FIXME: mention timers here - when you tell learners they have 5 minutes for an exercise, keep yourself honest.]

[FIXME: create a backlog of "what ifs?" and other questions that you can sort through and think about while learners are doing exercises.]

## Tip 8. Embrace your mistakes.

No matter how well prepared you are, you will make mistakes:
typos are hard to avoid,
you may overlook something from the lesson instructions, etc.
This is not really a problem, and can actually be turned into a teachable moment,
so called "positive error framing" (doi:10.1080/00223980.2012.748581).
Experiencing the instructor making a mistake allows learners to see how to diagnose and correct them.
Some mistakes are actually an opportunity to point something out,
or reflect back on something covered earlier.
Novices are going to spend at least some their time making similar mistakes,
but how to deal with the is left out of most textbooks.
[FIXME: this paragraph has all the right points but the order feels choppy.]

[FIXME: making mistakes gives the learners permission to make and share theirs.]

## Tip 9. Leave no learner behind.

[FIXME: but this isn't really what sticky notes do, since you _may_ still have to leave someone behind.
Maybe "get real-time feedback" would be a better title?]

Give each learner two sticky notes of different colours, e.g., blue and yellow.
[FIXME: except some people are blue-yellow colorblind]
These can be held up for voting, but their real use is as status flags.
If someone has completed an exercise and wants it checked,
they put the yellow sticky note on their laptop;
if they run into a problem and need help,
they put up the blue one.
This is better than having people raise their hands because they can keep working while their flag is raised,
while signalling to any available helpers who to go to.

Also,
the use of sticky notes allows the instructor to quickly see from the front of the room what state the class is in.
Sometimes a blue sticky note involves a technical problem that takes a bit more time to solve.
To prevent this issue slowing down the whole class too much,
use the occasion to take the small break you had planned to take a bit later,
giving yourself or any helpers you may have time to fix the problem.

## Tip 10. Have fun.

[FIXME: GVW would move this advice into the conclusion, and replace it with "Turn learners into co-instructors", then talk about having learners call out lines of code that the instructor types in, pair programming, shared note-taking, etc.]

Teaching is performance art and can be rather serious business.
Don't let this scare you:
it is OK to add an element of play,
i.e.,
to use humor and improvisation to liven up the teaching.
How much you are able and willing to do this is really a matter of personality and taste as well as experience.
It becomes easier when you are more familiar with the material, allowing you to relax more.

Choose your words and actions wisely, though.
Remember that you want the learners to have a welcoming experience and a positive learning environment:
a misplaced joke can ruin this in an instance.
Start small: just saying "that was fun" after something worked well is a good start.

## Sources for these ten quick tips and further reading

These tips were developed in the context of Software Carpentry
and a first edition appeared on [their blog](https://software-carpentry.org/blog/2016/04/tips-tricks-live-coding.html.)
They have become part of the Carpentries [instructor training](https://carpentries.github.io/instructor-training) materials.
These also use example vidoes contrasting [live coding done poorly](https://youtu.be/bXxBeNkKmJE)
and [live coding done well](https://youtu.be/SkPmwe_WjeY).
[*Teaching Tech Together*](https://teachtogether.tech/) has a section on [live coding](https://teachtogether.tech/#s:performance-live).

Thanks to Dr David Martin
(University of Dundee, Scotland)
for suggesting the word 'participatory' to distinguish this form of live coding from other forms.

Potential co-authors/pre-reviewers: Neil Davis, Rayna Harris, Greg Wilson
