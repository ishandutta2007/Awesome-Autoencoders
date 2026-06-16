# Awesome-Autoencoders
## Top AI Models and Algorithms Using Autoencoders

Autoencoders are unsupervised neural networks designed to compress input data into a lower-dimensional **latent space** and reconstruct it. They are primarily applied in **dimensionality reduction**, **anomaly detection**, and **generative tasks**.

---

### 1. Variational Autoencoders (VAEs)
* **First Used:** 2013
* **Seminal Paper:** [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)
* **How they work:** Unlike standard models, VAEs learn the *probability distribution* of data rather than mapping inputs to fixed vectors. They represent the latent space using mean and standard deviation, allowing you to sample points and generate entirely new data.
* **Use Cases:** Image generation, data augmentation, and latent interpolation.
* **Detailed Info:** [Deep Dive into VAEs](./docs/variational-autoencoders.md)

### 2. Convolutional Autoencoders (CAEs)
* **First Used:** 2011
* **Seminal Paper:** [Stacked Convolutional Auto-Encoders for Hierarchical Feature Extraction](https://www.researchgate.net/publication/221078652_Stacked_Convolutional_Auto-Encoders_for_Hierarchical_Feature_Extraction)
* **How they work:** CAEs replace standard fully connected layers with convolutional layers. This allows the model to preserve spatial hierarchies, making them highly effective for pixel-based data.
* **Use Cases:** Image compression, image segmentation, and facial feature extraction.
* **Detailed Info:** [Deep Dive into CAEs](./docs/convolutional-autoencoders.md)

### 3. Denoising Autoencoders (DAEs)
* **First Used:** 2008
* **Seminal Paper:** [Extracting and Composing Robust Features with Denoising Autoencoders](https://dl.acm.org/doi/10.1145/1390156.1390294)
* **How they work:** DAEs are trained by deliberately injecting noise into the input data and forcing the model to reconstruct the original, uncorrupted version. This forces the algorithm to learn robust, fundamental data patterns rather than merely memorizing input pixels.
* **Use Cases:** Image denoising, audio enhancement, and robust feature extraction.
* **Detailed Info:** [Deep Dive into DAEs](./docs/denoising-autoencoders.md)

### 4. Sparse Autoencoders
* **First Used:** 2007
* **Seminal Paper:** [Sparse Feature Learning for Deep Belief Networks](https://proceedings.neurips.cc/paper/2007/hash/836696dc7909383818e11f074744d2d4-Abstract.html)
* **How they work:** These algorithms apply a penalty that limits the number of active neurons (sparsity constraint) in the hidden layers. Even if the network has a large capacity, it is forced to activate only a few specific nodes, extracting granular, distinct features.
* **Use Cases:** Feature extraction and uncovering hidden structural patterns in datasets.
* **Detailed Info:** [Deep Dive into Sparse Autoencoders](./docs/sparse-autoencoders.md)

### 5. Sequence / Natural Language Autoencoders
* **First Used:** 2014
* **Seminal Paper:** [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)
* **How they work:** Adapted for sequential data, these models (like RNN Autoencoders) encode variable-length text or time-series into a fixed-length vector and decode them back.
* **Use Cases:** Neural machine translation, sentence generation, and time-series anomaly detection.
* **Detailed Info:** [Deep Dive into Sequence Autoencoders](./docs/sequence-autoencoders.md)

### 6. AutoRec & DeepRec (Recommendation Algorithms)
* **First Used:** 2015
* **Seminal Paper:** [AutoRec: Autoencoders Meet Collaborative Filtering](https://dl.acm.org/doi/10.1145/2740908.2742726)
* **How they work:** These algorithms use autoencoder architectures to predict missing values in a user-item matrix. The input is a partial rating history, and the network output reconstructs the complete user preferences.
* **Use Cases:** Collaborative filtering and recommendation engines.
* **Detailed Info:** [Deep Dive into AutoRec](./docs/autorec.md)

---

## 📺 Recommended Tutorial Video

For a visual breakdown of how Autoencoders work and how to implement them, check out this guide:

[![Autoencoders Explained](https://shields.io)](https://youtube.com)

## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Autoencoders&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Autoencoders&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Autoencoders&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Autoencoders&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>
