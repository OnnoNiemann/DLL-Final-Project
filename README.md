# Knowledge Distillation and Student Teacher Models
Author: Onno Niemann

- Problem knowledge distillation aims to solve: Complex models are slow at inference and require large memory -> especially problematic when deployed to small devices

- Idea: Distill knowledge of complex model (teacher) into simpler model (student) to save memory and enable fast inference

![grafik](https://user-images.githubusercontent.com/99264777/153218936-8e8c28bd-fb78-43be-8d56-4ca33d6ef07e.png)

## Outline of Notebook
1. Load MNIST Data
2. Define LeNet-5 Model Architecture
3. Teacher Training
4. Knowledge Distillation - Loss Function and Detailed Background
5. Knowledge Distillation (Student Training)
6. Experiments
7. Conclusions and Future Research

## References

- Hinton G, Vinyals O, Dean J. 2015. Distilling the Knowledge in a Neural Network.

- LeCun Y, Bottou L, Bengio Y, Haffner P. 1998. Gradient-Based Learning Applied to Document Recognition. In: Proceedings of the IEEE, volume 86. pp. 2278 - 2324.

- Stanton S, Izmailov P, Kirichenko P, Alemi A, Wilson A. 2021. Does Knowledge Distillation Really Work?. 35th Conference on Neural Information Processing Systems (NeurIPS 2021), Sydney, Australia.

## Image References

- https://towardsdatascience.com/knowledge-distillation-simplified-dd4973dbc764. Time of access: 02.02.2022.
