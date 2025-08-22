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
- **Office:** Alden 106

### Office Hours

Given the relatively small population of our course, appointments will not be
necessary; i.e., **all office hours are walk-in only**. That means first come,
first serve.

| Day | Time          |
| :-- | ------------: |
| Wed | 5p - 6p       |
| Fri | 6p - 8p       |

### A Note on Contacting the Instructor

Unfortunately, I have obligations outside of Allegheny College (namely, a day
job with local aerospace manufacturer Acutec) that generally makes regular
communication during normal business hours difficult, if not sometimes
impossible. That having been said, I will make all efforts to reply to attempts
to communicate with me within a timely manner: generally within one 24-hour
period, excluding weekends and holidays (work-life balance is important for
*all* of us).

Additionally, it's worth noting that between class sessions, lab, and my office
hours, there is ample opportunity for us to see each other in-person on a daily
basis should you so desire! (Again, excluding the aforementioned weekends and
holidays; absence makes the heart grow fonder, after all.) I suspect this will
make face-to-face conversation the preferred method of communicating with one
another.

If my suspicion proves incorrect and you'd really rather just write me outside
of the times we see each other, my *preferred* mode of asynchronous
correspondence is Discord; here "preferred" means the mode in which you're most
likely to get the swiftest response.

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
time management to use those working weeks wisely to complete the requirements
associated with the culminating project.

Release week itself will take place during exam week. During our scheduled final
exam period you can expect a demo and presentation, as well as one final
(lengthier) **performance review** with the instructor.

### Course Calendar

| Week Starting            | Type      | Theme                    | Reading    |
| ------------------------ | --------- | ------------------------ | ---------- |
| 8/26 (no lab)            | Commit    | Orientation              | Chapter 1  |
| 9/1 (no lab)             | Commit    | Parts of a Language      | Chapter 2  |
| 9/8                      | Commit    | Enter Lox                | Chapter 3  |
| 9/15                     | Build     | Language Zoo             | N/A        |
| 9/22                     | Commit    | Scanning                 | Chapter 4  |
| 9/29                     | Commit    | Grammars                 | Chapter 5  |
| 10/6 (no TH class)       | Commit    | Parsing                  | Chapter 6  |
| 10/13                    | Build     | Mission Im-parse-ible    | N/A        |
| 10/20                    | Commit    | Expressions              | Chapter 7  |
| 10/27                    | Commit    | Statements               | Chapter 8  |
| 11/3 (no TU class)       | Commit    | Control Flow             | Chapter 9  |
| 11/10                    | Build     | Locking in Lox           | N/A        |
| 11/17                    | Commit    | Functions                | Chapter 10 |
| 11/24 (no TH class)      | Working   | N/A                      | N/A        |
| 12/1                     | Working   | N/A                      | N/A        |
| 12/8 (exam @ TU, 9am)    | Release   | N/A                      | N/A        |

## Grading: Assessing Your Learning

First and foremost, the purpose of our time together is to *learn*. We'll best
learn together by keeping up with course expectations and (of course) sharing
what we've discovered with one another. The grading strategies employed in this
class are built around those ideas.

There are exactly 100 points up for grabs over the course of the semester.
You'll begin with 0, and each week will have a finite number of opportunities to
pump that score up. Your score at the end of the semester will determine the
letter grade you receive.

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
  will submit via GitHub to me. These prompts always require a minimum of 200
  words to be considered complete, and your responses here will sometimes form
  the basis for performance review sessions in build/release weeks. The deadline
  for reflection entries is always **11:59pm on Saturday** in the week that it
  is assigned.

