# Maintaining a clean repository

In order to keep this repository clean and easy to learn from, we need to keep
a structure.

# Table of Contents

- [Submitting a Pull Request](#submitting-a-pull-request)
- [Naming conventions](#naming-conventions)
  - [Branch Names](#branch-names)
  - [Folder Names](#folder-names)
  - [File Names](#file-names)
- [Markdown structure](#markdown-structure)
  - [General](#general)
  - [Headers](#headers)
  - [Lists](#lists)
  - [Code](#code)

## Submitting a Pull Request

- What you need:
  - [Git](https://git-scm.com/) installed.
  - [Github](https://github.com/) account with contributing priviledges.

### What is a Pull Request

- A Pull Request is a request with changes to the files in the repository.
- It needs to be approved by an "admin", in this case one the club leaders.

### Getting Familiar with Terminal/Command Prompt

- What are those???
  - Terminal or Command Prompt are tools in which you can type commands to
    perform specific tasks, as opposed to using mouse and clicks.
  - This means better control, faster navigation and saving tons of time.
  - You can use the following commands in order to access folders and files
    instead of the simple click-and-open.
- Where is it?
  - You can find Terminal in your 'Application' folder under 'Utilities'.
    (/Applications/Utilities)
  - [DOUBLE CHECK] For Command Prompt:
    Press Win+R and type git cmd, then press enter. This will open
    command prompt. Otherwise, find Git CMD (search) and open it.
- How to use Terminal [Mac]:
  - Typing ```cd FOLDER``` will allow you to go into FOLDER. -- stands for
    - ```command directory```.
    - Typing ```cd ..``` will allow you to go back 1 folder.
  - Typing ```ls``` will you give you the current FOLDERS you can 'cd' into.
  - Typing ```pwd``` will give you your current location in the folders.
  - Typing ```mkdir wow``` will create a folder with name 'wow' in the current
    directory you are in (Type 'pwd' to find out where you are).
- How to use Command Prompt [Windows]:
  - Typing ```cd FOLDER``` will allow you to go into FOLDER.
    - Typing ```cd ..``` will allow you to go back 1 folder.
  - Typing ```dir``` will you give you the current FOLDERS you can 'cd' into.
  - Typing ```echo %cd%``` will give you your current location in the folders.
  - Typing ```mkdir wow``` will create a folder with name 'wow' in the current
    directory you are in (Type 'echo %cd%' to find out where you are).

### Getting Started

- You want to navigate to a folder that is easily accessible, so that you don't
  need to 'cd' into a lot of folders. When you make your edits, you need to be
  in the main folder holding all of your edits.
- For this case, this tutorial will create a folder in Desktop and do the edits
  from there.
1. Opening Terminal
2. ```cd Desktop```
3. ``mkdir workspace```
- Now you can run this command: ```git clone https://github.com/SMHS-Programming/club.git```
- So now you have created a direct clone of the repository, in this case in
  Desktop/workspace/club.

// TODO

### Everytime you do edits

Run BEFORE Making your changes:

1. ```git checkout master && git fetch origin master ```
2. ```git pull --rebase origin master```
  - If that doesn't work: ```git reset --hard origin/master```
  - Followed by" ```git pull --rebase origin master```.
3. ```git checkout -b BRANCH-NEW-NAME```

Make changes to your files etc. Then run:

1. ```git add --all```
2. ```git commit -m "DESCRIPTION"```
3. ```git push origin [BRANCH-NEW-NAME]```

After that, go into: [https://github.com/SMHS-Programming/club](https://github.com/SMHS-Programming/club)
and fill up the 'Compare & pull request' button.

## Naming conventions

### Branch Names

- All lowercase
- - as separators

### Folder Names

- All lowercase
- No Numbers, special characters
- - as separators

### File Names

- All lowercase
- - as separators
- All .md files should be capitalized.

## Markdown structure

To create nice looking markdown files, use:
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
When creating .md (markdown) files, follow the following rules:

### General

- Wrap all lines at 80 characters unless it's a long link preventing it from
  occurring.
- Make sure to put break lines between any markdown element

Good:

```
# Header 1

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam aliquam dui vel
posuere facilisis.

## Header 2

Mauris vulputate justo nisi, vitae euismod mauris euismod eu. Integer vitae
hendrerit nibh, sed porta sapien. Duis consectetur lacus id arcu consequat
aliquet.

### Header 3

Sed congue iaculis dapibus. Morbi et tempor nisl, sed mattis quam. Morbi
porttitor pharetra urna et dictum. Integer laoreet consequat velit, ac egestas
velit accumsan non.
```

### Headers

- Use different Header types as indentations
- Give a space after calling the pound combination (###[space]Word)
- Headers must be preceded by a line break after being called

### Lists

- Always use `-` as opposed to `+` or `*` for unordered lists
- Indent with 2 spaces (  -)
- Items should not end with a period unless necessary
- Lists exceeding 80 characters should be wrapped and aligned with next line.

```
- Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
```

### Code

- Code blocks should be followed and preceded by a blank line.

Look at
[hackEDU Contributing rules](https://github.com/hackedu/meta/blob/2360c50372eb331cc46c67e6faf5bcdb7d4655d0/markdown_style_guide.md)
as they are quite similar.
