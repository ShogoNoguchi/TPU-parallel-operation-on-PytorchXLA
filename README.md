低レベルAPIを用いた実装によって、TPUの動作を深く理解しました。
# TPU-parallel-operation-on-PytorchXLA
I realized parallel operation codes of TPU with pytorchXLA. The basic code is the same as the official pytorch tutorial. However, in order to run it in parallel, I reconstructed it while looking at the official XLA tutorial.

I have reconstructed the official pytorch tutorial below.

https://pytorch.org/tutorials/beginner/basics/optimization_tutorial.html


Today, I could only use one core because TPU was popular. But the code should be correct, so I'll try it again.

Learning can be done according to the number of cores available at the time.

Comments are welcome.
