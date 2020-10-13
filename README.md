# Adahessian in Fastai

This is an implementation of the [AdaHessian optimizer](https://arxiv.org/pdf/2006.00719.pdf) in fastai. Adahessian is the first, practically useful, second-order optimizer to have been developed and has shown impressive performance, especially within NLP where it consistently out-performs AdamW, the field's current default optimizer.

You can find the author's implementation along with a guides about second-order methods [here](https://github.com/amirgholami/adahessian)

Author's citation:
```
@article{yao2020adahessian,
  title={ADAHESSIAN: An Adaptive Second Order Optimizer for Machine Learning},
  author={Yao, Zhewei and Gholami, Amir and Shen, Sheng and Keutzer, Kurt and Mahoney, Michael W},
  journal={arXiv preprint arXiv:2006.00719},
  year={2020}
}
```
