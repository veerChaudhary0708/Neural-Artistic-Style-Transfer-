# PyTorch Neural Style Transfer 🎨

This project is a Python implementation of the Neural Style Transfer algorithm, originally described in the paper "A Neural Algorithm of Artistic Style" by Gatys et al. It allows you to take two images—a content image and a style image—and blend them together to create a new image that has the content of the first and the artistic style of the second.



## Features

* Uses a pre-trained **VGG19** network to extract content and style features.
* Employs the **L-BFGS optimizer**, which often produces higher-quality results.
* Includes **Total Variation Loss** as a regularization term to create smoother, more coherent images.
* All settings are centralized in a simple and easy-to-use **"Control Panel"** directly in the main script.
![content_style (1)](https://github.com/user-attachments/assets/98eaa11c-b2ff-4ff5-8f98-a93fc999895b)
![content_style](https://github.com/user-attachments/assets/235462c6-48d5-43ad-a09e-1936c5fe580e)
![green_bridge_vg_la_cafe_o_lbfgs_i_content_h_500_m_vgg19_cw_100000 0_sw_30000 0_tv_1 0](https://github.com/user-attachments/assets/dd05166a-3c32-4383-9563-d2c6285ac8df)

---
## Setup

To run this project on your local machine, follow these steps.

**1. Clone the repository:**
```bash
git clone <(https://github.com/veerChaudhary0708/Neural-Artistic-Style-Transfer-)>
cd <Neural-Artistic-Style-Transfer>
