# 📊 Data Analysis using Pandas

A practical and beginner-friendly repository for learning **data analysis and manipulation using Python Pandas**. This project contains Jupyter Notebooks covering fundamental to intermediate Pandas concepts, with hands-on examples and sample datasets.

Pandas is an open-source Python library designed for efficient data manipulation, analysis, and working with tabular data.

---

## 🚀 About the Project

This repository is designed to build a strong foundation in **Pandas and Data Analysis** through practical Jupyter Notebook examples.

The notebooks demonstrate how to:

* Create and work with Pandas DataFrames
* Load and process CSV files
* Select and filter data
* Clean and preprocess datasets
* Transform data
* Aggregate and group data
* Merge and join multiple datasets
* Reshape data using Melt and Pivot
* Perform practical data manipulation operations

The repository is especially useful for **students, beginners in Data Science, and Python developers** who want hands-on experience with Pandas.

---

## 📚 Topics Covered

| # | Topic                         | Notebook                                |
| - | ----------------------------- | --------------------------------------- |
| 1 | Core Data Structures          | `Core_Data_Structures_in_Pandas.ipynb`  |
| 2 | Creating DataFrames           | `Creating_Data_Frames.ipynb`            |
| 3 | CSV Data Handling             | `Working_with_Csv.ipynb`                |
| 4 | Data Selection & Filtering    | `Data_Selection_Filtering.ipynb`        |
| 5 | Data Cleaning & Preprocessing | `Data_Cleaning_and_preprocessing.ipynb` |
| 6 | Data Transformation           | `Data_Transformation.ipynb`             |
| 7 | Aggregation & Grouping        | `Aggregation_and_Grouping.ipynb`        |
| 8 | Merging & Joining             | `Merging_and_Joining.ipynb`             |
| 9 | Melt & Pivot                  | `Melt_and_Pivot.ipynb`                  |

---

## 🗂️ Repository Structure

```text
Data-Analysis-using-Pandas/
│
├── Aggregation_and_Grouping.ipynb
├── Core_Data_Structures_in_Pandas.ipynb
├── Creating_Data_Frames.ipynb
├── Data_Cleaning_and_preprocessing.ipynb
├── Data_Selection_Filtering.ipynb
├── Data_Transformation.ipynb
├── Melt_and_Pivot.ipynb
├── Merging_and_Joining.ipynb
├── Working_with_Csv.ipynb
│
├── data.csv
├── data_cleaning_sample.csv
├── data_updated.csv
│
└── README.md
```

---

## 🛠️ Technologies Used

* 🐍 **Python**
* 🐼 **Pandas**
* 📓 **Jupyter Notebook**
* 📄 **CSV**

Pandas provides data structures and tools for data analysis and manipulation in Python.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/sarhan-003/Data-Analysis-using-Pandas.git
```

### 2. Navigate to the Project

```bash
cd Data-Analysis-using-Pandas
```

### 3. Install Required Libraries

```bash
pip install pandas jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any `.ipynb` file and run the cells.

---

## 💡 Learning Path

For beginners, it is recommended to follow the notebooks in this order:

```text
Core Data Structures
        ↓
Creating DataFrames
        ↓
Working with CSV
        ↓
Data Selection & Filtering
        ↓
Data Cleaning & Preprocessing
        ↓
Data Transformation
        ↓
Aggregation & Grouping
        ↓
Merging & Joining
        ↓
Melt & Pivot
```

This progression moves from basic Pandas structures toward more advanced data manipulation techniques.

---

## 📌 Key Pandas Concepts

### DataFrames

Learn how to create and work with two-dimensional tabular data.

```python
import pandas as pd

data = {
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [21, 25, 23]
}

df = pd.DataFrame(data)

print(df)
```

### Reading CSV Files

```python
df = pd.read_csv("data.csv")

print(df.head())
```

### Selecting Data

```python
df["Name"]
```

### Filtering Data

```python
filtered_df = df[df["Age"] > 22]
```

### Grouping Data

```python
df.groupby("Department")["Salary"].mean()
```

### Merging DataFrames

```python
merged_df = pd.merge(df1, df2, on="ID")
```

### Reshaping Data

Pandas provides tools such as `melt()` and `pivot()` for changing the structure of tabular datasets.

```python
df.melt()
```

---

## 📈 Skills Developed

By completing this repository, you can develop practical knowledge of:

* Data manipulation
* Data cleaning
* Data preprocessing
* Exploratory data analysis fundamentals
* DataFrame operations
* CSV data processing
* Grouping and aggregation
* Dataset merging
* Data reshaping
* Working with real tabular datasets

---

## 🎯 Who Is This For?

This repository is suitable for:

* 👨‍🎓 Python & Data Science students
* 📊 Aspiring Data Analysts
* 🤖 Beginners learning Data Science
* 🐍 Python developers
* 📚 Anyone learning Pandas
* 💼 Students building a Data Science portfolio
* Improving analytical skills

---

## 🔮 Future Improvements

Possible additions to this repository include:

* [ ] Exploratory Data Analysis projects
* [ ] Data visualization using Matplotlib
* [ ] Data visualization using Seaborn
* [ ] Statistical analysis
* [ ] Real-world datasets
* [ ] Mini data analysis projects
* [ ] Advanced Pandas techniques
* [ ] Time-series analysis
* [ ] More practical exercises

---

## 🤝 Contributing

Contributions are welcome!

If you would like to improve this repository:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/new-topic
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add new Pandas example"
```

5. Push the branch

```bash
git push origin feature/new-topic
```

6. Open a Pull Request

---

## ⭐ Support

If you find this repository useful for learning Pandas, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Sarhan Bakarman**

GitHub: [@sarhan-003](https://github.com/sarhan-003)

---

## 📜 License

This project is intended for **educational and learning purposes**.

---

### 🔗 Repository

[Data Analysis using Pandas](https://github.com/sarhan-003/Data-Analysis-using-Pandas)
