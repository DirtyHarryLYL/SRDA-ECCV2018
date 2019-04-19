# Dataset: Instance-60k & 3D Object Models from SRDA

**SRDA: Generating Instance Segmentation Annotation via Scanning, Reasoning and Domain Adaptation**

Wenqiang Xu*, Yong-Lu Li*, Cewu Lu. (*=equal contribution) 

ECCV2018

Google Drive: [[Instance-60k & 3D Object Models]](https://drive.google.com/drive/folders/1t941oiLk40XQX2Q9a2HPmiDRUpiwazJO?usp=sharing)

The 3D object models are reconstructed through Structure from Motion (SfM), Multi-View Stereo (MVS), Surface Reconstruction and Texture Mapping. More details can be found in our paper.

Process:

iPhone video sequence --(SfM)--> Sparse Point Cloud --(MVS)--> Dense Point Cloud --(Possion SR)--> Mesh --(UV Mapping)--> Rough Model --(Semi-automatic Edited) --> Final Model

## Citation
If you find our work useful in your research, please consider citing:
```
@inproceedings{xu2018srda,
  title={SRDA: Generating Instance Segmentation Annotation via Scanning, Reasoning and Domain Adaptation},
  author={Xu, Wenqiang and Li, Yonglu and Lu, Cewu},
  booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
  pages={120--136},
  year={2018}
}
```
