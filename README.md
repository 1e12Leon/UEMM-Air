<div align="center">

# UEMM-Air: Enable UAVs to Undertake More Multi-modal Tasks

[Liang Yao (姚亮)](https://multimodality.group/author/%E5%A7%9A%E4%BA%AE/) 
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp; 
[Fan Liu (刘凡)](https://multimodality.group/author/%E5%88%98%E5%87%A1/) ✉ 
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp;
[Shengxiang Xu (徐圣翔)](https://multimodality.group/author/%E5%BE%90%E5%9C%A3%E7%BF%94/) 
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp; 

[Chuanyi Zhang (张传一)](https://ai.hhu.edu.cn/2023/0809/c17670a264073/page.htm) ✉ 
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp;
Shimin Di (邸世民)
<img src="assets/SEU.png" alt="Logo" width="15">, &nbsp; &nbsp;
Xing Ma (马幸)
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp; 
Jianyu Jiang (江建谕)
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp; 

Zequan Wang (王泽权)
<img src="assets/hhu_logo.png" alt="Logo" width="15">, &nbsp; &nbsp; 
[Jun Zhou (周峻)](https://experts.griffith.edu.au/7205-jun-zhou) 
<img src="assets/Griffith.png" alt="Logo" width="15">


<img src="assets/hhu_logo.png" alt="Logo" width="15"> Hohai University, &nbsp; &nbsp;
<img src="assets/SEU.png" alt="Logo" width="15">Southeast University, &nbsp; &nbsp;
<img src="assets/Griffith.png" alt="Logo" width="15"> Griffith University

✉ *Corresponding Author*

🤗[UEMM-Air](https://huggingface.co/datasets/1e12Leon/UEMM-Air)

</div>


## News
- **2025/1/20**: We have open-sourced the dataset generation system, which can be found in the [AirNavigation](https://github.com/1e12Leon/AirNavigation).
- **2024/12/11**: Welcome to UEMM-Air! Dataset is open-sourced at this repository.

## Introduction
![Fig2](https://github.com/user-attachments/assets/58b2bc84-9643-43f2-89a4-b14dd91ce47d)

We present a large-scale synthetic drone vision dataset with 6 paired multimodal streams (120k+ sequences) and 4D task versatility , enabling comprehensive research in perception, navigation, and autonomy. Built on Unreal Engine, it offers photorealistic aerial scenarios with precise physics, diverse environmental variations, and pixel-perfect annotations. The paired modalities (e.g., RGB/Depth/IR/LIDAR/Event/SAR) facilitate cross-modal learning and domain adaptation studies, while the multi-task support (detection, segmentation, pose estimation, scene understanding) encourages holistic perception modeling. Its synthetic nature ensures scalability, reproducibility, and rare-event coverage, addressing critical gaps in real-world drone datasets. This work establishes a new benchmark for robust, generalizable vision systems in complex aerial environments.


## Download the UEMM-Air 📂

*  🤗[Hugging Face](https://huggingface.co/datasets/1e12Leon/UEMM-Air)

### Multi-modality Images
*  [BaiduYun](https://pan.baidu.com/s/1AgrehM3Bs-aiVLVrdswWeQ?pwd=xcpe)

### Object Detection
*  [BaiduYun](https://pan.baidu.com/s/1bkG3G3nUre65yk0XjeaQ5w?pwd=a3qt)

### Instance Segmentation
*  [BaiduYun](https://pan.baidu.com/s/1TEwa8NrmbDK_Vd_zpysHug?pwd=y1f4)

### Referring Expression Segmentation
*  [BaiduYun](https://pan.baidu.com/s/1hO5h2UdYwxJrLmk4oStupg?pwd=wqxi)
  
### Image-Text Retrieval
*   [BaiduYun](https://pan.baidu.com/s/1O-U84fhqsJruyEV-UDKx8w?pwd=jppd)
  

## License 🚨
This dataset is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC-BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

By downloading or using the Dataset, as a Licensee I/we understand, acknowledge, and hereby agree to all the terms of use. This dataset is provided "as is" and without any warranty of any kind, express or implied. The authors and their affiliated institutions are not responsible for any errors or omissions in the dataset, or for the results obtained from the use of the dataset. **The dataset is intended for academic research purposes only, and not for any commercial or other purposes.** The users of the dataset agree to acknowledge the source of the dataset and cite the relevant papers in any publications or presentations that use the dataset. The users of the dataset also agree to respect the intellectual property rights of the original data owners.

## Citation🎈

```bibtex
@misc{yao2025uemmair,
      title={UEMM-Air: Make Unmanned Aerial Vehicles Perform More Multi-modal Tasks}, 
      author={Liang Yao and Fan Liu and Shengxiang Xu and Chuanyi Zhang and Xing Ma and Jianyu Jiang and Zequan Wang and Shimin Di and Jun Zhou},
      year={2025},
      eprint={2406.06230},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2406.06230}, 
}
```
