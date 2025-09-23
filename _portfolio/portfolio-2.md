---
title: "Continous Control with MuZero"
excerpt: "
<div style='max-width:740px; margin:0 auto; text-align:center;'>
  <em style='display:block; margin-bottom:16px; font-size:1.1em;'>
    Bachelor thesis at TU Delft on how action sampling strategies influence the performance of Sampled MuZero in continuous control. (Apr. 2024 &ndash; June 2025)
  </em>
  <div style='display:flex; justify-content:center; gap:16px;'>
    <img src='/images/sampling.png' style='width:350px; border-radius:2%;'>
    <img src='/images/cheetah.jpg' style='width:350px; border-radius:2%;'>
  </div>
</div>
"
collection: portfolio
---

[Paper](https://repository.tudelft.nl/record/uuid:964311c3-49af-4f30-b2f7-823b78c05cd1) \| [Poster](/files/muzero-poster.pdf)

During my bachelor thesis at TU Delft, I explored how **action sampling strategies** affect the performance of **Sampled MuZero**, a model-based reinforcement learning algorithm designed for continuous control tasks such as robotics.

Unlike discrete domains (e.g., chess or Go), continuous actions—like torques applied to robot joints—cannot be enumerated. Sampled MuZero addresses this by **sampling a fixed number of candidate actions** from a distribution β during Monte Carlo Tree Search (MCTS). However, little was known about how the choice of β or the use of **progressive widening** influences performance.

If you’re interested in the full technical details, including results on the Brax HalfCheetah benchmark and further experiments, you can read the paper [here](https://repository.tudelft.nl/record/uuid:964311c3-49af-4f30-b2f7-823b78c05cd1):