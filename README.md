# ROB535-Tean13-Final-Project
Part 1 of the Perception final project for ME599/NAVARCH565/ROB535 Fall2021, Team 13. 
Team members: 
Heming Huang, Jingyu Song, Michelle Ji, Min Deng, Tingjun Li, Yingxue Wang



## Data and Resources

Link to Kaggle Competition: [here](https://www.kaggle.com/c/rob535-fall2021-task1/overview).

Data to competition: [here](https://drive.google.com/drive/u/1/folders/15LPTXADcZGv0ZE262yqdwFHDTnP_R_Bx)

A pre-trained model can be found on the Google Drive [here](https://drive.google.com/file/d/1Wn9kTnS5ioVZ-yJ36ZPtKq3lIbA0npBZ/view?usp=sharing)

You need to be in the umich organization to access the dataset.


## Project Setup

### Option 1: 
The project requires:
```
python 3
numpy
torch
torchvision
opencv
matplotlib
csv
```
Download the repository with SSH by running 
```
git clone git@github.com:wangy319/ROB535-Tean13-Final-Project.git
```
and configure the required enviornment. 

### Option 2: 

To save the effort of downloading and installing the packages, we suggest you to open the jupyter notebook (.ipynb) file using [Google Colab](https://colab.research.google.com/?utm_source=scs-index), by opening the file ["Vehicle_Classification_Team_13_submission.ipynb"](https://github.com/wangy319/ROB535-Tean13-Final-Project/blob/main/Vehicle_Classification_Team_13_submission.ipynb) on github and click on "Open in Colab" button on the top-left of the file. Follow the instructions specified in the document to setup the connection to Drive and play around with the project code. A GPU session is suggested to improve the training and evaluation speed of the model.


## Code Explanation

```
Vehicle_Classification_Team_13_submission.ipynb -> jupyter notebook file
Vehicle_Classification_Team_13_submission.py -> python script that contains the same code as the notebook
```

Code Structure
```
Enviornment Setup
| Colab Setup code
Project Code
| Dataset definition
| Model Definition
| Training -> Will save the checkpoints for every epoch; modify hyper parameters for training.
| Model Evaluation -> Generate .csv file for test-set evaluation

```
Please refer to ["Vehicle_Classification_Team_13_submission.ipynb"](https://github.com/wangy319/ROB535-Tean13-Final-Project/blob/main/Vehicle_Classification_Team_13_submission.ipynb) for more detailed instructions. 



