# CMPSC 201: Programming Languages (Fall 2025)

## Boilerplate: Description, Distributions, & Outcomes

### Course Description

The course description, per the academic bulletin, is as follows:

> A study of the fundamental concepts that arise in different programming
language paradigms. Students learn how programming languages are designed and
implemented, and how these factors affect the overall usability, performance,
and effectiveness of computer software. Participating in hands-on activities
that often require teamwork, students gain experience in leveraging the styles
and features of programming languages to implement and evaluate correct and
efficient computer software. During a weekly laboratory session, students use
state-of-the-art technology to complete projects, reporting on their results
through both written documents and oral presentations. Students are invited to
use their own departmentally approved laptop in this course; a limited number of
laptops are available for use during class and lab sessions.

### Distribution Requirements

This course fulfills two distribution requirements: **Quantitative Reasoning**
**(QR)** and **Scientific Process and Knowledge (SP)**. Again, per the academic bulletin:

> **Quantitative Reasoning** is the ability to understand, investigate,
communicate, and contextualize numerical, symbolic, and graphical information
towards the exploration of natural, physical, behavioral, or social phenomena.

> Courses involving **Scientific Process and Knowledge** aim to convey an
understanding of what is known or can be known about the natural world; apply
scientific reasoning towards the analysis and synthesis of scientific
information; and create scientifically literate citizens who can engage
productively in problem solving.

### Course Learning Outcomes

Students who successfully complete this course should expect to be able to:

1. Correctly identify and describe the steps in the design and implementation of
   a programming language.

2. Effectively use programming language constructs to design correct, efficient,
   and well-tested programs in multiple programming languages, including but not
   limited to Java.

3. Interpret and use an existing programming language grammar.

4. Design, implement, and evaluate a correct scanner and parser for a
   programming language.

5. Using knowledge of the general principles of programming languages, correctly
   implement a computer program in a heretofore unknown programming language.

## Your Instructor: Jeff Normile

### Contact

- **Email:** jnormile@allegheny.edu
- **Phone:** (814) 332-2883
- **Office:** Alden 105

### Office Hours

Given the relatively small population of our course, appointments will not be
necessary; i.e., **all office hours are walk-in only**. That means first come,
first serve.

| Day | Time          |
| :-- | ------------: |
| Wed | 4:30p - 5:30p |
| Fri | 6:30p - 8:30p |

### A Note on Contacting the Instructor

Unfortunately, I have obligations outside of Allegheny College (namely, a day
job with local aerospace manufacturer Acutec) that generally makes regular
communication during normal business hours difficult, if not sometimes
impossible. That having been said, I will make all efforts to reply to attempts
to communicate with me within a timely manner: generally within one 24-hour
period, excluding weekends and holidays (work-life balance is important for
*all* of us, after all).

Additionally, it's worth noting that between class sessions, lab, and my office
hours, there is ample opportunity for us to see each other in-person on a daily
basis should you so desire! (Again, excluding weekends; absence makes the heart
grow fonder, after all.) I suspect this will make face-to-face conversation the
preferred method of communicating with one another.

If my suspicion proves incorrect and you'd really rather just write me outside
of the times we see each other, my preferred mode of asynchronous correspondence
is Discord; here "preferred" means the mode in which you're most likely to get
the swiftest response.

## Textbook: *Crafting Interpreters*

