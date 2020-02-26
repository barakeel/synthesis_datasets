This is the data accompanying the paper
Deep Reinforcement Learning for Synthesizing Functions in Higher-Order Logic.

## Synthesis problems and solutions

The ``combin_target`` and ``dioph_target`` contains the generated datasets.
In each directory, the files ``train_export`` and ``test_export`` gives you 
respectively the training and the testing set of problems.
Each problem is followed by one possible solution on the next line.

The other files in these directories contains the same data in a format easily 
readable from HOL4. 
To be able to re-use the datasets in the HOL4 format for combinators, one need 
to switch to the commit bcd916d1251cced25f45c90e316021d0fd8818e9 as the format 
for exporting terms was recently updated.

## TPTP problems

The TPTP problems for combinators are available in the ``TPTP/train/i`` and 
``TPTP/test/i`` directories.
