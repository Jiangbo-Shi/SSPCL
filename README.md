# Gastric Cancer Semantic Segmentation (GCSS) dataset
- Download link:  
  - Baidu Cloud: https://pan.baidu.com/s/1EEmuDCQez1odggab3lElFQ; Extraction code: GCSS  
  - Zenodo: https://zenodo.org/record/8176354
- Annotation: The annotation of each ROI is a pixel matrix. {1,2,3,4,5} represent `tumor`, `lymphoid stroma`, `desmoplastic stroma`, `smooth muscle`, and `necrosis`. {-1, 0, 6} represent `others`. 
- Data statistics: 100 ROIs cropped from the 100 gastric cancer cases of the TCGA-STAD project.

# Citation
If you find our work helpful for your research, please consider citing:
```
@ARTICLE{SSPCL,
  author={Shi, Jiangbo and Gong, Tieliang and Wang, Chunbao and Li, Chen},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={Semi-Supervised Pixel Contrastive Learning Framework for Tissue Segmentation in Histopathological Image}, 
  year={2023},
  volume={27},
  number={1},
  pages={97-108},
  doi={10.1109/JBHI.2022.3216293}}
```
