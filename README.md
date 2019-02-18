# Protein Sequence Encoding

The python script to encode protein sequences using different encoding methods.

# Requirements

* Python 2 or 3
    - json
    - argparse

# Usage

./SequenceEncoding.py -seq="XXXXXX" [options]

positional arguments:

    seq                   The protein sequence to be encoded.

optional arguments:

    -h, --help            show this help message and exit
      
    --encoding_type ENCODING_TYPE      
                          The encoding type. [One_hot, One_hot_6_bit,
                               Binary_5_bit, Hydrophobicity_matrix,
                               Meiler_parameters, Acthely_factors, PAM250, BLOSUM62,
                               Miyazawa_energies, Micheletti_potentials, AESNN3,
                               ANN4D, ProtVec]. 
                          Default: One_hot.
                        
    --overlap             The word extraction strategy for ProtVec encoding: overlap.
                        
    --non-overlap         The word extraction strategy for ProtVec encoding: non-overlap.

# Reference

Xiaoyang Jing, Qiwen Dong, Daocheng Hong, Ruqian Lu. Amino acid encoding methods for protein sequence: a comprehensive review and assessment. Submitted, 2019.