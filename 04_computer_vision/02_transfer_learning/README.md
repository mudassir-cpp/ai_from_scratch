# Transfer learning

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

* [ ] Load `resnet18` (or MobileNet) pretrained
* [ ] Replace `fc` for your class count
* [ ] Freeze backbone → train head → unfreeze last block
* [ ] Smaller LR on backbone than head
* [ ] Measure train time vs from-scratch
