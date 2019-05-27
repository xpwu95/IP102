## IP102: A Large-Scale Benchmark Dataset for Insect Pest Recognition

This work was accepted by CVPR 2019 as a **oral** paper.

The IP102 datset contains more than $75,000$ images belongs to $102$ categories. A natural long-tailed distribution presents on it. In addition, we annotate $19,000$ images with bounding boxes for object detection. The IP102 has a hierarchical taxonomy and the insect pests which mainly affect one specific agricultural product are grouped into the same upper-level category.

### File Structure

The IP102 dataset can be downloaded from [Baidu](https://pan.baidu.com/s/1I5NKaa7B8lmB9bqsz4tGZA) (pw: meg3) or [Google](https://drive.google.com/open?id=1dnw8Z4XIADWBdLX0ecokRwqVmRKJa-QP).
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

The index and name of each insect pest sub-class in the IP102 dataset can be found in [supplementary material](./supplements_cvpr19_ip102.pdf).


### Additional Information
If you find the IP102 helpful, please cite it as
```
@inproceedings{Wu2019Insect,
  title={IP102: A Large-Scale Benchmark Dataset for Insect Pest Recognition},
  author={Xiaoping Wu and Chi Zhan and Yukun Lai and Ming-Ming Cheng and Jufeng Yang},
  booktitle={IEEE CVPR},
  year={2019},
}
```

ATTN: This dataset is free for academic usage. For other purposes, please contact Xiaoping Wu (xpwu95@163.com).
