# Projektarbeit
## 1. Overview
This project focuses on implementing a machine learning model for predicting the outcome of soccer matches, with the goal of achieving the highest possible prediction accuracy. A Random Forest algorithm is used as the core machine learning model, which uses various match-related data such as team performance, statistics, and other relevant features to predict whether a team will win, lose, or draw. By analyzing historical match data, the model is designed to optimize the accuracy of future football match predictions.

## 2. How-To Run ?

The following steps outline one methode to execute the project. Please note that this process requires the installation of **Miniconda**. **Miniconda** is a minimal installer for **Conda**, a package management system and environment management tool.

1. **Install Miniconda:**
   - Download and install Miniconda from the official website: [Miniconda Installation](https://docs.conda.io/en/latest/miniconda.html)
   - Follow the installation instructions for your operating system.

2. After installing Miniconda, open the **terminal** and create a new environment using the following command:
   ```conda create --name myenv python=3.8```

3. Activate the Environment:
   ```conda activate myenv```
4. To run the projekt following packages have to be installed: numpy, pandas, matplotlib, scikit-learn, pip, soccerdata
    ```conda install numpy, pandas, matplotlib, scikit-learn, pip```
5. soccerdata is a package which is not included in the **Conda** libery to install use following command:
   ```pip install soccerdata```
6. After successfully installing all packages you can open the jupyter notebook and run the project.
   - to run the project use following command:
   ```jupyter notebook```
      


