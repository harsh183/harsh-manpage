---
layout: post
title: Advice on UIUC BS CS in 3 years
comments: true
external-url:
tag: Advice
toc: true
---

Despite having graduated from UIUC a couple of years ago, I still answer lots of questions about graduating from UIUC CS in 3 years. While it sounds very accelerated, it's totally possible for most people in this degree with the right planning. I also don't think it's the right idea for most people, though there are good reasons to do it. I'll try to address both of these seemingly contradictory ideas in this post, since it's better to make informed choices about your degree path. At a deep level, you have to be clear on what this degree means to you and how it plays into your life goals.

To be clear, I'm not your advisor and not a replacement for one. Please meet with them every single semester with your plan and be upfront about this. A lot of people think advisors aren't friendly to 3-year plans, but they were fantastic and very helpful with mine and helped me reshuffle it so it was more realistic. If you seem uncertain, they'll guide you toward a risk-averse path, which is the right answer for most people, but showing preparedness and determination can get you strong support. That being said, feel free to email/DM me with your plan and I'll try to give feedback.

Note: The info here is based on what is true at the time of writing. The CS requirements will keep changing slowly as the years go by, but the mindset will stay largely the same. Feel free to reach out or make a [pull request](https://github.com/harsh183/harsh-manpage/pulls) if you'd like to update any information.

## Figure Out Your Overall Goal 

While people talk about UIUC in 3 years, it can mean very different things. I highly suggest spending a lot of time reflecting on what matters to you.

### 6 Semesters

This is what most people mean, where it's 6 full priced time Fall & Spring semesters. These will typically happen over 3 calendar years but many people might pad it out with internships, study abroad, and gap semesters.

I suggest this if you're optimizing on
* money spent less on education
* time spent in class
* more room for internships than the 3-5 summers normally available

### 3 Calendar Years with Summer Semesters

Including summer classes can actually get 7-8 ish semesters but still only take 3 calendar years, while having a more spread out workload and time to focus on education like the typical 4 year plan.

This has many of the same advantages of the 6 semester plan, but with more breathing room. I'd suggest this to those optimizing for
* less years spent as a student
* having a gap year or similar

### Consider 7 semesters

While 6 semesters is a little tight, 7 actually gives far more breathing room in the degree plan and it can still save money. Your 7th semester can also be a part-time semester, which is cheaper to do, and this allows a longer college experience, one more summer break/internship, and often a longer break between a job start and the end of college. UIUC will still let you do the May graduation ceremony even if you [graduate in December](https://commencement.illinois.edu/eligibility/). UIUC's typical degree plans also account for 7 semesters to allow for some slack in case of life circumstances, co-op/internships, and study abroad so it feels quite manageable.

Note for OPT: If you graduate in December keep in mind it reduces the lottery attempts from 4 to 3 for the duration of an OPT. It might seem small from afar, but I've seen people _really_ regret this.

## Plan

Start planning early, ideally before your first semester. This needs coordination around proficiency tests, degree requirements, and paperwork. It is still possible to do this later in your degree, but the later you start, the more stressful it gets. Make a worksheet of what every semester will include, with clearly defined classes or class groups, to ensure the whole plan works.

### Understand the CS and Math Main Sequence Really Well

The main thing to keep in mind is making progress on the core CS sequence as quickly as possible. Once you get past 225, it unblocks a lot of chains at once, so getting there early helps a lot. Use your degree page to map out your exact sequence, but for most CS majors the common part looks like this [DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph):

<img src="/assets/images/cs-and-math-uiuc-dag.png">

Note: This image is made using Evan Wallace's [Finite State Machine Designer](https://madebyevan.com/fsm/) that you'll definitely see in many of your UIUC classes.
 
* I'm using double circles to indicate the terminal class in each required sequence
* CS classes are indicated with no number, and I'm using `M` to indicate Math classes
* 'con' stands for concurrent since CS 233 normally required CS 225 unless cross registered with CS 225. I highly suggest both at once.

The longest chain is length 5 in both Math and Computer Science, so ensure that you're making strong progress toward each. This strictly forms the lower bound of how quickly you can graduate. If your goal is 6 semesters, this means you only get a single semester where you're not progressing on the longest chain, and I recommend having that one semester be the last one, but knowing that you have some slack here can be good if a semester gets too rough. Later I'll talk about proficiency tests, which can shorten the [main sequence](https://www.space.com/22437-main-sequence-star.html) and get you to electives quicker.

In the past, prereqs weren't as strictly enforced, so some of the older advice you will get may not apply, but often it's still possible if you ask nicely and acknowledge to advisors, professors, and the department that this might blow up in your face. Usually this is also easier after your first semester since you can point to your strong academic record so far. I had a friend who took CS 233, 374, and 421 at the same time for their third semester, and did CS 225 alongside 126 (precursor to 128) during the second semester. I don't recommend relying on this, but it can certainly help. Having overrides on prereqs worked well for me when I was signing up for grad classes since their enforcement is less strict and professors have far more leeway.  
 
Some of these classes also have math requirements, so keep those moving too. I have seen some first-years take CS 357 and 361, but slot them in when it makes sense for your plan. This also depends on which electives you're more interested in. For example, I wanted exposure to C and systems-level stuff for my electives, so I took CS 357 early since it aligned with my Statistics classes. I wasn't as interested in the programming language side, so I put CS 421 toward my senior year. I had a passing interest in functional programming, but not enough to go much deeper than type inference and `lex`+`yacc`. 

If you're not sure what you want yet, frontload core classes so you keep more optionality and can decide more later.

### Keep the main math sequence in mind

The Math sequence is more linear: MATH 220/221 -> MATH 231 -> MATH 241 -> MATH 415/CS 257 -> CS 357

Quite a lot of people come in with credit for Calc 1 (such as IB) and even credit for Calc 2 (APs, college courses), so they start further along in the sequence. Unless you went to a narrow slice of elite American and international schools, though, you'll usually start around the beginning.  

I suggest first trying to get through the placement/proficiency tests so you can start as far as possible based on your current knowledge. Just like the longest CS chain, you should keep making progress on this in almost every semester. Just like the main CS sequence, make progress on this every semester.

Some of the newer CS + X majors vary in how far you need to go in this sequence, so you might need to keep less of this in mind. However, I personally think every CS major should understand multivariate calc and linear algebra, so I strongly suggest taking them anyway unless it really gets in the way of your graduation plans. I've used concepts from these a lot in later classes, and they've often come up in my work as well. 

### CS College of Engineering - Account For Electives

If you're in CS in the College of Engineering, you'll have 8 electives: 6 have to be within CS, and 2 can be outside. For most people I'd still suggest doing all CS anyway since that's what we attend university for, but go based on your interests and your semester's overall difficulty. As soon as you're able to, generally in your second year, start loading up on electives as they unlock. Assuming you finish CS 225+233 by the end of your third semester, you'll have to take 3 electives for 2 more semesters and 2 electives for one semester. 

Not all electives are equal in difficulty, so definitely keep this in mind as you slot things in.

### CS (+|&) X - Frontload your X Classes

There are quite a few of these majors, so I'm generalizing here, but almost all of them function kind of like a minor and don't require too many electives beyond fulfilling a handful of groups. The X portion of your major likely also has a main sequence that's 4-5 classes long, so you should be moving that along almost every semester too. For example, I was in CS and Statistics, so I was also pushing along my Statistics main sequence, which definitely made the earlier parts of college harder. If you need to, move more of the general education requirements towards the end of the degree.

### CS (+|&) X - Consider CS 233 + CS 341 over CS 340 + Two electives

Not all, but many of these majors offer a choice to opt out of the harder CS 233 (Computer Architecture) and CS 341 (Systems Programming), for taking CS 340 (Introduction to Computer Systems) alongside two 400 level electives. I strongly reccomend everyone do CS 233+CS 341 despite this, and let me address a few common reasons:

* Past GPA trap: The lower GPA averages of [241](https://1010labs.org/gpa?course=CS+241&semester=All) of the last decade have largely disppeared in today's [CS 341](https://1010labs.org/gpa?course=CS+341&semester=All), and CS [233](https://1010labs.org/gpa?course=CS+233&semester=All) has much higher averages than [231](https://1010labs.org/gpa?course=CS+231&semester=All). While there's still a GPA risk of a lower grade in a class with a lot of homework and content, I don't think the risk is very significant provided your schedule has enough room to actually study and understand the material, like _any_ class. 
* Faster Graduation: If you follow the CS 225+CS233 concurrent combo, then CS 341 is only one more semester anyway, so it won't help the 3 year plan by too much. If CS225+CS340 was concurrently possible, it could be an interesting strategy to consider. In terms of saving overall time, having to take an entire additional class to make up for not taking CS 341 is definitely more work, unless the two electives selected are really easy ones. It is possible to do some of the electives before CS 340, but most are unlocked by CS 225 you'll be taking right before anyway. However, it's quite likely that most  will take at least two electives anyway, so then it can represent less academic work to take the CS 340 pathway. 
* Easier Pathway: It is true that CS 340 spends less time on the rigourous parts of CS 233 and CS 341, and if that's your goal this pathway is indeed easier. Personally I think things like understanding basic processor internals, assembly, systems programming, network primitives, latency/throughput tradeoffs and relatively lower level programming is quite a critical part of a great CS education, and they're in the core sequence for the reason. I've found this knowledge to come to use in so many different places in my later classes, professional work, and personal interests. Depending on your own goals and interests, this might still make sense for you so spend some time understanding the differences between material. I'd start with the [2020 document](https://courses.grainger.illinois.edu/cs240/fa2020/static/lectures/cs240-topics.pdf) detailing topic by topic comparisions of the pathway, then looking at a recent syllabus for [CS 340](https://cs340-schatz.com/syllabus), then compare to [CS 341 Syllabus](https://cs341.cs.illinois.edu/syllabus.html) and [CS 233 Learning Goals](https://siebelschool.illinois.edu/academics/courses/cs233). The 340 syllabus page also explains the difference quite well.
> This course has significant overlap with CS 233 and CS 341. CS 233 and CS 341 invest 8 credit hours in going into detail on topics that CS 340 covers in 2 credit hours. Our briefer overview is sufficient for many purposes, but leaves out details needed for hardware-aware application domains such as embedded systems and cybersecurity. The remaining credit hour in 340 explores how to use containers and service architectures to create internet applications.

### General Education Requirements

Graduating in 3 years means making tradeoffs, and this will often be at the expense of the broad liberal arts education that large universities like UIUC are known for. Those classes are genuinely great, and it's hard to get this kind of educational opportunity later in life, but taking high-effort gen ed classes will make 3 years more daunting. There are many UIUC classes that can count toward two or even three requirements, as well as some eight-week online forum-post style classes that are very little work. 

Similar to the earlier sequences, the students who went to the _right schools (tm)_ will have quite a few of these requirements already fulfilled, but it is still quite doable. Proficiency tests still help here for things you do have prior knowledge of. 

Many students have the same idea, and these classes can book out quickly, so don't have too rigid a plan for exactly when you'll finish each requirement, as long as you're moving along on gen eds. As you progress later in your degree, you'll be able to register earlier, and being in the honors program also helps.

In terms of scheduling I suggest pushing this later in your degree because I think it's more important to hit your core degree requirements upfront, especially for CS&X/CS+X, but this can be fairly flexible. If you do have a language requirement I think it's fine to do towards the end because it doesn't really unlock anything too meaningful. 

Personally I enjoyed my higher-effort comp lit classes a lot, and getting to survey new fields like linguistics, disability studies, and horticulture was great. Despite the tight timeline, you can still take many interesting gen eds, but this will always come at a cost and this is tragically a luxury.

### Understand The Relative Difficulty of Classes To Balance A Semester

While planning you should have a solid idea of the rough difficulty of a given semester's schedule because you don't want to accidentally burn yourself out. This is a marathon, not a sprint, and having the right pacing throughout is key. For the ~5-6 real classes you're taking each semester, aim for two hard, three medium, and one easy class. Depending on your planning, you might end up with a semester where you have three hards which you'll have to power through.

Figuring out which class falls into which bucket isn't easy. I like to approach this along these axes:

* how much work a class has: homework, midterms, quizzes, MPs, team projects, readings
* how intellectually challenging a class is
* how do students typically perform
* past background in the class
* how interesting you find the class

For example CS 374 didn't take me much work a week and only had 3 exams, but it was definitely a lot of thinking each week to arrive at optimal solutions, while CS 341 wasn't as challenging but it needed discipline as it was a lot of work each week in terms of homework with very careful debugging. I won't suggest taking both together, but you can balance out your semesters exactly.

What might be easy for you might be hard for others, and you might find yourself getting humbled by a class most students consider quite easy, but generally averages across a large sample hold, so I recommend understanding data. 

#### GPA 

The first piece of data you should understand is the GPA averages for the class:
* [GPA++](https://1010labs.org/gpa) - enter a class, class level or just filter by category (e.g. `CS 4`) to see gpa history by professor - developed by my uiuc roommates
* [waf.cs GPA visualizations](https://waf.cs.illinois.edu/discovery/gpa/) many different great data visualizations - developed in the group led by Professor Wade Fagen-Ulmschneider

As someone who loves education and learning, it feels bad to talk about optimizing classes around GPA. I don't think the point of an education is taking the easiest possible classes to get a piece of paper, but I'm also someone who overplayed my hand in the past and got burned. I think it's possible to keep a shorter graduation timeline in mind while also learning quite a bit effectively.

#### Past Student Reviews

The second piece of data is more subjective, since it's mostly from disgruntled students who can be very unreliable narrators, and it has all sorts of demographic and difficulty bias mixed in. Still, I think it's useful for things like workload or course structure that GPA data can't capture. Usually I'd look on:

* [RateMyProfessors](https://www.ratemyprofessors.com/) - Has basically every American university on it, but the data quality is _really_ bad. 
* [r/uiuc](https://www.reddit.com/r/UIUC/) - and similar subreddits have discussion on various classes and professors. It's a little better than RMP but not a lot better.

Also make sure to filter by class since the same professor can be totally different by class, but trends across classes hold like teaching quality or friendliness. If an instructor is new to UIUC, you can often find online gossip from their previous university too.

UIUC also collects internal teacher evaluations called ICES, with far better completion rates and less bias toward upset students, but these are only accessible within the department. I do wish it were public since it is much better than the places I've linked, and there's a good [r/uiuc discussion about this](https://www.reddit.com/r/UIUC/comments/10i1ng9/why_are_ices_forms_not_public/). It still suffers from a lot of the same biases I mention though.

#### Public Teaching Material

UIUC CS has a great culture of just publishing teaching material on the open internet, which is great for learners outside UIUC, but also students who aren't in the class yet. In breaks before term started, I'd often just watch lectures from a past semester or read their textbooks and slide materials as a broad first pass. Depending on your experience learning the material, it is a great way to get some understanding of how hard a class might be, but I'm putting it lower in my recommendations because it's really hard to judge without having access to the homework and exams. As a side bonus, doing this will often make the classes easier since we learn better with multiple passes.

### Overloaded Semesters Due To Fixed Cost

Unlike many other universities, UIUC is a fixed cost once you cross 12 credits (full-time semester), which means that you should think about sustainably overloading (>18 credits) when possible because there's no extra cost here. I crossed it for many of my semesters for this reason since you're getting more product for the same price. If any of your semesters are part-time, the tradeoffs are really different, but for a 3-year plan you're likely taking full-time semesters. If you have lots of incoming credit as you enter UIUC, you probably won't actually need to overload.

I don't recommend overloading your very first semester since university is already a huge change, and living in a new setting  where everything is different. Advisors will usually try to stop you as well.

### Credit Fillers

Quite a lot of people have a large amount of pre-existing college credit coming into college, to the point of sophomore/junior by credit hours is a running [joke](https://www.reddit.com/r/UIUC/comments/9fclw7/when_a_freshman_tells_you_that_theyre_a_sophomore/). While many of these credits are quite useless in terms of getting to advanced classes earlier, it does save the effort of having to fluff up credit hours to graduate in 3. Not having this means taking 21.33 credits each semester which is quite a lot, and assuming you don't overload the first semester and take 18, this leaves 22 credits overload for every single remaining semester. Actually having that kind of load with a realistic class schedule is going to be too much for most people, so you should strongly consider taking credit hours that require virtually no work just to check this box. 

There are many options here:
* at the start of your degree there might be some orientation/job training classes that take little work. For example, I had optional [LAS 100 - College Success for International Students](https://las.illinois.edu/resources/classes/las100) that gave 2 credit hours and [CS 199 - Course Assistant Training](https://siebelschool.illinois.edu/academics/courses/cs199) for 1 hour. 
* many electives have a 4 credit grad version, and 3 credit undergrad version. The difference in amount of work required isn't too large for _most_ classes, so I suggest doing the grad version in those scenarios. While it's only one extra credit at a time, these do add up. As a side bonus you do learn more and can even double count it for your UIUC Masters. 
* 8 week online-only classes where it's practically just writing short discussion posts. I ended up learning a bit more than I anticipated and some of the readings were great, but these are definitely not at the level of a standard college class.
* trying some activity based easy classes like walking or vegetable gardening. Some can be deceptive though, 1 credit Ice Skating was my hardest class I've ever tried in my life, I regularly went to so many office hours and extra skate sessions and still ended up dropping out because I was so _behind_.
* CS 397/497/499 research credit. This can be a lot of work so your experience may vary, but I found it quite interesting and it didn't really feel like work at all. I did this almost every single semester and nearly hit the departmental maximum. 
* community college classes at places like Parkland which can be far less work, though this will cost extra money

If someone doesn't have a strong starting point in terms of the CS or Math sequence, it makes sense to be hesitant about a three year plan, but I don't think anyone should decide against the three year plan because of the overall credit hour requirement.

### Think about Summer Classes [Optional]




## Proficiency & Placement Tests

The chain length of 5 is the main thing to tackle, and the best way to do that is starting at an earlier point. Many of you will have Math already at the earlier point, but UIUC doesn't recognize high school level AP/IP Computer Science counting for intro so you'll likely have to consider that to begin with, and then see whatever else you can do. Try to start out with MATH 220/221 and CS 124 out of the way so that you have chain length 4 to cover in 3 years which is far more doable.

[proficiency.cs.illinois.edu](https://proficiency.cs.illinois.edu/) is a great website with detailed information on the exams, and you can take the first four core sequence classes: CS 124, CS 173, CS 128, CS 225. 

The Math department lists out their proficiency tests [here](https://math.illinois.edu/academics/undergraduate/proficiencyexaminations) which I suggest reading. Similar to CS, you can go quite far in the core sequence: MATH 220, MATH 231, MATH 241, MATH 257.

Someone being able to do _all_ of these is quite rare, but people can often get surprisingly far. These are free, so I suggest trying them anyway. My suggestion is to target CS 124, CS 173, and one math test from wherever you're starting. Doing more than that is a lot to prep for over the summer. If this is winter, only target one test.

The right time for these tests is usually before your first semester begins, which means summer for most people. It does get in the way of that peaceful break between high school and college, but I didn't really mind it since I had 4 months and was interning at a pretty active startup anyway. There's also some window to do these right before the second semester and before the start of the summer term, but it's not worth thinking about much later since these only cover early-sequence classes.

If you don't prof out of these classes, your first semester will be lighter on major classes, so it's a good time to frontload gen eds and keep the 3-year plan going. 

### CS 124

If you have done high school computer science, or self learned it growing up, this is likely the right test for you. Definitely take a moment to brush up on Java and the basics of object oriented programming. There's a public online version of the class _with the daily homework assignments_ at [learncs.online](https://www.learncs.online/) which you should complete. There's also [CS 199: Even More Practice](https://cs199emp.netlify.app/) that me and a few others wrote with review slides and 3 problems per session you can also do. 

If you find this taking longer than 2 weeks or don't really have any CS experience, I _strongly_ suggest taking the class instead. Having the right CS foundation will pay dividends for the rest of your college life and future career. It will make the 3 year plan harder, so also consider if you really want to do the degree faster since having a better education is worthwhile. 

Personally I did CS 124 anyway, though more out of a feeling of misplaced imposter syndrome, and I loved the class enormously. I went on to be part of its course staff for nearly my entire college life, won an [outstanding course assistant award](https://siebelschool.illinois.edu/about/awards/undergraduate-scholarships-awards/outstanding-course-assistants), made most of my college friends across several years from there and got to spend a lot of time thinking about the near future of CS education.

### CS 173

If you did high school math or self-learned topics like set theory or basic proofs, I suggest the CS 173 proficiency test too. Start by reading Professor Margaret Fleck's amazing textbook [Building Blocks for Theoretical Computer Science](https://mfleck.cs.illinois.edu/building-blocks/index-sp2020.html). It's a wonderful book that I kept going back to years after the class, and it helped me learn so much. It doesn't assume too much background and explains all the core concepts of the class really well, so definitely familiarize yourself with it. After that, look at the [CS173 Official Study Material](https://courses.grainger.illinois.edu/cs173/fa2025/Help-info/study-resources.html), especially the past examlets. 

If you find yourself not sailing through all of it, like I did, just take the class. Personally I was good with about half of the material but lacking on the rest, and I gained a lot from taking the class which helped me do well in CS 374 later and excel in my new grad interviews. 

### Calc Tests

I suggest only doing tests at a level of math you've already learned, but for review, check out [Paul's Online Notes](https://tutorial.math.lamar.edu/) for Calc I+II+III. I used them a lot as a student, and they're very well written. I also liked the videos by [Khan Academy](https://www.khanacademy.org/math/calculus-1), and I think they have many practice problems too. Often when I was stuck, I used [Wolfram Alpha's Solver](https://www.wolframalpha.com/) (made by UIUC CS Professor [Stephen Wolfram](https://math.illinois.edu/directory/profile/wolfram)) to cross-check while practicing.

My own high school credit started me at Calc II so I wasn't too worried about it, but in hindsight I should have been starting in Calc III.

### ALEKS Placement Test

UIUC has students take the [ALEKS PPL Mathematics Assessment Exam](https://math.illinois.edu/academics/undergraduate/ALEKS) when starting out to figure out whether they should start with Calc I or earlier. I didn't prep at all for this since calc was very fresh for me, but I suggest doing a bit of review beforehand. If you don't get placed into Calc I, I highly suggest taking the time to build the right math foundation in your coursework and avoiding calc proficiency tests for now. 

## Understanding UIUC's Cost

The main reason I saw people do a shorter time is cost, and it's very important to understand what your cost will be based on your choice of plan so you can make the right tradeoffs. A guide to fully optimizing your cost at UIUC is beyond the scope of this page and there's a lot written on this online, but I think it's important to understand it broadly as it relates to how your degree plan will go.

### Typical Semesters

* There's a three tier structure for [tuition](https://www.admissions.illinois.edu/invest/tuition), with in state students at the cheapest rate, around double for out of state and slightly higher for international students.
* UIUC has a [fixed tuition cost](https://www.uaps.uillinois.edu/student_programs/guaranteed_tuition) for four years of your degree. This eliminates the biggest source of variance worry about.
* Fall and Spring Semesters don't charge by [credit hour](https://registrar.illinois.edu/tuition-fees/tuition-info/). The best price ratio is still with overloaded semesters, but if you can make your last semester part time, that will also save a lot.
  - 12 >= credits - minimum of full time and no price increase for going beyond.  
  - 6-11.99 credits - 2-3 typical classes
  - 1-5.99 credits - 1-2 classes

### Summer Tuition

While it is per cerdit hour and still followed the three tier structure, the cost is around half of typical tuition, so it can still win if the alternative is extra fall/spring semesters. Most students aiming to reduce costs will live in off-campus apartments, which usually run on yearly leases, so there's no extra marginal housing cost in that case, especially since the supply of summer sublets is much higher than demand. 

With summer you have to remember that most courses are compressed to 8 weeks so it's actually twice as fast. If you want to recharge between semesters, are doing research, are interning somewhere I suggest only taking a single class. If you're fine with the intensity of a normal semester, take two classes. Taking more than that can be challenging so I don't suggest it.

If you just finished living in the dorms, summer sublets can also be really cheap if you look carefully. I did not look carefully, trusted the wrong person, and had multiple break-ins which contributed to a [campus massmail](https://massmail.illinois.edu/massmail/28664.html), which accidently cost thousands in 'rent'.

### Housing And Related Expenses

The other large cost in UIUC is housing, especially with the mandatory overpriced one year requirement that acts as a quasi-tuition that many aid/scholarships don't adequately cover. Urbana and Champaign are relatively affordable places to live with quite a lot of midrise dense housing that's connected to public transit, so after your first year the market rate living you can get will be much cheaper and you'll likely have far more space over the dorms at a fraction of the price.

In the past, I've not seen the university grant exceptions due to financial hardship, medical disabilities, and even people who spent the first year doing remote university were forced into the sophmore year dorms. There are [exceptions](https://studentcode.illinois.edu/article2/part2/2-201) for a few rare cases, but don't count on it. 

First read the pricing pages for the [dorms](https://housing.illinois.edu/cost), even the cheapest quad sharing room cost twice what having my own room in a market rate apartment literally next to campus near the CS building cost. I suggest taking the cheapest meal plan (12+15), and at least a triple since it's barely more expensive than a quad. If you get lucky, there's another UIUC scheme called [Private Certified Housing](https://certified.housing.illinois.edu/pch-resources/rates/) which has some cheaper rates, but these have limited capacity and go out very quickly. Some are religiously affiliated so keep that in mind.

The general tradeoff you need to keep in mind is that almost all market leases will include the summer and winter, so having one less calendar year on campus will literally save quite a bit on campus cost of living.

### Aid And Scholarships

Despite aid/scholarship often not being adequate, most instate and some out of state students qualify for more than they think they realize. Information on these are really scattered but it's really worthwhile to reduce the sticker shock of education. There's a large scattering of these out here, I'm listing a few that I'm aware of, but there are many more that are just very poorly documented.

* [Illinois Commitment](https://www.osfa.illinois.edu/illinois-commitment/) - Families with under $75K in asserts and income (at the time of writing) get 4 years of tuition covered. Note this doesn't guaruntee dorms.
* [Office Of Financial Aid](https://www.osfa.illinois.edu/) - If you can submit FAFSA in time, there's more than many expect. 
* [Illinois Scholarships Main Page](https://www.admissions.illinois.edu/invest/scholarships) - Listing many scholarships at university and college levels
* [UIUC Merit-Based Scholarships](https://www.osfa.illinois.edu/types-of-aid/scholarships/merit-based-scholarships/) - List of many scholarships. The university also automatically considers many people when applying


### Winter Classes

There are also winter classes, but it's a very short break and these typically just get gen eds out of the way, which I don't think is better than doing it in a normal semester, especially with the double/triple and 8-week classes that exist. I honestly liked using winters as a true guilt-free break of doing nothing and spending time with family to recharge for the next year. I also came from a part of the world with very standard daylight duration, so this helped me recover from the seasonal depression a bit.


## During the Degree

Past detailed planning and getting a good starting point through tests, now comes actually following through. How to do your degree well is a huge topic and out of scope for this post, and I'll leave some helpful links at the end. More specific to the three-year plan, every semester make sure to:

* track your degree progress against your overall plan - I did this with Google Sheets, but use whatever tool fits best for you. With every semester, things become more solidified and you can reshuffle as needed as long as you're still good on the overall plan and main sequence. I also kept 3-year and 4-year variants of my plan, and you should plan branches accordingly.
* right before and after you register for classes, run a [DARS Audit](https://registrar.illinois.edu/academic-records/dars-audit/) to ensure your academic plan is actually working
* go to your advisor every single semester with your plan and audit so far and the classes for the remaining semesters to get their thoughts
* do well in your classes, learn, and have fun!


## Caveats

There are some important caveats of following the 3 year plan you should keep in mind. Besides my points below, also read these:

* [a great r/uiuc thread](https://www.reddit.com/r/UIUC/comments/17g87he/benefits_and_detriments_of_graduating_in_335_years/)
* [Angela Zhang's reflection on finishing MIT CS in 3 years](https://qr.ae/pFsQdX) 
* The Daily Pennsylvanian's [Why some Penn students decide to graduate in three years](https://www.thedp.com/article/2017/03/graduating-in-three-years-from-penn)

### Opportunity Costs

Many students arrive at college with a scarcity mindset when it comes to interesting things to do, since school was often a far more limited environment compared to the sheer abundance of what's available in terms of classes, clubs, research. 3 years is still perfectly doable while having a lot of fun side questing, but keep in mind you'll get to do a lot less than most of your peers who are spending 4 years. While there's an abundance of opportunity, your true scarcity is having a shorter timeframe and you should take extra care in what you take on. 

If you start taking on too much, the opportunity cost can be your three-year plan. I actually ended up in that situation: I wanted to do lots of fun extra classes, do research and teaching almost every semester, have a really busy social life, and go deeper into an area of study that has excited me almost all my life, so I abandoned my plan toward the end of my second year. Part of my motivation was also COVID-19 taking away the in-person campus experience I enjoyed so much, so ironically I ended up spending 3 years on campus anyway.

### Less Internship Time 

Besides being fantastic learning opportunities, internships are also a prime hiring pipeline through return offers. Graduating early can mean less chances of return offers, though keep in mind internships before your final year don't give full time return offers and just return for another internship. So you can actually have the same amount of internships that are eligible for full time return offers. Due to increased flexibility from having an accelerated timespan, I saw many friends do a fall/spring co-op internship during your final year to vastly increase their odds for full-time return offers.

### Shorter Rose Colored College Campus Life

Besides just the educational and career 

<!-- shorter student life -->

## Reasons

Only do this plan if you have a good reason. College is designed around the 4-year cycle for a reason and the minimum degree requirements are intentionally light. If you can get the full college experience, I highly recommend it, but circumstances really vary and privilege absolutely applies. Having a good motivation driving you here will be key to being successful. Here are my thoughts on common reasons I've heard:

## Bad Reasons

I think almost all reasons to graduate early are valid, but here are a few I'd caution against:

### Peer group 

If your main motivation is seeing your friends do it and wanting to do it too, I'd suggest against that, since their circumstances might not match yours and it might be driven by pointless competitiveness. As time goes on, a lot of that peer group might end up doing 7 or 8 semesters, which is far more doable, and then you took on extra stress for nothing. It is nice to take classes in sync with your peer group, so I suggest doing that and piling on extra things once they wrap up. Many people who did three ended up living on campus for a fourth year as well, so many friends might still be around.

### Personal Challenge

I am always in support of people taking on a harder pathway to grow, but I'd suggest that a 4 year plan with more challenging classes, research, internships, and teaching is a far better personal challenge to grow. You can follow pretty much all of the above advice and just use the extra breathing room to go further in your interests. It's really hard to get this kind of environment after undergrad.

## Good Reasons

I think the primary reason to think about this is cost, but I saw many other good reasons too:

### Sticker Price

Despite being a state university, UIUC isn't cheap, especially if you're out of state and international.

If you are fortunate enough to afford the full four years I highly recommend it, I was extremely fortunate to be able to and that is what enabled me to take four years in college. Doing so much HCI research, taking several grad level classes, having a very broad general education, near daily social plans, getting to be part of teaching almost every semester and summer, going on endless sidequests and meeting my long term life partner happened because I had the luxury to fill it out. These were the best years of my life till that point, and I am so sentimental about my time at UIUC. 

I think it's wild that tax funded universities with [free land](https://www.admissions.illinois.edu/discover/history) in a dedicated college town that doesn't even pay the staff that well can still cost so much. Unfortunately, that is the reality of today and college debt is a burden that can really drag, even in a field with very high salaries like Computer Science.

### Industry Opportunity Cost

Related to the idea of a price tag, the financial opportunity cost of an entire year of working is an expense people should acknowledge as the cost of getting the full degree experience. For many people who are doing a three-year plan, their new-grad salaries can be $150k-$250k and I've seen a few offers like $500k. I don't know if these kinds of offers will last long term, but at present there is a sizable sum of money that people are walking away from. In a long career of 40-50 years and compounded growth, it might not amount to a large portion of overall net worth, but it is a _lot_ of money nevertheless. This one year's pay can become a large part of adequate retirement savings depending on the circumstances of retirement.

### Doing A Combined Masters  

I knew many people who did a 3+1 BS+MS program, which let them graduate at the same time as their typical cohort, have the same number of internships, and walk out with a nicer degree. While most CS-related jobs no longer have a _huge_ boost for doing a master's like in the past, it's still a sizable bump in few cases, and not having to take a career break for one is really nice. Access to classes is quite similar to undergrad, but getting a whole extra degree for taking a full schedule of 4 years of CS classes is nice. As many CS degrees don't have an explicit 3+1 program, you can just apply for a master's to start right after. Generally most good students will get in through home-field bias and internal connections.

This can actually work out cheaper than a normal 4-year degree too, because grad-school teaching and research positions often come with tuition waivers and stipends, while the undergrad equivalents barely hit minimum wage and don't offer as many hours. Many people I know got to experience 4 years at UIUC more cheaply because of this, though it'd be nice if undergrads were given the same level of waivers like some [universities do](https://eecsdsstaff.org/know-your-rights/fee-remission/).

Note for OPT: keep in mind doing a combined program for 4 years will skip the 3 years of undergrad OPT (1 year normal + 2 years STEM), which means less time in industry and lottery attempts if that is your goal. If you're targeting academia this is fine, but just keep this caveat in mind.

### Starting Grad School Earlier 

As an undergrad, UIUC enables you to get a grad student-like experience with teaching, research, grants, publishing and upper div classes, but why not just become a graduate student earlier if you're really sure about your path. Being a grad student explicitly makes it easier, and having an extra year to focus on research can really produce better outcomes for many students. I still recommend spending the full time in undergrad to explore if being a grad student is the right move and not getting locked into the wrong research area, but getting there a year earlier can be nice. If you also intended to do a PhD at UIUC, this can be quite streamlined since you can double dip the initial breadth requirements from undergrad too.

### Study Abroad

Studying in a different country is an extremely worthwhile experience and it really forces you to grow in all sorts of great ways. It's also just fascinating seeing how different cultures approach the same topics, even a relatively standardized field like Computer Science. Having fewer semesters at UIUC means you could do an 8 or even 12 month study abroad if you wanted. A funny side effect is that you can even save money doing this because universities in other developed countries are much cheaper than American ones. For most people, this is a great chance in life to just spend a few months living in another country that won't naturally come up again in life. 

I didn't do this personally because my entire UIUC experience was already _studying abroad_, but I knew international students who used it to try even more countries.

### Industry Internships

While doing part-time semester internships and full-time 3-5 summer internships in a normal 4-year/8-semester plan is already quite a lot of room for internships, doing this can let you do even more. Especially towards the end of a degree. Typically there's a lot of burden on the summer after junior year's internship to net a return offer, but having a spring or fall co-op/full-time internship right before graduation can increase the odds of a full-time return offer quite drastically. Interning is also just a fantastic learning experience: mentorship, sampling different industries, relatively lower stakes for career mistakes, trying different tech stacks. This can also help on the money front, I knew someone who covered the gap between scholarships and tuition with savings from numerous internships.

Also keep in mind that UIUC's [Research Park](https://researchpark.illinois.edu/), Champaign county tech offices, and Chicago [City Scholars](https://cityscholars.grainger.illinois.edu/) can let you intern around while taking proper semesters too, though it can be a little tough to balance both so I suggest lighter loads. 

### Not Liking University or Wanting to Spend Less Time Here

Some people don't like life in academia. Others miss family that's often in a different city, state, or country, don't find the right social crowd, or simply want to get their education and resume life back home. Whatever someone's reason, I think it's valid, even though I'd love it if everyone wanted to spend a long time at UIUC and experience what I did. Time is a very precious resource, and if less time at UIUC aligns with your goals, I think that is absolutely worth it.

## Links 

These are largely out of scope for this page, but I think they're also worth checking out:

* My guide on [Staying Productive](/productive) - a lot of different strategies you should A/B test on to be highly effective
* [Drshika Asher](https://www.drshika.com/)'s [UIUC Mental Health Sources Links Collection](https://uiuc-mh-resources.netlify.app/)
* Drshika and I also wrote a SWE interview [prep guide](https://tinyurl.com/cs-interview-prep) which is about prepping for DS&A style algorithms effectively while using time well from when we were CS 225 CAs
* [How to Be a Study Ninja](https://www.grahamallcott.com/books/study-ninja) by Graham Allcott is one of the rare self-help advice books on doing really well as a student that I suggest. Most of this field has very vague advice that doesn't work, but this book is really actionable and chances are you're already doing some of it
* Drshika, [Monika Para](https://www.linkedin.com/in/monicapara/), and I also ran a summer series of follow along workshops focused on a fun and friendly start to side projects called [Summer of Side Projects](https://sosp22.com/). Go through these tutorials and then use it as a fun launching point to quickly explore your interests and build up a nice portfolio.
* [Testing 101](https://sosp22.com/testing101) is a small guide I wrote on the red-green-refactor mindset on having clear failing tests, working in small increments till each piece works, and then using that as a way to prevent regressions while building more code on top. The topic of programming productivity is a really complex one, but the main trend I noticed among successful students as a course assistant was the ones who worked in small increments, tested those increments, and debugged very quickly because there was only a small portion of unconfirmed code in most cases. Doing a 3 year plan does mean learning to work effectively and I think this is a good starter point.

Good luck!

Thanks to Monika Para, Drshika Asher, Divvyam Arora, and Davis Keene for taking an early look at this post.
