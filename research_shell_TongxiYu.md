## Introduction

*Mental health* is a growing concern globally, with **suicide** being one of the leading causes of death among young adults. Identifying individuals who may be at risk of suicide and providing them with appropriate support can be challenging, especially given the stigma often associated with mental health issues. In this project, we aim to use **supervised machine learning** to classify text messages as either neutral or suicidal, based on their content. This could potentially help identify individuals who may be at risk and provide them with timely support.

## Dataset

We obtained our dataset from [Kaggle](https://www.kaggle.com/datasets/reihanenamdari/mental-health-corpus?resource=download), which originally contained 27,975 text messages. However, for the purposes of this project, we retrieved only **5,000 rows of data**. Each row of the dataset contains two columns:
- The first column contains the *text message content*.
- The second column contains the *class of the message*, with **0 representing neutral** and **1 representing suicidal**.

## Data Preparation and Model Training

To prepare our data for machine learning, we used natural language processing techniques such as:
- *Tokenization*
- *Removing stop words*
- *Stemming*

We then split our data into a training set of **3,500 rows** and a testing set of **1,500 rows**. To ensure the reliability of our results, we applied **k-fold cross validation** with 5 folds.

## Data Visualization

Below is a screenshot of the frequent words in the dataset:

![Frequent Words](/frequent_words.png)

## Model Evaluation

We fitted several supervised machine learning models to our data, including:
- **Random Forest**
- **Elastic Net**
- **Logistic Regression**
- **Boosted Tree**

We evaluated the performance of these models using various metrics such as **accuracy** and **ROC curve**. The best-performing model will be selected as the final model for classifying text messages as either neutral or suicidal.

## Shell Question
- How would you list all files in the current directory, including hidden ones?
```sh
ls -a
```

- What command would you use to find the number of lines in a file named `data.txt`?
```sh
wc -l data.txt
```
*Mental health* is a growing concern globally, with **suicide** being one of the leading causes of death among young adults. Identifying individuals who may be at risk of suicide and providing them with appropriate support can be challenging, especially given the stigma often associated with mental health issues. In this project, we aim to use **supervised machine learning** to classify text messages as either neutral or suicidal, based on their content. This could potentially help identify individuals who may be at risk and provide them with timely support.

## Dataset

We obtained our dataset from [Kaggle](https://www.kaggle.com/datasets/reihanenamdari/mental-health-corpus?resource=download), which originally contained 27,975 text messages. However, for the purposes of this project, we retrieved only **5,000 rows of data**. Each row of the dataset contains two columns:
- The first column contains the *text message content*.
- The second column contains the *class of the message*, with **0 representing neutral** and **1 representing suicidal**.

## Data Preparation and Model Training

To prepare our data for machine learning, we used natural language processing techniques such as:
- *Tokenization*
- *Removing stop words*
- *Stemming*

We then split our data into a training set of **3,500 rows** and a testing set of **1,500 rows**. To ensure the reliability of our results, we applied **k-fold cross validation** with 5 folds.

## Data Visualization

Below is a screenshot of the frequent words in the dataset:

![Frequent Words](/frequent_words.png)

## Model Evaluation

We fitted several supervised machine learning models to our data, including:
- **Random Forest**
- **Elastic Net**
- **Logistic Regression**
- **Boosted Tree**

We evaluated the performance of these models using various metrics such as **accuracy** and **ROC curve**. The best-performing model will be selected as the final model for classifying text messages as either neutral or suicidal.

## Shell Question
- How would you list all files in the current directory, including hidden ones?
```sh
ls -a
```

- What command would you use to find the number of lines in a file named `data.txt`?
```sh
wc -l data.txt
```
- How can you search for the string "error" in all `*.log` files in the current directory?
```sh
grep "error" *.log
```

- Describe how you would change the permissions of a file named `script.sh` to make it executable.
```sh
chmod +x script.sh
```

- How would you display the last 20 lines of a file named `output.log`?
```sh
tail -n 20 output.log
```

- Explain how to combine the contents of `file1.txt` and `file2.txt` into a new file named combined.txt.
```sh
cat file1.txt file2.txt > combined.txt
```

- How would you check for the presence of the word "Completed" in a file named `status.txt` and display the line containing it?
```sh
grep "Completed" status.txt
```

- What command can you use to sort the lines in a file named `unsorted.txt` in alphabetical order and save the result to a new file named `sorted.txt`?
```sh
sort unsorted.txt -o sorted.txt
```
