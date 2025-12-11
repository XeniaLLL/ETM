# Solving Discrete (Semi) Unbalanced Optimal Transport with Equivalent Transformation Mechanism and KKT-Multiplier Regularization 
[NeurIPS25](https://openreview.net/forum?id=rzjWktciDM) 

## Abstract
Semi-Unbalanced Optimal Transport (SemiUOT) shows great promise in matching two probability measures by relaxing one of the marginal constraints. Previous solvers often incorporate an entropy regularization term, which can result in inaccurate matching solutions. To address this issue, we focus on determining the marginal probability distribution of SemiUOT with KL divergence using the proposed Equivalent Transformation Mechanism (ETM) approach. Furthermore, we extend the ETM-based method into exploiting the marginal probability distribution of Unbalanced Optimal Transport (UOT) with KL divergence for validating its generalization. Once the marginal probabilities of UOT/SemiUOT are determined, they can be transformed into a classical Optimal Transport (OT) problem. Moreover, we propose a KKT-Multiplier regularization term combined with Multiplier Regularized Optimal Transport (MROT) to achieve more accurate matching results. We conduct several numerical experiments to demonstrate the effectiveness of our proposed methods in addressing UOT/SemiUOT problems.

## Citation
If you find HyperFed useful or inspiring, please consider citing our paper:
```bibtex
@inproceedings{liao2023hyperfed,
  title={Solving Discrete (Semi) Unbalanced Optimal Transport with Equivalent Transformation Mechanism and KKT-Multiplier Regularization},
  author={Liu, Weiming and Liao, Xinting and Dan, Jun and Wang, Fan and Yu, Hua and Dong, Junhao and Dong, Shunjie and Qi, Lianyong and Ong, Yew-Soon},
  booktitle={The Thirty-ninth Annual Conference on Neural Information Processing Systems}
  year={2025}
}
```
