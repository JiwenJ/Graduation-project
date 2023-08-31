## <div align="center"> Graduation Project</div>
 
#### Title: Multi-objective detection and instance segmentation of shield tunnel diseases based on deep learning
We utilize yolov5-7.0 to perform the object detection and instance segmentation tasks for shield tunnel diseases, for example, cracks, damages, and seepage.

<div align="center">
  <img width="20%" src="https://raw.githubusercontent.com/JiwenJ/Graduation-project/main/doc/images/crack.png">
  <img width="20%" src="https://raw.githubusercontent.com/JiwenJ/Graduation-project/main/doc/images/damage.png">
  <img width="20%" src="https://raw.githubusercontent.com/JiwenJ/Graduation-project/main/doc/images/seepage.png">
</div>





## <div align="center">Documentation</div>

<details open>
<summary>Install</summary>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone https://github.com/JiwenJ/Graduation-project.git  # clone
cd yolov5
pip install -r requirements.txt  # install
```

</details>

<details open>
<summary>Dataset preparation</summary>
dd

</details>


<details open>
<summary>Train from scratch</summary>


</details>

<details open>
<summary>Train with transfer learning</summary>


</details>


<details open>
<summary>Inference</summary>


</details>


<details open>
<summary>Weights</summary>


According to our experiments, we conclude the object detecttion results in the following tables:
<div class="center" align="center">
  
|编号|加入注意力机制|修改特征金字塔|修改损失函数|mAP@0.5|mAP@0.5:0.95|权重下载|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1|&cross;|&cross;|&cross;|72.5|43.1|[[Google Drive]](https://drive.google.com/drive/folders/19fuBpVvFBI8lmgbjvfALcimQ1omT0YXi?usp=drive_link)|
|2|&check;|&cross;|&cross;|71.4|35.3|[[Google Drive]](https://drive.google.com/drive/folders/19fuBpVvFBI8lmgbjvfALcimQ1omT0YXi?usp=drive_link)|
|3|&cross;|&check;|&cross;|74.6|40.6|[[Google Drive]](https://drive.google.com/drive/folders/19fuBpVvFBI8lmgbjvfALcimQ1omT0YXi?usp=drive_link)|
|4|&cross;|&cross;|&check;|78.9|47.8|[[Google Drive]](https://drive.google.com/drive/folders/19fuBpVvFBI8lmgbjvfALcimQ1omT0YXi?usp=drive_link)|
|5|&check;|&check;|&check;|**80.1**|**48.0**|[[Google Drive]](https://drive.google.com/drive/folders/19fuBpVvFBI8lmgbjvfALcimQ1omT0YXi?usp=drive_link)|

</div>

1: What we refer to is YOLOv5s-7.0.

The best combination for object detection in our experiments is YOLOv5 with BiFPN, SIoU and AM. You can download the weight from [[Google Drive]](https://drive.google.com/drive/folders/19fuBpVvFBI8lmgbjvfALcimQ1omT0YXi?usp=drive_link).

</details>





## <div align="center">Improvement</div>

## <div align="center">Result</div>
<div align="center">
  <img width="70%" src="https://raw.githubusercontent.com/JiwenJ/Graduation-project/main/doc/images/result.png">
</div>

## <div align="center">Contact</div>
- E-mail: 1546631808@qq.com


## <div align="center">Acknowledgement</div>
Data credit to
Computation resource
tutorial
