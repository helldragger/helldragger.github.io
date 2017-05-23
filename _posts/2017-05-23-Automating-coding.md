---
layout:     post
title:      "Automatisation of programming"
date:       2017-04-20
categories: dev
type:       auto
---

Well, it's been a week since I have had this idea in my head: what if I could instantaneously call some generic algorithm to my editor and don't having to add a big library as dependency, in order to stop having to reinvent the wheel each time I code something? Why should I keep losing my time rewriting again and again the same algorithms I use all the time?

That's the moment I decided to do something about it, a simple database of algorithms, that I could call anytime, any day, anywhere, from any text editor, I named it: **Modular Programming**!

## Modular Programming

The source code can be retrieved here: https://github.com/helldragger/ModularProgramming

### The idea

The basic idea is simple, I want to:
  - Be able to invoke *any algorithm I ever made* easily
  - Be able to invoke it *in any text editor* I may use
  - Be able to *use it across the world* if I want to
  - Keep the invocation *as simple as possible*

### The basics

That's it. I then started to work on it and determined some basic needs to my project:
  - a network communication between database and client
  - a hook between client, keyboard hotkeys and text selection
  - a file database to store my algorithms in an ordered manner

#### My actual experience about these concepts

Ok. I never had to deal with any network coding, I never had to deal with such file systems, and I never had to use python for clipboard and keyboard stuff. 
*BUT* I already made some bots and macros using AutoHotKey, using clipboard and user selection is a piece of cake with this language! But making a network connection using AHK to a python server as been one of the worst idea I ever had...

### The difficulties encountered

#### Using AHKsocket as a network lib to discover sockets

#### Trying to replace AHK with python

### What I learned from all this

#### Network is horribly painful to code when inexperimented

#### Python is not good at all to deal with other applications

#### Travis is a pain to setup on projects using unsupported languages 
