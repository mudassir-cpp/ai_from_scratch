# Month 3 — Daily tracker (Oct 2026)

Change `[ ]` → `[*]` → `[x]`.

---

## Week 1 — Tensors

### Day 1 — Install PyTorch
* [ ] CPU or CUDA install from pytorch.org
* [ ] `torch.rand(3, 4).shape`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 2 — Indexing + matmul
* [ ] Slice, `view`, `reshape`, `@`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 3 — Autograd
* [ ] backward on a tiny graph; print grads
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 4 — Manual vs autograd
* [ ] Linear + MSE grads by hand vs PyTorch
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 5 — nn.Linear
* [ ] One layer, random data, one step of Adam
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 6 — Overfit one batch
* [ ] 32 samples, train until loss ~0
* [ ] Log — hours: ___  shipped: ___  stuck: ___

---

## Week 2 — MLP

### Day 7 — Rest / review
* [ ] Explain zero_grad and train/eval
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 8 — Module
* [ ] Two-layer MLP class
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 9 — Cross-entropy
* [ ] Logits vs softmax; `F.cross_entropy`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 10 — DataLoader
* [ ] MNIST download, batch, plot 8 digits
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 11 — First full epoch
* [ ] Train 1 epoch, print loss
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 12 — Val loop
* [ ] `no_grad` accuracy
* [ ] Log — hours: ___  shipped: ___  stuck: ___

---

## Week 3 — Train properly

### Day 13 — Optimizer + LR
* [ ] SGD vs Adam, 2 LRs, table of val acc
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 14 — Regularize
* [ ] dropout or weight_decay; did val improve?
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 15 — Checkpoints
* [ ] save best val acc `state_dict`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 16 — Curves
* [ ] plot train/val loss and acc
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 17 — Shape debug
* [ ] Intentionally break a shape; fix from the error
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 18 — Repro seed
* [ ] seed everything; two runs match loss at step 1
* [ ] Log — hours: ___  shipped: ___  stuck: ___

---

## Week 4 — Project

### Day 19 — Rest / review
* [ ] Training loop from memory on paper
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 20 — Project structure
* [ ] `model.py` + `train.py`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 21 — Hit 90%
* [ ] test acc ≥ 0.90
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 22 — Error gallery
* [ ] save wrong predictions
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 23 — README
* [ ] hyperparams + how to train
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 24 — Optional CNN peek
* [ ] one `Conv2d` instead of flatten (optional)
* [ ] Log — hours: ___  shipped: ___  stuck: ___

---

## Week 5 — Ship

### Day 25 — Tests
* [ ] forward pass shape test `(B,10)`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 26 — Clean
* [ ] requirements, no dead code
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 27 — Push
* [ ] curves in `results/`
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 28 — Teach-back
* [ ] backprop in 10 lines of English
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 29 — Buffer
* [ ] leftover checkboxes
* [ ] Log — hours: ___  shipped: ___  stuck: ___

### Day 30 — Month close
* [ ] Mark month 3 `[x]` in root README
* [ ] Log — hours: ___  shipped: ___  stuck: ___
