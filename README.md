# weather_powerline_insulator

Hy, Peace be upon you, 

This is the source code for the paper, "Weathering the Storm: Evaluating the Generalization of recent Object Detection Models for UAV Power Line Inspection of Insulators in Challenging Meteorological Conditions" submitted in The 4th International Conference on Innovative Research in Applied Science, Engineering and Technology - IRASET’2024, May 16-17, 2024 - Fez, Morocco

### Paper Abstract

Unmanned aerial vehicles (UAVs) have demonstrated substantial improvements in the efficiency of power line inspections. The application of sophisticated deep learning object detection algorithms facilitates automated anomaly identification through drone imagery, significantly expediting inspection processes. This not only enhances operational efficiency but also leads to cost reductions and diminished associated risks. Nonetheless, challenges arise, particularly in the face of adverse weather conditions. Drone-captured images featuring snow, rain, or fog introduce noise, compromising image clarity and quality, thereby posing a significant hurdle for object detection models. Our research is centered on two main objectives: (i) assessing the impact of weather disturbances on the model's efficacy, and (ii) determining the necessity of training the model in a noisy context for detecting broken porcelain insulators—a critical component of power line infrastructure. The study evaluates model performance metrics trained on clear images, tested on noise-free datasets, and those with simulated noise (snow, fog, and rain). Additionally, recent object detection models (YOLOV8 and RTDETR) trained on three noisy datasets (snow, fog, and rain) are tested on their respective noisy test datasets, with benchmarking against a model exclusively trained on clear images. The findings reveal a slight superiority of the model trained in a clear context over its noisy counterpart in the corresponding test environment. However, marginal efficiency gains are observed when training a model in a noisy environment and testing it in the same context. Ultimately, the results affirm the model's generalization ability, indicating that training in a noisy context is not imperative, considering the limited added value compared to potential risks associated with data collection operations in extreme conditions. 

### Data

Data used for this study can be found here : 
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/dead223b-3855-401d-9ec4-4194cfe24b55) Original : https://universe.roboflow.com/search?q=idid_original&t=metadata
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/02c09780-c3e1-4844-b3c5-ccf72acbf797)Original + Rain : https://universe.roboflow.com/search?q=idid_rain&t=metadata
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/181fec43-d13c-4af8-9aca-9d034e5d7cad)Original + Snow : https://universe.roboflow.com/search?q=idid_snow&t=metadata
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/79de1b4d-7873-44b6-b845-81fca2e6377c)
Original + Fog : https://universe.roboflow.com/search?q=idid_fog&t=metadata




### Experiments


Run this Colab notebook to replicate the results obtained : https://colab.research.google.com/drive/14HN3xUVLOkSmENkUWIpjF_vGuxgpUtvf?usp=sharing

### Results

Training results can be found here:
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/4a355f2f704e4fd9aa5406664b2d3062/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/c08793dbc3a745469dfa6ff6cbc11fd1/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/4752108b666f4eb480e4b539135dbe96/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/ce4b05cf090440e8901e41227bcf5bd2/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/22446e358ca64035be10082530735185/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/8b85dcbb793846f4832a085135674859/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/f5bf0032095b4f3cbd8c7609c3f2d762/output/execution
https://app.clear.ml/projects/a0dd7d1674014fb09a00509c8a2a88b7/experiments/970d1031a82c4c7b806325f32eb4846d/output/execution

### Citation

Too add

### License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). Please see the [LICENSE.md](LICENSE) file for details.

### Acknowledgments

We express our gratitude to Ultralytics YOLOv8 for their valuable contributions and resources, which greatly assisted in the development and execution of this research.

### Contact 
Please don't hesitate to report an issue on this GitHub repository if you require further information or assistance. I would be delighted to provide help and support.
