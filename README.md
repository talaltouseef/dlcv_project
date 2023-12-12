
<h3>Detectron2</h3>
The changes made to the Visualizer class for the 2D segmentation mask is at the following fork: <a>https://github.com/talaltouseef/detectron2</a>

<h3>Data</h3>
The input images, trained models and rendered images of the Nerf models are contained in a folder named "NerfStudio" hosted here: <a>https://drive.google.com/drive/folders/1K2O2cYJvdJzObSSjfnaIDlWHU9FJMlSH?usp=sharing</a> <br>
Download and place this folder inside the root of the git repository

<h3>Instance-NeRF</h3>
Clone the repository from <a>https://github.com/lyclyc52/Instance_NeRF</a>. We follow the steps described by the authors without any changes. Replace the files in the instance_nerf_files folder of our repository in the following directories of the cloned repository: <br>
./instance_nerf/main_nerf_mask.py <br>
./instance_nerf/scripts/project_3d_masks.py <br>
./instance_nerf/nerf/provider.py <br>
./instance_nerf/nerf/utils.py <br>
