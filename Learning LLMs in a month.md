# The philosophy of ML
- [Bitter lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html)
## Resources
- [Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- [nanoGPT](https://github.com/karpathy/nanoGPT)
# Course plan
## Week 1: Neural Network Fundamentals
- Basic neural networks with visual intuition
    - Neurons, layers, and activation functions
    - Gradient descent with clear visualizations
    - Backpropagation explained using chain rule
- Practical coding: Build and train a feedforward network on MNIST
    - Focus on understanding forward/backward passes
    - Experiment with different architectures/hyperparameters
    - Visualize gradients and learning process
## Week 2: Attention and Self-Attention
- Moving from feedforward to attention
    - Query/Key/Value intuition
    - Understanding attention weights visually
- Practical exercise: Implement attention mechanism
    - Start with associative recall task
    - Extend to modular arithmetic if time permits
- Text processing fundamentals
    - Tokenization and embeddings
    - Positional encoding
## Week 3: GPT Architecture and Generation
- GPT architecture deep-dive
    - Multi-head attention
    - Layer normalization and residual connections
- Generation strategies
    - Implementing KV-cache from scratch
    - Different sampling methods (greedy, temperature, top-k)
    - Hands-on: Build a simple speculative decoding system
- Understanding probability distributions in generation
## Week 4: Training and Fine-tuning
- Working with nanoGPT
    - Code walkthrough
    - Training a small model
- Parameter-efficient fine-tuning
    - Understanding LoRA
    - Implementing and experimenting with LoRA
    - Comparing full fine-tuning vs LoRA
- Final project options:
    1. Train a small model from scratch on custom dataset
    2. Fine-tune existing model using LoRA
    3. Build an efficient generation pipeline with speculative decoding