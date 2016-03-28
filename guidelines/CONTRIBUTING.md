# Maintaining a clean repository

In order to keep this repository clean and easy to learn from, we need to keep
a structure.

# Table of Contents

- [Using Terminal/Command Prompt](#using-termina/command-prompt)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Markdown structure](#markdown-structure)

## Using Terminal/Command Prompt

- Basic commands:
  - ```cd```: Change directory. Ex: ```cd github```.
  - ```ls```: List files in current directory. (Note: ```dir``` for Windows)

## Submitting a Pull Request

- Start off by going into your Terminal/Command Prompt and navigate into the
  club folder. Most cases would be:
  1. ```cd github```
  2. ```cd club```

- Once there, run the following commands:
  1. ```git checkout master && git fetch origin master ```
  2. ```git pull --rebase origin master```
    - If that doesn't work: ```git reset --hard origin/master```
    - Followed by" ```git pull --rebase origin master```.
  3. ```git checkout -b BRANCH-NEW-NAME```

- Add your slides/changes and then:
  1. ```git add --all```
  2. ```git commit -m "DESCRIPTION"```
  3. ```git push origin [BRANCH-NEW-NAME]```

Once doing this, head over to [here](http://github.com/SMHS-Programming/club)
and click on ```Compare & pull request```. Click on it, add description if
needed and that's all! You are done with your Pull Request.

## Markdown Structure

We use markdown in order to format our raw content, like using headers etc. You
can use:
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### Headers - 3 type.

- Biggest: ```# This is a type 1 header```
- Medium: ```## This is a type 2 header```
- Smaller: ```### This is a type 3 header```

### Bold text

Use ```**``` to bold some text. Ex: ```**This** is bolded text```.

### Links

Use: ```[Link 'name'](link URL)```
Ex: ```[Click here for google!](http://google.com)```

### Lists

Use: ```-``` for unordered list.
Use: ```1.``` for ordered list.
