# Izarra Villareal CS 81 Module 7 Assignment 7A: Code Review

## What part of the code was most confusing and why?
# The most confusing part of the code for me is the "index % frames.length" because it appears to be a modulus operation, but I still do not fully understand how that works exactly. If the index is 0, how can you divide 0 by the length of the frames array?

## How does the animation help visualize asynchronous behavior?
# The animation helps visualize asynchronous behavior because the page does not reload in the browser to make the animation function. The animation functions entirely asynchronously in the background without having to reload the page every time it changes just by using the setInterval function.

## What did you change or improve, and what effect did it have?
# I changed the initial cycleCount to 5 instead of 0 to shorten the entire load time required for the animation cycles to complete.