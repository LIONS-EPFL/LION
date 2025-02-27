[![arXiv](https://img.shields.io/badge/arXiv-2502.16249-B31B1B?style=for-the-badge&logo=arXiv&logoColor=white)](https://www.arxiv.org/abs/2502.16249)

# LION 🦁

This repository includes the codes for LION model on image classification and Masked Language Modleing. Our Image Classification repo is based on [Deit](https://github.com/facebookresearch/deit) and the MLM is based on [M2-BERT](https://github.com/HazyResearch/m2/tree/main).

# Image Classification

`python -m torch.distributed.launch --nproc_per_node=4 --use_env main.py --model lion_base_patch16_224 --batch-size 256 --data-path /datapath --output_dir /outputpath --mask_type Decay --order S --format Attention`






# Citation
If you use this work, please consider citing the paper:

```
@article{afzal2025linear,
  title={Linear Attention for Efficient Bidirectional Sequence Modeling},
  author={Afzal, Arshia and Abad Rocamora, Elias and Candogan, Leyla Naz and Puigdemont, Pol and Tonin, Francesco and Wu, Yongtao and Shoaran, Mahsa and Cevher, Volkan},
  journal={arXiv preprint arXiv:2502.16249},
  year={2025},
  url={https://arxiv.org/abs/2502.16249},
  doi={10.48550/arXiv.2502.16249}
}
```

----------

# Commercial License


##### © All rights reserved. ECOLE POLYTECHNIQUE FEDERALE DE LAUSANNE, Switzerland, Laboratory for Information and Inference Systems (LIONS), 2025. See the [LICENSE.TXT](https://github.com/LIONS-EPFL/LION/blob/main/LICENSE.txt) file for more details
