# Photoconsistent and Trajectory Guided Novel-View Synthesis Tool for UAV Cinematography Based on Autoregressive Transformers

> Novel view synthesis is the task of generating new images that render an object or scene from a different viewpoint than the one given. It aims to create new views of a specific subject starting from a number of pictures taken from a known points of view. The novel view synthesis problem can be approached in two different ways: as a problem of interpolation of images between two known images or extrapolation of images from one or a subset of images. During this work, the problem of the extrapolation will be addressed. Taking advantage of the fact that it is possible to pre-calculate the trajectories that we want the camera that takes the images to execute, from a series of known shot-types. Based on that and on the Autoregressive Transformers, it is presented a end-to-end tool for novel-view synthesis from previously unvisited points of view for aerial cinematography robots.

![proposed_tool_diagram](./docs/proposed_tool_diagram.png)

---

## Repo content overview

It contains three main folders: 

* [**airsim_dataset_generator**](./airsim_datasets_generator/README.md): It contains all the necessary tools for communicating with Airsim using Python as well as for generating trajectories or visualising them. This will simplify the task of generating datasets for computer vision.

* [**proposed_tool**](./proposed_tool/README.md): Contains the ROS nodes of the proposed tool.


## Citation

If you use this code for any academic work, please cite our original [paper](https://ieeexplore.ieee.org/abstract/document/10734750):

```bibtex
@INPROCEEDINGS{10734750,
  author={Montes-Grova, Marco A. and Mygdalis, Vasileios and Pérez-Grau, Francisco J. and Viguria, Antidio and Pitas, Ioannis},
  booktitle={2024 IEEE 34th International Workshop on Machine Learning for Signal Processing (MLSP)}, 
  title={Photoconsistent and Trajectory Guided Novel-View Synthesis Tool for UAV Cinematography Based on Autoregressive Transformers}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
  keywords={Extrapolation;Interpolation;Conferences;Robot vision systems;Machine learning;Cinematography;Signal processing;Transformers;Trajectory;Robots;Applications of machine learning;Generative AI for Multimedia;UAS Applications},
  doi={10.1109/MLSP58920.2024.10734750}}
```


## Funding

---

<img src="./docs/ai4media_logo.jpg" alt="AI4MEDIA" height="30%" width="30%">

Supported by AI4MEDIA - A European Excellence Centre for Media, Society and Democracy.
More information: <a href="https://www.ai4media.eu/">ai4media.eu</a>

<img src="./docs/eu_flag.png" alt="eu_flag" height="45" align="left" >  

This project has received funding from the European Union's Horizon 2020  
research and innovation programme under grant agreement 951911.
