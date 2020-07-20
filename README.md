# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Peer Code Review

### Getting Started
You'll be placed in groups, send your group a link to your github repo. To start reviewing someone's code
- Fork their repository
- Clone it to your local machine
- install all necessary dependencies (for example, if using node, run `npm i`)
- Open up a sharable document to put notes in (Like a google doc or [HackMD](https://hackmd.io/))
- Get their project running on your local machine.

## Why Code Review?

- Identify bugs, syntax and logical errors with fresh 👀
- Saves time! ⏰
- Helps verify that all requirements are fully implemented ✔️
- Flex your collaborative muscles 💪🏽
- Assure quality (i.e. Does the code adhere to the style guide? Is code repetitive? Can you create a more elegant solution?) 🧐

### Things to Consider when doing Peer review

Read [This article](https://mtlynch.io/human-code-reviews-1/) on the inter-personal aspect of doing code review.
* Label items that are more nit-picking: the convention is to prevace it with `nit:` _(things that would not prevent code from going into production like "naming could be cleaner")_
* Be gentle; this person spent time writing this code
* Recognise when something is personal taste versus structurally relevant
* Pick out a couple of places where the developer did well.

### Questions to ask

The main focus is to look for potential bugs and edge cases. After that, look at proper naming, clear organization, appropriate code complexity _(complex only when it needs to be)_, etc.
This is by no means an exhaustive list of questions to ask, but it should get you started

* Is it easy to understand?
* Is the style consistent? _(Is there consistency between usage of single-quotes vs. double quotes? Are all the functional components declared the same way?)_
* Are there any repetitive lines of code?
* How often did they commit? 
* Did their commit messages appropriately indicate what they worked on?
* Are there any TODO items? Have they been labeled?
* Is the organization of the code clear and intuitive? 
* Are the variable names clear and descriptive?
* Are there any places where the developer is trying to be clever? _(Is there abstraction that isn't being used or "optimizations" that add unnecessary complexity?)_
* Are the comments clear and useful? _(Comments should should say why you are doing something because what you are doing should be apparent in the code)_