No textbook purchases are required for this course. Rather, this course utilizes
content from the first ten chapters of Robert Nystrom's
[*Crafting Interpreters*](https://craftinginterpreters.com/contents.html), which
is available for free in a webbook format.

## Course Structure: Our Blueprint for Learning

Allow me to set expectations upfront: you will receive very few lectures from me
over the course of this semester. Instead, much of our time will be centered
around learning by *doing*. What that doing actually entails will of course vary
from week to week, but each week's activities will almost always follow one of
three formats: commit weeks, build weeks, and a release week.

### Commit weeks

Commit weeks are so named because they, like a `git commit`, represent small,
incremental steps on our shared learning journey that we will progressively
iterate and build upon. The objective here is to *commit* to completing a series
of small tasks that aim to help you *commit* key learnings to memory. (One
thing you'll quickly learn about me is that I like to *commit* to a bit.)

Put plainly, these weeks will consist of bite-sized deliverables centered around
a specific topic or theme for the week. You can generally expect an assigned
reading from the course textbook, group discussions (both in-class and via
Discord), small individual and team deliverables, and an expectation to engage
in some personal introspection via reflection entries. 

### Build weeks

A build week is all about doing just that: *build*ing something. If commit weeks
are about learning new ideas, then build weeks are about demonstrating that
learning. (Which, pedagogically speaking, helps to reinforce that learning as
well. Neat!)

Build weeks will see you working with teammates to complete a one-week project 
aiming to demonstrate your achievements with one (or more) of the course's
specific learning objectives. You can expect to share a brief (5-10 minute) demo
and presentation of what you've accomplished with the class. Additionally, these
weeks will be used to conduct one-on-one **performance reviews**, which will be
elaborated on later in this document.

### Release week (& working weeks)

When building software, it generally takes a series of commits to put a build
together, and it often takes several iterations of builds to come up with a
release that one is proud to, well, *release*. This is the final stop on our
learning journey, and if we're diligent this semester it should prove to be a
worthwhile one.

You'll work with teammates to put together a sizable project that demonstrates
your mastery of course learning objectives. The big release week will be
preceded by a few working weeks, where no new tasks will be assigned by the
instructor; however, you'll need to take ownership of your own (and your team's)
time management to use those "free" weeks wisely to complete the requirements
associated with the culminating project.

Release week itself will take place during exam week. During our scheduled final
exam period you can expect a demo and presentation, as well as one final
(lengthier) **performance review** with the instructor.

## Grading: Assessing Your Learning

First and foremost, the purpose of our time together is to *learn*. We'll best
learn together by keeping up with course expectations and (of course) sharing
what we've discovered with one another. The grading strategies employed in this
class are built around those ideas.

There are exactly 100 points up for grabs over the course of the semester.
You'll begin with exactly 0, and each week will have a finite number of 
opportunities to pump that score up. Your score at the end of the semester will
determine the letter grade you receive.

### Letter Grade Conversion Chart

| Score | Grade |
| :---- | :---: |
| 93+   | A     |
| 90+   | A-    |
| 87+   | B+    |
| 83+   | B     |
| 80+   | B-    |
| 77+   | C+    |
| 73+   | C     |
| 70+   | C-    |
| 67+   | D+    |
| 63+   | D     |

### Point Breakdown

The 100 possible points from this course are derived from the following sources:

| Week Type | # of Occurrences | Points per Occurrence | Total Points |
| :-------- | :--------------- | :-------------------- | :----------- |
| Commit    | 10               | 5                     | 50           |
| Build     | 3                | 10                    | 30           |
| Release   | 1                | 20                    | 20           |

### Commit Week Points

Each commit week has 5 points up for grabs, one each for the following
activities:

- **Attendance**: once during each commit week I will take attendance on a
  random day. Attend class/lab and the point is yours. Miss and you forfeit it.

- **Discord Discussion**: I will share a discussion prompt in the class Discord
  channel at the start of the week. By **Wednesday, at 11:59pm** you are
  required to respond to the prompt with a *novel contribution* (meaning your
  post must share an insight not already shared by a peer). Respond with a novel
  contribution by the deadline to receive a point. Miss and you forfeit it.

- **Individual Deliverable**: each commit week will include one deliverable that
  you are solely responsible for. The deadline for this deliverable may vary by
  week, but will be communicated by the start of the week in which it is due.
  Almost every deliverable will involve demonstrating a working program on your
  device to the instructor. Succeed in this task and the point is yours. Miss
  and you forfeit it.

- **Team Deliverable**: each commit week will also include one deliverable that
  your assigned team will produce together. As with individual deliverables,
  the deadline for this may change from week to week, but will always be
  communicated by the start of the week in which it is due. Team deliverables
  will also often include demonstrating a working program on one or more of your
  teammate's devices. Importantly, **all teammates will either receive or**
  **forfeit this point together**. Nobody left behind!

- **Reflection Entry**: each week I will assign one reflection prompt that you
  will submit via GitHub to me. These prompts always require a minimum of 250
  words to be considered complete, and your responses here will sometimes form
  the basis for performance review sessions in build/release weeks. The deadline
  for reflection entries is always **11:59pm on Friday** in the week that it is
  assigned.

### Build Week Points

Each of the 3 build weeks will have 10 points up for grabs, split between a
project demo, a brief presentation, and an individual performance review.

- **Project demo and presentation**: 5 points will be tied to specific tasks
  involving the project demo and presentation. These tasks will vary from
  project to project.

- **Performance review**: during build weeks, I will meet with each of you
  individually during team working time to conduct one-on-one performance
  reviews. The content of these reviews will be revealed closer to review time,
  but you can generally expect a brief (5 minute) discussion with myself
  where I ask you to sincerely evaluate your contributions in class, and orally
  test your mastery of course learning objectives.

### Release Week Points

The culminating project for the semester, there are a total of 20 points tied
to release week, which will take place during the final exam period.

The 20 points available from release week come from the following sources:

- **Project demo and presentation**: your team will demonstrate your final
  product to the class for 15 possible points based on meeting certain project
  and presentation requirements.

- **Final performance review**: the final 5 points of the semester will come
  from one final one-on-one review session with the instructor. Again, expect
  me to ask you to honestly evaluate your own performance, and orally test your
  mastery of course learning objectives.

## Tokens: The Second Chance System

I get it, life happens. Sometimes you might miss a deadline. While you should
generally make every effort to *avoid* this outcome, occasionally it's
inevitable. I want to recognize this fact of life, but at the same time if I do
away with penalties for missed deadlines altogether, it becomes very difficult
to facilitate our learning *together*: if you're on page five while the rest of
the book club is on page five-hundred, then you're not going to get much out of
book club, and book club isn't going to get much out of *you*.

This being the case, once a deadline has passed, there will be no opportunity to
reclaim any missed points...with three exceptions at your discretion, that is.
In keeping with department tradition, CMPSC 201 offers students three tokens
that can be cashed in to make up work for three missed deadlines. These *cannot*
be applied to any deliverables pertaining to release week, or the one-on-one
performance review sessions with the instructor. All else (including demos and
presentations for build weeks) is fair game, with one caveat: if it's a team
assignment you're attempting to make up, then *all* team members must fork over
one token each.

There may (or may not) be opportunities to earn extra tokens this semester. That
will be for all of us to discover together.

## Course Calendar: The Road Ahead

| Week Starting            | Type      | Theme                    | Reading    |
| ------------------------ | --------- | ------------------------ | ---------- |
| 8/26 (no lab)            | Commit    | Orientation              | Chapter 1  |
| 9/1 (no lab)             | Commit    | Parts of a Language      | Chapter 2  |
| 9/8                      | Commit    | Enter Lox                | Chapter 3  |
| 9/15                     | Build     | Language Zoo             | N/A        |
| 9/22                     | Commit    | You Can Scan, Man        | Chapter 4  |
| 9/29                     | Commit    | Getting Grammatical      | Chapter 5  |
| 10/6 (no TH class)       | Commit    | Unambiguity              | Chapter 6  |
| 10/13                    | Build     | Mission Im-parse-ible    | N/A        |
| 10/20                    | Commit    | The Value of Evaluation  | Chapter 7  |
| 10/27                    | Commit    | State of the State       | Chapter 8  |
| 11/3 (no TU class)       | Commit    | Flow Machines            | Chapter 9  |
| 11/10                    | Build     | Locking in Lox           | N/A        |
| 11/17                    | Commit    | Locking up Lox           | Chapter 10 |
| 11/24 (no TH class)      | Working   | N/A                      | N/A        |
| 12/1                     | Working   | N/A                      | N/A        |
| 12/8 (meeting TU @ 9am)  | Release   | N/A                      | N/A        |
