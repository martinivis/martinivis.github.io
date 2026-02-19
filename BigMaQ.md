---
permalink: /BigMaQ/
---

<link rel="stylesheet" href="/assets/css/style.css">

<h1 class="paper-title">
BigMaQ: A Big Macaque Motion and Animation Dataset Bridging Image and 3D Pose Representations
</h1>


### ICLR 2026

<p align="center">

<b>Lucas Martini¹² · Alexander Lappe¹² · Anna Bognár³ · Rufin Vogels³ · Martin A. Giese¹</b><br><br>

¹ Hertie Institute, University of Tübingen &nbsp;&nbsp;
² IMPRS-IS &nbsp;&nbsp;
³ KU Leuven<br><br>

</p>

<p align="center">
<a href="https://arxiv.org">📄 Paper</a> |
<a href="https://github.com">💻 Code</a> |
<a href="#">📊 Dataset</a> |
<a href="#">🎞 Video</a>
</p>


<div align="center">
  <img src="/assets/images/BigMaQ/teaser.png" width="700">
</div>

---

## Abstract
<div class="abstract-box">
The recognition of dynamic and social behavior in animals is fundamental for advancing several areas of the life sciences, including ethology, ecology, medicine and neuroscience. Recent progress in deep learning has enabled an automated recognition of such behavior from video data. However, an accurate reconstruction of the three-dimensional (3D) pose and shape has not been integrated into this process. Especially for non-human primates, the animals phylogenetically closest to humans, mesh-based tracking efforts lag behind those for other species, leaving pose descriptions restricted to sparse keypoints that are unable to fully capture the richness of action dynamics. To address this gap, we introduce the <b>Big Ma</b>ca<b>Q</b>ue 3D Motion and Animation Dataset (<b>BigMaQ</b>), a large-scale dataset comprising more than 750 scenes of interacting rhesus macaques with detailed 3D pose descriptions of skeletal joint rotations. Recordings were obtained from 16 calibrated cameras and paired with action labels derived from a curated ethogram. Extending previous surface-based animal tracking methods, we construct subject-specific textured avatars by adapting a high-quality macaque template mesh to individual monkeys. This allows us to provide pose descriptions that are more accurate than previous state-of-the-art surface-based animal tracking methods. From the original dataset, we derive BigMaQ500, an action recognition benchmark that links surface-based pose vectors to single frames across multiple individual monkeys. By pairing features extracted from established image and video encoders with and without our pose descriptors, we demonstrate substantial improvements in mean average precision (mAP) when pose information is included. With these contributions, <b>BigMaQ</b> establishes the first dataset that both integrates dynamic 3D pose-shape representations into the learning task of animal action recognition and provides a rich resource to advance the study of visual appearance, posture, and social interaction in non-human primates.
</div>
---

## Citation

```
@inproceedings{martini2026bigmaq,
  title     = {BigMaQ: A Big Macaque Motion and Animation Dataset Bridging Image and 3D Pose Representations},
  author    = {Martini, Lucas and Lappe, Alexander and Bogn{\'a}r, Anna and Vogels, Rufin and Giese, Martin A.},
  booktitle = {International Conference on Learning Representations (ICLR)},
  year      = {2026}
}
```

