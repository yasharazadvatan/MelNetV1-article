# MelNetV1
MelNet: A Fast and Accurate Deep Learning Algorithm for Object
Detection.

# Dataset
This model is trained on KITTI dataset.


# How to Use

## 1. For detection purposes
1. Download the checkpoint from the link below:

   https://drive.google.com/file/d/1dhrZeWM_ZzyxyDArC_jniGVSDWTxjfZc/view?usp=sharing
   
2. Run the codes from MelNet-inference.ipynb in Jupyter Notebook.
## 2. For training on custom dataset
1. This codes load the dataset in YOLO format. You can see an annotation example in './dataset/valid_example/labels' folder.
2. If you have your own custom dataset with different annotation system, then you can train it by running thecodes in MelNet.ipynb in jupyter notebook. You can change the codes for your purposes to load the dataset.

# Article
Access my article from the link below:

    https://doi.org/10.48550/arXiv.2401.17972

# Citation
Please cite as:

    @INPROCEEDINGS{
      Azadvatan2024arXiv,
      author={Azadvatan, Yashar and Kurt, Murat},
      title = {MelNet: A Real-Time Deep Learning Algorithm for Object Detection},
      journal = {arXiv preprint arXiv:2401.17972},
      pages = {arXiv:2401.17972},
      year = {2024},
      month = jan,
      eid = {arXiv:2401.17972},
      doi = {10.48550/arXiv.2401.17972},
      url = {https://doi.org/10.48550/arXiv.2401.17972}, 
      archivePrefix = {arXiv},
      eprint = {2401.17972}
    }
