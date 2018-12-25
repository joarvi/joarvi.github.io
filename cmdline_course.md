---
layout: default
---

# Overview of the Command-Line Course

This section will give you an overview of the Command-Line Course. Contents of the course have have been divided in 7 section i.e. in 7 weeks.

The final grade consist of:

| Part                        | Weight          |
| --------------------------- |:---------------:|
| Quizzes (Week 1-6)          | 75%             |
| Final Assignment (Week 7)   | 25%             |
| Final Grade                 | 100%            |

## Week 1 - Introduction to Command-Line Environments

Basic commands

* Some commands that were presented in the first week were for example ls, cd, mkdir and mv

Text editors (Nano)

File formats

## Week 2 - Navigating a UNIX System

Continuing with some basic commands

```
cp
ln
```

Access permissions

```
chmod
```

SSH

SFTP

## Week 3 - Corpus Processing

Frequency list

Text Processing Commands

Regular expressions, grep, and sed

```
grep -E
```

## Week 4 - Scripting and UNIX Configuration Files

Creating a sample .bashrc file

UNIX Environment Variables

Scripts (bash)

```
#!/bin/bash

if result="$(
	diff -y -W78 <(
		find $1
	) <(
		find $2
	) )" 
then
	echo "1" # not equal
	echo 
else
	echo "2" # equal
	echo
fi
```
## Week 5 - Installing and Running Programs

Running and Installing Software: Basics

Running and Installing Software: Python

```
pip3 install guess_language-spirit
```

Running and Installing Software: C and C++

Use of make command 

## Week 6 - Version Control

Git
```
$ git add -A
$ git commit “Initial commit.” 
$ git push
```

## Week 7 - Building Webpages using GitHub Pages

Ruby

Bundle

Jekyll

```
bundle exec jekyll serve
```

Markdown 

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

GitHub Pages
