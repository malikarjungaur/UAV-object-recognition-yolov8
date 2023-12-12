# UAV-object-recognition-yolov8
UAV object recognition yolov8

With the widespread use of UAVs in commercial and industrial applications, UAV detection
is receiving increasing attention in areas such as public safety. As a result, object detection
techniques for UAVs are also developing rapidly. However, the small size of drones, complex airspace
backgrounds, and changing light conditions still pose significant challenges for research in this
area. Based on the above problems, this paper proposes a tiny UAV detection method based on
the optimized YOLOv8. First, in the detection head component, a high-resolution detection head is
added to improve the device’s detection capability for small targets, while the large target detection
head and redundant network layers are cut off to effectively reduce the number of network parameters
and improve the detection speed of UAV; second, in the feature extraction stage, SPD-Conv is
used to extract multi-scale features instead of Conv to reduce the loss of fine-grained information
and enhance the model’s feature extraction capability for small targets. Finally, the GAM attention
mechanism is introduced in the neck to enhance the model’s fusion of target features and improve
the model’s overall performance in detecting UAVs. Relative to the baseline model, our method
improves performance by 11.9%, 15.2%, and 9% in terms of P (precision), R (recall), and mAP (mean
average precision), respectively. Meanwhile, it reduces the number of parameters and model size by
59.9% and 57.9%, respectively. In addition, our method demonstrates clear advantages in comparison
experiments and self-built dataset experiments and is more suitable for engineering deployment and
the practical applications of UAV object detection systems.
