#AI CLASSICAL SEARCH ASSIGNMENT

This is an assignment in AI for comparing DNA sequences and calculating the score of comparison.
As this is implemented in Classical way I have used normal python.

It compares nitrogen bases at corresponding positions.

The sequences are string inputs which the user must enter.

Criteria for the score:
  match=+5
  mismatch=-4
  gap=-12

The functionality of the code:
  It first compares cleans the sequences then checks if they are valid
  Once that is done it first compares the sequences and calculates the score
  After this one of the sequences is complemented and the comparison is run again and score is once again calculated.
  Whichever score is higher that score is shown

Why compare with the complement?
  The reason for complementing a sequence is because DNA has a double helical structure with two parallel yet complemented sequences.
  DNA has 4 nitrogen bases Adenine, Guanine, Cytosine and Thymine. A(Adenine) is always paired with T(Thymine) via a hydrogen double bond and C(Cytosine)
  is always paired with G(Guanine) via a hydrogen triple bond.
  
  So when we compare the DNA from two different people we are taking one strand from each and compare.
  
  Lets say sequence from person A is AGTCAGTC and sequence from person B is TCAGTCAG.
  
  Now, when comparing both sequences we initially think they are different. Let us complement DNA of person A. 
  The complemented sequence is TCAGTCAG which is the same as the DNA of person B!
