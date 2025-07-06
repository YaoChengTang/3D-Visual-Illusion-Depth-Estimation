<h1 align="center"> 3D Visual Illusion Depth Estimation </h1> 

![Video Data](./Fig/illusion_data.jpg)

Preview Dataset:
- **Baidu Drive**: [Download Link](https://pan.baidu.com/s/1pe9G7thzjBII5_d9EtVUpQ?pwd=4sch)
- **Google Drive**: Uploading (link will be added soon)

Full Dataset:
The full dataset will be released in one month.



- ## StereoSimulator
    Pipeline used to generate stereo data with videos from web or generative model

    <figure style="text-align: center;">
    <img src="./Fig/mono_pipeline.jpg" alt="mono_pipeline" style="width: 100%;">
    <figcaption style="font-style: italic; margin-top: 8px; text-align: center;">Data generation pipeline for web-source data</figcaption>
    </figure>

    <figure>
    <img src="./Fig/stereo_pipeline.jpg" alt="stereo_pipeline" style="width:100%;">
    <figcaption style="text-align: center; font-style: italic; text-align: center;">Data generation pipeline for videos from generative models</figcaption>
    </figure>

- ## VLM-driven Mon-Stereo Fusion
    The VLM-driven monocular-stereo fusion model

    <figure style="text-align: center;">
    <img src="./Fig/Model.jpg" alt="model" style="width: 100%;">
    <!-- <figcaption style="font-style: italic; margin-top: 8px;">Data generation pipeline for web-source data</figcaption> -->
    </figure>

- ## Results
    Results on a part of different illusions

    <figure style="text-align: center;">
    <img src="./Fig/3d-vis-illusion.jpg" alt="model" style="width: 100%;">
    <figcaption style="font-style: italic; margin-top: 8px; text-align: center;">Illusions on Generated Data</figcaption>
    </figure>

    <figure style="text-align: center;">
    <img src="./Fig/3d-Illusion-vis2.jpg" alt="model" style="width: 100%;">
    <figcaption style="font-style: italic; margin-top: 8px; text-align: center;">Illusions on Real-world Data</figcaption>
    </figure>

    <figure style="text-align: center;">
    <img src="./Fig/3d-Illusion-vis1.jpg" alt="model" style="width: 100%;">
    <figcaption style="font-style: italic; margin-top: 8px; text-align: center;">Mirror Illusions</figcaption>
    </figure>

    <figure style="text-align: center;">
    <img src="./Fig/3DDet.jpg" alt="model" style="width: 100%;">
    <figcaption style="font-style: italic; margin-top: 8px; text-align: center;">Illusions in 3D Detection</figcaption>
    </figure>

    More visualizations in 3D lane detection, occupancy prediction, and planning are coming soon.
