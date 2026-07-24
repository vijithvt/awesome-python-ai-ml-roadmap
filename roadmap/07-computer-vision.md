# Track B — Computer Vision

**Time:** 8–12 weeks after the shared core  
**Goal:** build and evaluate vision systems under realistic data conditions.

## Learning sequence

1. Images as tensors, color, resizing, normalization
2. CNNs and transfer learning
3. Augmentation and invariances
4. Classification metrics and error slices
5. Object detection and segmentation concepts
6. Data annotation and quality control
7. Robustness, domain shift, imbalance
8. Inference, latency, model export, monitoring

## Resources

- [PyTorch Computer Vision tutorials](https://docs.pytorch.org/tutorials/intermediate/torchvision_tutorial.html)
- [CS231n](https://cs231n.stanford.edu/) and its [notes](https://cs231n.github.io/)
- [Hugging Face Computer Vision Course](https://huggingface.co/learn/computer-vision-course/)
- [Albumentations documentation](https://albumentations.ai/docs/)
- [CVAT documentation](https://docs.cvat.ai/docs/) for annotation workflows

## Exercises

1. Visualize every preprocessing and augmentation step.
2. Verify labels after geometric transformations.
3. Compare a simple baseline with transfer learning.
4. Inspect false positives/negatives by class and capture condition.
5. Evaluate performance under blur, compression, lighting, and rotation shifts.
6. Measure per-image latency on CPU and available accelerator.
7. Select confidence thresholds from error costs.
8. Write annotation instructions and measure annotator agreement on a sample.

## Capstone: visual inspection service

Build a classifier or detector for a non-safety-critical inspection task. Include
dataset provenance, annotation quality, split-by-source to reduce leakage, transfer
learning, robustness tests, an error gallery, API/batch inference, model card, and
monitoring signals for input drift.
