theme: Fira, 5
autoscale: true

![fit](media/TIY-Logo-500px-white.png)

---

# About Me

---

![fit](media/TIY-Logo-500px-white.png)

^ Back End Instructor at The Iron Yard

---

![fit](media/riley.png)

^ I have promised my girlfriend that I would include a photo of our dog Riley in each presentation I do.

^ I am the Backend Instructor here at The Iron Yard.

---

# telephony

![fit](media/switchboard-operator.jpg)

---

# space

![fit](media/BMRST.png)

^ Worked in the aerospace industry on command-destruct systems for rocket launches

---

# signage

![fit](media/Real-Digital-Media-Rave-Cinemas-Digital-1.jpg)

^ Built digital signage systems using Rails, Content Distribution Systems, and a custom Linux OS for embedded devices

---

# Tampa Ruby

![fit](media/tampa-rb.png)

---

![fit](media/ruby-for-the-newbie.png)

---

# What is Ruby?

^ Ruby is a programming language

---

## “Programming Language”

^ A programming language is a formal constructed language designed to communicate instructions to a machine, particularly a computer.

^ Programming languages can be used to create programs to control the behavior of a machine or to express algorithms.

---

![fit](media/compiler-virtual-machine.png)

^ Modern "programming language" generally refers to higher-level human readable code as opposed to lower level "machine language" instructions your computer hardware understands.

---

![fit](media/i-heard-you-like-programming-languages.png)

^ Programming languages are basically written in other programming languages.

^ Which might beg the question, “which came first, the chicken or the egg?”

---

![fit](media/first-program.png)

^ This is generally considered to be the first computer program ever written.

^ Anyone guess when this was written?
^ Around 1840 (that’s about 175 years ago).

^ Charles Babbage gives a lecture in Italy, 1840 about his theoretical computation machine, the Analytical Engine, written up in French by an Italian engineer.

---

![fit](media/ada-lovelace.gif)

^ Eventually Ada Lovelace is commissioned to translate it to English. She augments it with her own notes, the last of which, Note G includes an algorithm for the Analytical Engine to compute Bernoulli numbers.

---

![fit](media/analytic-engine.jpg)

^ It is considered the first algorithm ever written for implementation on a computer.

^ Ada made the conceptual leap that the Analytical Engine could be used to solve problems of any complexity.* This photo is of a recreation, at the time the machine what hypothetical, and had yet to be constructed.

^ * She was only 27.

---

![fit](media/punch-card.jpg)

^ The first "modern" programming languages, like Fortran were punched into cards.

---

![fit](media/cards.jpg)

---

![fit](media/card-machine.jpg)

^ Nowadays we use text editors and IDEs to edit code.

^ Not boxes full of punched cards.

---

![fit](media/laptop.jpg)

^ Now we write code on these.

---

![fit](media/matz.jpg)

^ Yukihiro Matsumoto
^ first released Ruby in December of 1995.

^ "Programmers often feel joy when they can concentrate on the creative side of programming. So Ruby is designed to make programmers happy."

---

# MINISWAN

^ Unofficial Ruby community Motto

^ Matz is nice, and so we are nice.

---

## Real World Ruby

^ Before we get into the details of programming in Ruby, what are some things you can do it Ruby?

---

![fit](media/rails.png)

^ Websites, with Ruby on Rails. Biggest use case, very popular choice

---

![fit](media/basecamp.jpg)

^ Rails was created while building Basecamp by DHH.

---

![fit](media/hulu.jpg)

---

![fit](media/goodreads.jpg)

---

![fit](media/airbnb.jpg)

---

![fit](media/kickstarter.jpg)

---

![fit](media/urban-dictionary.png)

---

![fit](media/funny-or-die.jpg)

---

![fit](media/twitter.jpg)

---

![fit](media/groupon.jpg)

---

![fit](media/living-social.jpg)

---

![fit](media/imgur.png)

---

![fit](media/github.tiff)

---

# Mobile & Native Applications

---

![fit](media/rubymotion.png)

---

![fit](media/shoes.jpg)

^ fun project by kind of a toy

---

![fit](media/qt.jpg)

^ Ruby bindings Qt, Wx Widgets, GTK

^ popular cross-platform desktop GUI libraries, Windows, Linux, Mac

---

# Sysadmin

^ Systems administration
^ general scripting, XML,  CSV Parsing, FTP downloads

---

# DEVOPS

^ a portmanteau of "development" and "operations"

---

![fit](media/chef.png)

---

# Robots

---

![fit](media/artoo.png)

^ Artoo, Arduino, Rasberry Pi, Drone / Quadcopters

---

![fit](media/sphero.png)

---

# 3D Modeling & Visualization

---

![fit](media/sketchup.jpg)

^ Sketchup, popular tool, Acquired by Google, Scripting API in Ruby

---

# Syntax

---

```ruby

2 + 2

```

---

```ruby

2 + 2 # => 4

```

---

```ruby

# This is a comment

```

^ not a hashtag

^ Ruby ignores anything on a line after the #

---

```ruby
x = 5
```

^ assignment to a variable

---

```ruby
x * 2 # => 10
```

^ variables can be used in statements

---

```ruby
s = "This is a string of characters."
```

^ between the quotes is a “string of characters”

---

```ruby
s.upcase # => "THIS IS A STRING OF CHARACTERS."
```

---

```ruby
def hello
  puts "Hello, World!"
end
```

^ this defines a method called hello.

^ everything between the def and the end are stored a procedure with the name “hello” and can be called later for execution

---

```ruby
hello
> "Hello, World!"
```

^ printing, “Hello, World!”

---

```ruby
def greet(name)
  "Hello, " + name + "."
end

greet "Jason" # => "Hello, Jason."
```

^ define a method that takes an argument

---

```ruby
3.times do
  puts greet("Jason")
end
```

^ some methods use a special kind of argument called a block

^ Parenthesis are not always optional

---

![fit](media/zen.gif)

---

# OOP
## Object oriented Programming

> Ruby is an object oriented language.

> Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which are data structures that contain data, in the form of fields, often known as attributes; and code, in the form of procedures, often known as methods.

---

![fit](media/animal.png)

---

![fit](media/animals.png)

^ The class is like a blue print, we can create instances of it, that hold attributes, and references back to the method on the class.

---

![fit](media/animals-code.png)

^ Explain the class

---

# Hands on

---

# Let's Code!

## http://repl.it

^ DO THE CODE!

---

![fit](media/math.jpg)

---

^ Feeling like this?

^ Take a short break to rest.

---

![fit](media/binary.png)

---

![fit](media/binary-search-animated.gif)

---

![fit](media/try-ruby.jpg)

^ Where to go from here?

---

# @GavinStark

# @ambethia

---

![fit](media/atom.png)

---

![fit](media/terminal.png)

---

![fit](media/windows-cmd.png)

---

### http://learnrubythehardway.org/book/

---

### http://cli.learncodethehardway.org/book/

---

![fit](media/learn-to-program.png)

---

# Thank You

---
