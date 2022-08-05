# Multi-perspective Scientific Document Summarization Shared Task


We use a modified fork of [huggingface transformers](https://github.com/huggingface/transformers) for our experiments.


* Use the newly created environment for running rest of the commands.

#### Install environment

```sh
pip install requirements.txt
```

### Data format:

* We used the dataset released in the [MuP2022](https://github.com/allenai/mup) shared task

* Make sure to create `train, dev, test' csv files with column names "text" and "summary"


### Run the script

To fine-tune any huggingface model you can use the `run.sh` script. When running the different models described in the paper, ensure you pass the appropriate arguments.

```sh
sh run.sh
```
