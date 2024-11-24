# Beyond Integration: SuperGLUE Facilitates Explainable Training Framework for Multi-modal Data Analysis

This is the official implementation of **SuperGLUE**, which is an improved version of GLUE. **SuperGLUE** has better integration performances, and it is also capable of integrating arbitary numbers and arbitary omics by addressing [this issue](https://github.com/gao-lab/GLUE/pull/114). **SuperGLUE** has a statistical test framework to identify significant feature interaction.

## Install

Please refer [GLUE](https://github.com/gao-lab/GLUE) to prepare the necessary environments for running. 

Please use this instruction to install SuperGLUE

```
pip install .
```

To find the relationships between cell states and features, please install shap:

```
pip install shap
or
conda install -c conda-forge shap
```

## Tutorial

Please see the attached files for running **SuperGLUE** for multi-omic data integration.

## Acknowledgement

We thank developers of [GLUE](https://github.com/gao-lab/GLUE) for their suggestions.

## Citation

Please use the following links for citation:
```
@article{liu2024beyond,
  title={Beyond Integration: SuperGLUE Facilitates Explainable Training Framework for Multi-modal Data Analysis},
  author={Liu, Tianyu and Zhao, Jia and Zhao, Hongyu},
  journal={bioRxiv},
  pages={2024--11},
  year={2024},
  publisher={Cold Spring Harbor Laboratory}
}
```

