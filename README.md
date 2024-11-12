# G11 Machine Translation Project

This is the team project for CS4248.

**The codes in the file `MT.ipynb` contain the final submission version for our project.
Other codes in the `optuna/` and `prefix_lora/` directories are tuning codes.**


## Directory Structure

- **`test_data/`**: Contains testing data files for model evaluation.
- **`src/`**: The main source code directory.
  - **`optuna/`**: Contains the code used for hyperparameter tuning with Optuna.
  - **`prefix_lora/`**: Contains the code implementing prefix tuning and LoRA (Low-Rank Adaptation) methods.
  - **`MT.ipynb`**: This is the final notebook file where our best model, based on the results of tuning and optimization,
  is implemented and saved. This version represents the optimal model configuration for the project submission.

## Reference

- **Model**: The initial model is based on the MarianMT architecture, sourced from [Helsinki-NLP/OPUS-MT-train](https://github.com/Helsinki-NLP/OPUS-MT-train). This pre-trained multilingual model serves as the base for our experiments and fine-tuning processes.
- **Training Datasets**: The training data used to fine-tune the model are:
  - [ALMA-Human-Parallel](https://huggingface.co/datasets/haoranxu/ALMA-Human-Parallel)
  - [X-ALMA-Parallel-Data](https://huggingface.co/datasets/haoranxu/X-ALMA-Parallel-Data)

