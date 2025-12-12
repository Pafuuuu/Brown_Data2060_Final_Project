# 📊 CART Regression From Scratch — Data2060 Final Project

This project implements a fully functional CART regression tree (Classification and Regression Trees) from scratch in Python.
The implementation includes:

- Mean Squared Error (MSE) impurity

- Greedy, top-down recursive binary splitting

- Leaf prediction via region averages

- Pruning controls (max depth, min samples per leaf, impurity thresholds)

- Predict-time traversal with no external dependencies

To ensure correctness, the project includes a full suite of unit tests, comparisons with scikit-learn’s DecisionTreeRegressor, and validation on a real-world dataset (Airfield Statistics).
---

## 🛫 Airfield Dataset

The Airfield Statistics dataset contains daily weather and runway condition measurements, including:

- Days of air frost

- Precipitation

- Sunshine hours

- Humidity (%)

- Wind speed

- Weather/flight condition category

- Runway temperature metrics

Target variable:
Aircraft total movements

This dataset is used as a real-world benchmark for evaluating tree model behavior.

---

## 🛠️ Environment Setup

This project uses a conda environment for full reproducibility.

### `data2060.yml`

```yaml
name: data2060
channels:
- conda-forge
dependencies:
- python = 3.12.11
- matplotlib = 3.10.5
- pandas = 2.3.2
- scikit-learn = 1.7.1
- numpy = 2.3.2
- pytorch = 2.7.1
- jupyter
- pytest = 8.4.1
- quadprog

prefix: /opt/conda

```

### `Install the environment`
```bash
conda env create -f data2060.yml
conda activate data2060
```
## 📁 Repository Structure
```
prefix: /opt/conda
├── data/
│      ├── airfield_statistics_test.csv
│      └── airfield_statistics_train.csv                 
├── src/
│   └── final_project.ipynb 
|                   
├── data2060 presentation.pdf
| 
├── final_project.pdf
| 
├── data2060.yml
└── README.md
```
## 👤 Author

Xuanyao (Clark) Qian
Brown University, Data Science Institute

GitHub: https://github.com/Pafuuuu

Email: xuanyao_qian@brown.edu

Junhe Chen
Brown University, Data Science Institute

GitHub: https://github.com/qazwsxL

Email: junhe_chen@brown.edu

Han Huang
Brown University, Data Science Institute

GitHub: https://github.com/hanhuang-Rosie

Email: han_huang@brown.edu

Junwei Su
Brown University, Data Science Institute

GitHub: https://github.com/Pafuuuu

Email: junwei_su@brown.edu

## 📄 License

This repository is provided for academic and educational use under the MIT License.

