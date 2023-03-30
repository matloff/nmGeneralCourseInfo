
# How Things Work in Norm Matloff's Classes

## Sorry for the Length

Yes, this document is absurdly long. But it contains information
concerning almost any question you might have on course policy and
procedure, and thus is vital material.

For example, when you are about to finish Homework I, this document will
tell you how to submit it, how it will be graded, and whether you are
allowed to submit it late--very important information.

If unforeseen conditions arise, some of this material may change.



# Communication with Me by E-Mail

You are welcome and encouraged to send me e-mail. You'll find that I
generally respond quickly. Please keep these points in mind:

-   Please include the course number in the Subject line, e.g.
    'ECS 132'.

-   Please do NOT send me screenshots unless it's really necessary. I
    often check mail from low-bandwidth connections, which makes
    receiving images a problem. So if, say, you are going to send me
    code, then send me the code, not a picture of the code! If you need
    to some me code + error message, use the Unix 'script' commend.

# Lecture Format

My lecture style is very nontraditional.

* The textbook evolved originally from my course notes, so this is what
    I discuss in class.  So, you can focus on what I'm saying about the
    concepts, rather being distracted by taking notes.

    In a class with no textbook but having a required set of readings, I
    will lecture out of those readings.

* Does that mean you need not go to class?  No, class attendance is vital 
    to doing well in the course.  During lecture I elaborate on what is 
    in the book/readings.  **Note that many of these
    elaborations will show up later on the quizzes.**


* I seldom write on the blackboard (or on my projected screen).
    Instead, I talk about what's in the textbook. I typically will ask
    you to open to a certain page, and then will call your attention to
    various sentences, examples and pictures on that page. The lectures will
    consist mainly of discussion and amplification of the examples in the
    textbook, with additional explanation. **It is intended that you read
    the given pages in a lecture after the lecture, not before;** the
    lecture guides you in what to expect, e.g. points that you must pay
    special attention to.

* Since "the notes have already been taken for you" (in the form
    of the book), **you will take rather few notes.**  Your time in lecture
    should be spent **listening carefully to the lecture--and even more 
    carefully to answers thtat I give to student questions during 
    lecture**--and only take notes on points that arise that are not 
    in the book.

# Quizzes

### Frequency

A Quiz will be given almost every week in discussion section. Quizzes
will not be announced; assume that there will be one each week.

Note for ECS 132: In numeric problems, exact answers are required, not
simulation, unless the latter is specified.

**All the old quizzes, with solutions, are available on our class Web
page.** It would be quite advantageous to you if you were to look
through them, to see what kinds of questions are asked.

### Why quizzes?

I give weekly quizzes in lieu of midterm and final exams.  It's a lot of
work for me, composing and grading a quiz every week, but
But I do this for two reasons:

-   It's a natural way to ensure that you don't fall behind, which is a
    serious problem for universities using the quarter system.

-   It's much better for the student, with far less pressure. Giving a
    midterm and a final is quite stressful to the students, as they
    count so much in a course grade. Giving Quizzes instead relieves
    that stress.

-   It's also better for your grade. In a final exam, you could be
    misgraded and never know it.

### Each student must have his/her own course materials

Note that Quizzes are open-book, and there is no sharing of books or
other materials during Quizzes, nor are electronic devices allowed.[^1]
Thus every student must have his/her own PDF copy of the textbook and
any other course materials.

### There are no makeup quizzes

Life is complicated. You may miss a Quiz due to illness, a job interview
or whatever. If you miss a Quiz, for whatever reason, it simply will
become one of the two Quizzes you exclude from your grade.

There are no makeup Quizzes, and no early or late ones.

### Quiz on the last day of lecture

The last Quiz, given in lecture on the last day of class, will cover
material we've gone through since the coverage of the previous quiz.

Depending on the class size, this quiz may be given on a group basis,
i.e. you will work on the Quiz with your
Homework Group. 

**NOTE: Your attendance is required.**

### Partial credit on quiz problems

Quiz problems will be short answer, but you still may be able to get
partial credit, in the case of arithmetic or algebra errors, or in the
case of code, spelling or syntax errors. In fact, you will probably get
full credit in those situations. But it is your responsibility to bring
it to my attention after the grades are out.

