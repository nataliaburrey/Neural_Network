[
<img width="389" alt="Screen Shot 2021-06-18 at 5 00 22 PM" src="https://user-images.githubusercontent.com/80833988/122624788-b0fbf800-d056-11eb-94cf-45d862c05d4c.png">
](url)


# Neural Network



:star: Challenge 13

> "In this Challenge, I will assume the role of a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.
"


[
<img width="1399" alt="Screen Shot 2021-06-18 at 4 57 21 PM" src="https://user-images.githubusercontent.com/80833988/122624698-54004200-d056-11eb-89f1-09aa480062ff.png">
](url)


📌 
## Table of content
- [Overview of the project and project goals](https://github.com/nataliaburrey/Neural_Network#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/nataliaburrey/Neural_Network#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/Neural_Network#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/Neural_Network#work-with-github)
    - [How to install](https://github.com/nataliaburrey/Neural_Network#how-to-install)
- [Project findings](https://github.com/nataliaburrey/Neural_Network#project-findings)
- [Helps recruiters](https://github.com/nataliaburrey/Neural_Network#helps-recruiters)
- [License](https://github.com/nataliaburrey/Neural_Network#license)




## Overview of the project and project goals

Given CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The CSV file contains a variety of information about each business, including whether or not it ultimately became successful. 
Using machine learning and neural networks building skills, decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.


1. Create a binary classification model using a deep neural network.

2. go through three technical deliverables: 

    - Preprocess data for a neural network model.

    - Use the model-fit-predict pattern to compile and evaluate a binary classification model.

    - Optimize the model.




## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Following libraries were imported

```
# Import the required libraries and dependencies

import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

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

git clone https://github.com/nataliaburrey/Neural_Network.git
```

now you can find repo on your desktop


* Choose [ venture_funding_with_deep_learning.ipynb ] file to see the Jupyter Notebook with code.


## Project findings

Following code displaying findings for each model:
[
<img width="1082" alt="Screen Shot 2021-06-21 at 7 54 34 PM" src="https://user-images.githubusercontent.com/80833988/122855732-831ee980-d2ca-11eb-9940-05e191e2fac0.png">
](url)


Resulting models saved into RESOURCES folder:

<img width="776" alt="Screen Shot 2021-06-21 at 7 47 05 PM" src="https://user-images.githubusercontent.com/80833988/122855048-78b02000-d2c9-11eb-8dfd-97e97bb35152.png">


## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales.

Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.

AskBCS Learning Assistant channel was used to troubleshoot some of the accuring problems outside of the classroom



## License

MIT


📔 Contact me: 
📩 nataliaburrey@gmail.com
