<div align="center">
    <p>
    <img src="./src/title.png" alt="imagintalk Logo" style="weight: 200px;">
    </p>
     <p>
    Official project of demo samples for <br>
    <b><em>Shushing! Let's Imagine an Authentic Speech from the Silent Video</em></b>
    </p>
     <a href="https://arxiv.org/abs/2503.14928"><img src="https://img.shields.io/badge/arXiv-2503.14928-b31b1b.svg" alt="arxiv"></a>    
    <a href="https://imagintalk.github.io"><img src="https://img.shields.io/badge/Project-ImaginTalk-blue" alt="project"></a>
    <a href="https://github.com/imagintalk/imagintalk.github.io"><img src="https://img.shields.io/badge/Python-3.8+-orange" alt="version"></a>
    <a href="https://github.com/imagintalk/imagintalk.github.io"><img src="https://img.shields.io/badge/PyTorch-2.0+-brightgreen" alt="python"></a>
    <a href="https://github.com/imagintalk/imagintalk.github.io"><img src="https://img.shields.io/badge/License-MIT-red.svg" alt="mit"></a>
</div>


### 📰 News
* 20/03/2025 Released the Web project.
  

### 📕Introduction

Vision-guided speech generation aims to produce authentic speech from facial appearance or lip motions without relying on auditory signals, offering significant potential for applications such as dubbing in filmmaking and assisting individuals with aphonia. Despite recent progress, existing methods struggle to achieve unified cross-modal alignment across semantics, timbre, and emotional prosody from visual cues, prompting us to propose *Consistent Video-to-Speech (CV2S)* as an extended task to enhance cross-modal consistency. To tackle emerging challenges, we introduce **ImaginTalk**, a novel cross-modal diffusion framework that generates faithful speech using only visual input, operating within a discrete space. Specifically, we propose a discrete lip aligner that predicts discrete speech tokens from lip videos to capture semantic information, while an error detector identifies misaligned tokens, which are subsequently refined through masked language modeling with BERT. To further enhance the expressiveness of the generated speech, we develop a style diffusion transformer equipped with a face-style adapter that adaptively customizes identity and prosody dynamics across both the channel and temporal dimensions while ensuring synchronization with lip-aware semantic features. Extensive experiments demonstrate that ImaginTalk can generate high-fidelity speech with more accurate semantic details and greater expressiveness in timbre and emotion compared to state-of-the-art baselines.


<div align="center">
    <p>
    <img src="./src/main.png" alt="imagintalk.github.io pipeline" style="weight: 350px;">
    </p>
</div>
