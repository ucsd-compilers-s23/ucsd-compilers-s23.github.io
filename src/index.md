![doodle](./doodle.jpg)

# UCSD CSE131/231 Syllabus and Logistics

- [Joe Gibbs Politz](https://jpolitz.github.io) (Instructor)
- Mark Barbone (tutor)
- Shubham Bhargava (tutor)
- Nico Lehmann (TA, 🦀)
- Rachel Lim (TA)
- Abhishek Sharma (TA)
- Ruochen Wang (TA)

[Basics](#basics) -
[Schedule](#schedule) -
[Staff &amp; Resources](#staff--resources) -
[Grading](#course-components-and-grading) -
[Policies](#policies)

In this course, we'll explore the implementation of **compilers**: programs that
transform source programs into other useful, executable forms. This will
include understanding syntax and its structure, checking for and representing
errors in programs, writing programs that generate code, and the interaction
of generated code with a runtime system.

We will explore these topics interactively in lecure, you will implement
an increasingly sophisticated series of compilers throughout the course to
learn how different language features are compiled, and you will think
through design challenges based on what you learn from implementation.

This web page serves as the main source of announcements and resources for the
course, as well as the syllabus.

## Basics

- Lecture: [Catalyst 0125](https://map.concept3d.com/?id=1005#!m/576554), 12:00-12:50pm (noon) Mon/Wed/Fri
- Discussion Section: [SOLIS 107](https://blink.ucsd.edu/sponsor/advancement/advancement-services/stewardship/named-buildings/solis-hall.html), 4:00-4:50pm Friday
- Tests **(in Friday Discussion Section)**: May 5 (Week 5), June 2 (Week 9)
- Final Exam (used for making up test credit): Wed June 14, 11:30-2:30, Location TBD

- Podcasts: [podcast.ucsd.edu](https://podcast.ucsd.edu/watch/sp23/cse131cse231_a00)
- Q&A Forum: [EdStem](https://edstem.org/us/courses/38748)
- Gradescope: [https://www.gradescope.com](https://www.gradescope.com)
- Textbook/readings: There's no official textbook, but we will link to
  different online resources for you to read to supplement lecture. Versions
  of this course have been taught at several universities, so sometimes I'll
  link to those instructors' materials as well. Some useful resources are:
  - [The Rust Book](https://doc.rust-lang.org/book/) (also [with embedded quizzes](https://rust-book.cs.brown.edu/))
  - [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf)
  - [UMich EECS483](https://maxsnew.com/teaching/eecs-483-fa22/)
  - [Northeastern CS4410](https://courses.ccs.neu.edu/cs4410/)

## Schedule

The schedule below outlines topics, due dates, and links to assignments. The
schedule of lecture topics might change slightly, but I post a general plan so
you can know roughly where we are headed.

The typical due dates are that **assignments** are due on Tuesday evenings and
**quizzes** are due Friday evenings.

### Week 9:
- Handouts:
  - “Monday ” Handout: [(pdf)](https://drive.google.com/open?id=1-wfiOdPL6smtwGfWd_GltUGiYF6Y3fd3&usp=drive_fs)
  - “Monday” Video: [(mov)](https://drive.google.com/file/d/106pTiFcJ0A_VPaG_3iumd39mJ8O-d01k/view)
  - Wed Handout: [(pdf)](https://drive.google.com/open?id=11sbplhXa97v0wHPvRwP5la-Y_YZLbij2&usp=drive_fs)
  - Friday Handout [(pdf)](https://drive.google.com/file/d/11z-7MhvdjffI8MgrOZV3oF09DTE4vNy0/view?usp=drivesdk)



### Week 8:
- Handouts:
  - Monday Handout: [(pdf)](https://drive.google.com/file/d/11Oa5JhCGMl_tbjzrP9h4eE-0H4e_GbK7/view?usp=share_link)  [(pptx)](https://docs.google.com/presentation/d/11DVMTLinA85y3fbHmaEcJPpPKoUS5DiP/edit?usp=share_link&ouid=105656546547059517622&rtpof=true&sd=true) [(filled)](https://drive.google.com/file/d/1FbsqmPwXNsa3Pka1gyR4Cdsr1vLtK3kf/view?usp=share_link)
  - Wednesday Handout: [(pdf)](https://drive.google.com/file/d/11nf4wQWzyfFSybv1icX_52vN7zFMWaLd/view?usp=share_link)  [(pptx)](https://docs.google.com/presentation/d/11fmzGibK9k8U-8_AV-6iLMkxIW2pmDF-/edit?usp=share_link&ouid=105656546547059517622&rtpof=true&sd=true)
  - Friday Handout: [(pdf)](https://drive.google.com/open?id=11pYhD3rIdOPQ4O1AEuAhZE8VuCn5Dohm&usp=drive_fs)
- Reading and Resources
  - [Implementation of ANF](https://github.com/ucsd-compilers-s23/lecture1/blob/flatten/src/main.rs#L50)
  - [Might on ANF](https://matt.might.net/articles/a-normalization/)
  - [Lerner on ANF](https://courses.ccs.neu.edu/cs4410/lec_anf_notes.html)
  - [Jhala on ANF](https://ucsd-cse131.github.io/sp21/lectures/04-boa.html)
  - [Politz on ANF (I forgot that I had written this)](https://www.cs.swarthmore.edu/~jpolitz/cs75/s16/n_anf-tutorial.html)
  - [Pfenning on Liveness](https://www.cs.cmu.edu/~fp/courses/15411-f08/lectures/04-liveness.pdf)

### Week 7:
- Handouts:
  - Monday Handout: [(pdf)](https://drive.google.com/open?id=10prpN9EVhU1BPfpgDDsZjEpy-p6mauj4&authuser=jpolitz%40ucsd.edu&usp=drive_fs)  [(pptx)](https://docs.google.com/presentation/d/10eVuV8gXYLNpFAs61vjdCuaZ45tiSyx3/edit?usp=share_link&ouid=105656546547059517622&rtpof=true&sd=true) [(filled)](https://drive.google.com/file/d/1mWfC5H6v_0MbO23Oc2Cee6B8fz-_V2Fv/view?usp=share_link)
  - Wednesday Handout: [(pdf)](https://drive.google.com/file/d/10rWE3fzStKvzD_wpKMlyrZ45ZkQiwLCP/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/10qdRRHrAWrLQQ_DfSMLgTcVw1nMr9ae6/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true) [(notes)](https://drive.google.com/file/d/1llafRhpA8FTCZZngm_9G3qaUALr90Mgv/view?usp=share_link) 
  - Friday Handout: [(pdf)](https://drive.google.com/file/d/119qdwLq6YHhKOzQzjcKP1c-B-PZ4reV7/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/10s-0oBxichZzxEYI6ihbal_TMsjIIY-C/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true) [(filled)](https://drive.google.com/file/d/1jhJDa8xQ7s9M3NJGhHLdL9IG_c2CXzRL/view?usp=share_link)
- Reading and Resources
  - [Wilson on GC](./week67/gcsurvey.pdf)

### Week 6
- Handouts:
  - Monday Handout: [(pdf)](https://drive.google.com/file/d/10N6pBYMXlmNcj44ZG0lfE7R2TUu76Rtk/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/10CQguVrO_CsM5tRdB-s6P1uG8k4j_lhD/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true) [(filled)](https://drive.google.com/file/d/1WtEB0rxFsUcKT38s3VQBsY_XMs7wpUeR/view?usp=share_link)
  - Wednesday Handout: [(pdf)](https://drive.google.com/open?id=10Oi5eDSom0ooIZh6544saNasxVrEbFaX&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(pptx)](https://docs.google.com/presentation/d/1-jBhVNii45-dd0HwwTh_AZueaecoYlGE/edit?usp=share_link&ouid=105656546547059517622&rtpof=true&sd=true)
  - Friday Handout: [(pdf)](https://drive.google.com/open?id=10cELq6XOarsRYQcnNBSnHl-72FoARbZc&authuser=jpolitz%40ucsd.edu&usp=drive_fs)[(pptx)](https://docs.google.com/presentation/d/10c2RfDK5E8qLacnqZ9np0JhpVU5vHhiI/edit?usp=share_link&ouid=105656546547059517622&rtpof=true&sd=true) [(filled)](https://drive.google.com/file/d/1Fir7zmXnfBWDUKhxTLS4WnjAAFWatXgc/view?usp=share_link)
- Reading and Resources
  - [Pairs Implementation](https://github.com/ucsd-compilers-s23/lecture1/tree/egg-eater)
  - [New/Lerner on Pairs and Tuples](https://maxsnew.com/teaching/eecs-483-fa21/lec_tuples_notes.html)
  - [New/Lerner on Mutable Tuples](https://maxsnew.com/teaching/eecs-483-fa21/lec_mutable-tuples_notes.html)
  - [New/Lerner on Garbage](https://maxsnew.com/teaching/eecs-483-fa21/gc.pdf)


### Week 5
- Handouts:
  - Monday Handout: [(pdf)](https://drive.google.com/file/d/1-jEMoSArvCf0LdIb14Q7Gb_0iOmgig3p/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-fw8ySJnoNvdiCy6xVJik2KoZIM9qyAd/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true) [(filled)](https://drive.google.com/file/d/17wgnP5RIvzZjyC_ONaLLYy88-EejGyKk/view?usp=share_link) 
  - Wednesday Handout: [(pdf)](https://drive.google.com/file/d/1-sW0TLc02EqjLKmoZD-tsZp4rQ1CynjH/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-qBKC14vKPwmOHN7sJ9aU9EnxnWdXVa4/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true)
  - Friday Handout: [(pdf)](https://drive.google.com/file/d/102m4bDEZEIDMXrjMAJvLkbGgJ7WF03bz/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-vFIGpVCc2rYWjK_104rJVRw6VUgZ_1E/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true)

### Week 4 - Functions and Calling Conventions

- [Assignment (due Wednesday, May 3, 10pm)](./week4/index.md)
- Handouts and recordings:
  - Monday Handout: [(pdf)](https://drive.google.com/file/d/1-5hSur3hmEAciOPWTaTOkk-Oa52zNzKL/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-5a4jzUUbO_mUY6GJ_iVR1tMyOkcMzTz/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true)
  - Wednesday Handout: [(pdf)](https://drive.google.com/file/d/1-WP0sx7mJNHwSFFa9UVWPIDiJN1v_7Qr/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-djfbJ3JJ5ijQP7DOWkUvBAm27NOCDnz/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true)
  - Friday Handout: [(pdf)](https://drive.google.com/file/d/1-cPkeTcqGrrEIVQf1_gO1vAdsDQ_E4gY/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-X_KaWnFNFgw5Vth-coIFGA6TERJmhB8/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true) [(filled)](https://drive.google.com/open?id=1-iF3jpc4RwkmOoczuRquXVRGsiDJYZXt&authuser=jpolitz%40ucsd.edu&usp=drive_fs)
  - [Monday Recordings](https://drive.google.com/drive/u/0/folders/1HkhKGG2XGbjWUJV2xozTOh-qBkHuYBoF)
  - Calling Conventions:
    - [Using Negative RSP offsets](https://github.com/ucsd-compilers-s23/lecture1/tree/diamondback)
    - [Subtracting depth(e) from RSP](https://github.com/ucsd-compilers-s23/lecture1/tree/stack_alloc_first)
- Reading and Resources:
  - [José Manuel Calderón Trilla on Tail Calls](https://twitter.com/josecalderon/status/1247983114875527171?s=20)
  - [Tail Calls the Musical](https://www.youtube.com/watch?v=-PX0BV9hGZY)
  - [Lerner/New on Errors](https://maxsnew.com/teaching/eecs-483-fa21/lec_function-calls_notes.html)
  - [Lerner/New on Defining Functions](https://maxsnew.com/teaching/eecs-483-fa21/lec_function-defs_notes.html)
  - [Lerner on Tail Calls](https://course.ccs.neu.edu/cs4410sp20/lec_tail-calls_stack_notes.html)

### Week 3 - Tags, Conditionals, and Loops

- [Assignment (due Tuesday, April 25)](./week3/index.md)
- Handouts:
  - Monday Handout: [(pdf)](https://drive.google.com/open?id=1-6vUpvSapNiC2KsKigUnU2bKi_YFAQ7c&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(pptx)](https://docs.google.com/presentation/d/1-93ApFcsJpvs8cZI_0160pfjjVEmWj_8?rtpof=true&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(code)](https://github.com/ucsd-compilers-s23/lecture1/tree/cobra)
  - Wednesday Handout [(pdf)](https://drive.google.com/open?id=1-SCUezmScSj-c17rCKmK-4wYqTn1tLdU&authuser=jpolitz%40ucsd.edu&usp=drive_fs)
  - Friday Handout [(pdf)](https://drive.google.com/file/d/1-UfeA9oHc-8o8jDrjNLVBhoajhDhtPBO/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1-1EH6n5o6niyLlGOcEO0EV8pKeF8vIIH/edit?usp=share_link&ouid=108036649104448650609&rtpof=true&sd=true)  [(code including print)](https://github.com/ucsd-compilers-s23/lecture1/tree/cobra) [(code including targets)](https://github.com/ucsd-compilers-s23/lecture1/tree/contexts)
- Reading and Resources:
  - [Max New on Conditionals](https://maxsnew.com/teaching/eecs-483-fa21/lec_if_notes.html)
  - [Mark Barbone on x86_64 calling convention](https://markis.cool/posts/2023-04-17-sysv-abi.html)
  - [Wikipedia on x86_64 calling convention](https://en.wikipedia.org/wiki/X86_calling_conventions#System_V_AMD64_ABI)

### Week 2 - Binary Operators, Booleans, and Conditionals

- [Assignment (due Tuesday, April 18, 10pm)](./week2/index.md)
- Handouts:
  - Monday Handout: [(pdf)](https://drive.google.com/file/d/15xYXbx9VVfXv9-xuKqH8lcMLKt8gP4cu/view?usp=share_link)
    [(pptx)](https://docs.google.com/presentation/d/1i3Mf3UVZoHmXJy3RhHpa4WMgt_M-MD38/edit?usp=share_link&ouid=117453768726816085396&rtpof=true&sd=true)
  - Wednesday Handout: [(pdf)](https://drive.google.com/open?id=1pyn-5AhrBKH4nE4V4g3VWKDD-HM9J3R5&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(pptx)](https://docs.google.com/presentation/d/14c0AVN8LQH3_JH6YswtJbjWYlPJTS9UC?rtpof=true&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(code)](https://github.com/ucsd-compilers-s23/lecture1/tree/lecture3)
  - Friday Handout: [(pdf)](https://drive.google.com/open?id=1--oHIGna7kRj0w7yYmtHYsX7Iprjhvj1&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(pptx)](https://docs.google.com/presentation/d/1--VHG_NpiO_CF6OUlksf-G3a4EJ9yNnp?rtpof=true&authuser=jpolitz%40ucsd.edu&usp=drive_fs) [(filled)](https://drive.google.com/open?id=1-1p5EQoMrJ4iLgXgsHaXLOUOnbuSP-TX&authuser=jpolitz%40ucsd.edu&usp=drive_fs)
- Reading and resources:
  - [Memory Representation of Values in Ocaml](https://dev.realworldocaml.org/runtime-memory-layout.html)
    _More discussion of a language with tagged value representations (and Ocaml
    is type-checked!)._
  - [V8 Blog Post Including Number Representations](https://v8.dev/blog/pointer-compression)
    _This goes a little further than we are right now, but focus on the fact
    that V8, one of the widely deployed JS engines, uses tag bits for
    its numbers._
  - [Max New on Let and the Stack](https://maxsnew.com/teaching/eecs-483-fa21/lec_let-and-stack_notes.html)
    _Max New and Ben Lerner have done a nice job writing up notes on some of
    my original scrawlings around this material. They don't use exactly the
    same style or make the same decisions I do in this class, but things are
    close enough to be useful._

### Week 1 - Rust and Source to Assembly Conversion

- [Assignment (due Tuesday, April 11, 10pm)](./week1/index.md)
- Reading and resources:
  - Friday Handout: [(pdf)](https://drive.google.com/file/d/1eYTybBS3QNRYkhIbsEnPCHXGACMqEJ5p/view?usp=share_link) [(pptx)](https://docs.google.com/presentation/d/1gGeC4Wp68sHLZLR6YbPAAdJk3NevdYcM/edit?usp=share_link&ouid=117453768726816085396&rtpof=true&sd=true)
  - Wednesday Handout: [(pdf)](https://drive.google.com/file/d/1WgOu07dQTGT9NXzGqnDUHDprMRq5btRn/view?usp=sharing) [(pptx)](https://docs.google.com/presentation/d/1QO22FXOAui0fT_2zbixQh6cwFzWEz2pi-2RRU4EuLBI/edit?usp=share_link) [(code)](https://github.com/ucsd-compilers-s23/lecture1)
  - [Monday Handout](https://drive.google.com/file/d/1AOZ-MRYc1DYdbBlz6xkMrETaeCfHujZI/view?usp=share_link)
  - [Rust Book Chapters 1-6](https://doc.rust-lang.org/book)
  - [x86-64 quick reference (Stanford)](https://web.stanford.edu/class/archive/cs/cs107/cs107.1196/guide/x86-64.html)
  - [x86-64 quick reference (Brown)](https://cs.brown.edu/courses/cs033/docs/guides/x64_cheatsheet.pdf)

## Staff & Resources

Office hours are concentrated on Friday, Monday, and Tuesday, since most
assignments are due Tuesday evening. Please check the calendar before you come
in case there have been any changes. When you come to the office hour, we may
ask you to put your name in the queue using the whiteboard. Read the
description about [collaboration below](#policies) for some context about
office hours. The office hours schedule is below; each event has details about
remote/in-person:

<iframe src="https://calendar.google.com/calendar/embed?src=c_c1586a0a6e6455fce678e079b70229d7a08fa87ff273967e084fdb60683da37f%40group.calendar.google.com&ctz=America%2FLos_Angeles" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

## Course Components and Grading

Your grade will be calculated from **engagement**, **assignments**, and **tests**.

**Assignments** are given periodically, typically at one or two week intervals.
On each you'll get a score from 0-3 (Incomplete/No Pass, Low Pass, Pass, High Pass).

There are two **tests** in the course, one in week 5 and one in week 9, given
in the Friday discussion sections. Tests also get a score from 0-3. Finals week
and the usual final exam block will give an opportunity to make up credit on
these if you miss them or get low scores.

**Engagement** has two components – class participation and weekly (p)review
quizzes. Most lectures will come with a 1-2 page handout, and you can submit
the handout any time up until the start of the next lecture. Credit is given
for reasonable effort in engaging with the notes from the day on the handout.
Quizzes will release each week around Wednesday, and be due Sunday evening.
These serve as a review of the past week and a preview of the coming week.

The standards for grade levels are:

- **A**:
  - Exam point total 5 or higher (High Pass on one exam and Pass or better on the other) (including final make-up)
  - **One of**:
    - High Pass on half the assignments, Pass on others, no missing assignments
    - High Pass on 4 of 5 assignments from A4 (Caduceus) and later (planned
      8 total assignments, actual total TBD), any grade on the other
      assignmentst. (If we end up with less than 8, I'll update this)

- **B**:
  - Exam point total 4 or higher (one High Pass and one Low Pass, or two Passes) (including final make-up)
  - **One of**:
    - Pass or above on all assignments, up to one missing assignment
    - High pass on two assignments from A1-4, High pass on two
      assignments from A5-8, any grade on others
- **C**
  - Exam point total 3 or higher (including final make-up)
  - Pass or above on half the assignments, any score on the others

You get credit for a quiz by getting most of the questions right.
**Engagement** is used to add +/- modifiers at the end of the quarter, and
won't make the difference between A/B/C etc.

**Comprehensive Exam**: For graduate students using this course for a
comprehensive exam requirement, you must get "A" achievement on the exams. Note
that you can use the final exam make-up time to do this!


## Policies

### Programming

In your professional programming life, some of your work will be highly
collaborative with lots of expert advice available from senior developers and
from sites like StackOverflow. This is a common case in many Web-focused
companies, in academia, and on open-source projects. It’s a great way to get
exposed to new techniques, share knowledge, and generally enjoy teamwork. In
contrast, some of your work will involve figuring out programming problems on
your own, where you are the first person to encounter an issue, or the first
person to try using a new library in the context of your application. You
should get experience in both types of situations; we might call the former
kind of process **open to collaboration** and the latter **closed to
collaboration**.

In terms of courses, this split also makes sense. Programming assignments
serve (at least) two roles. First and foremost, they are a mechanism for you
to learn! By directly applying the techniques and skills we discuss in class,
you get practice and become a better programmer. Second, they are an
assessment mechanism – as instructional staff we use them to evaluate your
understanding of concepts as demonstrated by your programs. Open
collaboration can reduce frustration while learning and give you chances to
enjoy collaboration and lots of help, but may not let us accurately evaluate
your understanding. Closed assignments are an opportunity for you to
demonstrate what you know by way of programming (and some of the frustration
of working through a problem on your own is _healthy_ frustration).

There are two types of assignments in this course:

- **Open collaboration** assignments, for which you can talk to anyone else in
  the course, post snippets of code online, get lots of help from TAs, and
  generally come up with solutions collaboratively. TAs will be happy to look
  at your code and suggest fixes, along with explaining them. There are a few
  restrictions:
  - Any code that you didn't write must be cited in the README file that goes
    along with your submission
    - **Example:** On an open collaboration assignment, you and another student
      chat online about the solution, you figure out a particular helper method
      together. Your README should say “The FOO function was developed in
      collaboration with Firstname Lastname”
    - **Example:** On an open collaboration assignment, a student posts the
      compilation strategy they used to handle a type of expression you were
      struggling with. Your README should say “I used the code from the forum
      post at [link]”
  - Anyone you work with in-person must be noted in your README
    - **Example:** You and another student sit next to each other in the lab,
      and point out mistakes and errors to one another as you work through the
      assignment. As a result, your solutions are substantially similar.  Your
      README should say “I collaborated with Firstname Lastname to develop my
      solution.”
  - You cannot share publicly your entire repository of code or paste an entire
    solution into a message board. Keep snippets to reasonable, descriptive
    chunks of code; think a dozen lines or so to get the point across.
  - You still _cannot_ use whole solutions that you find online (though
    copy-paste from Stack Overflow, tutorials etc, if you need help with Rust
    patterns, etc.) You shouldn't get assistance or code from students outside
    of this offering of the class. All the code that is handed in should be
    developed by you or someone in the class.
  - If you can get ChatGPT, Copilot, or another LLM to generate code that works
    for the course, feel free, but you **must** put comments in your code
    describing the prompt you used to get it if you do. If you have Copilot on,
    put a comment if it generates an entire method or match case.

  This doesn’t mean the staff will be handing out answers. We’ll mostly
  respond with leading questions and advice, and you shouldn’t expect a
  direct answer to questions like “am I done?” or “is my code right?”

  There is no guarantee the assistance you get from your classmates is
  correct. It is your responsibility to use your judgment to avoid using an
  idea on the course message board that is wrong, or doesn’t work with your
  solution; we won’t necessarily tell you one way or another while the
  assignment is out.

  If we see that you used code from other students and didn’t cite it in
  the README, the penalty will range from a point deduction to an academic
  integrity violation, depending on the severity. Always cite your work!

- **Closed collaboration** assignments, where you cannot collaborate with others.
  You can ask clarification questions as private posts or of TAs.
  However, TAs will not look at your code or comment on it. Lab/office hours
  these weeks are for conceptual questions or for questions about past
  assignments only, no code assistance. On these assignments:
  - You cannot look at or use anyone else's code for the assignment
  - You cannot discuss the assignment with other students
  - You cannot post publicly about the assignment on the course message
    board (or on social media or other forums). Of course, you can still
    post questions about material from lecture or past assignments!
  - All of the examples in the open collaboration section above would be
    academic integrity violations on a closed collaboration assignment
    **except** for using tutorials/LLMs. If you use code from tutorials/Stack
    Overflow/LLMs, cite them as described above.

You can always use code from class or shared by the instructional team
(properly attributed).

Programming assignments will explicitly list whether they are open or closed
collaboration.

You should be familiar with [the UCSD
guidelines](http://senate.ucsd.edu/Operating-Procedures/Senate-Manual/Appendices/2)
on academic integrity as well.

### Late Work

Late work is generally not accepted, because often we'll release partial or
full solutions immediately following the deadline for an assignment.
Opportunities for making up missed credit are given in other ways, and will be
described throughout the quarter.

### Regrades

Mistakes occur in grading. Once grades are posted for an assignment, we will
allow a short period for you to request a fix (announced along with grade
release). If you don't make a request in the given period, the grade you were
initially given is final.

### Exams

There will be two tests during the quarter (held in discussion section) and a
final exam. There are no make-up tests for the tests during the quarter.
However, the final exam will have sections that correspond to each of the
in-class tests, and if your score on that part of the final is higher than
your score on that in-class test, the exam score replaces it. This includes
the case where you miss an in-class test (scoring a 0), but can regain credit
from that part of the final exam. This policy is designed to encourage you to
treat the in-class tests as _learning opportunities_ so that you can study
any mistakes you make and re-apply that knowledge on the final.

In addition, if you score high enough on the tests during the quarter, you can
skip the final exam with no penalty and just have the test grades applied as
your exam score.

You are not allowed any study aids on exams, aside from those pertaining to
university-approved accommodations. References will be provided along with
exams to avoid unnecessary memorization.

You cannot discuss the content of exams with others in the course until grades
have been released for that exam.

Some past exams are available at the link below for reference on format
(content changes from offering to offering so this may not be
representative):

<https://drive.google.com/drive/folders/1yPxZ-nqRpC9Gz63JIavhQgfnyhA0uGIs?usp=sharing>

### Laptop/Device Policy in Lecture

There are lots of great reasons to have a laptop, tablet, or phone open
during class. You might be taking notes, getting a photo of an important
moment on the board, trying out a program that we're developing together, and
so on. The main issue with screens and technology in the classroom isn't your
own distraction (which is your responsibility to manage), it's the
distraction of **other students**. Anyone sitting behind you cannot help but
have your screen in their field of view. Having distracting content on your
screen can really harm their learning experience.

With this in mind, the device policy for the course is that if you have a
screen open, you either:

- Have only content onscreen that's directly related to the current lecture.
- Have unrelated content open and **sit in one of the back two rows of the
room** to mitigate the effects on other students. I may remind you of this
policy if I notice you not following it in class. Note that I really don't
mind if you want to sit in the back and try to multi-task in various ways
while participating in lecture (I may not recommend it, but it's your time!)

### Diversity and Inclusion

We are committed to fostering a learning environment for this course that
supports a diversity of thoughts, perspectives and experiences, and respects
your identities (including race, ethnicity, heritage, gender, sex, class,
sexuality, religion, ability, age, educational background, etc.).  Our goal is
to create a diverse and inclusive learning environment where all students feel
comfortable and can thrive.

Our instructional staff will make a concerted effort to be welcoming and
inclusive to the wide diversity of students in this course.  If there is a way
we can make you feel more included please let one of the course staff know,
either in person, via email/discussion board, or even in a note under the door.
Our learning about diverse perspectives and identities is an ongoing process,
and we welcome your perspectives and input.

We also expect that you, as a student in this course, will honor and respect
your classmates, abiding by the UCSD Principles of Community
(<https://ucsd.edu/about/principles.html>).  Please understand that others’
backgrounds, perspectives and experiences may be different than your own, and
help us to build an environment where everyone is respected and feels
comfortable.

If you experience any sort of harassment or discrimination, please contact the
instructor as soon as possible. If you prefer to speak with someone outside
of the course, please contact the Office of Prevention of Harassment and
Discrimination: <https://ophd.ucsd.edu/>.
