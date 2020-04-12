# Knitting and Crochet Tracker

I want to make a tiny baby web app in order to keep track of my knitting projects. I'm imagining something on the row-level, where you have an easy way to program a knitting pattern, and where it will keep track of your project for you.

e.g. I am imagining a small Flask situation where really there is just:
(1) A home page
(2) Templates (recipes) and projects (instances)
    => Maybe GET requests for both
    => We don't even need users, just bookmark the page to come back to it
(3) Maybe an easy way to convert something to a recipe?
    => Like for instance: A conventional knitting parser that parses comma delimited knitting instructions
    => I also just want a pattern designer: e.g. 'insert 2 length rib here, insert cable here, etc.' Knitting patterns as chunks of data! Modularize knitting patterns!
    => This is secondary, I think any reasonable input templating system is ok for this.
        => But definitely should be modular and loopy. Like have a concept of a 'chunk' that you can rep x n
        => I like the idea of patterns as recursive data structures?