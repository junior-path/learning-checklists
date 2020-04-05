# From zero to Ruby on Rails

## What's this?

This list guides programming students on what they should learn and has a focus on Ruby and Ruby on Rails.

If you are just getting started with programming, why start with Rails and not C? Well, this checklist is for people who don't have the luxury of spending months and years studying all theory, or for people in a hurry to get to results, to get a job.

When in college, students will usually start with C for studying algorithms, practicing memory management and other fields. That configuration is very valuable as it imprints in the student's brain how to deal with bare topics that are very close to mathematics, without the abstractions that new and modern languages use to hide away that complexity. When students get out of college, they have deep knowledge on the basic of computer science (depending on the institution, of course).

For everyday's job in IT, though, rarely will someone need to deal with memory management or binary trees until you have reached a level close to seniority. Databases like Postgres will implement indexes using binary trees, and so you will not be in a hurry to learn how to implement them right away before using it. You won't need to memorize Quicksort before you can use Ruby's `sort` method.

The loss in basic computing science knowledge should be compensated with fast start in developing real systems that can be used by real customers. It is the student's responsibility to pick up on the computer science topics that were not covered in this guide later when some basic progress has been made.

## Who's this for?

This checklist is meant for people who are starting their career with a focus on Ruby on Rails and have not enrolled in a college course, nor have experience with programming, but need a guide on what to learn next. This include other technologies that are commonly used alongside Ruby on Rails, as well as ethics and productivity.

## How to progress on this checklist

Pick an item, then Google. In some case there will be links for resources.
Some items require basic understanding about concepts while others mention actual execution.

Try to follow the items in order. They're structured in a way so that you will acquire understanding in more cohesive manner.

It is fine not to follow the checklist items in order, though. Some people will need to learn HTML/CSS, while others will get a project and have to jump into Docker right away.

## Checklist 1: Basics

At this level, you're learning very general concepts about many different topics, without diving into any of them. You're trying to make sense of it all.

Start with some concepts:

- [ ] HTML: what's its purpose? Create an HTML file in your computer and show an image in that page.
- [ ] CSS: what's its purpose? Create a CSS stylesheet in an HTML page, and change some colors to get a basic understanding of how it's used.
- [ ] HTTP: What is HTTP? Why was it created? Where is it used? 
- [ ] HTTP: describe an HTTP request cycle (request, response, status codes, headers, body). [This article](https://blog.skylight.io/the-lifecycle-of-a-request/) is good and clear on this subject.
- [ ] Basics on how to use the Unix (Linux/Mac) terminal, how to list files, change and create directories.
- [ ] Know how to create a Ruby file in the terminal and execute it.
- [ ] JSON: understand what it is and memorize its format.

It's also important to look at some very basic data structures and algorithms.

- [ ] What is the purpose of data structures? List some data structures.
- [ ] What is a graph? What are some general problems in society that can be modeled as graphs?
- [ ] What is a binary search?

Continue with some concepts:

- [ ] OOP: Understand the concept of Object Oriented Programming and classes.
- [ ] Ruby: have seen syntax for functions (`def`), classes (`class`) and how to instance objects.
- [ ] Ruby: what is an array? What is a hash? What's the difference between the two?
- [ ] Understand what is Git.
- [ ] Understand what is Github.
- [ ] Understand what is a database.
- [ ] Explain what is a Ruby gem.

Then, it's important to understand the basic structure of a Ruby on Rails application. [This tutorial](https://guides.rubyonrails.org/getting_started.html) goes through some of the items below and is recommended.

- [ ] What is Ruby on Rails? Why was it created? Why is it used instead of just regular Ruby or HTML?
- [ ] Basics about Routes: what are `resources`, `root_path`, `rake routes`
- [ ] Basics about Controllers: what are the 7 actions? How are model instances loaded in controllers?
- [ ] Basics about Views: how are view files organized? Understand what is ERB. How is Ruby code injected inside views? What are helpers and how do you use them?
- [ ] Basics about Models: open `rails console` and list records from the database; create new records.
- [ ] What is `rails server`?
- [ ] What are Model Validations in Rails, and what's its basic syntax.

Beyond Rails:

- [ ] Be able to explain what is an API.
- [ ] Make sure you have cloned a Github repository.
- [ ] Understand the purpose of SQL.
- [ ] Postgres: what is a table? What are the columns in a table?
- [ ] What's the difference between some databases like Postgres, MySQL, SQLite and Redis.
- [ ] What is automated testing? What's unit tests? Acceptance tests? What's TDD and what's BDD?
- [ ] What's RSpec? What's Capybara?
- [ ] Write first RSpec test. [This tutorial](https://semaphoreci.com/community/tutorials/getting-started-with-rspec) is really good.

Sources:

- https://guides.rubyonrails.org

## Checklist 2: Beginner

At this point you know the basic concepts and how they fit together, although you don't know how to use them. You often ask for help and you're starting to put more effort into the actual commands needed to get things done.

You're also learning new concepts, although from a very high level. Meanwhile, you're getting deeper into some concepts from the previous level.

Let's study some of the main data structures:

- [ ] Stack
- [ ] Queue
- [ ] Binary tree

Now, back to Ruby.

- [ ] Ruby: what is the Enumerable module.
- [ ] Ruby: what are exceptions and how to use them? [This article](http://blog.honeybadger.io/a-beginner-s-guide-to-exceptions-in-ruby/) is a good start.
- [ ] Postgres: what are indexes? Why are they important? What are multi-column indexes?
- [ ] HTTP: what is REST? [Article](https://code.tutsplus.com/tutorials/a-beginners-guide-to-http-and-rest--net-16340).
- [ ] Understand the purpose of the Sidekiq gem.
- [ ] Understand the basics about message queues, what is it and why they are used.
- [ ] Understand why Docker exists and what problems it's trying to solve.
- [ ] Understand difference between RSpec and TestUnit gems.
- [ ] Understand RSpec's subject, let, hooks and exceptions. [This tutorial](https://semaphoreci.com/community/tutorials/rspec-subject-helpers-hooks-and-exception-handling) is pretty good.
- [ ] Have written automated tests in Rails, specifically Model tests and Capybara tests. [This ebook](https://semaphoreci.com/ebooks/rails-testing-handbook) has some good examples. You can ignore Cucumber for now.
- [ ] Understand what are test stubs, mocks and doubles. [This tutorial](https://semaphoreci.com/community/tutorials/rspec-subject-helpers-hooks-and-exception-handling) is a good start.

Continue on algorithms.

- [ ] Understand what is Asymptotic notation (example: `O(n)`) and why it's important.
- [ ] Solve: in an array from 1..20, remove even numbers, leaving odd numbers.
- [ ] Solve: in an array from 1..20, return a new array where each element is multiplied by itself (example: `[1, 2, 3, n..., 20]` becomes `[1, 4, 9, n^2..., 400]`).
- [ ] Ruby: what is the `map` function.
- [ ] Ruby: what is the `reduce` function.

## Checklist 3: Intermediary

At this level you're comfortable doing research and solving problems. You still need help with architectural decisions and you struggle a bit with some concepts, but you can accomplish tasks with confidence.

- [ ] Docker
- [ ] What are [P vs NP problems](https://en.wikipedia.org/wiki/P_versus_NP_problem).
- [ ] What are threads? What's Ruby GIL?

This is also a good moment to get introduced to some of the main [data structures](https://www.geeksforgeeks.org/data-structures/).

- [ ] Get deeper into Asymptotic notation, being able to analyze a function and come up with its complexity notation.
- [ ] Linked List
- [ ] Linked List vs Array
- [ ] Hash Maps
- [ ] Hash Tables
- [ ] Hash Functions
- [ ] Tree Traversal
- [ ] Binary Trees: includes algorithms like Binary Search Trees (BST), Self-Balancing Binary Search Tree, Breadth First Traversal (BFS) and Depth First Traversal (DFS).

It's also time to look deeper into Postgres.

- [ ] PG Indexes: B-Tree and sorting (default)
- [ ] PG Indexes: Hash
- [ ] PG Indexes: GiST (Generalized Search Tree)
- [ ] PG Indexes: GIN (Generalized Inverted Indexes)

## Checklist 4: Advanced

- [ ] CAP Theorem
- [ ] https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing
- [ ] http://slinkp.com/falsehoods-programmers-believe-about-apis.html
- [ ] https://github.com/kdeldycke/awesome-falsehood
- [ ] https://en.wikipedia.org/wiki/CAP_theorem

## Checklist 5: Expert

Once you're at this point, you will know what to study.
