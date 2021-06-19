[
<img width="389" alt="Screen Shot 2021-06-18 at 5 00 22 PM" src="https://user-images.githubusercontent.com/80833988/122624788-b0fbf800-d056-11eb-94cf-45d862c05d4c.png">
](url)


# Neural Network



[
<img width="1399" alt="Screen Shot 2021-06-18 at 4 57 21 PM" src="https://user-images.githubusercontent.com/80833988/122624698-54004200-d056-11eb-89f1-09aa480062ff.png">
](url)


:star: Challenge 13

> "In this Challenge, I will assume the role of a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.
"


📌 
## Table of content
- [Overview of the project and project goals](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#work-with-github)
    - [How to install](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#how-to-install)
- [Helps recruiters](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#helps-recruiters)
- [License](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/README.md#license)




## Overview of the project and project goals

Using my new knowledge of the imbalanced-learn library, the goal is to create a Jupyter notebook that  contains logistic regression model to compare two versions of the dataset. First - the original dataset. Second- resample the data by using the RandomOverSampler module from the imbalanced-learn library.

For both cases:
- get the count of the target classes
- train a logistic regression classifier
- calculate the balanced accuracy score
- generate a confusion matrix
- generate a classification report.




## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Following libraries were imported

```
# Import the required libraries and dependencies
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/Credit_risk_resempling.git
```

now you can find repo on your desktop


* Access the report [report-template.md](https://github.com/nataliaburrey/Credit_risk_resempling/blob/main/report-template.md)
* Choose [ credit_risk_resempling.ipynb ] file to see the Jupyter Notebook with code.


## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales.

Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.

AskBCS Learning Assistant channel was used to troubleshoot some of the accuring problems outside of the classroom



## License

MIT


📔 Contact me: 
📩 nataliaburrey@gmail.com
