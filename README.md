## IP102: A Large-Scale Benchmark Dataset for Insect Pest Recognition

This work was accepted by CVPR 2019 as a **oral** [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wu_IP102_A_Large-Scale_Benchmark_Dataset_for_Insect_Pest_Recognition_CVPR_2019_paper.pdf).

The IP102 datset contains more than $75,000$ images belongs to $102$ categories. A natural long-tailed distribution presents on it. In addition, we annotate $19,000$ images with bounding boxes for object detection. The IP102 has a hierarchical taxonomy and the insect pests which mainly affect one specific agricultural product are grouped into the same upper-level category.

### File Structure

The folders are arranged like this:
```
IP102
├──Classification
|	├── Images.tar
|	├── train.txt
|	├── val.txt
|	├── test.txt
├──Detection
|	├── VOC2007
|	│   ├── Annotations.tar
|	│   ├── ImageSets/Main
|	│   │   ├── trainval.txt
|	│   │   ├── test.txt
|	│   ├── JPEGImages.tar
```

The index and name of each insect pest sub-class in the IP102 dataset can be found in [supplementary material](./supplements_cvpr19_ip102.pdf) or [classes.txt](./classes.txt).


### Additional Information
If you find the IP102 helpful, please cite it as
```
@inproceedings{Wu2019Insect,
  title={IP102: A Large-Scale Benchmark Dataset for Insect Pest Recognition},
  author={Xiaoping Wu and Chi Zhan and Yukun Lai and Ming-Ming Cheng and Jufeng Yang},
  booktitle={IEEE CVPR},
  pages={8787--8796},
  year={2019},
}
```

ATTN: This dataset is free for academic usage. For other purposes, please contact Xiaoping Wu (xpwu95@163.com).
