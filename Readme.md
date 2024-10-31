# Training a Transformer model for Predicting if statements

## Recent updates
- 🔥 **News**: ``2024/10/31``: The [Dataset](https://drive.google.com/drive/folders/100X2rtYo3oV4Rt9cPjkDi3z2hU9_csr7?usp=sharing) creation has been completed.


# 📗 Dataset Creation Procedure
For every research data is very importent. In this assignment, we need almost ```200k``` of data where we'll use ```150k``` for training the model and ```50k``` for testing the model. To collect the data we use [SEART](https://seart-ghs.si.usi.ch/) website. We use only 2 main parameters to collect the github repositories, first of all the number of contributers should be at least ```100``` and the code lines should be more than ```1000``` lines. We use this because we want to ensure that we can collect larger projects and our procedure will be easy.\
```Step 1:``` Collect the repos from ```SEART``` website.\
```Step 2:``` Save all the repos links as ```repo_links.csv```\
```Step 3:``` Clone the repository\
```Step 4:``` Find the file that endswith ```.py```\
```Step 5:``` Check if there any methods present in that file that contains ```if``` conditions\
```Step 5:``` If any methods contains the ```if``` conditions save that file into ```csv`` file
