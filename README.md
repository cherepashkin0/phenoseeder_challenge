# phenoseeder_challenge
Supporting files, scripts, metrics for wheat seed 3d phenotyping data challenge on evalai. 

# Link to the data will be published soon
[link_to_data](https://b2share.fz-juelich.de/records/b716920e6c4342879ddb46fbcfbafe17)

# Data structure
```
seed_dataset
├── raw_3d_station_images
│   ├── train
│   │   └── 0000
│   │       ├── rotation_000.tif
│   │       ├── rotation_010.tif
│   │       ├── ...
│   │       └── rotation_350.tif
│   └── test
│       └── 0003
│           ├── rotation_000.tif
│           ├── rotation_120.tif
│           └── rotation_240.tif
├── raw_gt_point_clouds
│   └── train
│       └── 0000_Surface.ply
├── preprocessed_3d_station_images
│   ├── train
│   │   └── 0000
│   │       ├── rotation_000.tif
│   │       ├── rotation_010.tif
│   │       ├── ...
│   │       └── rotation_350.tif
│   ├── test
│   │   └── 0003
│   │       ├── rotation_000.tif
│   │       ├── rotation_120.tif
│   │       └── rotation_240.tif   
│   └── preprocessed_gt_point_clouds
│       └── train
│           ├── 0000
│           ├── rotation_000.ply
│           ├── rotation_010.ply
│           ├── ...
│           └── rotation_350.ply          
├── 2d_station_images
│   ├── train
│   │   └── 0000_2D.png
│   └── test
│       └── 0003_2D.png
└── projection_matrices
    ├── train
    │   └── 0000_ProjectionMatrices.txt
    └── test
        └── 0003_ProjectionMatrices.txt
```
