# Multi-perspective Scientific Document Summarization Shared Task


We use a modified fork of [huggingface transformers](https://github.com/huggingface/transformers) for our experiments.

#### Install environment

```sh
pip install requirements.txt
```

### Data format:

* We used the dataset released from [MuP2022](https://github.com/allenai/mup) github

* Make sure to create `train, dev, test' csv files with column names "text" and "summary"


### Run the script

To run the any sequence to sequence model you can use the `run.sh` script.

```sh
sh run.sh
```
