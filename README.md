# Advanced Data Scinec - TU Berlin [Part-2]

> Training material and references Data Science training with Python.

## Contents
This repository contains training material in the form of references, example notebooks, and some challenging exercises. These exercises try to cover machine learnings basics such as time-series analysis, visualization analysis, as well as clustering, classification and network analysis techniques.

> You can find the link to the slides for this training [here]

## Prequisite knowledge
For this training, we assume a basic knowledge of Python ecosystem used for data science. Basic knowledge of:
- python moduled such as numpy, pandas, matplotlib and seaborn. 
- Jupyter notebook
- data visualization

## Acknowledgments
This repository would not exist without the work of many great minds. In particular we would like to acknowledge `Kaggle` for being awesome with their contests and varied data sets

## Disclaimer
This repository is solely meant for training purposes. We tried to include links to the original sources where possible. People are free to fork this repository and add more exercises, links, tutorials, and examples.

---
# Submit Homework
In order to submit you homeworks you need follow these steps:

### 1- Forking the repository
Firstly `Fork` this repository by clicking on `Fork button` on the top-right corner of the repository
<img width="476" src="https://user-images.githubusercontent.com/8464089/172586015-befb9e2d-3521-4a2f-b5ec-7d9764820d96.png">
This will allow you to create a copy of the repository and then you can make changes without affecting the upstream repository
### Cloning your forked repository
At this point you have a fork of this repository on your github but you do not have the files on your local computer.
1) Go to your github (github.com). click on your profile picture on the top-righ corner and select `Your repositories`.
(![Screen Shot 2022-06-08 at 11 50 05 AM](https://user-images.githubusercontent.com/8464089/172587608-06c771a4-b1d5-4fa2-8664-55c021e82f84.png)
2) Find the `Data-Science-Training-Python-Part-2` and navigate to the fork repository.
3) Above the list of files, click `Code`.
<img width="476" src="https://user-images.githubusercontent.com/8464089/172588270-f8d227ee-e149-40fc-9908-df88ee064b96.png">
4) Copy the URL for this repository
5) Open `Terminal` and change your current working directory to the location where you want to have this repository by typing following and replace `LOCAL-PATH-TO-REPOSITORY` with your actual path:

```console
cd LOCAL-PATH-TO-REPOSITORY
```
7) Type `git clone` and paste the URL. It will look like this, with your GitHub username instead of YOUR-USERNAME:

```console
git clone https://github.com/YOUR-USERNAME/Data-Science-Training-Python-Part-2.git
```
9) Press `Enter` and you will see that it will download the repository into your local computer.

### Do your homework
1) Copy the exercise that you want to work on from the `exercises` into `homeworks` using the following command:
```console
cd LOCAL-PATH-TO-REPOSITORY/Data-Science-Training-Python-Part-2
cp exercises/NAME-OF-EXERCISE-FILE.ipynb homeworks
```
2) Now that you have a copy version of the exercise in the `homeworks` go to this folder and start working on your solution. You can start working on the `ipynb` file using Jupyter Notebooks

### Commit and Push your changes
In order to save your changes on the fork you need to do write the following commands in yout Terminal:
```console
cd LOCAL-PATH-TO-REPOSITORY/Data-Science-Training-Python-Part-2/homeworks
git add .
git commit -m "PUT-SOME-COMMIT-MESSAGE-HERE"
git push origin main
```
> don't forget to put `"` before and after your commit message

### Open pull request to submit your homework
Once you have done with your homework you need to follow these steps to submit it:
1) Click on this [link](https://github.com/Advanced-Data-Science-TU-Berlin/Data-Science-Training-Python-Part-2/compare)
2) Click on the `compare across forks`
<img width="476" alt="Screen Shot 2022-06-08 at 12 27 57 PM" src="https://user-images.githubusercontent.com/8464089/172594755-a0529e26-5581-48a3-8572-1a5c8f7e3f68.png">
3) in the `head repository` drop-down, find and select your fork which should be something similar to this:

```
YOUR-USERNAME/Data-Science-Training-Python-Part-2
```
5) In the description part mention your team members and team-id
6) Click `Create pull request`

Well Done! :)
8) 
