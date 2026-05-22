## Hi, I'm Ariel.
I'm currently finishing a Master of IT.

**Featured Projects**<br>
[Computer Vision Sports Analytics (badminton stroke classifier)](https://github.com/Kira-Le/badminton_stroke_classification) - Extends the state-of-the-art [BST](https://github.com/Va6lue/BST-Badminton-Stroke-type-Transformer) CV + time-series architecture, recording new top benchmarks on the published [ShuttleSet](https://github.com/wywyWang/CoachAI-Projects/tree/main/ShuttleSet) evaluation set.
 - Part of a group-project repo (currently WIP). The src/bst_refactor/ subtree is my contribution, covering model build and data pipeline.
 - Currently in build: a new model layer to overcome the feature signal ceiling, adding RGB input from a fine-tuned [X3D-S](https://research.facebook.com/publications/x3d-expanding-architectures-for-efficient-video-recognition/) backbone.

[Object Detection (Australian Ferns)](https://github.com/ahalp90/fern-detection-comparison) - Comparative study of two object detection models on a hand-annotated dataset.
- Dataset scraped from iNaturalist and annotated in CVAT; splits stratified by per-class annotation density. The pipeline is reproducible from the source CSVs.
- Compares YOLOv8m (CNN-based detector) with RetinaNet on a MiT-b0 backbone (hybrid CNN+transformer).
- Explainable-AI tools (GradCAM, EigenCAM) are used to understand classification confusion, introduce hard negative images, validate improvements in feature mapping.
- Each architecture was refined across a series of hyperparameter grids. 

[LSTM Market Classifier](https://github.com/ahalp90/lstm-market-classifier) - Time-series inference model and data pipeline.
 - Analytical write-up, Python scraper modules and detailed notebook.
 - Most of the implementation code is private, but shoot me a message if you're working on something similar and want to talk about it.

Other projects include a [Java Chess GUI](https://github.com/ahalp90/Chess-GUI), [Java Ordering System](https://github.com/ahalp90/Restaurant-Ordering-System) and [Relational Database with Custom Views](https://github.com/ahalp90/Relational-Database-SQL-MovieDirect).
