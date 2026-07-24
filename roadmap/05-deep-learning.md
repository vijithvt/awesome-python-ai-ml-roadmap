# Stage 5 — Deep Learning with PyTorch

**Time:** 6–10 weeks  
**Prerequisite:** classical ML and gradients  
**Goal:** train, debug, evaluate, and package neural models.

## Learning sequence

1. Tensors, shapes, devices, dtypes
2. Datasets, data loaders, transforms
3. Modules, forward pass, loss, autograd
4. Training/validation loops and checkpoints
5. Optimizers, schedules, initialization, regularization
6. CNNs and transfer learning
7. Sequence and attention concepts
8. Experiment tracking and reproducibility
9. Error analysis, robustness, inference optimization

## Primary resources

- [PyTorch Learn the Basics](https://docs.pytorch.org/tutorials/beginner/basics/intro.html)
- [Dive into Deep Learning](https://d2l.ai/) — interactive, code-first reference
- [fast.ai Practical Deep Learning](https://course.fast.ai/) — applied alternative
- [CS231n notes](https://cs231n.github.io/) for vision concepts

Choose PyTorch as the first framework. Learn another framework only when a project or
employer requires it; the underlying concepts transfer.

## Exercises

1. Trace shapes through a multilayer network by hand and in code.
2. Implement a training loop without a high-level trainer.
3. Deliberately overfit a tiny batch to validate the pipeline.
4. Plot training/validation curves and diagnose three failure modes.
5. Compare training from scratch with transfer learning.
6. Run an ablation for augmentation, regularization, or architecture.
7. Make results reproducible and document remaining nondeterminism.
8. Profile inference latency and model size.
9. Create a model card with class-wise errors and unsafe uses.

## Build: transfer-learning classifier

Choose a modest, openly licensed image or text dataset. Build:

- deterministic data preparation and documented splits;
- baseline, pretrained model, and controlled comparison;
- training configuration and tracked experiments;
- class-wise metrics, qualitative error gallery, and limitations;
- saved artifact plus batch/online inference;
- CPU fallback and clear hardware requirements.

## Checkpoint

From a blank file, write and explain the data pipeline, model, training loop,
validation, checkpointing, and inference path. Debug one intentional shape or device
error without pasting the stack trace into an AI assistant.
