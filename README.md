# Student Performance Indicator

### Problem Statement
In this project, the system in focus is the Student Performance in exams. We built a model that predicts the marks of students considering various features like ['gender', 'race_ethnicity', 'parental_level_of_education', 'lunch', 'test_preparation_course' , 'math_score', 'reading_score', 'writing_score']. 


## Tech Stack Used
1. Python 
2. Pandas 
3. Numpy
4. Matplotlib
5. Machine learning algorithms
6. Docker


### Step 1: Clone the repository
```bash
git clone https://github.com/vishalsingh3363/ML_PROJECT.git
```

### Step 2- Create a conda environment after opening the repository

```bash
conda create -n venv python=3.8 -y
```

```bash
conda activate sensor
```

### Step 3 - Install the requirements
```bash
pip install -r requirements.txt
```


### Step 4 - Run the application server
```bash
python src/components/data_ingestion.py
