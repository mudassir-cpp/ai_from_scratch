# Month 4 — Computer vision (Nov 2026)

**Goal:** convolution, transfer learning, and an image model you can retrain. Each CNN topic has its own folder under [`deep_dive/`](deep_dive/README.md).

**You ship:** [`03_project_image_classifier`](03_project_image_classifier/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] CNN mechanics
* [ ] Augmentation + regularization
* [ ] Transfer learning (ResNet or similar)
* [ ] Deep dive: all 6 topics
* [ ] Image classifier project shipped

---

## What to learn

### CNNs — [`01_cnns`](01_cnns/README.md)

* [ ] Conv, stride, padding, pooling, receptive field
* [ ] Why conv beats a giant Linear on images
* [ ] BatchNorm, dropout
* [ ] Tiny CNN from scratch on CIFAR-10 or Fashion-MNIST

### Transfer — [`02_transfer_learning`](02_transfer_learning/README.md)

* [ ] Pretrained backbone, freeze vs fine-tune last blocks
* [ ] ImageNet normalization
* [ ] Augmentation: flip, crop, color jitter — train only

---

## Deep dive (own folder)

| # | Topic | Folder |
|---|-------|--------|
| 1 | Convolution | [`deep_dive/01_convolution`](deep_dive/01_convolution/README.md) |
| 2 | Pooling & BatchNorm | [`deep_dive/02_pooling_batchnorm`](deep_dive/02_pooling_batchnorm/README.md) |
| 3 | CNN architectures | [`deep_dive/03_cnn_architectures`](deep_dive/03_cnn_architectures/README.md) |
| 4 | Data augmentation | [`deep_dive/04_data_augmentation`](deep_dive/04_data_augmentation/README.md) |
| 5 | Transfer learning | [`deep_dive/05_transfer_learning`](deep_dive/05_transfer_learning/README.md) |
| 6 | Fine-tuning | [`deep_dive/06_fine_tuning`](deep_dive/06_fine_tuning/README.md) |

---

## 1% bar

* [ ] Draw a conv layer: in/out channels, kernel, spatial size
* [ ] Fine-tune a pretrained net and beat your from-scratch CNN
* [ ] Write failure cases (lighting, class confusion)

---

## Project

Image classifier — [`03_project_image_classifier/README.md`](03_project_image_classifier/README.md)

## Resources

* [ ] [PyTorch CIFAR tutorial](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html)
* [ ] [Transfer learning](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html)

Open [`DAYS.md`](DAYS.md).
