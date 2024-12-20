# Controllable Expressive 3D Facial Animation via Diffusion in a Unified Multimodal Space

<div align="center">

Anonymous Authors

Submitted to ICME 2025

<!-- [Paper](#) | [Project Page](#) | [Code](#)  -->

</div>

## Abstract
Audio-driven emotional 3D facial animation encounters two significant challenges: (1) reliance on single-modal control signals (videos, text, or emotion labels) without leveraging their complementary strengths for comprehensive emotion manipulation, and (2) deterministic regression-based mapping that constrains the stochastic nature of emotional expressions and non-verbal behaviors, limiting the expressiveness of synthesized animations. To address these challenges, we present a diffusion-based framework for controllable expressive 3D facial animation. Our approach introduces two key innovations: (1) a FLAME-centered multimodal emotion binding strategy that aligns diverse modalities (text, audio, and emotion labels) through contrastive learning, enabling flexible emotion control from multiple signal sources, and (2) an attention-based latent diffusion model with content-aware attention and emotion-guided layers, which enriches motion diversity while maintaining temporal coherence and natural facial dynamics. Extensive experiments demonstrate that our method outperforms existing approaches across most metrics, achieving a 21.6\% improvement in emotion similarity while preserving physiologically plausible facial dynamics.

## Method Overview
<div align="center">
<img src="assets/framework.jpg" width="800px"/>
</div>

## Supplementary Video Materials

### Introduction Video in Different Emotions
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="videos/intro_combined_video_professional.mp4" type="video/mp4">
    </video>
    <em>Introduction Video in Different Emotions</em>
  </div>


### Comparison of Different Methods (MEAD_emo dataset)
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="videos/algorithm_comparison_m019_front_surprised_level_1_023_crop_detail.mp4.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="videos/algorithm_comparison_m033_front_angry_level_1_014_crop_detail.mp4.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="videos/algorithm_comparison_w018_front_sad_level_2_008_crop_detail.mp4.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="videos/algorithm_comparison_w024_front_disgusted_level_2_056_crop_detail.mp4.mp4" type="video/mp4">
    </video>
    <video width="80%" controls>
      <source src="videos/algorithm_comparison_w024_front_happy_level_2_007_crop_detail.mp4.mp4" type="video/mp4">
    </video>
    <em>Comparison of Different Methods (MEAD_emo dataset)</em>
  </div>

### Comparison of Different Methods (HDTF dataset)
<div class="grid-container">
  <div class="grid-item">
    <video width="80%" controls>
      <source src="videos/algorithm_comparison_wra_kristinoem1_crop_256_000_detail.mp4.mp4" type="video/mp4">
    </video>
    <em>Comparison of Different Methods (HDTF dataset)</em>
  </div>

### Weight Comparison Experiment
<div align="center">
<video width="80%" controls>
  <source src="videos/weight_comparison_fear.mp4" type="video/mp4">
</video>
<video width="80%" controls>
  <source src="videos/weight_comparison_happy.mp4" type="video/mp4">
</video>

<br>
<em>Demonstration of Different Weights Effects</em>
</div>


### Comparison of Diffrent Modalities Driven Methods
<div class="grid-container">
  <div class="grid-item">
    <video width="100%" controls>
      <source src="videos/modality_comparison_fear.mp4" type="video/mp4">
    </video>
    <video width="100%" controls>
      <source src="videos/modality_comparison_happy.mp4" type="video/mp4">
    </video>
    <video width="100%" controls>
      <source src="videos/modality_comparison_sad.mp4" type="video/mp4">
    </video>
    <em>Comparison of Diffrent Modalities Driven Methods</em>
  </div>

### Ablation Study on Different Components
<div class="grid-container">
  <div class="grid-item">
    <video width="100%" controls>
      <source src="videos/Components_comparison.mp4" type="video/mp4">
    </video>
    <em>Ablation Study on Different Components</em>
  </div>

## Citation
If you find our work useful, please consider citing:
