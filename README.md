# Leveraging Synthetic Data to Learn Video Stabilization Under Adverse Conditions


<img src='https://github.com/A-Kerim/Leveraging-Synthetic-Data-to-Learn-Video-Stabilization-Under-Adverse-Conditions/blob/0c8ce7dfbc86b32aa7dac9df40d2371fe85d9bd0/images/introduction.pdf'>
Our key idea is to use specially-designed synthetic data to train an affine transformation
matrix estimation CNN.

## Contact Authors
Abdulrahman Kerim, PhD Student, at Lancaster University, a.kerim@lancaster.ac.uk
Leandro Soriano Marcolino, Lecturer at Lancaster University, l.marcolino@lancaster.ac.uk

## Abstract
Video stabilization plays a central role to improve videos quality. However, despite
the substantial progress made by these methods, they were, mainly, tested under
standard weather and lighting conditions, and may perform poorly under adverse
conditions. In this paper, we propose a synthetic-aware adverse weather robust
algorithm for video stabilization that does not require real data and can be
trained only on synthetic data. We also present Silver, a novel rendering engine
to generate the required training data with an automatic ground-truth extraction
procedure. Our approach uses the specially generated synthetic data for training an
affine transformation matrix estimator avoiding the feature extraction issues faced by
current methods. Additionally, since no video stabilization datasets under adverse
conditions are available, we propose the novel VSAC105Real dataset for evaluation.
We compare our method to five state-of-the-art video stabilization algorithms using
two benchmarks. Our results show that current approaches perform poorly in at least
one weather condition, and, even training in a small dataset with synthetic data only,
we achieve the best performance in terms of stability average score, distortion score,
success rate, and average cropping ratio when considering all weather conditions.
Hence, our video stabilization model generalizes well on real-world videos and does
not require large-scale synthetic training data to converge.

## Acknowledgements
A. Kerim is supported by FST studenship, Lancaster University.