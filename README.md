# The Deep Comedy 2.0
Generate poetry in Dante’s style, using the Divine Comedy for 
training 

Tip: use of Transformers is recommended
* respect of endecasyllables is erratic
* the rhyme structure is problematic

## Syllabification
1. Syllables in poetry have little to do with grammatical syllables.
2. All verses in the Divine Comedy are perfectly formed.

See the article about the [Syllabification of the Divine Comedy](https://arxiv.org/abs/2010.13515);
(the syllabified source of the Comedy is available on github)

## GOALS:
* build a neural network for poetry syllabification, yelding a
syllabified version of the verse in input, e.g.
mi /ri/tro/vai /per /u/na /sel/va o/scu/ra
* exploit the previous algorithm to improve the well formedness
of generated verses;
* (optional) try to respect the caesura on the 5th or 7th syllable
(essential for metric purposes).

## Explainability
Look at syllabification as a form of explainability:
you claim your verse is well formed, so give me evidence by
telling me how you would split it into the expected number of
syllables.

The explanation must be learned contextually with the
solution (and should hopefully drive it).
