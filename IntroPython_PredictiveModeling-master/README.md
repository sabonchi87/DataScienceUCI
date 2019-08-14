# CSU-LA/NASA DIRECT-STEM data science workshop
## Introduction to Python and Predictive Modeling

- Instructors: 
    - Preston Putzel (**email:** pputzel at uci dot edu)
    - Casey Graff (**email:** graffc at uci dot edu)

# Schedule

## Day 1

| Time                       | Activity                                                                    |
| -------------------------- |:----------------------------------------------------------------------------|
| **9:00-10:00 am**           | Introductions and course overview                                           |
| **10:00-11:30 pm**          | __Session 1.1__: Coding warm-up                                      |
| **11:30-1:00 pm**          | Lunch
| **1:00-2:45 pm**           | __Session 1.2__: Python's scientific computing infrastructure               |
| **2:45-3:00 pm**           | Break                                                                |
| **3:00-4:00 pm**           | __Session 1.3__: Exploratory data analysis in Python        |

## Day 2

| Time                       | Activity                                                                    |
| -------------------------- |:----------------------------------------------------------------------------|
| **9:00-11:30 am**          | __Session 2.1__: Linear regression                             |
| **11:30-1:00 pm**          | Lunch                                                                       |
| **1:00-2:45 pm**           | __Session 2.2__: Logistic regression                             |
| **2:45-3:00 pm**           | Break |
| **3:00-5:00 pm**           | __Session 2.3__: Intro to version control w/ git and Cloud Computing |


# Workshop preliminaries


- For this workshop we will be using the Anaconda distribution of Python 3.6
- Follow these instructions to download and install Python on your local machine, **even if you already have Python installed!**
- If you already have an Anaconda distribution of Python 3.6 installed, you can probably skip this; otherwise, please continue
- If you *really* think you don't need to install Python, please e-mail me to confirm :)

## Python download & installation instructions 
1. Go to the [Anaconda download page](https://www.anaconda.com/download/)
2. Click on the link to download **Python 3.6** for your system
	- Make sure you grab the correct version for your operating system! Ask if you have any questions
3. Install Anaconda
4. Install Python packages
	- Windows:
		- Open the **Anaconda Prompt** application that installed with Anaconda
		- Enter `conda update conda`
		- Enter `conda install anaconda`

	- Mac and Linux:
		- Open the shell/terminal
		- Enter `conda update conda`
		- Enter `conda install anaconda`
5. Download the workshop repository from the [github repo](https://github.com/caseyagraff/IntroPython_PredictiveModeling)
	- Click the green button on the right 'Clone or download', then click 'Download ZIP'
6. Using your terminal (Mac/Linux) or the Anaconda Prompt (Windows), `cd` to wherever you saved the repository (`cd` is the command for changing directory; so on my system I type `cd Desktop/data_science/teaching/IntroPython_PredictiveModeling` to get to the directory where I put the workshop folder)
7. Open Jupyter notebook by typing `jupyter notebook`; this should open a tab in your internet browser.
8. Click on test_notebook.ipynb to open the test notebook
9. Follow the instructions in the notebook. Contact your instructor if there is an error.
