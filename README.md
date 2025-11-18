# Supplement material for ICLR Submission.

## Installation

We follow [DeepSeek-Prover-V1.5](https://github.com/deepseek-ai/DeepSeek-Prover-V1.5), which uses Lean 4 version 4.9 and the corresponding Mathlib. Please refer to the following instructions to set up the environments.

1. **Install Lean 4**

Follow the instructions on the [Lean 4 installation page](https://leanprover.github.io/lean4/doc/quickstart.html) to set up Lean 4.

2. **Install required packages**
```sh
conda env create -f goedelv2.yml
```

3. **Build Mathlib4**

```sh
cd mathlib4
lake build
```

## Evaluation

```sh
bash scripts/pipeline.sh
```