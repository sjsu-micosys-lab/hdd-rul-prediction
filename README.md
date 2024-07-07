# Large-scale End-of-Life Prediction of Hard Disks in Distributed Datacenters

This repository contains the code for Large-scale End-of-Life Prediction of Hard Disks in Distributed Datacenters

### Citation

#### Bibtex

```
@inproceedings{hdd=rul-prediction,
  author={Mohapatra, Rohan and Coursey, Austin and Sengupta, Saptarshi},
  booktitle={2023 IEEE International Conference on Smart Computing (SMARTCOMP)},
  title={Large-scale End-of-Life Prediction of Hard Disks in Distributed Datacenters},
  year={2023},
  volume={},
  number={},
  pages={261-266},
  doi={10.1109/SMARTCOMP58114.2023.00069}}
```

#### In text

```
R. Mohapatra, A. Coursey and S. Sengupta, "Large-scale End-of-Life Prediction of Hard Disks in Distributed Datacenters," 2023 IEEE International Conference on Smart Computing (SMARTCOMP), Nashville, TN, USA, 2023, pp. 261-266, doi: 10.1109/SMARTCOMP58114.2023.00069.
```

### Steps to run:

- Download the dataset from the links provided.
  - They are named as `data_*.zip`.
  - You will need to provide the path and list of zips to extract the data.
- Create the condensed `.csv` files by running `code/dataset/XX.ipynb` Notebooks.
  - This creates files based on the provided models in input. You will ideally need all the .csv files to reproduce results. An extension of this work is to use the Postgres Pipeline (discussed in paper) not provided in this repo.
- Run the Notebook in `code/training/XX.ipynb` to train the LSTM on this dataset.

### Dataset

[Backblaze Hard Drive Test Data (Logs)](https://www.backblaze.com/cloud-storage/resources/hard-drive-test-data)

#### Feel free to reach out to the authors with any questions about the experiments.
