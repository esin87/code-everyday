# 100 Days Of Code Log

### Day 0: April 6, 2021

**Today's Progress**: Busy day! Wrote a solution for Project Euler Problem 42. 

**Thoughts:** I've been working on the Project Euler problems for a while now, and really enjoy the mathematical challenges they pose. Problem 42 was a relatively straightforward one, in which you take an array of words, calculate whether each word is a triangle word, and return the count of all the words that are triangle words. I plan to refactor this problem and use the quadratic formula instead of manually calculating whether it's a triangle number!

**Link to work:** [Project Euler problem #42: Coded Triangle Numbers](https://github.com/esin87/project_euler/blob/main/041-050/p042.js)


### Day 1: April 7, 2021

**Today's Progress**: Another busy day of teaching. Worked on my solution for Project Euler Problem 43 this evening. 

**Thoughts:** I love the Project Euler challenges because I learn something new with each problem, or reinforce a pattern that I've used previously and refine it. To solve today's problem on Sub-string divisibility, I made use of an older recursive solution for generating all possible permutations of 0-9 pandigital numbers. I tried the naive, brute-force approach first of looping through all ten-digit numbers and checking if they were pandigital, but my code was hanging. In the end, my algorithm is not the most efficient, but runs in about 4-5 seconds, which is well under the 60-second rule for P.E. Learned about and made use of `console.time` to measure how long my function took to run on my machine. 

Planning to spend some time working on larger projects soon, but finding that the P.E. problems definitely deliver on that hit of instant gratification and bite-size learnings that make me feel programming momentum on busy days. 

**Link to work:** [Project Euler Problem #43: Sub-string Divisibility](https://github.com/esin87/project_euler/blob/main/041-050/p043.js)

### Day 2: April 8, 2021

**Today's Progress**: Reworked some CoffeeScript for a Slack-Hubot today, gave some feedback on code for a MERN app, and also completed Project Euler Problem 44. 

**Thoughts:** Felt a little bit all over the place today, but reminded of a few important topics. First, in the excitement of learning a new technology, don't forget the basics -- in frontend, making sure our components transpile down to good, semantic HTML is important. Second, test locally before deploying, even if you're copying and pasting parts of functionality, that in theory should work. Room for human error is always present. Third, get something working first, even if it's not pretty. Fulfill the requirements of the brief, then go back and refine. 

My solution to this last Project Euler problem is a good example of my last point. It's not the prettiest, and relies on prior knowledge that the first correct pair of numbers is the solution to exit the function early. Thinking about how I can go back and refactor without needing to first generate a ton of pentagonal numbers first. Will probably need to create the numbers dynamically in the form loop instead of generating them all and needing to look them up. Will also just need a way to check if the number is pentagonal for the sums and differences. 

**Link to work:** [Project Euler Problem #44: Pentagonal Numbers](https://github.com/esin87/project_euler/blob/main/041-050/p044.js)
