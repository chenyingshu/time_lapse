# Time-of-Day Neural Style Transfer for Architectural Photographs

<a href="https://chenyingshu.github.io/time_of_day/"><img src="https://img.shields.io/badge/WEBSITE-Visit%20project%20page-blue?style=for-the-badge"></a>
<a href="https://github.com/hkust-vgd/architectural_style_transfer"><img src="https://img.shields.io/badge/CODE-Access%20Github-red?style=for-the-badge"></a> 

[Yingshu Chen]()<sup>1</sup>,
[Tuan-Anh Vu]()<sup>1</sup>,
[Ka-Chun Shum]()<sup>1</sup>,
[Binh-Son Hua](https://sonhua.github.io/)<sup>2</sup>,
[Sai-Kit Yeung](https://www.saikit.org/)<sup>1</sup> <br>
<sup>1</sup>The Hong Kong University of Science and Technology, <sup>2</sup> VinAI Research

> **Abstract:** 
Architectural photography is a genre of photography that focuses on capturing a building or structure in the foreground with dramatic lighting in the background. Inspired by recent successes in image-to-image translation methods, we aim to perform style transfer for architectural photographs. However, the special composition in architectural photography poses great challenges for style transfer in this type of photographs. Existing neural style transfer methods treat the architectural images as a single entity, which would generate mismatched chrominance and destroy geometric features of the original architecture, yielding unrealistic lighting, wrong color rendition, and visual artifacts such as ghosting, appearance distortion, or color mismatching. In this paper, we specialize a neural style transfer method for architectural photography. Our method addresses the composition of the foreground and background in an architectural photograph in a two-branch neural network that separately considers the style transfer of the foreground and the background, respectively. Our method comprises a segmentation module, a learning-based image-to-image translation module, and an image blending optimization module. We trained our image-to-image translation neural network with a new dataset of unconstrained outdoor architectural photographs captured at different magic times of a day, utilizing additional semantic information for better chrominance matching and geometry preservation. Our experiments show that our method can produce photorealistic lighting and color rendition on both the foreground and background, and outperforms general image-to-image translation and arbitrary style transfer baselines quantitatively and qualitatively. Our code and data will be made available to facilitate future work on this problem.

## Citation
If you find our data or work useful in your research, please consider citing: 
```bibtex
@inproceedings{chen2022timeofday,
  title={Time-of-Day Neural Style Transfer for Architectural Photographs},
  author={Chen, Yingshu and Vu, Tuan-Anh and Shum, Ka-Chun and Hua, Binh-Son and Yeung, Sai-Kit},
  booktitle={International Conference on Computational Photography (ICCP)},
  year={2022},
  organization={IEEE}
}
```


## Todo list:
<!-- - [ ] Semi-segmentation tool (but maybe put in 3d color proj?)-->
- [x] Data segmentation preprocessing instruction
- [ ] Source code
- [ ] Blending/Geometry optimization (resolution restoration)
- [ ] Pretrained model
- [ ] Data (train set with request, eval set public)
<!-- - [ ] Segmentated data (TBD) -->

<!-- ## Contact
For any questions, please contact -->
