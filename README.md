This is a jupyter notebook that shows an algorithm that finds words within algebraic sequences in text.

The idea for this project came from Eliyahu Rips' 1990s work on algebraic codes found in The Book of Genesis. Read the 'Bible Code' trilogy by Michael Drosnin if you are more interested. 
Essentially, correlated words and names were found spatially near each other through this tactic. (For example, 'Yitzhak Rabin' (frmr Israeli PM), 'assassination', and 'Yigal Amir' (Rabin's assassin) were found overlapping in one section of The Bible). T  

For a more concrete example, take the sentence 'Everyone poops, except for Pokemon'. We would approach this first by taking out all non-alpha characters.

everyonepoopsexceptforpokemon

From here, say we want to see the words are hidden within the algebraic sequence with stride X. So we want to find all the possible words for every other Xth character.
More concretely:

stride 2, first char:
eeynposxetopkmn
Here we see the word 'top'

stride 2, second char:
vroeopecpfroeo
Here we see the words 'ope', 'fro', and 'pec'


