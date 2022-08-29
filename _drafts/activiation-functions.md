# Lessons from 2018 Fast.AI Deep Learning Course

## PyTorch
-1 means however large a mini-batch is.

## Cycle Length
?

## Test Time Augmentation (TTA)
?

## Finding Optimal Learning Rate


## Differential Learning Rate

Freezing a layer means the weights in the layer do not change when we perform back-propagation.

Used with transfer learning.
Unfreezing different subsets of layers is different.
With differential learning rates we retrain the entire network but different subsets of the network have different learning rates. This is because the earlier layers likely won't need to be changes as much as the later layers.

## Activiation Functions


Each activation function has it's own personality.



ReLU:


Softmax:
- is appropriate when only one class is selected (single-label classification. Not suitable for multi-label classification.
- the sum of all the outputs equals to one.

Sigmoid:
- used for multilabel problem.
- now multiple entries can be high at once.
- now each output can have a probability between zero and one.

<img src="https://latex.codecogs.com/png.latex?\dpi{300}&space;y&space;=&space;mx&plus;b" title="y = mx+b" />

## Metrics

F-beta_score
The balance between false positives and false negatives


##

Audio, images, text is all Unstructred Data.
Structured Data would be a database. Each row is an observation. This is where pandas come in useful.

Relational dataset. Multiple datasets that are connected together.


