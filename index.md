## Motivation

Detecting 3D objects in urban environment is a fundamental and challenging problemfor motion planning in order to plan a safe route in autonomous driving. Specifically, autonomousvehicles (AVs) need to detect and track moving objects such as pedestrians, cyclists and vehicles inrealtime. Computation speed is critical. AVs carry a variety of sensors such as camera and LiDAR(Light Detection and Ranging), etc.  Recent approaches for 3D object detection either fuse RGBimage from camera and point cloud from LiDAR or use point cloud alone. Point cloud is irregularand extremely computational, but it is crucial for accurate 3D estimation compared with 2D images.Therefore, converting and utilizing point cloud data more efficiently and effectively has become theprimary problem in the detection task, which is also quite interesting and challenging for us.

## Our Approach
As a single-stage point-based method, our network is composed of three modules.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/minzhang-1/fast-3d-object-detection/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
