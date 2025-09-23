---
title: "Pruning Bayesian Neural Networks"
excerpt: "<div style='width:400px; margin:0 auto; text-align:center;'>
  <em style='display:block; margin-bottom:8px;'>
    5-month Robotics Minor team project constructing a fully autonomous transportation robot for VDL.
  </em>
  <img src='/images/BNN pruning.png' style='width:400px; border-radius:2%; margin-top:12px;'>
</div>"
collection: portfolio
---

[Paper](https://repository.tudelft.nl/record/uuid:37ad4553-de94-4d66-b0e2-11996e03ef50) \| [Poster](/files/honours-poster.pdf)

Bayesian Neural Networks are great because they don’t just make predictions—they also tell us how uncertain those predictions are. The problem is, they’re really compute-intensive. They need lots of memory and repeated forward passes, which makes them hard to use in real-world settings like edge devices or safety-critical systems.

In this work, I tackled that problem by designing a way to prune these networks at the neuron level. Instead of trimming individual weights, my method removes whole neurons while keeping the overall predictive behavior intact. Using a Wasserstein distance–based loss, the process automatically balances performance with efficiency—no manual tuning required.

The results are exciting: on benchmarks like UCI regression tasks and Fashion MNIST, I was able to cut more than 80% of the neurons while still preserving accuracy and uncertainty estimates. Even better, the pruned subnetworks often trained faster, supporting the Lottery Ticket Hypothesis in the Bayesian setting. This means we’re a step closer to making BNNs practical and scalable for real-world applications.


