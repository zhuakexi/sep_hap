# sep_hap
transform imputed .pairs file to phase resolved .pairs file

in short

|readID |chr1 | pos1 | chr2 | pos2 | strand1 | strand2 | phase0 | phase1 | phase_prob00 |phase_prob01| phase_prob10 | phase_prob11 |
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|. | chr1| 590424 | chr1 | 47666673 | +  | + | . | . | 0.008 | 0.025 | 0.005 | 0.963 |0.025  | 0.005 |  0.963|

will be transformed to

|readID |chr1 | pos1 | chr2 | pos2 | strand1 | strand2 | phase0 | phase1 |
|-|-|-|-|-|-|-|-|-|
|. | chr1| 590424 | chr1 | 47666673 | +  | + | 1 | 1 |

for phase_prob1 is biggest among four.