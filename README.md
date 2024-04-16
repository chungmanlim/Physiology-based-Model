# Can a Computer Tell Differences between Vibrations?: Physiology-Based Computational Model for Perceptual Dissimilarity Prediction

## Paper
Lim, C., & Park, G. (2023, April). Can a computer tell differences between vibrations?: Physiology-based computational model for perceptual dissimilarity prediction. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (pp. 1-15).

LINK: https://dl.acm.org/doi/abs/10.1145/3544548.3580686

## [File] PM_tester.exe
PM execution file. You should add your vibration set with '.txt' format into "./Vibration" before running this file. As a result of the running, a predicted perceptual dissimilarity matrix, 'PM_Prediction.txt', will be generated.
				
## [Folder] Vibration
A vibration set for the test. For testing, we provide 8 vibration patterns.
1. All vibrations that you want to predict must be in the path of "./Vibration".
2. All vibrations' sampling rate must be 10kHz.
3. All vibrations' durations in the vibration pattern set must be the same. If they are different, please apply zero-padding to shorter patterns.

## Citation
@inproceedings{lim2023can,
  title={Can a computer tell differences between vibrations?: Physiology-based computational model for perceptual dissimilarity prediction},
  author={Lim, Chungman and Park, Gunhyuk},
  booktitle={Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems},
  pages={1--15},
  year={2023}
}
