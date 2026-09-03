# YOLO assets reference

I checked current open-source YOLO dataset examples. The common layout is:

```text
dataset/
├── images/
│   ├── train/
│   └── val/
├── labels/
│   ├── train/
│   └── val/
└── data.yaml
```

Ultralytics documents this structure and the matching normalized label format (`class x_center y_center width height`).

References:
- Ultralytics YOLO dataset guidance: https://github.com/ultralytics/skills/blob/main/skills/yolo-datasets/SKILL.md
- Ultralytics custom-data tutorial: https://github.com/ultralytics/ultralytics/blob/main/docs/en/yolov5/tutorials/train-custom-data.md

I am not copying third-party image files into this repository unless their license explicitly permits redistribution. This avoids putting unlicensed assets into the repo.
