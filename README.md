# CPSC 312 Project

# Wordle 2.0!

Our project will be a version of Wordle with more visual flare! Specifically, completion of the puzzle, 
depending on the number of guesses taken, will display a different celebratory animation! 
Additionally, there will be no limits of how many wordles a player can complete each day! 🤡

This project is in fulfillment of the [CPSC 312 2024W1 project requirements](https://steven-wolfman.github.io/cpsc-312-website-2024W1/project.html).

## Team Members

Our team is:

+ Grace Gale (52524915): optional-awesome-nickname-2
+ Ivan Orozco Vasquez (29979267): Wazmo 🤼 
+ Kae Rene Boey (82279530): kay-othic
+ Kyle Webster (68017623): Mr. Lizard
+ Sophia Schwandt (33428384): optional-awesome-nickname-3

We call ourselves: Typeclass Clowns 🤡

## Acknowledgments

We surely built on the work of others! Here are resources and people we got support from:

+ A list of acknowledgments with a brief explanation of support received, e.g.:
  ChattGPT:
  - We used chatgpt to come up with our team nam

  Sources of Reference:
  - OG Wordle Game: https://www.nytimes.com/games/wordle/index.html
  - 6 letter words: https://www.litscape.com/words/length/6_letters/6_letter_words.html 

## Product Pitch

What's wrong with wordle:
- not flamboyant enough!
- 6 letters instead of 5, wordle has 6 letters, why are you guessing 5??? (wordle, clowns, rubric)
- daily limit thing

The product:
- better wordle!
- with celebratory animations for completion
- 'limited edition' animations (wordle burns and turns to ashes for halloween🔥, pie day!)
- no daily limits
- keep score (of streaks, guessing stats, leaderboard & regional leaderboard)
- online!

Be sure that this touches clearly on the [project requirements](https://steven-wolfman.github.io/cpsc-312-website-2024W1/project.html#project-requirements).


## Minimal Viable Project


Make clear:
+ how this builds meaningfully toward your product pitch above, without being nearly as much work,
- the final project envisions multiple variants of things (i.e. celebratory animations, dif types of leaderboard)

+ how it builds on the strength and power of the language, and
- input recognition needed (IO as learned in class recently)
- we evaluate letter by letter, so haskell treating strings as list of char makes it easier
- will definitely need high order functions and function composition 

+ how it leads naturally to learning and applying some new element of the language (including what that element is!)
- a GUI! (animation, colour, formatting displays etc)
- how to make something web-based





## Proof of Concept


Tell us:

+ what key element of your project the proof-of-concept focuses on
- algorithm to check which letters are right (?) based off user input [at min: check if letter is in word]
- outputs _ letter not in word, * if in word but not right place, letter itself if in right place
- outputs instructions and outputs

+ what makes that such an important element
- it's the backbone that makes wordle word
- no checking algorith = no winning = :((
- players need the feedback in order to continue playing
- its the core algorithm of wordle


+ how completing this gives you confidence that, with sufficient work, you could complete the full (minimal viable) project
- the algorithm is the core of the game, after this, we just need to make the target word more dynamic, UI more friendly, add animated flares
- UI stuff doesn't affect if the program runs, just aesthetics
- more flexibility with UI elements, algorithm needs to work

- target word will be hardcoded for now



Include links (likely even line-level links, which are easy to create in Github) throughout to critical pieces of
the code to make it easy for us to understand what you've accomplished and how it fulfills the requirements.

Also include instructions for us to test and run your code. (See our guidelines below.)

A good goal to aim for is the top rubric item from proposal grading:

> Fully functional proof-of-concept is easy to use and review, and it clearly demonstrates a key element necessary for the overall project.




### How to test and run the code: Haskell

Replace this section with instructions to us for how to test and run your code.

As it is currently set up, editing works best if you first `cd` into the `haskell` subdirectory and open VS Code on that directory (`code .`). There is a `Makefile` with some helpful aliases, but you can also just use `stack` as normal.

Note: We expect to be able to test your code by running `stack test`. Included among your tests should be some that demonstrate the core functionality of your code. (We will be running `make haskell-eval` from the project root.)

We should be able to further explore your code's functionality by running `stack ghci`, and you should instruct us on some interesting cases to try.

If you include instructions different from these, be **absolutely sure** that they will work well for us in whatever environment we run your code and that they will be as easy to use as the instructions above!



### How to test and run the code: Prolog

Replace this section with instructions to us for how to test and run your code.

We have set up a simple test file for you to extend using [Prolog Unit Testing](https://www.swi-prolog.org/pldoc/doc_for?object=section(%27packages/plunit.html%27)) library for testing. Included among your tests should be some that demonstrate the core functionality of your code. Please remove the example tests before you submit or you will lose marks. (We will be running `make prolog-eval` from the project root.)

In the `prolog` directory, you can run `make test` to run the unit tests. You can also load the test file into the swipl repl with `make test-repl` and in that repl you can run `run_tests.` to run those tests.

If you include instructions different from these, be **absolutely sure** that they will work well for us in whatever environment we run your code and that they will be as easy to use as the instructions above!
