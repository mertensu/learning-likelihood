# Learning the Likelihood: Using DeepInference for the Estimation of Diffusion-Model and Lévy Flight Parameters (Voss, Mertens, Radev)
This repository contains the Jupyter notebooks for training of the diffusion and lévy flight model on both clean and contaminated data. There are two
additional folders named _img_ and _model\_checkpoints_ with the latter containing a pretrained network.

The datasets used for the training of the models can be downloaded from the following link:

to be inserted...

Please create a data folder at the level of _img_ and _model\_checkpoints_ with the following structure:

```bash
├── diff
│   ├── clean
│   │   ├── diff_ref_0_1.csv
│   │   ├── diff_ref_0_2.csv
│   │   ├── diff_ref_0_3.csv
│   │   ├── diff_ref_0_4.csv
│   │   └── diff_ref_0_5.csv
│   ├── contaminated
│   │   ├── diff_ref_100_1.csv
│   │   ├── diff_ref_100_2.csv
│   │   ├── diff_ref_100_3.csv
│   │   ├── diff_ref_100_4.csv
│   │   └── diff_ref_100_5.csv
│   ├── diff_test_0.csv
│   ├── diff_test_100.csv
│   ├── diff_test_sl_0.csv
│   └── diff_test_sl_100.csv
└── levy
    ├── clean
    │   ├── levy_ref_0_1.csv
    │   ├── levy_ref_0_2.csv
    │   ├── levy_ref_0_3.csv
    │   ├── levy_ref_0_4.csv
    │   └── levy_ref_0_5.csv
    ├── contaminated
    │   ├── levy_ref_100_1.csv
    │   ├── levy_ref_100_2.csv
    │   ├── levy_ref_100_3.csv
    │   ├── levy_ref_100_4.csv
    │   └── levy_ref_100_5.csv
    ├── levy_test_0.csv
    ├── levy_test_100.csv
    ├── levy_test_sl_0.csv
    └── levy_test_sl_100.csv
```
