# Frequency-aware Uncertainty Gaussian Splatting for Dynamic Scene Reconstruction

![image](https://github.com/user-attachments/assets/e1d83227-1d61-4903-bb25-56a35924aa1d)

# Abstract
3D Gaussian Splatting has recently achieved remarkable progress in dynamic scene reconstruction. However, there remain two practical challenges: (1) Existing methods typically employ a strict point-wise deformation structure to model dynamic attributes, while neglecting the uncertain motion correlation in  local space, leading to inferior adaptability to complex scenes. (2) The inherent low-frequency bias properties of Gaussians often lead to blurring artifacts due to the insufficient high-frequency learning of variable motions. To address these challenges, we propose a novel Frequency-aware Uncertainty Gaussian Splatting, termed {FUGS}, for adaptively reconstructing dynamic scenes in the Fourier space. Specifically, we design an Uncertainty-aware Deformation Model (UDM) that explicitly models motion attributes using learnable uncertainty relations with neighboring Gaussian points. Such a paradigm is capable of facilitating temporal and spatial motion correlation learning, thereby enabling flexible Gaussian deformations. Subsequently, a Dynamic Spectrum Regularization (DSR) is developed to perform coarse-to-fine Gaussian densification through low-to-high frequency filtering. By weighting the gradient with frequency distance, the Gaussian attribute is adaptively adjusted according to the scene complexity. Benefiting from the flexible optimization, our method achieves high-fidelity reconstruction of complex scenes while enjoying real-time rendering. Extensive experiments on synthetic and real-world datasets show that our {FUGS} exhibits significant superiority over state-of-the-art methods.

![image](https://github.com/user-attachments/assets/14d7c2cc-de5f-48f7-97e9-f2911f5068e7)

# Results

<video width="320" height="240" controls>
  <source src="path/to/video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
