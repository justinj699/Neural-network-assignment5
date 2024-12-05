#Assignment-5-Data Tools

Neural Networks, inspired by the human brain, process information using interconnected nodes. These nodes take inputs, apply weights and biases, pass the result through an activation function, and produce outputs. The network has layers: input for data, hidden for processing, and output for predictions.

In this assignment, we worked on the drug.csv dataset, analyzing it using a neural network to understand its structure and insights. Multi-layer networks, like those used here, handle complex, non-linear relationships, forming the basis of modern AI systems.

##Getting Started
This guide offers a detailed walkthrough for setting up and running the project on your local machine. It assumes a basic understanding of programming, with Python as the primary language used. If you are new to Python, it is recommended to learn its fundamentals before moving forward. In addition to setup instructions, the guide includes a comprehensive section on deploying the project in a live environment. This section provides practical advice on achieving seamless integration and functionality, ensuring the project moves smoothly from development to an operational phase.

###Prerequsites
1. GIT (Optional)
2. Anaconda navigator
3. Dataset to run the neural network algoritim

####Installation

Follow these simple steps To set up your environment:

Go to the Anaconda website:
Open your web browser and visit https://www.anaconda.com/download. This is where you can find the software needed for this project.

Download the installer:
On the download page, choose the version that matches your operating system. You can select MacOS,Windows, or Linux depending on the software you are using. Once selected, click the download  to save the installer file to your computer.

Install Anaconda:
After the file is downloaded, locate it in your "Downloads" folder and double-click on it to start the installation. Follow the on-screen instructions. You can keep the default settings unless there are any specific requirements.

Open the Anaconda application:
After installation, locate the Anaconda application on your system. On Windows, check the Start Menu, while on macOS or Linux, use the search function to find "Anaconda Navigator."

Launch Jupyter Notebook:
In Anaconda Navigator, you’ll find various tools. Select "Jupyter Notebook," which will launch a new tab in your default web browser.

Alternative way to open Jupyter Notebook:
You can also search for "Jupyter Notebook" in your computer’s search bar and click on it to open directly.


##### Code Execution
Step 1: Clone the Repository (If Git is Installed)

•	Open your command prompt (Windows) or terminal (Mac/Linux).
•	Use the git clone command to copy the repository to your computer.
•	This will create a folder containing all the project files.

Step 2: Download as a ZIP File (If Git is Not Installed)

•	Visit the repository page in your browser.
•	Click the Code button (usually green) and select Download ZIP.
•	Save the ZIP file to your computer and extract it using a file extractor (e.g., Windows File Explorer or macOS Archive Utility).


Step 3: Open Jupyter Notebook
•	Open Anaconda Navigator and click Jupyter Notebook to launch it in your default web browser.
•	Navigate to the folder where you cloned or extracted the project files.
•	Open the file named Assignment-4.ipynb.


Step 4: Run the Code

1.In the notebook, you’ll see blocks of code called cells.
To run a cell:
Click inside it and press Shift + Enter, or

2.Click the Play button in the toolbar.
Run each cell in order, one at a time.

###### Explaining Code

##Installing the libraries

To set up the environment, install the necessary libraries using pip:

Neural Network Classifier Overview

The Neural Network Classifier is configured with the following settings:

hidden_layer_sizes=(5, 4, 5): Three hidden layers with varying sizes to balance model complexity.
activation='relu': Speeds up training by mitigating the vanishing gradient issue.
solver='adam': Optimizer that adapts the learning rate, requiring minimal manual adjustment.
max_iter=10000: Caps the training process at 10,000 iterations, with early stopping if convergence is reached.
random_state=100: Ensures reproducibility by controlling the randomness.

Model performance is evaluated using:

Confusion Matrix: Displays a comparison of predicted and actual values, showing true positives, true negatives, false positives, and false negatives.
Classification Report: Includes metrics like precision (accuracy of positive predictions), recall (ability to detect positive cases), F1-score (balance between precision and recall), and support (class distribution).
Decision Tree Classifier Overview
The DecisionTreeClassifier is initialized with random_state=100 to ensure consistent and reproducible outcomes.

Performance evaluation metrics:

Confusion Matrix: Highlights the accuracy of predictions by comparing predicted and actual values for all classes.
Classification Report: Provides detailed metrics such as precision, recall, F1-score, and support to measure the effectiveness of the model.

###### Authors

•	Justin Joseph

####### License
This project is licensed under the MIT License - see the LICENSE.md file for details

####### Acknowledgment

•	Rejoy James, DATA 1202-03 DATA ANALYSIS TOOLS ANALYTICS














