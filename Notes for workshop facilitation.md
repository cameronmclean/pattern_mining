Notes for workshop facilitation
===============================

It is important for both facilitator and participants to be clear about
what we are trying to achieve.


>We want to create a shared vocabulary to talk about and annotate lab protocols
>in a way that is intuitive, and supports the task of experimental design and 
>solving problems at the bench.

The workshop is all about thinking of the _design_ of lab procedures, the ways 
we do things, and the reasons for the ways we do things in a successful 
experiment.

>Our tools to support science typically neglect the process in which physical
>experiments are actually designed. An experiment has specific goals, and also
>constraints (time, cost, manpower...), and requires access to specific 
>resources. The ability to design an experiment that optimally addresses all
>these concerns is critical part of scientific problem solving. 
>
>Normally we design experiments informally, and specify them in lab books or 
>loose notes. We need capabilities to assist scientists in identifying 
>resources, specifying, maintaining, and sharing experimental design. The 
>capability to navigate and manage the process would be great.

######Chin, G., Schuchardt, K., Myers, J., & Gracio, D. (2000). Participatory workflow analysis: Unveiling scientific research processes with scientists.

Think about how you search for a cooking recipe or a lab protocol. We typcially
search through a range of procedues, and see how they vary. What variations or 
ratios change between versions? What makes one recipe seem better than another?
Which parts most appy to you, and what do you need or are tyring to achieve?...
This is one examle of the kind of work we aim to support.

We might (will!) have different experiences about what is important for a given 
protocol. This is good. The point of patterns is to start with experience and
work towards more objective, testable, and deeper truths.

The notes here are complimentary and _additional_ to the brief instructions on 
the slides.

##The Presentation (Workshop Guidance)

Note upfront we intend to share the info collected under a CC-BY license.

Introduction to design patterns is kept relatively short - one shouldn't need 
to become a pattern expert before we dive into extracting expert knowledge and
the salient features of a lab scenario. 

We have the precious time of practitioners in the room - they don't need a long
seminar on the life, works, and influence of Christopher Alexander.

We briefly show a motivating example of how we can specify the 'forces' 
operating in a live imaging experiment, and how annotation of a method 
description can be useful for searching or deeper understanding.

The workshop is designed to step through various activities without too much
preamble, and hopefully at the end we will have arrived at enough raw material
from which we can build a proto-pattern. Emphasising the "forces" and 
uncovering recurring design rationale and constraints that matter in practice 
is the main objective. These will later form a pragmatic vocabulary we can use 
to annotate other protocols.

Some of the activities ask similar questions - it is OK to repeat responses. 

Also, many tasks have a drawing bit - its fun - no matter your drawing ability!

##I think I know less than I thought

Note also, that the tasks may well be challenging. There is no tension or
need to worry if in front of our collegues we realise we don't know something 
that we feel we ought to, or if we turn out to be misled about something.
The 'illusion of knowledge' is a well documented phenomena - unless challenged
our conceptual and explanatory understanding of even familar things or 
processes is sketchy and shallow at best. This is a permissive environment, and
our aim is to uncover where such deeper knowledge can be useful, expose it, and
make it sharable. 

_Note:_ It might be useful to segregate groups or workshops into similar levels
of experience / hierarchy to prevent some folks from being afraid to speak up 
amongst their peers. The Focud Group reference below has good suggestions.

######Lawson, R. (2006). The science of cycology: failures to understand how everyday objects work. Memory & Cognition, 34(8), 1667–1675. 

###Abstraction
Merely abstracting and generalising a protocol is not necessarily a pattern.
But it helps.
Abstraction helps us focus on the critical feature(s) of entities in the
context. We then ask 'why this?' generalisation makes the concepts transferable.

Some people really struggle with making abstractions. That's cool. 
We don't expect every person or group to fly through and make a pattern at the
end. It very much depends on the protocol selected, background knowledge,
individuals cognitive styles, caffination levels etc.. Encourage those who 
seem to be struggling or disheartened to act as an audience or reader so others
can test or improve the clarity of their explanations.


