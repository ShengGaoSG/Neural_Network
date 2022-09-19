
# Neural Network



Challenge 13

> "In this Challenge, I will assume the role of a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.
"


## Table of content
- [Overview of the project and project goals](https://github.com/ShengGaoSG/Neural_Network#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/ShengGaoSG/Neural_Network#software-version-control)
    - [Libraries](https://github.com/ShengGaoSG/Neural_Network#libraries)
    - [Work with GitHub](https://github.com/ShengGaoSG/Neural_Network#work-with-github)
    - [How to install](https://github.com/ShengGaoSG/Neural_Network#how-to-install)
- [Project findings](https://github.com/ShengGaoSG/Neural_Network#project-findings)
- [License](https://github.com/ShengGaoSG/Neural_Network#license)




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

git clone https://github.com/ShengGaoSG/Neural_Network.git
```

now you can find repo on your desktop


* Choose [ venture_funding_with_deep_learning.ipynb ] file to see the Jupyter Notebook with code.


## Project Findings
Following code displaying findings for each model:
<img width="840" alt="Screen Shot 2022-09-19 at 1 16 24 AM" src="https://user-images.githubusercontent.com/107383254/190953669-a6caf667-cd18-4547-aa63-baaca9384907.png">



Resulting models saved into RESOURCES folder:
<img width="584" alt="Screen Shot 2022-09-19 at 1 17 13 AM" src="https://user-images.githubusercontent.com/107383254/190953707-ba594717-258a-4a18-b294-ce3e3a1e8eb7.png">

## License

MIT


📔 Contact me: 
📩 sheng_gao@outlook.com
