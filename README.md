# Deep Learning Examples

A collection of machine learning examples. Based on the course **Machine Learning Basics**, University of Debrecen.

## Project Directory (Colab Version)

You can access the Colab version of the project directly on Link:

[drive.google.com/drive/folders/1J1P-MPw_w8uqze2SuIxIy8AySrrAyc5l?usp=sharing](https://drive.google.com/drive/folders/1J1P-MPw_w8uqze2SuIxIy8AySrrAyc5l?usp=sharing)

## Project Directory (Standalone Version)

You can access the non-Colab version of the project directly on GitHub:

[github.com/KeremDUZENLI/python-scipy-machine-learning](https://github.com/KeremDUZENLI/python-scipy-machine-learning)

## Install

1. Download Python 3.6.8: [Python 3.6.8 Download](https://www.python.org/downloads/release/python-368/)
2. Check Python versions installed: `py -0`
3. Check the default version: `python --version`
4. Check python locations: `where python`
5. Verify python 3.6.x location: `...\AppData\Local\Programs\Python\Python36\python.exe`

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/KeremDUZENLI/python-scipy-machine-learning.git
   ```
2. Create a virtual environment:
   ```sh
   ...\AppData\Local\Programs\Python\Python36\python.exe -m venv myEnv
   ```
3. Activate the virtual environment:
   - **Windows**: `myEnv\Scripts\activate`
   - **Linux/macOS**: `source myEnv/bin/activate`
4. Update pip:
   ```sh
   python -m pip install --upgrade pip
   ```
5. Update setuptools:
   ```sh
   pip install --upgrade setuptools
   ```

<!-- 6. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
7. Freeze dependencies (optional):
   ```sh
   python -m pip freeze > requirements.txt
   ``` -->

## Notebooks

1. Install Jupyter:
   ```sh
   pip install jupyterlab
   ```
2. Register Python Environment:
   ```sh
   pip install jupyterlab ipykernel
   python -m ipykernel install --user --name=myEnv --display-name "Python (myEnv)"
   ```
3. Launch Jupyter:
   ```sh
   jupyter lab
   ```
4. Change Kernel:
   ```sh
   Change kernel in Jupyterlab (Select after choosing the .ipynb file) =
   Kernel → Change Kernel → Python (myEnv)
   ```

### Notebook Descriptions

- [1. ](notebooks/X.ipynb) – Basics...
- [2. ]()

## Acknowledgments

This project is based on the **Machine Learning Basics** course at the **University of Debrecen**

- **Prof. Dr. András Hajdu** – Dean, Head of Department

  - _Department of Data Science and Visualization, Faculty of Informatics, University of Debrecen_
  - Email: [hajdu.andras@inf.unideb.hu](mailto:hajdu.andras@inf.unideb.hu)

- **Dr. Balázs Harangi** – Associate Professor, Deputy Head of Department

  - _Department of Data Science and Visualization, Faculty of Informatics, University of Debrecen_
  - Email: [harangi.balazs@inf.unideb.hu](mailto:harangi.balazs@inf.unideb.hu)

- **Kerem Düzenli** – PhD Candidate, University of Debrecen

  - _Creator and maintainer of this repository_
  - Email: [kerem.duzenli@inf.unideb.hu](mailto:kerem.duzenli@inf.unideb.hu)

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b YourBranch
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```sh
   git push origin YourBranch
   ```
5. Open a pull request.

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. This means you are free to:

- **Share** – Copy and redistribute the material in any medium or format.
- **Adapt** – Remix, transform, and build upon the material.

However, **you may not use the material for commercial purposes**.

For details, see the [LICENSE](LICENSE) file or read more at [Creative Commons](https://creativecommons.org/licenses/by-nc/4.0/).

## Disclaimer

This repository is intended **only for educational and research purposes**. The authors and contributors assume no responsibility for misuse of the code or any implications arising from its use.

## Support My Work

If you find this resource valuable and would like to help support my education and doctoral research, please consider treating me to a cup of coffee (or tea) via Revolut.

<div align="center">
  <a href="https://revolut.me/krmdznl" target="_blank">
    <img src="https://img.shields.io/badge/Support%20My%20Projects-Donate%20via%20Revolut-orange?style=for-the-badge" alt="Support my education via Revolut" />
  </a>
</div> <br>
