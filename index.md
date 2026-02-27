---
title: Lucas Martini
permalink: /
---




<style>

.site-title { display: none !important; }
.site-header { display: none !important; }

/* Hide Minima's automatic page title */
.post-title,
.page-heading h1,
.page-heading {
  display: none !important;
}

.site-header + .page-content {
  padding-top: 0 !important;
}

.wrapper {
  max-width: 1100px !important;
}
  

/* Container that prevents accumulating indentation */
.projects {
    margin: 0;
    padding: 0;
  }
  
.project {
  display: flex;
  align-items: flex-start;
  gap: 20px;
}

  .project a {
    text-decoration: none;
    color: inherit;
  }

  .project-thumb {
  width: 220px !important;
  min-width: 220px;     /* prevents shrinking */
  max-width: 220px;     /* overrides theme max-width */
  height: auto;
  flex-shrink: 0;       /* prevents flex shrinking */
  display: block;
  border-radius: 6px;
}

  .project-content {
    flex: 1 1 auto;           /* take remaining space */
    min-width: 0;             /* IMPORTANT: prevents weird wrapping */
  }

  .project-content h3 {
    margin: 0 0 0px 0;
    text-align: left;
    line-height: 1.2;
    font-size: 1.05em;        /* optional: slightly smaller */
  }

  .project-meta {
    margin: 0 0 0px 0;
    font-size: 0.95em;
  }

  .project-desc {
    margin: 0 0 0px 0;
  }

  .project-links a {
    margin-right: 0px;
  }

  /* Only stack on genuinely small screens */
  @media (max-width: 520px) {
    .project {
      flex-direction: column;
    }
    .project-thumb {
      width: 100%;
      max-width: 320px;
    }
  }




.intro {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 40px;
  margin-bottom: 30px;
}
  
.intro-text {
  flex: 1;
}

.intro-photo img {
  width: 220px;
  border-radius: 10px;   /* softer look */
}
</style>



<br>
<br>




<div class="intro">

  <div class="intro-text">
    <h1>Lucas Martini</h1>
    <p>
      I am a researcher working in the field of computational neuroscience, computer vision and machine learning, with a focus on 3D pose estimation, motion capture, animal behavior analysis, and representation learning.
After I received my Bachelor's and Master's Degree at the Karlsruhe Institute of Technology (KIT), I started my PhD at the University of Tübingen and the International Max-Planck Research School for Intelligent Systems (IMPRS-IS). 
    </p>
    <p>
      Recently, I have been exploring how visual systems encode motion, shape, and social interaction.
Please find a list of recent projects and publications that I have been involved in below.
    </p>
  </div>

  <div class="intro-photo">
    <img src="/assets/images/Profile/profile.jpg" alt="Profile photo">
  </div>

</div>



---

## Projects

<div class="projects">

  
<div class="project">
  <a href="/BigMaQ/">
    <img class="project-thumb" src="/assets/images/BigMaQ/teaser.png" alt="BigMaQ teaser">
  </a>

  <div class="project-content">
    <h3>
      <a href="/BigMaQ/">
        BigMaQ: A Big Macaque Motion and Animation Dataset
      </a>
    </h3>

    <p class="project-meta">
      <strong>Lucas Martini</strong>, Alexander Lappe, Anna Bognár, Rufin Vogels, Martin A. Giese<br>
      <em>ICLR</em>, 2026
    </p>

    <p class="project-desc">
      A large-scale 3D motion dataset of rhesus macaques with detailed pose annotations, showcasing improved action recognition over classical behavioral descriptors in animals using surface based modeling.
    </p>

    <p class="project-links">
      <a href="/BigMaQ/">Project Page →</a>
    </p>
  </div>
</div>


<div class="project">
  <a href="https://www.nature.com/articles/s41467-025-60945-5">
    <img class="project-thumb" src="/assets/images/PoseTuning/Fig1.webp" alt="Pose tuning paper teaser">
  </a>

  <div class="project-content">
    <h3>
      <a href="https://www.nature.com/articles/s41467-025-60945-5">
        Keypoint-based modeling reveals fine-grained body pose tuning in superior temporal sulcus neurons
      </a>
    </h3>

    <p class="project-meta">
      Rajani Raman, Anna Bognár, Ghazaleh Ghamkhari Nejad, Albert Mukovskiy, <strong>Lucas Martini</strong>, Martin A. Giese & Rufin Vogels<br>
      <em>Nature Communications</em>, 2025
    </p>

    <p class="project-desc">
      Investigates the body pose and orientation tuning of neurons based on avatar stimuli and keypoint modeling, deepening our understanding of body pose representations in the brain.
    </p>

    <p class="project-links">
      <a href="https://www.nature.com/articles/s41467-025-60945-5">More →</a>
    </p>
  </div>
</div>


<div class="project">
  <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/28ef7ee7cd3e03093acc39e1272411b7-Abstract-Conference.html">
    <img class="project-thumb" src="/assets/images/SharedFeatures/teaser.png" alt="Shared-feature visualization teaser">
  </a>

  <div class="project-content">
    <h3>
      <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/28ef7ee7cd3e03093acc39e1272411b7-Abstract-Conference.html">
        Parallel backpropagation for shared-feature visualization
      </a>
    </h3>

    <p class="project-meta">
     Alexander Lappe, Anna Bognár, Ghazaleh Ghamkhari Nejad, Albert Mukovskiy,  <strong>Lucas Martini</strong>, Martin A. Giese, Rufin Vogels<br>
      <em>NeurIPS</em>, 2024
    </p>

    <p class="project-desc">
      A deep-learning feature visualization approach to identify shared features of body selective neurons with associated out-of-category object features.
    </p>

    <p class="project-links">
      <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/28ef7ee7cd3e03093acc39e1272411b7-Abstract-Conference.html">More →</a>
    </p>
  </div>
</div>


<div class="project">
  <a href="https://www.biorxiv.org/content/10.1101/2024.01.29.577734v2.abstract">
    <img class="project-thumb" src="/assets/images/MacAction/teaser.jpg" alt="MacAction teaser">
  </a>

  <div class="project-content">
    <h3>
      <a href="https://www.biorxiv.org/content/10.1101/2024.01.29.577734v2.abstract">
        MacAction: Realistic 3D macaque body animation based on multi-camera markerless motion capture
      </a>
    </h3>

    <p class="project-meta">
      <strong>Lucas Martini</strong>, Anna Bognár, Rufin Vogels, Martin A. Giese<br>
    </p>

    <p class="project-desc">
      Investigates the realism of full-body avatar animations based on keypoints and deep-learning based temporal interpolation.
    </p>

    <p class="project-links">
      <a href="https://www.biorxiv.org/content/10.1101/2024.01.29.577734v2.abstract">More →</a>
    </p>
  </div>
</div>
</div>

<!--
**martinivis/martinivis** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
