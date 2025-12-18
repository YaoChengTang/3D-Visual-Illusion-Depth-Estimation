<h1 align="center">3D Visual Illusion Depth Estimation</h1>

<p align="center">
  <a href="https://huggingface.co/datasets/AdamYao/3D_Visual_Illusion_Depth_Estimation"><img src="https://img.shields.io/badge/HuggingFace-Data-blue?logo=huggingface" alt="Hugging Face Train Data"></a>
  &nbsp;
  <a href="https://huggingface.co/datasets/AdamYao/3D_Visual_Illusion_Depth_Estimation_Real"><img src="https://img.shields.io/badge/HuggingFace-Data-blue?logo=huggingface" alt="Hugging Face Eval Data"></a>
  &nbsp;
  <a href="https://arxiv.org/abs/2505.13061"><img src="https://img.shields.io/badge/ArXiv-Paper-red?logo=arxiv" alt="ArXiv Paper"></a>
  &nbsp;
  <a href="https://huggingface.co/AdamYao/3D_Visual_Illusion_Depth_Estimation"><img src="https://img.shields.io/badge/HuggingFace-Model-blue?logo=huggingface" alt="Model Weights"></a>
</p>

<p align="center">
  <img src="./Fig/illusion_data.jpg" alt="Video Data" style="width: 100%;">
</p>

<h2 align="center">StereoSimulator</h2>

<p>Pipeline used to generate stereo data with videos from the web or the generative models.</p>

<p align="center">
  <img src="./Fig/mono_pipeline.jpg" alt="mono_pipeline" style="width: 100%;">
  <br>
  <em>Data generation pipeline for web-source data</em>
</p>

<p align="center">
  <img src="./Fig/stereo_pipeline.jpg" alt="stereo_pipeline" style="width: 100%;">
  <br>
  <em>Data generation pipeline for videos from generative models</em>
</p>

<h2 align="center">VLM-driven Mon-Stereo Fusion</h2>

<p>The VLM-driven monocular-stereo fusion model.</p>

<p align="center">
  <img src="./Fig/Model.jpg" alt="model" style="width: 100%;">
</p>

<h2 align="center">Results</h2>

<p>
  Results on different illusions.  
  A part of the demo images can be downloaded from 
  <a href="https://drive.google.com/file/d/163pjMDnZnO2V4DeiKOpQD4KYP7_Us4j0/view?usp=sharing">Google Drive</a>.
</p>

<p align="center">
  <img src="./Fig/3d-vis-illusion.jpg" alt="Illusions on Generated Data" style="width: 100%;">
  <br>
  <em>Illusions on Generated Data</em>
</p>

<p align="center">
  <img src="./Fig/3d-Illusion-picture.jpg" alt="Illusions on Real-world Data" style="width: 100%;">
  <br>
  <em>Illusions on Real-world Data</em>
</p>

<p align="center">
  <img src="./Fig/3d-Illusion-mirror.jpg" alt="Mirror Illusions" style="width: 100%;">
  <br>
  <em>Mirror Illusions</em>
</p>

<p>We provide illusion masks in our dataset and encourage their use and extension to other 3D tasks, such as 3D detection.</p>

<p align="center">
  <img src="./Fig/3DDet.jpg" alt="Illusions in 3D Detection" style="width: 100%;">
  <br>
  <em>Illusions in 3D Detection</em>
</p>

<p align="center">
  More visualizations in 3D lane detection, occupancy prediction, and planning are coming soon.
</p>
