# StyleGAN Video (SGV) &mdash; Official TensorFlow Implementation

StyleGAN Video (SGV) is a machine-learning-assisted, GPU-accelerated open source video codec. SGV is implemented in TensorFlow, building upon NVIDIA's groundbreaking StyleGAN neural network architecture. The encoder is a modified version of the StyleGAN projector, with support for cut detection, keyframe initialization and adaptive quality thresholds. The generator network is used as decoder, achieving impressive performance on modern GPUs. StyleGAN latent vectors can be exported and imported directly, enabling a variety of popular image enhancement features, like style transfer, de-aging or pose-shifting.

SGV supports full HD 1080p (upsampled from 1024p) video at a fixed aspect ratio of 1:1, popular in the machine learning community. While highly optimized for frontal human portrait shots, it can represent arbitrary sequences of moving images with stunning fidelity. Future versions of SGV may add support for sound, different aspect ratios and additional optimizations, specifically for cat videos, horse videos, car videos, and other categories of popular content.

SGV, along with the SGV file format specification, will be released in May 2020.
