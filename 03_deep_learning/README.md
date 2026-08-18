# Month 3 — Deep learning basics (Oct 2026)

**Goal:** train a neural net in PyTorch you can debug (shapes, loss, overfit a batch). Every core concept has its own folder under [`deep_dive/`](deep_dive/README.md).

**You ship:** [`04_project_mnist`](04_project_mnist/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Tensors + autograd
* [ ] MLP, activations, losses, optimizers
* [ ] Training loop you wrote (not only Lightning)
* [ ] Deep dive: all 8 topics
* [ ] MNIST project ≥90% test acc

---

## What to learn

### Tensors — [`01_tensors_autograd`](01_tensors_autograd/README.md)

* [ ] `Tensor` shapes, `view`/`reshape`, device (`cpu`/`cuda`)
* [ ] Autograd: `requires_grad`, `backward`, `.grad`
* [ ] Why you `zero_grad`

### Networks — [`02_networks_backprop`](02_networks_backprop/README.md)

* [ ] `nn.Module`, `nn.Linear`, ReLU, softmax
* [ ] Cross-entropy vs MSE for class labels
* [ ] SGD vs Adam (defaults, LR)
* [ ] Overfit 1 batch as a sanity check

### Training — [`03_training_loop`](03_training_loop/README.md)

* [ ] Dataset / DataLoader
* [ ] train vs eval, `torch.no_grad`
* [ ] Save `state_dict`, plot loss/acc
* [ ] Dropout / weight decay as regularizers

---

## Deep dive (own folder)

| # | Topic | Folder |
|---|-------|--------|
| 1 | Tensors | [`deep_dive/01_tensors`](deep_dive/01_tensors/README.md) |
| 2 | Autograd | [`deep_dive/02_autograd`](deep_dive/02_autograd/README.md) |
| 3 | Activations | [`deep_dive/03_activations`](deep_dive/03_activations/README.md) |
| 4 | Loss functions | [`deep_dive/04_loss_functions`](deep_dive/04_loss_functions/README.md) |
| 5 | Optimizers | [`deep_dive/05_optimizers`](deep_dive/05_optimizers/README.md) |
| 6 | MLP from scratch | [`deep_dive/06_mlp_from_scratch`](deep_dive/06_mlp_from_scratch/README.md) |
| 7 | DataLoader | [`deep_dive/07_dataloader`](deep_dive/07_dataloader/README.md) |
| 8 | Regularization | [`deep_dive/08_regularization`](deep_dive/08_regularization/README.md) |

---

## 1% bar

* [ ] Write a training loop from memory
* [ ] Debug a shape error in 2 minutes
* [ ] Overfit 32 images to ~100% then generalize with LR/reg

---

## Project

MNIST MLP — [`04_project_mnist/README.md`](04_project_mnist/README.md)

## Resources

* [ ] [PyTorch tensors](https://pytorch.org/tutorials/beginner/basics/tensorqs_tutorial.html)
* [ ] [PyTorch autograd](https://pytorch.org/tutorials/beginner/basics/autogradqs_tutorial.html)
* [ ] [Build the neural network](https://pytorch.org/tutorials/beginner/basics/buildmodel_tutorial.html)

Open [`DAYS.md`](DAYS.md).
