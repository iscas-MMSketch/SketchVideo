# SketchVideo
Dataset accompanying the paper **Fine-grained video retrieval with scene sketches**.

### Dataset Summary

Our **Scene-level Sketch-Video Dataset (SketchVideo)** is proposed for fine-grained scene-level sketch-video research like sketch-based video retrieval and synthesis. SketchVideo contains 1,126 video clips collected from YouTube, and 6,713 corresponding sketches forming clip-level and frame-level representations, drawn by 30 amateur painters with diverse personal painting skills and styles. All strokes in the sketches are annotated with instance-level labels. 

**Download**: [SketchVideo]()

### Dataset Structure
The sketch-video pairs are provided in three folders (video, sketch, and sketch JSON files), and each pair contains one clip-level storyboard sketch (which can contain instances in different video frames) and several keyframe sketches (each of which contains instances in one video frame).
```
├── video
├── sketch		          
└── sketch_json  (contains stroke information)
```

## Citation

```
@article{zuo2023fine,
  title={Fine-grained video retrieval with scene sketches},
  author={Zuo, Ran and Deng, Xiaoming and Chen, Keqi and Zhang, Zhengming and Lai, Yu-Kun and Liu, Fang and Ma, Cuixia and Wang, Hao and Liu, Yong-Jin and Wang, Hongan},
  journal={IEEE Transactions on Image Processing},
  volume={32},
  pages={3136--3149},
  year={2023},
  publisher={IEEE}
}
