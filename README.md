# xai-and-model-size
This repository will contain supplementary code associated with the article:

### Model complexity and XAI evaluation: Does more complex architecture provides better explanations?

The ResNet18, ResNet34, ResNet50 and ResNet101 have been trained from scratch and evaluated on the same COVID-19 lung X-ray dataset to check whether the more complex architectures provide better explanations. Saliency Maps, GradientSHAP, and Integrated Gradients methods have been used to provide pixel attributions.

Finally, the Positive Pixel Attribution ratio concerning provided ground-truth disease masks was calculated to check how many positively attributed pixels lay within the ground-truth mask.

Conclusion - there is no statistically significant difference between means of the average number of positively attributed pixels within ground-truth masks across the ResNet models.

Note: Full reproducibility is provided

![grads](https://github.com/mateuszcedro/xai-and-model-size/blob/main/notebook/Grads.png)
