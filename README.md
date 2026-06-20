# 2-Hourglass-Problem
A brute-force solution solver for the 2 Hourglass Problem, wherein you must time exactly N minutes given 2 hourglasses of B minutes and C minutes.


## Rules of thhe 2 Hourglass Problem
  * You start with two hourglasses of times B and C minutes, each with no sand flowing.
  * Time starts as soon as you flip an hourglass.
  * You may reflip an hourglass anytime an hourglass empties itself into one of its cavities.
    * This means that with an hourglass of 5 minutes and an hourglass of 7 minutes, you could start both hourglasses at the same time and flip the 7 minute hourglass after the 5 minute hourglass finishes, leaving you with a 2 minute timer. At the same time, you may flip the 5 minute hourglass, and, after 2 minutes, be left with a 3 minute timer.
  * Hourglasses may not be paused, only flipped.
  * You have no way of keeping track of time aside from the completion of an hourglass.
