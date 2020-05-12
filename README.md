# Convolutional Neural Network to classify toy DNA sequences

### Description
In this project I first generate a random nucleotide sequence. Based on this sequence, I create  "variants" by introducing controlled random variation within. I next introduce controlled random "mutations" for a subset of the list. 
As such a binary classification problem with positives, i.e. the sequences carrying the mutations and initial variations, and negatives, i.e the sequences carrying only the variations, is created for which a simple CNN is trained to distinguish between these two subsets of sequences.

### TO DO
- Finish evaluation
- Tidy up
- Try varying flanking region length with sequence cropping
