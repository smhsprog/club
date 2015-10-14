# Guidelines

This folder will contain tools for the Leaders to use for the club:

# Table of Contents

- [Maintaining a clean repository](CONTRIBUTING.md)
- [Safe Content](#safe-content)
- [Activities](#activities)
  - [Rock Paper Scissors](#rock-paper-scissors)
  - [For Loop](#human-for-loops)
- [General Workshop guidelines](#general-workshop-guidelines)
 - [Portfolio](#portfolio)
- [First Meeting](#first-meeting)
  - [Setting Up](#setting-up)
  - [Presentation](#presentation)
  - [Introductory Talk](#introductory-talk)
  - [Curriculum](#curriculum)
  - [Week Cycles](#week-cycles)
- [General Meetings](#general-meetings)
- [Project Week](#project-week)
- [Distracted hackers](#distracted-hackers)
  - [Approaching it](#approaching-it)


# Maintaining a clean repository

Follow [CONTRIBUTING.md](CONTRIBUTING.md) rules to help build this club!

# Safe Content

To make sure no files are lost and avoid confusion, follow the following rules:

1. When editing, making or deleting files, you must create a separate
   branch or commit to a branch, never commit to master branch.
2. If you do create a new branch, name it with whatever you have edited the
   most. Ex: `guidelines`
3. When committing to a branch, name it first with whatever you have edited the
   most followed by a brief summary. Ex: `guidelines: Added some guidelines`
4. Once done, do a pull request, which will be named with the commit name,
   and assign another other leader to approve the request. In need of an
   emergency change, make sure you have everything correct by going to the
   "Files Changed" tab in the pull request and accept the request yourself.

Bad Demo Video:

<a href="https://www.youtube.com/watch?v=OWqhTm0rcX4&feature=youtu.be">
<img src="http://img.youtube.com/vi/OWqhTm0rcX4/0.jpg"  
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

# Activities

### Rock Paper Scissors

```
Time: 5-15 min
Materials: none
Number: best for 10-30
```

Separate the hackers in groups of 3-7, depending on the amount of people there
are.

Everyone plays rock paper scissors against each other, 1 vs 1 best of 1s. They
must introduce each other to remember names. If you lose you leave the circle.
Now in order to win, (Depending on the number of people) you need to be able to
remember the names of the people you have defeated.

### Human For Loops

```
Time: 10-20 min
Materials: Whiteboards
Number: Groups of 6-10.
```

This activity involves the hackers to work in a group and solve a for loop. The
point of this activity is to teach the hackers how for-loops work. Make sure
you have explained what for loops are, If/Else and briefly talk about variables.

Example for-loop:

```
sum = 0;
for(int i = 120; i < 157; i++) {
  if(i % 3 == 0) {
    sum = i + sum;
  } else {
    sum = i - sum;
  }
}
```

Each person in each group will have a role:

- CEO - Chief Executive Officer
- CTO - Chief Technology Officer
- CFO - Chief Financial Officer
- CDO - Chief Data Officer
- CMO - Chief Manager Officer
- CSO - Chief Strategy Officer
- CIO - Chief Insurance Officer // Just in case

- CEO Will coordinate everything and retain the i value as well as a log.
  - Ex: `sum = 0, i = 120`
- CTO Will check if the loop proceeds or not.
  - Ex: `i < 157 Proceed!` || `i = 157 Don't Proceed! Give result to CEO`
- CFO Will check if the if-statement is true or false
  - Ex: `i % 3 == 0, Go to if' || 'i % 3 not == 1, Go to else.`
- CDO Will conduct the if part
  - Ex: `sum = i + sum, here is sum.`
- CMO Will conduct the else part
  - Ex: `sum = i - sum, here is sum.`
- CSO Will increment the value and give it to the CTO
  - Ex: `i is i+1, here you go CTO.`
- CIO Can help the CEO keep track of the numbers.

# General Workshop Guidelines

Have each workshop structured as it follows:

- Name of workshop
  - Demoing
  - What will be learned
  - During Workshop

Talk about what the hackers will learn, where is it applied. Proceed with a demo
.

Have links ready up and working.

When creating a workshop, have a bit.ly link ready for the hackers.

## Portfolio

Link to workshop: [link](https://github.com/hackedu/hackedu/blob/master/playbook/workshops/portfolio/README.md)

Bit.ly: http://bit.ly/1QqW0Rv

```
Expected time to finish: 60min.
Given time: 2 1-week-cycles days ~70min.
Level: Beginner.
```

### Demoing

Regular Demo: [link](http://output.jsbin.com/fugoki/2)

What: A personal portfolio with Picture, Heading and a small paragraph.

Advanced Demo: [link](http://jsbin.com/gameyi/2)

Possibilities: Creating social media links, creating an email form, youtube
video.

### What will be learned

- All websites use html and css. CSS is super important.
- Hackers will learn how to find solutions by themselves using google.
- How to use HTML and CSS to create a website.

### During Workshop

Leaders:

- Make sure they fill up the form at the end of the workshop at the end of the
  second day.
- Provide help to the hackers, insist in using google, tell them to follow the
  lines of: \[Language] (Problem), give an example: spanish How to say hello.
- Create 2 challenges, Advanced and Ultra.
  - Advanced should be possible for any hacker.
  - Ultra must be very challenging and difficult.
  - Make sure to provide the languages the Challenge is possible in.



# First Meeting

Welcome to Programming Club!

## Setting Up

- Make sure you have one leader welcoming everyone to the club.

Ex: ` Welcome to Programming Club! Come on in! `

- Have the rest of the leaders talking to new hackers as they come in and create
  a friendly environment.

Ex: `Hello There! I'm Samuel Escapa, one of the
 leaders of this club, what's your name? [Peter] Hi Peter, Welcome!`

- Have a signup sheet: [Here](https://docs.google.com/spreadsheets/d/14p7mebY3Sa_BoRtAG8taHM-Q7fw5I8m1jVlSSylV61A/edit?usp=sharing)

## Presentation

Have a good start presentation after new hackers have settled, introduce all
leaders and advisor. Talk about __briefly__ what the club is about, and
split the talking time to all the leaders. Have a transition between each
person talking.

Ex: `This is why programming is so important. Next Kevin
will talk about our curriculum for this year.`


Here down, you are talking to the hackers.

## Introductory Talk

- Why is programming awesome?
  - Programming brings unlimited opportunities to anybody in the
    world with the right technologies.
  - Make School Founder Jeremy Rossman had this great speech.
  - Your smartphone is more powerful than the computer we used to send a human
    to the moon.
  - Only 60 years ago, our technologies would have been considered magic. And
    in a world where magic exists, there are people who know how to use magic,
    and then there are muggles.
  - You want to be in category A.
  - Every year that goes by, there are more and more industries that can be
    transformed by computers. In fact, it's hard to think of an industry that
    won't be disrupted by technology.
  - If you were the king of the Roman Empire in 25, you would have ruled over
    56.8 million people. But by 2016, 2 billion consumers will have smartphones,
    which means you can impact 2 billion lives.

## Curriculum

- What are we learning this year.
  - We are going to learn how to make great websites and web applications!
  - Starting briefly with HTML/CSS (It's totally fine if you don't
    know what it is)
  - We will then proceed with Javascript and Node.js.
  - Microsoft, Paypal, Quizlet and surprisingly Walmart use Node.js.

## Week Cycles

- We are going to work in cycles of 5 weeks.
  - 1st and 2nd week will be Workshops, where we will learn new skills and use
    previous ones to advance.
  - 3rd and 4th week will be project time, where you will work with a partner to
    create a project.
  - 5th week will be demo week, everyone will demo and ship their new project to
    the club.


## [Ice Breaker](#ice-breakers)

If there is enough time, proceed to do Rock Paper Scissors.

# General Meetings

For General meetings, follow the slides found in the meetings folder
accordingly.

Use: `https://docs.google.com/viewer?url=[URL OF RAW PDF]`

# Project Week

//TODO

# Distracted Hackers

Hackers tend to get bored during a workshop especially if it's long. They would
just roam around the internet and play video games, in some cases, they would
distract other hackers into it.

## Approaching it

- Be friendly
- Don't
  - seem or get defensive
  - exert your authority
  - seem frustrated
  - All of these will make you look bad.
