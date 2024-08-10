
# AI Classical Search Assignment: DNA Sequence Comparison

## Project Overview

This assignment focuses on comparing DNA sequences using a classical approach implemented in Python. The system compares nitrogen bases at corresponding positions and calculates a comparison score based on predefined criteria.

## Tools and Language

- **Python**: Used for implementing the classical search algorithm for DNA sequence comparison.

## Input and Criteria

- **Sequences**: String inputs representing DNA sequences, entered by the user.
- **Gap Representation**: Gaps can be denoted by '_', '-', or ' '.
- **Scoring Criteria**:
  - Match: +5
  - Mismatch: -4
  - Gap: -12

## Functionality

1. **Sequence Cleaning and Validation**: The input sequences are first cleaned and validated to ensure correctness.
2. **Comparison and Scoring**: 
   - The sequences are compared base by base, and the score is calculated.
   - The comparison is then repeated with one of the sequences complemented, and a new score is calculated.
   - The higher of the two scores is selected and displayed.

## Why Compare with the Complement?

DNA's double-helical structure consists of two parallel but complementary strands. DNA is composed of four nitrogen bases: Adenine (A), Guanine (G), Cytosine (C), and Thymine (T). A is always paired with T via a hydrogen double bond, and C is paired with G via a hydrogen triple bond.

When comparing DNA sequences from two different individuals, you are essentially comparing one strand from each. For example:

- Sequence from Person A: `AGTCAGTC`
- Sequence from Person B: `TCAGTCAG`

At first glance, these sequences appear different. However, when you complement Person A's sequence, it becomes `TCAGTCAG`, which matches Person B's sequence. This demonstrates the importance of comparing both the original and complemented sequences.

## Conclusion

This project showcases a classical AI approach to DNA sequence comparison, leveraging the biological nature of DNA to ensure accurate and meaningful results. The implementation demonstrates how computational techniques can be applied to biological problems, offering insights into genetic similarities.
