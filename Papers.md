## Papers

[Wavenet: a Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499)
- Proposes a neural network to generate raw audio waveforms (not spectrograms)
- Uses causal convolutions to acheve this by predicting the waveform in an autogregressive manner
- Used atrous causal convolutions to increace the receptive field and used gated nonlinearities
- Expirements include speech generation, text to speech and music generation

[Neural Synthesis of Binaural Speech from Mono Audio](https://openreview.net/pdf?id=uAX8q61EVRu)
- Novel method to create stereo audio from mono audio (speech recording) conditioned on a relative position between the listener and the source
- Uses a "time warp" neural network to create the stereo audio with temporal consistency
- Released a new large dataset of in the wild binaural audio
- Insight/proofs as to why L1 reconstruction is better than L2 for raw audio signals

[Improved Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2102.09672)
- Shows ways to increace the sample quality of Denoising Diffusion Probabilistic Models (DDPMs)
- This is done by making the model learn the covariance in addition to the mean of the samples
- Shows many comparisons to GANs

[Reward is Enough](https://www.sciencedirect.com/science/article/abs/pii/S0004370221000862)
- Argues that maximising reward is sufficent to acheve intelligence
- Hypothesis that the generic objective of reward maximisation can create all inteligent behaviours
- In a multi-agent system, other agents are part of the environment