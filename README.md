# PEVuln

## Introduction
PEVuln is a dataset created for research into *exploitable malware* by utilizing the malware vulnerability database [Malvuln](https://www.malvuln.com/ "Malvuln - Malware security vulnerabilty research and exploits targeting malware, worms and viruses"), and software vulnerability database [ExploitDB](https://www.exploit-db.com/ "Exploit Database - Exploits for Penetration Testers, Researchers, and Ethical Hackers") to create a new malware dataset. Currenlty the dataset consists of 864 vulnerable malware samples, 35,241 non-vulnerable malware samples, 1,425 vulnerable benign samples, and 7,905 non-vulnerable benign samples.

We aim to update this dataset regularly as the *Malvuln* and *ExploitDB* databases update to aid in increasing sample size for use with AI. 

More about our paper can be found [here](https://pure.qub.ac.uk/en/publications/pevuln-a-benchmark-dataset-for-using-machine-learning-to-detect-v "PEVuln: a benchmark dataset for using machine learning to detect vulnerabilities in PE malware")

If you are using or adding to this dataset in a project or publication, please reference our paper:
```
@inproceedings{ross2024pevuln,
  title={PEVuln: a benchmark dataset for using machine learning to detect vulnerabilities in PE malware},
  author={Ross, Nathan and Olukoya, Oluwafemi and Martinez-del-Rincon, Jesus and Carlin, Domhnall},
  booktitle={Conference on Applied Machine Learning for Information Security},
  year={2024},
  organization={IEEE Xplore}
}
```

## Downloading the Dataset
Because of the size of the dataset, we opted for using Git Large File Storage (LFS). To install the dataset, using ```git clone <repo>``` should work with LFS and install all files accordingly. 

## Contact
Feel free to contact Nathan (nross12@qub.ac.uk) if you have questions.