###Protocol Pictionary
This exercise is ~5-10mins
Encourage abstract thinking, have fun.
#####Get folks to put their twitter handles on their forms for easy attribution.
Allow a few mins at the end - 
Help break the ice by having participants explain to their group what their 
picture is, the essence of what their protocol does....

At this point, it may be obvious that some protocols are too large.
If so - 
For the next sections, have the participants choose a subprotocol - 
a potentially reusable chunk that they are familiar with.
eg. antibody selection for the task, rather than (animal>Ab>section>histology>
analysis>....)


###Analysis and Shared Experience
This exercise is ~15 solo, then a few more minutes collective thinking.
Here we aim to get at the _context_, think about the general type of 
problem the protocol is an answer to. We start with critical reflection
from those most familiar with the procedure. We aim to articulate at a 
higher level, the functional purpose of the protocol, and the context
around it. In discussion with other group members, who may also have 
experience, we can collect tips and tricks, and scenarios where this 
type of protocol can be used.   


###Abstracting the 'whats' and 'whys'
Forces (why's) can be anything - social, technical, economic, physical...
We want to enumerate all the 'forces' in the protocol. Some forces will 
repeatedly occur. Some 'forces' may be present, but not end up being part of 
the final pattern - of all the variables, only some will form the important 
subsystem. By using existing protocols, we are starting with positive examples.
It is also possible to find forces by starting with negative examples and ask
why it didn't work (what forces were not resolved). This is powerful, but it is
harder to find negative examples in the literature. 

For drawing icons, some concepts are nearly impossible. Google images for ideas
or nounproject for CC licensed pictograms is a good source for inspiration.
We don't want to spend too long on the pictograms though - time is limited,
and elucidating the concepts is more important. 

Note - for some of the steps the 'what' and 'why' might be extremely obvious - 
cool, just write a bullet point and move on. :-) 


####Defining the problem
This gets us closer to the true forces. The problem defines the field of 
forces. The problem definition sets up the pattern format, helps us think
about the context, which forces are important, and how the force are resolved.

Thinking about the general problem that our protocol solves gets us to a more
abstract, reusable set of concepts.


###Graphing the forces
The idea here is to try and express the general problem that the protocol 
solves as a network of forces, diagrammatically. From the previous exercise
there are likely important variables that interact - e.g. the need to 
completely immobilise a live sample for imaging but also keep it alive and 
happy.

We want to try and sketch out here all the 'forces' involved in the procedure
and show which ones interact.

Our protocol solves a problem, the 'forces' are the things that shape the 
problem _and_ its solution. They are the things we have to address.

As with the previous section, nounproject and google images can be used to
inspire quick icon sketches. 

Precisely defining how all the forces can interact can be difficult.
Sometimes its a maximally connected graph.
The connections don't have to be perfect for our purposes, just try and 
approximate. 


###Pattern Template
Woo Hoo! Were nearly done. Next it remains to try and consolidate all the info
we have just extracted into a pattern like format. Patterns are more shareable,
critique-able, human friendly to read. 

We need to spend some to justify and explain the rationale and supporting info
for the important elements - to show that our pattern is recurring, general and
"real". The rationale is also critical to help others understand 'why', to 
apply the pattern themselves, and provide scientific evidence from the 
literature so we can justify the pattern concepts and test them.


###Done!
Enough for one day. It's all quite demanding on the brain - folks are probably
exhausted. Next we need to collate and add the collected info the website.
And design pictograms, etc. Still lots to do, but we should now have plenty of
raw material and knowledge dumps to further shape, and craft into potential
patterns. 

Ensure to follow up with participants if they indicate the are keen. It's nice 
to know their efforts are valued, being built on, and helpful. Ideally they can
contribute and refine things further if they are so motivated. 


###References, other info...
Focus Groups: A Practical Guide for Applied Research by Richard A Krueger and 
Mary Anne Casey is essential reading for those wanting to host workshops.
https://www.worldcat.org/title/focus-groups-a-practical-guide-for-applied-research/oclc/758250697?referer=di&ht=edition

