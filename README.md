# Multi-instrument multi-joint annotation for EndoVis'15 instrument subchallenge dataset
This is our new multi-joint annotation for [EndoVis'15](https://endovissub-instrument.grand-challenge.org/) MICCAI Challenge dataset, which can be used for multi-instrument pose estimation.

## Citation
If you use the annotation in your research, please use the following BibTeX entry.
```
@article{du2018articulated,
  title={Articulated multi-instrument 2-D pose estimation using fully convolutional networks},
  author={Du, Xiaofei and Kurmann, Thomas and Chang, Ping-Lin and Allan, Maximilian and Ourselin, Sebastien and Sznitman, Raphael and Kelly, John D and Stoyanov, Danail},
  journal={IEEE transactions on medical imaging},
  volume={37},
  number={5},
  pages={1276--1287},
  year={2018},
  publisher={IEEE}
}
```

## Data 
After downloading the EndoVis'15 dataset, the dataset is separated into training (in *Tracking_Robotic_Training* folder) and test data (in *Tracking_Robotic_Testing* folder). The training data includes four 45 seconds ex vivo video sequences of interventions, the test set is composed of 15 seconds additional video sequences for each of the training sequence, and two additional 1 minute recorded interventions. The frame resolution is 720 × 576 pixels. Frames examples are shown below:

@@ -24,21 +39,6 @@ The tool numbering in the annotation files helps distinguish between the scissor
- Tool3: Right Scissor
- Tool4: Left Scissor

## Citation
If you use the annotation in your research, please use the following BibTeX entry.
```
@article{du2018articulated,
  title={Articulated multi-instrument 2-D pose estimation using fully convolutional networks},
  author={Du, Xiaofei and Kurmann, Thomas and Chang, Ping-Lin and Allan, Maximilian and Ourselin, Sebastien and Sznitman, Raphael and Kelly, John D and Stoyanov, Danail},
  journal={IEEE transactions on medical imaging},
  volume={37},
  number={5},
  pages={1276--1287},
  year={2018},
  publisher={IEEE}
}
```

## Contact
If you have any queries, please contact me.
