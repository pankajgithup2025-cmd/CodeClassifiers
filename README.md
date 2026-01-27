This repository presents a comprehensive deep learning framework for mango leaf disease classification, implementing a wide range of state-of-the-art CNN and transformer-based architectures, including ViT-B16, VGG19, ResNet-50/101, AlexNet, EfficientNet-B1, ConvNeXt-Large, MobileNetV1, DenseNet161, Xception, and Inception-V4. All models are initialized with pretrained weights and systematically fine-tuned for agricultural disease recognition.

The models are trained and evaluated on three complementary datasets: (i) a real-world mango leaf disease dataset and Publicly avaibale Tomato-village dataset, (ii) a GAN(styelGAn3 and LeafGAN-augmented dataset, and (iii) a Leafdiffusion-based synthetic dataset, enabling a detailed analysis of data scarcity and generalization. To further enhance performance, the framework investigates the effect of multiple color space transformations (RGB, HSV, Lab, and YCbCr)* on classification accuracy.

All implementations are optimized using Bayesian hyperparameter optimization combined with 5-fold cross-validation, ensuring robust, unbiased, and reproducible performance evaluation. This repository serves as a benchmark-ready, extensible resource for researchers working on plant disease classification, data augmentation, and reliable model selection in precision agriculture.


# Our proposed Dataset MangoLeafDS2025 with high-quality Mango leaf images can be accessed at : https://www.kaggle.com/datasets/pankajsthakre/mangoleafds2025 
 Kindly cite dataset with DOI as :
 @misc{pankajkumar_thakre_jagdish_chakole_2026,
	title={MangoLeafDS2025},
	url={https://www.kaggle.com/dsv/14384560},
	DOI={10.34740/KAGGLE/DSV/14384560},
	publisher={Kaggle},
	author={Pankajkumar Thakre and Jagdish Chakole},
	year={2026}
}