If a problem has a mathematical answer, do NOT submit it in simplified
form. For instance, write $2(3^2-1$ rather than 16. This will increase
your chances of getting partial credit. Note conversely that SIMPLIFIED
ANSWERS MIGHT NOT GET CREDIT, EVEN IF CORRECT.

In answers involving coding
make liberal use of comment lines, so as to explain your thinking.  This
will be especially important for partial credit.

### Open-materials policy

**TESTS ARE TAKEN ON AN OPEN-MATERIALS BASIS.** Bring the textbook and
other course materials with you to each Quiz. You are also welcome to
bring whatever other materials you wish, e.g. technical books,
dictionaries, whatever you want. Whatever you bring, **make absolutely
sure that you remember to bring all your course materials, as many of
the Quiz questions will refer to specific pages in them.**

OMSI, the tool we use to submit and grade quizzes, has a PDF viewing
feature. You may use that to view your textbook, providing it fills your
computer screen while you are using it.

Please note that in program code on the Quizzes you are only allowed to
use language, functions, etc. constructs presented so far in our course.

### Electronic Devices

Other than using your laptop with OMSI, you are not allowed to use any
electronic devices, INCLUDING CALCULATORS, during Quizzes.

### Re-assessment of Quiz Grading

If you believe you deserve more points on a Quiz problem, I am happy to
look at it again -- PROVIDED you submit a request to me within two weeks
of my sending out grades.

After course grades are submitted, university policy forbids grade
changes based on "re-assessment of the quality of the student's work."
Grade changes may be made in cases of genuine clerical error.

# OMSI

You will use the OMSI system, *http://github.com/matloff/omsi*, to take
the Quizzes and to submit your Homework, on your laptop computer **in
class.**  (Note the emphasis; you must be physically present in class.) 
Your machine does NOT need to be a fancy laptop; an old, slow machine is
fine.

### Preparation

You must read the material at the above link, and the OMSI rules,
*http://heather.cs.ucdavis.edu/OMSIrules.html* THOROUGHLY before the
first Quiz.  It is imperative that you conduct your own dry run, playing
the roles of both the instructor and student.  Since VPN may be an
issue, it is recommended that in your dry run, your host the server on
CSIF and run your laptop from home.

### Coding questions, in Quizzes and Homework

Your code will be executed by the grading tool.  Thus syntax etc. must
be correct.  If your code doesn't run, it still will be evaluated by the
person who grades it, but for full credit it must run.

Unless asked to do so, you need not including error-checking code.

In most classes I teach, we use the R language.  The documentation here
will assume R, but of course it still applies to other languages with
small changes.

### Numeric questions (e.g. ECS 132)

Exact answers are required; do not use simulation unless asked to do so.

You will use R to answer any Quiz problem that requires a numerical
answer. (Use of R code enables automatic grading of math problems.) And
it must be real R! Here are some examples of non-R:

    1 + 2 = 3
    2 x 2
    3 over 2
    five
    the matrix has 5 rows

OMSI will run your code, and obviously non-R will cause an error.

### It must be real R

Remember, when your quiz is graded, any numeric questions will be
executed by R. If it is "Renglish," a mixture of R and English, an
execution error will occur.

In the case of questions with numerical answers, write them in program
style, using R syntax, e.g. using \* for multiplication, `^` (carat) for
exponentiation, %% for the mod operator, etc. Call **exp()** for
evaluating powers of e = 2.71\... and **pi** for 3.14\...

Use the concatenate function, **c()** if a numerical problem asks for
more than one number, e.g.

    > c(1.2,88,6)
    [1]  1.2 88.0  6.0

### Useful, likely crucial, R functions

Here are examples of R functions you may find useful: **length()**
**choose()**, **combn()**, **sum()**, **min()**, **max()**, **exp()**,
**log()**, **integrate()**.

Here are examples of **integrate()**:

    > integrate(function(t) 2*t/15,2.5,4)$value  
    [1] 0.65
    > integrate(function(t) 2*t^2/15,1,4)$value 
    [1] 2.8
    > integrate(function(t) sqrt(abs(t)) *
    dnorm(t,mean=10,sd=2.1),-Inf,Inf)$value
    [1] 3.144017

Did you notice the \"\$value\" above? Without it, the class object is
printed--in English--and thus not readable by my grading script.

# Homework Groups 

The following will be done in Groups:

-   Homework

-   (possibly) the last Quiz of the quarter, in lecture

-   the take-home Term Project

So, get to be very good friends with your Group, as you will be working
with them constantly!

### Forming groups

Group size must be at least three (two if the class enrollment is under
25), and no more than four.

During the first week of class, the TA will ask you to either state the
membership of a Group you formed on your own, or state that you will to
be placed into a Group. If you and someone else in the class wish to
form a Group, then ask the TA to assign one or two more people to your
Group.

### Group participation: your responsibilities

* **YOUR HOMEWORK PARTNERS DEPEND ON YOU.**

* Don't think, "I'm just taking the course P/NP" or "I'm a graduating
    senior," and then do little or nothing in the Homework.  To do so
    would be harmful to your Group partners

* Repeated failure to work cooperatively with your Group may result in
    a **substantial penalty** being applied to your course grade, including
    your **possibly getting an F for the course.**

* Please do not allow things to deteriorate to the point at which I send
    you an e-mail message titled, "Your course grade is in jeopardy."

* If one or more Group members repeatedly fail to comply with the above,
they will be placed in separate, one-person Groups. This means not only
the Homework but also the Group Quizzes and, most importantly, the Term
Project.

# Regarding Academic Dishonesty

An embarrassing subject which nevertheless must be mentioned is academic
dishonesty, i.e. cheating.

### My general policy

**If a student is found to be cheating, it will be treated as a VERY
SERIOUS matter, not a harmless prank, AND WILL BE REFERRED TO STUDENT
JUDICIAL AFFAIRS. It will harm his/her standing at the university, and
also possibly make it difficult for him/her to get a job when seeking
employment after graduation.**

**IMPORTANT NOTICE:** Starting Fall 2018, all UCD instructors are
required to explicitly inform students that they are subject to the 
[Code of Academic Conduct](http://sja.ucdavis.edu/files/cac.pdf).


change, effective Fall 2018, is that "...authority [is granted] for
instructors to assign a student a maximum grade penalty of 'F' for a
course -- as opposed to an 'F' only on the examination or assignment in
question -- when academic misconduct is admitted or is determined by
adjudication to have occurred" (e-mail message from Academic Senate
Office, Sept. 27, 2018).

### Quizzes

Any communication with others during Quizzes is forbidden, and will be
prosecuted. Any student found cheating will receive a grade of F in that
quiz, and possibly an F in the course (grade in the COURSE, not just on
that Quiz).  

Please work as follows during Quizzes:

-   Official university policy forbids "Wandering eyes," talking during 
    exams...or leaving the exam room without permission.

-   **To avoid the appearance of cheating, make sure that OMSI is the
    only app on your screen at all times.**  No e-mail, Web browser etc.
    windows may be present.

-   Try to sit in alternate seats if possible.

-   **ABSOLUTELY NO TALKING** to classmates at any time during the Quiz.

-   Keep your OMSI screen hidden when you are not actually writing, so
    that it will not be so exposed to view.

-   It would be greatly appreciated if you **USE THE RESTROOM BEFORE THE
    EXAM STARTS, RATHER THAN DURING THE EXAM.**

Thanks very much for your help.

Please note that in the case of larger classes, students may be
photographed, including video.

Please do not wear hats during Quizzes.

### Homework 

**Outright copying of homework**, whether in the form of code or
algorithm or math, is of course an extremely serious violation of
university policy and personal ethics. Similarly, asking for advice on
the Internet, paying people to do your work, or otherwise improper
consultation, is again an extremely serious violation of university
policy and personal ethics.

**However, you are welcome, and indeed encouraged, to trade tips with
people in other Groups.** You may also on rare occasions ask people whom
you know outside the class for hints, say friends or relatives who have
some knowledge of the field, on a very limited basis.

You are also welcome to make reasonable use of the Web. For example, I'm
a big fan of Wikipedia and there is a ton of material on there.

# The Discussion Section

**The discussion section is required**. It will be used for the purpose
of giving Quizzes, and occasionally for presenting material not covered
in lecture. (That material will appear on Quizzes.)

**If the class has multiple discussion sections, you are NOT allowed to
take a quiz in a section you're not enrolled in.** Under rare
circumstances, you may ask the TAs involved for permission to take a
quiz in the "wrong" section; you must cc the instructor in making this
request.

## Our Class Web Page and Blog

Our class Web page is at
<http://heather.cs.ucdavis.edu/~matloff/xxx.html>, where xxx is our
course number, e.g. 132 for ECS 132. It contains information on office
hours and the like.

Our class Blog is linked to from our class Web page. **IT IS REQUIRED
THAT YOU READ THE BLOG EVERY DAY**; it's used to announce Homework
assignments (including clarifications), hints for Quizzes, and so on.

Any information disseminated on the Blog is considered part of official
course materials. This means for example that it may be needed in
Quizzes.

I will try to send an e-mail message informing you that a new blog post
has been made, but cannot guarantee it.

# Homework 

We will have approximately three to five Homework assignments through
the quarter, depending on the course and other factors.

### Homework Due Dates

The term *due date* means 11:59 p.m. of the stated date.

### Announcements

Homework assignments will be announced in the class Blog. (Note: An
assignment is not official until it is announced on the Blog, even
though it may appear on the Web before then.) The Homework specs
themselves will be on the course Web site, so look there when an
assignment is announced on the Blog.

Occasionally there will be news about a current Homework assignment,
such as clarifications, hints and so on. These will be announced in the
Blog.

### Programming Work

In general, you will not be docked points for poor style--indentation,
comments, etc. But you should do these things FOR YOURSELF, to help
organize your thinking, and to be able to understand your program two
months from now.

Use a debugging tool! Learn my Principle of Confirmation! Don't flail
for hours when you can actually shorten your debugging time by a large
fraction.

### Submitting Homework 

If the assignment includes mathematical work, e.g. as in ECS 132, you
must write up your solutions in LaTeX, in detailed, clear form. Don't
just write down equations; *explain* them.

It is REQUIRED that you use the Unix **tar** command to package all of
your files. In a course with math content, this means your **.tex** and
**.pdf**, and image files if any.

For a programming course, this will be just your source code files,
except in the Term Project, where you will follow the above rule for
math courses.

The file name will be **email1.email2\....tar** where the "email" fields
are the official UCD e-mail addresses of the members of your Group, e.g.
**jsmith.agutierrez.streddy.tjwong.tar**. Be sure to get those addresses
exactly correct, to avoid a situation in which your team member doesn't
get credit. **Be sure to use the proper e-mail address, NOT a different
one based on your UCD login. Your official address is the one used by
the TA and me in mailing you; check your records.**

**Your submission MUST be a .tar file and MUST use the above naming
scheme.** The TA may ask you to resubmit if you fail to comply.

In submitting your **.tar** file, make SURE not to make subdirectories.
When the grading script unpacks your **.tar** file, it will expect to
see all your work files in the same directory from which the script
invokes the **.tar** command.

You then submit your **.tar** file to the TA (not to me), using
**handin** on CSIF.

    handin taUserName hwkName yourMailAddresses.tar

(The TA will announce **hwkName**.)

### Interactive Homework Grading 

We will use interactive grading. The TA will announce Homework grading
times, and each Group will sign up for a time slot. **All members of the
Group must be present during the grading time.**

During a Group's time slot, the TA will ask each member of the Group
questions about their Homework submission, such as "What if the problem
had asked\...", "Explain in detail why you did it this way\...", "What
if you were to do it this way instead\..." The purpose of these
questions is to ensure that all partners are actively involved in all
the work. *The TA will also ask questions about the general course
material.*

**The TA will assign grades for each Group member. In some cases, these
grades will be identical, but if there is a disparity in the levels of
understanding the different Group members have regarding the assignment,
the TA will assign different grades to each member.**

It's not expected that all members of a Group are equally proficient in
programming or math, and thus it's not expected that everyone
contributed equally to their submitted work. However, it IS expected
that everyone was very actively involved.

You must be prepared to speak cogently about the ENTIRE assignment. In
particular, if you worked on one part of the assignment and Johnnie
worked on another, it is NOT acceptable to answer the TA's question
about Johnnie's part by saying "Oh, I don't know about that part,
because Johnnie did it."

The TA will e-mail me a report after grading an assignment, with
tentative grades for my approval. Below are samples of what the TA might
say.

**Example 1:**

> Group 3, John, Jim and Mary: All three students seemed to have
> actively contributed to this assignment, and all three answered my
> questions well. The program worked fine. Tentative grades--John A,
> Jim A, Mary A.

**Example 2:**

> Group 3, John, Jim and Mary: The program worked fine, but Mary seems
> to have done most of the work. John had some trouble answering my
> questions, and Jim could answer almost nothing. Tentative
> grades--John C, Jim F, Mary A.

**Example 3:**

> Group 3, John, Jim and Mary: The program worked mostly OK, but failed
> when I tried the input combination 8, 88 and 168. All three Group
> members did answer my questions well. Tentative grades--John A-, Jim
> A-, Mary A-.

In the case of ECS 132, there will be similar reports for math problems.

### If You Need Help, Hints, Etc. 

**Please note that Homework assignments here will NOT lay out a detailed
recipe, with tons of hints, telling you how to do the problems.**

The work is designed to be challenging and thought-provoking. This
thought-provoking nature of the assignments is the vehicle by which you
get to really understand the concepts. You are not necessarily expected
to see right away how to do an assignment. Instead, you are expected to
spend a considerable amount of time pondering the assignment, gradually
seeing more and more, until you finally see how to do the whole thing.
It is through that thought process that will develop insight into the
course material.

**The TA and I will be quite happy to help you, definitely including
giving you hints--but only if, after giving a matter considerable
thought, you still don't see what to do.** Once you have reached the
point where you cannot go any further, we very much you to seek help
from us. We want you to do well on the Homework!

### Late Work

An assignment is late if it is submitted to the TA after the due date.
If you are late, you will be assessed a 5% penalty the first late day,
and 10%-per-day penalty after that in your grade for that assignment.
(Since **handin** is available every day, each of the seven days of the
week counts as one day.) The maximum total penalty is 50%.

Each Group will be allowed a total of 2 late days over the quarter, time
which is not penalized. You can use this as being late 2 days with no
penalty on one assignment, or as being late 1 day with no penalty in
each of two assignments.

Don't squander your grace period days in the first assignment! The
subsequent ones will almost certainly be more difficult, so save your
grace time for then.

The TA will keep the appropriate records as to how many days of grace
period you have used.

## Term Project 

In lieu of a Final Exam, we have a Term Project, which also serves as
the last Homework assignment. It will be take-home and collaborative
with your Group, just as with your earlier assignments. It will be very
different from regular assignments, though:

-   It will be of a different nature, notably in its requirement that
    you submit a written report.

-   It will involve work approximately 2 times that of a regular
    assignment, and will be weighted accordingly, especially given the
    dual role of the Project as both Homework and a replacement for a
    final exam.

-   A good Term Project may be given heavy Extra Credit, substantially
    boosting your course grade, much more than a regular assignment
    would. I typically bump up your course grade according to the
    following scheme:

    -   B+ project grade: Bump up course grade 1 notch, e.g. B- to B.

    -   A- project grade: Bump up course grade 2 notches, e.g. B- to B+.

    -   A project grade: Bump up course grade 3 notches, e.g. B- to A-.

-   No late Term Projects will be accepted. I highly recommend that,
    during the course of your work on the Project, you periodically
    submit what you have to **handin**. That way, if you do miss the
    deadline, at least you will have something submitted for grading.

You submit your Project reports in the same manner as for Homework, as
detailed in Section [12.4](#subhwk){reference-type="ref"
reference="subhwk"}. **Make sure to heed the point about
subdirectories.** You use **handin**, in my directory (not the TA's) on
CSIF, using the subdirectory **xproject**, e.g. **50project**:

    handin matloff xproject yourMailAddresses.tar

Note these Project requirements:

-   Do a good, professional job.

-   Correct grammar and spelling, clarity/fluidity of the writing, etc.,
    do count -- a LOT.

-   You must use LaTeX.

-   You must adhere completely to the instructions. For instance, in ECS
    132, all work, *including graphics*, must be done in R.

-   Use bold font for program variables in text.

-   Use the **listings** package or similar for displayed code listings.

-   Full code listings must be included in an appendix.

-   Use Bibtex for references. Note: Lots of materials already have
    Bibtex entries available online, saving you work. In referencing a
    Web page, include at least the title and URL.

Details will be given later. If you are curious now, though, you can
find model examples in files with names of the form "Exemplarx\" on our
class Web site, e.g. <http://heather.cs.ucdavis.edu~matloff/132/>.

# Grading

Grading is noncompetitive (there is no "curve"), so it is possible for
everyone to do well.

### Weighting

The formula used is

*course grade* = 0.60 x *Quizzes grade* + 0.20 x *Homework grade* + 0.20
x *Term Project grade*

where the Homework and Quizzes grades are each on the 4-point scale (4
for an A, 3 for a B, etc., with + adding 0.3 and - subtracting 0.3).

(However, note the section below, Positive and Negative Factors in Your
Course Grade.)

### + and - Grades 

The threshhold for a grade of n is (n-1).85; the threshhold for an 'n-'
grade is (n-1).6; the threshhold for a '+' grade is n.2. So, for
example, if your weighted average from the above formula is between 2.6
and 2.84, your course grade is B-; if the average is between 2.85 and
3.19, your course grade is B; if the average is between 3.2 and 3.59,
your grade is B+.

### Quizzes Grade 

You will get a letter grade on each Quiz.

In recognition of the fact that on (rare) occasions -- for whatever
reason -- you will not be able to attend discussion section, or you
simply will have an "off day," your lowest two (letter) Quiz grades will
be thrown out. Your other Quiz letter grades will be averaged to produce
your overall Quizzes grade.

If you miss many quizzes, your course grade will be reduced, possibly to
an F, regardless of overall grades on the Quizzes, and Homework.

### Positive and Negative Factors in Your Course Grade 

This is not "CHEM 1A-style grading," calculated purely by formula, in
which falling 0.5% below the cutoff point for an A results in a grade of
B. The grade as determined above is just a lower bound. (However, see
below regarding negatives.)

### Factors Increasing Your Grade above the Formula

-   A good Term Project may be given heavy Extra Credit, substantially
    boosting your course grade, far more than a regular assignment
    would. (It affects writing letters of recommendation too.) Of
    course, it must be clear that the student actively participated in
    the Project. As noted earlier (Sec.
    [13](#project){reference-type="ref" reference="project"}(, I
    typically bump up a student's course grade by 1, 2 or 3 notches, for
    a B+, A- or A Project -- that's A LOT!

-   Student has been making a really strong effort in the class.

-   TA's detailed reports to me of the student's performance in the
    interactive Homework grading sessions show that the student has
    better insight than his/her Quiz scores show.

-   "All's well that ends well"-student showed a marked improvement in
    Quiz grades as the quarter progressed.

-   Student's insightful comments in class.

-   Student got one or more really difficult Quiz problems right that
    few or no other students got.

### Factors Reducing Your Grade below the Formula

Negatives can be an obstacle. Problems such as the following, though
rare, may have a major impact, e.g. making the student ineligible for
"special offers" such as the discarding of the two lowest quizzes, and
maybe even resulting in a D or F for the course grade:

-   A pattern of missing three or more Quizzes.

-   Little or no involvement in the Homework.

-   Little or no involvement in the Group Quiz or the Term Project.

-   Failure to finish the Term Project.

-   In a class with multiple discussion sections, taking quizzes without
    permission in a section other than the one the student is enrolled
    in.

Remember, the Term Project is assigned in lieu of a final exam. If this
is missing, or if you do almost no work on it, it will not merely be
treated as an F. Instead, you will be imposed a heavy penalty on your
course grade, and in fact possibly receive an I (Incomplete) grade. To
make up the I, you will be required to do a new project, by yourself.

### Example of How the "Special Offers" Can Make a Substantial Difference in Your Grade

This was a student in ECS 132.

Original quiz record:

    F A+ F C+ B+ D B

Add Quiz 0, practice using the OMSI system (most students get A+):

    F A+ F C+ B+ D B A+

Drop two lowest quizzes:

      A+   C+ B+ D B A+

Replace next-lowest quiz by "job interview" grade:

      A+   C+ B+ B+ B A+

Course grade according to formula (after the above changes):

    B+

Bumped-up course grade after two-notch bonus for A- project:

    A

Again, look at that original quiz record!

    F A+ F C+ B+ D B

Yet, A for course grade!

A- Term Project

# I Do Care!

I wish to emphasize that I care very much that you succeed in this
course, and I look forward to getting to know all of you.