- **Mapmaking Task**: in support of the first learning objective for the course
  (correctly identify and describe the steps in the design and implementation of
  a programming language) you will be making a visual map of a programming
  language and its many parts using the free tool
  [excalidraw](https://excalidraw.com/). Each week will see you add on to this
  running visual representation of what we're learning in class. Weekly
  additions to the map are due **11:59pm on Saturday** in the week that it is
  assigned. Like with personal reflection entries, these mapmaking tasks will
  sometimes form the basis for performance review sessions in build/release
  weeks.

### Build Week Points

Each of the 3 build weeks will have 10 points up for grabs, split between a
project demo, a brief presentation, and an individual performance review.

- **Project demo and presentation**: 5 points will be tied to specific tasks
  involving the project demo and presentation. These tasks will vary from
  project to project. All team members will receive the same number of points
  from these tasks.

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

My job is to facilitate your learning, and that's most effective when we're all
learning *together*. Put another way: if you're on page five while the rest of
the book club is on page five-hundred, then you're not going to get much out of
book club, and book club isn't going to get much out of *you*.

This being the case, once a deadline has passed, there will be no opportunity to
reclaim any missed points...with three exceptions to be used at your discretion,
that is. (I recognize that life happens, and these three exceptions are in
recognition of that simple truth.)

In keeping with department tradition, CMPSC 201 offers students three tokens
that can be cashed in to make up work for three missed deadlines.

Four guidelines apply to the cashing in of any tokens this semester:

1. They cannot be applied to missed performance review sessions, or any
deliverables pertaining to release week.

2. If you're applying tokens to team-based assignments, then *all* team members
must fork over one token each.

3. Tokens must be applied (and the relevant work submitted) within two weeks of
the original deadline. Once this two week period has elapsed, tokens can no
longer be applied to that assignment.

4. In addition to missed assignments, tokens can be used to resubmit assignments
in an attempt to receive a higher score: namely, for build week presentations &
demos (given that these are team projects though, they will require all team
members to spend one token each).

There may (or may not) be opportunities to earn extra tokens this semester. That
will be for all of us to discover together.

## Our Environment: Regarding Community & Accommodations

### Allegheny Statement of Community

> Allegheny students and employees are committed to creating an inclusive,
> respectful and safe residential learning community that will actively confront
> and challenge racism, sexism, heterosexism, religious bigotry, and other forms
> of harassment and discrimination. We encourage individual growth by promoting
> a free exchange of ideas in a setting that values diversity, trust and
> equality. So that the right of all to participate in a shared learning
> experience is upheld, Allegheny affirms its commitment to the principles of
> freedom of speech and inquiry, while at the same time fostering responsibility
> and accountability in the exercise of these freedoms.

It's worth noting that we will together create and enforce team-based codes of
conduct that will endeavor to uphold these college values. Failure to abide by
these codes of conduct (and the college's statement of community) will result
in grade penalties via performance review scores.

### Academic Accommodations

> Students with disabilities who believe they may need accommodations in this
> class are encouraged to contact Student Accessibility and Support Services
> (SASS) at (814) 332-2898.  Student Accessibility and Support Services is
> located in Pelletier Library.  Please do this as soon as possible to ensure
> that such accommodations are implemented in a timely fashion. Please see here
> for more details.

Beyond college-sponsored academic accomodations, if you ever feel that you need
an extra helping hand to manage course workload, please get with me ASAP. My
goal is to (say it with me now) ensure that we all learn *together*; achieving
this requires that none of us get left behind.

## Buyer Beware: A Note on AI

AI tools such as Copilot and ChatGPT are fairly ubiquitous these days, and they
have immense potential and utility in a variety of disciplines and industries.
I believe that part of responsibly preparing all of you for life beyond
Allegheny includes preparing you for the ways in which such AI tools can be a
boon, as well as a hindrance.

I encourage all of you to thoughtfully deliberate over which deliverables would
be conducive to AI assistance, and which would not. Knowing that the ultimate
goal of our time here is to (once more, with feeling) *learn together*, I think
you'll find you'll get the most out of this class by honestly grappling with
assignments as a human first, and then tagging in your AI tools of choice to
polish, refine, and elevate your contributions.

A word of warning: regardless of the extent to which you rely on AI tools to
complete deliverables, the one-on-one performance review sessions that will take
place during the semester will see you in an environment sans AI where you
must successfully communicate what you've learned in the course, and make up
a significant percentage of the available points this semester.
