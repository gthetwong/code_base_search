# Suffix Tree Based Code Base Search

In this mini-project we are going to build a code base search engine with
[suffix trees](http://en.wikipedia.org/wiki/Suffix_tree), [nodejs express
framework](http://expressjs.com/), and either backbonejs or angularjs
for your mvc framework; if you prefer to not use a frontend mvc, that's
fine too.

When you've finished, you'll be able to run:
`node server.js some/directory/to/index/in/a/suffix/tree` to load a code
base into a suffix tree.

You'll then be able to search your tree with:
`http://localhost:3000/search/substring_in_the_codebase`

Basically:
### Trie Hard, with a Vengeance.

### Before you write a single line of code: 

#### Understand suffix trees

* Why suffix trees exist
* What kinds of problems do suffix trees solve
* How do suffix trees work 
* How can we use a suffix tree to pull in the files of a code base to be
  able to search for matches in the code base?

#### Reading & Viewing

* [Suffix Tree wikipedia
  article](http://en.wikipedia.org/wiki/Suffix_tree)
* [A really good slide deck about suffix
  trees](http://www.cs.cmu.edu/~ckingsf/bioinfo-lectures/suffixtrees.pdf)
* [A video lesson with notes about suffix trees from the MIT Advanced Data
Structures Course](http://courses.csail.mit.edu/6.851/spring12/lectures/L16.html)

#### Set up your environment

* Fork this project under your github account
* Clone to your machine
* Run `npm install` from the root directory where you cloned
This will install the dependencies, which are specified in
`package.json`.
* Run `npm install jasmine-node -g`
This will install jasmine, so you may run the specs in the terminal.

#### Run the specs

* As usual, start by running the specs in
`spec/javascripts/suffix_tree_spec.js`.

* Some specs will pass, most will fail.

* The specs along with your *understanding* of suffix trees and the
  problem you are solving, will help you through the solution.

### One more time:

The key is to understand the problem and how suffix trees solve it,
before writing a single line of code. Make sure to draw diagrams of the
state changes as a suffix tree gets filled with suffixes. Understand the
differences in how new suffixes are added to the suffix tree in various
cases. Really, one more time, draw the state changes.
