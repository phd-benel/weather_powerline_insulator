![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/37953301-9b08-4f69-bba8-5f1bdb019eef)# weather_powerline_insulator

# Yolov8_gold

Hy, Peace be upon you, 

This is the source code for the paper, "Weathering the Storm: Evaluating the Generalization of recent Object Detection Models for UAV Power Line Inspection of Insulators in Challenging Meteorological Conditions" accepted in AI2SD Global Submit Symposium Serie On Energy, Enviromnent and Agriculture , 15-17 November 2023 - Marrakech, Morocco

### Paper Abstract

Unmanned aerial vehicles (UAVs) have demonstrated substantial improvements in the efficiency of power line inspections. The application of sophisticated deep learning object detection algorithms facilitates automated anomaly identification through drone imagery, significantly expediting inspection processes. This not only enhances operational efficiency but also leads to cost reductions and diminished associated risks. Nonetheless, challenges arise, particularly in the face of adverse weather conditions. Drone-captured images featuring snow, rain, or fog introduce noise, compromising image clarity and quality, thereby posing a significant hurdle for object detection models. Our research is centered on two main objectives: (i) assessing the impact of weather disturbances on the model's efficacy, and (ii) determining the necessity of training the model in a noisy context for detecting broken porcelain insulators—a critical component of power line infrastructure. The study evaluates model performance metrics trained on clear images, tested on noise-free datasets, and those with simulated noise (snow, fog, and rain). Additionally, recent object detection models (YOLOV8 and RTDETR) trained on three noisy datasets (snow, fog, and rain) are tested on their respective noisy test datasets, with benchmarking against a model exclusively trained on clear images. The findings reveal a slight superiority of the model trained in a clear context over its noisy counterpart in the corresponding test environment. However, marginal efficiency gains are observed when training a model in a noisy environment and testing it in the same context. Ultimately, the results affirm the model's generalization ability, indicating that training in a noisy context is not imperative, considering the limited added value compared to potential risks associated with data collection operations in extreme conditions. 

### Data

Data used for this study can be found here : https://github.com/phd-benel/VPMBGI 
IMGAUG PYTHON LIBRARY
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/dead223b-3855-401d-9ec4-4194cfe24b55)
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/02c09780-c3e1-4844-b3c5-ccf72acbf797)
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/181fec43-d13c-4af8-9aca-9d034e5d7cad)
![image](https://github.com/phd-benel/weather_powerline_insulator/assets/82882383/79de1b4d-7873-44b6-b845-81fca2e6377c)




### Model Architecture

Refer to this file for the model architecture : https://github.com/phd-benel/yolov8_improved_exp/blob/main/ultralytics/cfg/models/v8/yolov8_gold.yaml

![image](https://github.com/phd-benel/yolov8_gold/assets/82882383/28daae33-28c2-4113-abfc-cdf9e1a3a4a0)
Fig. 1. The overall simplified structure of the proposed improved model Yolov8-Gold. The orange blocks represent the new modules introduced in the Yolov8 architecture.

For a clearer explanation of the architecture, please refer to this: https://github.com/phd-benel/yolov8_gold/issues/1

### Experiments

https://colab.research.google.com/drive/14HN3xUVLOkSmENkUWIpjF_vGuxgpUtvf?usp=sharing

Run this Colab notebook to replicate the results obtained through the training of YOLOv8_Gold Model: https://colab.research.google.com/drive/1tuk6NXmcILxMYUiBYCgUQGLd_rMjtCWk?usp=sharing

### Results

Training results of Yolov8_gold_m' : ![results](https://github.com/phd-benel/yolov8_gold/assets/82882383/ab3fd48d-6be6-4121-b7fb-29cbe0afc82d)

Model weight of Yolov8_gold_m pretrained on VPMBGI : https://github.com/phd-benel/yolov8_gold/releases/download/untagged-afd4d8c9da44572fe2df/yolov8gold_m.pt

### Citation

Too add

### License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). Please see the [LICENSE.md](LICENSE) file for details.

### Acknowledgments

We express our gratitude to Ultralytics YOLOv8 , the contributors of the objectdetection_script repository and the authors of "Gold-YOLO: Efficient Object Detector via Gather-and-Distribute Mechanism" paper for their valuable contributions and resources, which greatly assisted in the development and execution of this research.

### Contact 
Please don't hesitate to report an issue on this GitHub repository if you require further information or assistance. I would be delighted to provide help and support.
