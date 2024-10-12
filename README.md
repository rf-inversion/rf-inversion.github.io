# Semantic Image Inversion and Editing using Stochastic Rectified Differential Equations

PyTorch implementation of [**Semantic Image Inversion and Editing using Stochastic Rectified Differential Equations**](https://arxiv.org/pdf/2405.17401).


<!-- **[Code will be released soon...]**   -->


Rectified flows for image inversion and editing. Our approach efficiently inverts reference style images in (a) and (b) without requiring text descriptions of the images and applies desired edits based on new prompts (e.g. “a girl” or “a dwarf”). For a reference content image (e.g. a cat in (c) or a face in (d)), it performs semantic image editing  e.g. “ sleeping cat”) and stylization (e.g. “a photo of a cat in origmai style”) based on prompts, without leaking unwanted content from the reference image (input images have orange borders).

![teaser](./data/main.png)


## 🔥 Updates
- **[2024.05.29]** [Paper](https://arxiv.org/pdf/2405.17401) is published on arXiv!


## Citation

```
@article{rout2024rfinversion,
  title={Semantic Image Inversion and Editing using Stochastic Rectified Differential Equations},
  author={Litu Rout and Yujia Chen and Nataniel Ruiz and Constantine Caramanis and Sanjay Shakkottai and Wen-Sheng Chu},
  journal={arXiv preprint arXiv:2405.17401},
  year={2024}
}
```

<!-- ## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=LituRout/RB-Modulation&type=Date)](https://star-history.com/#LituRout/RB-Modulation&Date) -->

## Licenses

Copyright © 2024, Google LLC. All rights reserved.
