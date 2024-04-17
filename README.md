# Lymphoma survival analysis

Multimodal Deep Learning for survival prediction of Lymphoma patients.

## Installation
* Setup environment (virtualenv is recommend, "pip install --upgrade pip wheel setuptools" may be needed)

* Use the package manager [pip](https://pip.pypa.io/en/stable/) to install package name.

```bash
pip install [package name]
```
* Setup and login for [wandb](https://wandb.ai/site) to save logs

## Repo structure
01.data (This folder contained the data using for pre-processing and preprocessed data for training)

* PET preprocessed as '.jpg'/'.png'
* The preprocessed clinical data highly recommend as '.txt'
* Label file highly recommend as '.tsv'

02.src (This folder contained the data preprocessing, train, eval, etc.. scripts)

## Contributing
If you use this code under any purpose, please contact Pham Sy Phuc (<phamsyphuc123@gmail.com>)

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

Source code is provided 'as-is' WITHOUT any WARRANTY or SUPPORT. Using this script is at YOUR OWN RISK.



## License

This project is licensed under the terms of the [MIT](https://choosealicense.com/licenses/mit/) license.
