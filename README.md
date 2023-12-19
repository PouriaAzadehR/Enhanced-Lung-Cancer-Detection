# Project Overview

This project focuses on enhancing lung cancer detection using machine learning methodologies and ensuring trust, transparency, and robustness in the model. Below is an outline of the project phases, methodologies, and future plans:

**Kaggle Link**: [Modified Resnet with Grad-CAM, Adversarial Attack](https://www.kaggle.com/code/pouriaazadehranjbar/modified-resnet-with-grad-cam-adversarial-attack)

**Kaggle Dataset Link**: [Adversarial Chest CT-scan Dataset](https://www.kaggle.com/code/pouriaazadehranjbar/modified-resnet-with-grad-cam-adversarial-attack)


## Phases:
1. **Transfer Learning and Grad-CAM (Phase 1)**
   - Utilized transfer learning techniques with ResNet50 for lung cancer detection.
   - Replaced the final layer for better fitting architecture and employed Grad-CAM for visualization.

2. **Adversarial Attacks (Phase 2)**
   - Investigated model susceptibility to adversarial attacks.
   - Employed adversarial training techniques to enhance model defense.

3. **Membership Inference Attacks (MIA) (Phase 3)**
   - Explored privacy concerns and potential overfitting via membership inference attacks (MIA).

4. **Deployment and Access (Phase 4)**
   - Constructed a robust cloud-native system for lung cancer detection.
   - Implemented user-friendly interfaces using Django, React, and Android.

## Future Phases:
### Future Plans for Security and Privacy Enhancement:
- **Federated Learning Integration**
  - Creating a collaborative environment among multiple institutions using FedAvg to aggregate model updates while preserving data privacy.

- **Differential Privacy Exploration**
  - Strategically adding noise at different pipeline stages to study its impact on both model performance and privacy preservation.

### Enhanced Model Interpretability:
- **Interpretability Methods Exploration**
  - Investigating global and local perspectives, model-specific, and model-agnostic interpretability methods to gain deeper insights into the model's decision-making process.
