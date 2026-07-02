# RDRF-dataset @ ECCV'2026

## Problem Definition
On rainy days, raindrops and reflections frequently co-occur in autonomous driving scenarios, posing challenges for onboard visual recognition systems or vehicle cameras during recording. 
Adherent raindrops and the reflections from camera side significantly reduce the visibility of captured images, and may lead to severe driving safety hazards. 
Therefore, Unified Removal of Raindrops and Reflections (UR$^3$) is a practical problem that requires urgent solution.

## How we capture the images
Our RDRF dataset is captured under real scenarios deliberately constructed in controlled environments.
For the hardware configuration, the camera is mounted on a tripod using an adjustable base, with the glass slab positioned in front of the lens.
We connect a signal receiver onto the camera, thereby enabling remote control of the shutter.
This wireless triggering mechanism can effectively avoid image misalignment caused by camera vibrations resulting from manual operation.
To ensure diversity, neither the camera nor the glass is fixed. 
They can be adjusted to simulate different shooting situations (\eg, camera-to-glass distances/angles).
In addition, we utilize two cameras (Sony ILCE-7RM4A and Nikon D7100) with zoom lens and choose different glass thicknesses (3 mm, 5 mm, and 8 mm) to further enhance diversity. 

<p align="left">
  <img width=950" src="assets/fig2-cr.png">
</p>

## Some Samples
<p align="left">
  <img width=950" src="assets/fig3-new.png">
</p>

## About RDRF-wild




<!-- ## Abstract @ ECCV’2026 -->

<!-- ## 📖 **Overview**  
PolarFree addresses the challenging task of reflection removal using polarization cues and a novel diffusion-based approach. Key contributions include:  
- **PolaRGB Dataset**: A large-scale dataset with diverse indoor and outdoor scenes, providing RGB and polarization images.  

![Dataset Overview](https://raw.githubusercontent.com/mdyao/PolarFree/doc/docs/static/images/dataset_overview.png)

- **Diffusion Model**: Utilizes diffusion processes to generate reflection-free priors, enabling precise reflection removal and improved image clarity.  
![Model Design](https://raw.githubusercontent.com/mdyao/PolarFree/doc/docs/static/images/model_design.png)

- **Superior Results**: Extensive experiments on the PolaRGB dataset show that PolarFree outperforms existing methods by ~2dB in PSNR, achieving cleaner reflection removal and sharper image details.  

- **Real-World Effectiveness**: PolarFree demonstrates robust performance in real-world scenarios, such as museums and galleries, effectively reducing reflections while preserving fine details.   -->



## Citation
If this work is useful for your research, please cite our paper. 
```BibTeX
@inproceedings{Liu2026ECCV-RDRF,
  title={Unified Removal of Raindrops and Reflections: A New Benchmark and A Novel Pipeline},
  author={Xingyu Liu and Zewei He and Yu Chen and Chunyu Zhu and Zixuan Chen and Xing Luo and Zhe-Ming Lu},
  booktitle={European Conference on Computer Vision (ECCV)},
  year={2026}
}
```