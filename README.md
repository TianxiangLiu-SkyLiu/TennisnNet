# TennisnNet: A Multi-Granularity Video Dataset for Broadcast Tennis Competition Understanding

<img src='pics/TennisNet.png'/>

## Statistics
<center>

|         2    | Clay Court   |  2          | Fine-tuned | Mean Class ACC | Top-1 ACC | Train-features            | Val-Features            | Feature-size per inst. |
|        2     |--------------|-------------|------------|----------------|-----------|---------------------------|-------------------------|------------------------|
| BN-Inception | BN-Inception | ImageNet    | -          | -              | -         | [Gym99-train-bninception] | [Gym99-val-bninception] | 12 x 1024 x 1 x 1      |
| ResNet50     | ResNet50     | ImageNet    | -          | -              | -         | [Gym99-train-r50]         | [Gym99-val-r50]         | 12 x 2048 x 1 x 1      |
| TSN          | BN-Inception | ImageNet    | Gym99      | 61.4           | 74.8      | [Gym99-train-tsn]         | [Gym99-val-tsn]         | 12 x 1024 x 1 x 1      |
| I3D          | ResNet50     | ImageNet    | Gym99      | 63.2           | 74.8      | [Gym99-train-i3d-imnet]   | [Gym99-val-i3d-imnet]   | 12 x 2048 x 1 x 1 x 1  |
| I3D          | ResNet50     | Kinetics    | Gym99      | 64.4           | 75.6      | [Gym99-train-i3d-kin]     | [Gym99-val-i3d-kin]     | 12 x 2048 x 1 x 1 x 1  |
</center>

## License

The annotations, metadata, label definitions, and official train/validation/test splits in this repository are licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).

The source code and utility scripts in the tools directory are licensed under the MIT License.

This repository does not host, redistribute, or license the original video files. All original videos remain the property of their respective copyright holders. Users are responsible for accessing the videos from the original platforms in accordance with their terms of service.
