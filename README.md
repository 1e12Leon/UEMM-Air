# UEMM-Air: A Synthetic Multi-modal Dataset for Unmanned Aerial Vehicle Object Detection

The development of multi-modal object detection for Unmanned Aerial Vehicles (UAVs) typically relies on a large amount of pixel-aligned multi-modal image data. However, existing datasets face challenges such as limited modalities, high construction costs, and imprecise annotations. To this end, we propose a synthetic multi-modal UAV-based object detection dataset, UEMM-Air. Specially, we simulate various UAV flight scenarios and object types using the Unreal Engine (UE). Then we design the UAV's flight logic to automatically collect data from different scenarios, perspectives, and altitudes. Finally, we propose a novel heuristic automatic annotation algorithm to generate accurate object detection labels. In total, our UEMM-Air consists of 20k pairs of images with 5 modalities and precise annotations. 
Moreover, we conduct numerous experiments and establish new benchmark results on our dataset. We found that models pre-trained on UEMM-Air exhibit better performance on downstream tasks compared to other similar datasets. 

![图片1](https://github.com/1e12Leon/UEMM-Air/assets/44053847/56f0e7b2-a757-4386-a47c-bceada76b79c)


## News

- **2024/10/10**: We generate more complex scenes and expand the UEMM-Air's scale to 100k pairs of multi-modal images!
- **2024/06/10**: We propose UEMM-Air. Dataset will be open-sourced at this repository.
  
## Download the Dataset 📂

### The Whole UEMM-Air
*  [BaiduYun](https://pan.baidu.com/s/1tny1Y8XS0K9bvBdWcToe8g?pwd=y6i7) 

### RGB
*  [BaiduYun](https://pan.baidu.com/s/1zrnhQtPC2OQM4TK2IEUBEA?pwd=tlw0) 

### Surface Normal
*  [BaiduYun](https://pan.baidu.com/s/1oGzXY56K4yfN0muNyInmuw?pwd=67mj) 

### Segmentation
*  [BaiduYun](https://pan.baidu.com/s/1gQDNFrDtaI-EQhXUifqvhQ?pwd=uum6) 

### Depth
*  [BaiduYun](https://pan.baidu.com/s/1HcHukVPYz6gTBQl5k7mc1Q?pwd=boep) 

### Annotations
*  [BaiduYun](https://pan.baidu.com/s/1jlLoKPE-nSvl148Wxpcm_A?pwd=zwo7) 

### Annotations (Fine-grained)
*  [BaiduYun](https://pan.baidu.com/s/1O3XUfcv1zq6gPGglaoP5ag?pwd=6sb5)


## License 🚨
By downloading or using the Dataset, as a Licensee I/we understand, acknowledge, and hereby agree to all the terms of use. This dataset is provided "as is" and without any warranty of any kind, express or implied. The authors and their affiliated institutions are not responsible for any errors or omissions in the dataset, or for the results obtained from the use of the dataset. **The dataset is intended for academic research purposes only, and not for any commercial or other purposes.** The users of the dataset agree to acknowledge the source of the dataset and cite the relevant papers in any publications or presentations that use the dataset. The users of the dataset also agree to respect the intellectual property rights of the original data owners.

## Citation🎈

```bibtex
@misc{liu2024uemmair,
      title={UEMM-Air: A Synthetic Multi-modal Dataset for Unmanned Aerial Vehicle Object Detection}, 
      author={Fan Liu and Liang Yao and Shengxiang Xu and Chuanyi Zhang and Xinlei Zhang and Ting Wu},
      year={2024},
      eprint={2406.06230},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
