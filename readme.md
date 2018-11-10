# Bach Chorale Generator

The end goal is to have an online Bach Chorale generator powered by AI/machine learning but supplemented with music theory knowledge/analysis.

## Analysis Ideas

* Defining a fitness function
* Interval analysis to match music theory rules
  * No consecutive fifths/octaves
  * Avoid parallel motion
* What if I transposed all chorales to C major?
  * Chordal analysis
    * Which chords appear most often?
    * Are less-common chords preceded/followed by certain other chords?
    * Construct a Markov chain for chord progressions