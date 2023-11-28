# LCCDE-Framework-for-Intrusion-Detection
Welcome to the repository for our cutting-edge cybersecurity solution, the Leader Class and Confidence Decision Ensemble (LCCDE), designed to safeguard smart vehicles from online threats in the era of the Internet of Vehicles (IoV)

This repository contains the code for the project LCCDE: A Decision-Based Ensemble Framework for Intrusion Detection in The Internet of Vehicles. It has two files:

LCCDE_Model.ipynb: The executable code for the project.

CICIDS2017_sample_km.csv: The dataset used for this project.

In today's smart vehicles, like self-driving cars and connected cars, lots of cool features work together with other vehicles and devices. But, because everything is so connected (known as the Internet of Vehicles or IoV), there's a risk of cyber-attacks. To protect these vehicles from online threats, smart systems using Machine Learning (ML) have been created. We came up with a clever system called Leader Class and Confidence Decision Ensemble (LCCDE). It picks the best ML method for each type of attack, like Ada Boost, Isolation Forest, Decision Tree, Naïve Bayes, and RNN model along with existing XGBoost, LightGBM, and CatBoost algorithms. These "leader" models, along with how sure they are about their predictions, help us accurately spot different cyber-attacks. We tested our system on real data from CICIDS2017 datasets, and it worked well for finding intrusions.

Abstract:
In the realm of safeguarding modern vehicles, especially self-driving and connected cars, from cyber threats arising due to internet and device connectivity, this research delves into the realm of Intrusion Detection Systems (IDS). These systems act as vigilant guardians, identifying and thwarting potential attacks on vehicles. The focal point of this study introduces a novel IDS known as "Leader Class and Confidence Decision Ensemble" (LCCDE). Departing from conventional approaches, LCCDE incorporates three sophisticated algorithms—XGBoost, LightGBM, and CatBoost—each offering a distinct perspective on attack detection. 

The innovation lies in allowing these algorithms to specialize in specific threat detection domains. By leveraging the collective results from these diverse algorithms, the IDS achieves heightened decision-making capabilities in discerning the occurrence of cyber-attacks. Through rigorous testing on datasets pertaining to car security, the proposed methodology demonstrated effectiveness in detecting both internal and external threats.

Building upon this foundation, our research introduces a new dimension to the ensemble— Ada Boost, Isolation Forest, Decision Tree, Naïve Bayes, and RNN. These algorithms, known for their robustness and versatility, are seamlessly integrated into the LCCDE framework. The introduction of these algorithms enriches the ensemble, further fortifying the IDS against a spectrum of cyber threats. Through this augmentation, we anticipate not only enhancing the overall performance of the IDS but also advancing the frontier of vehicle cybersecurity. Random Forest works like a wise council within the security team, creating a "forest" of decision trees where each tree offers its opinion on a potential cyber threat. 

This strategic augmentation anticipates not only enhancing the overall performance of the IDS but also propelling the frontier of vehicle cybersecurity. In summary, this research pioneers the application of advanced computer methods to fortify vehicular cybersecurity. This collective effort aspires to usher in a new era of resilient and adaptive intrusion detection systems tailored for the automotive domain, ensuring the continued safety and security of modern vehicles.

Dataset: 
CICIDS2017 dataset contains benign and the most up-to-date common attacks, which resembles the true real-world data (PCAPs).
IDS 2017 | Datasets | Research | Canadian Institute for Cybersecurity | UNB

Code:
LCCDE model for intrusion detection. “https://github.com/ganeshvadlamuri/LCCDE-Framework-for-Intrusion-Detection/blob/main/LCCDE_Model.ipynb”

Machine Learning Algorithms:
•	XGBoost
•	LightGBM 
•	CatBoost
•	Ada Boost
•	Isolation Forest
•	Decision Tree
•	Naïve Bayes
•	RNN model

Tools & Libraries:
•	Python 3
•	Jupyter Notebook
•	Pandas 
•	Numpy 
•	Matplotlib
•	Seaborn 
•	Sklearn
•	Statistics
•	AdaBoostClassifier 
•	DecisionTreeClassifier
•	GaussianNB
•	IsolationForest
•	Tensorflow
•	SimpleRNN

Steps to download and run the code:
Open GitHub Repository: Navigate to the GitHub repository you want to download using your web browser.
https://github.com/ganeshvadlamuri/LCCDE-Framework-for-Intrusion-Detection/tree/main

Click on "Code" Button: On the repository page, click on the "Code" button.
Select "Download ZIP": In the dropdown that appears, click on "Download ZIP.
 

Save the ZIP File: Your browser will prompt you to save the ZIP file. Choose the location on your computer where you want to save the file and click "Save."
<img width="697" alt="image" src="https://github.com/ganeshvadlamuri/LCCDE-Framework-for-Intrusion-Detection/assets/85800035/ed7d4df7-9f30-4dd5-ad87-5747ee9a32bc">


Extract the Contents: Right-click on the ZIP file and select "Extract All" or use your preferred extraction tool to unzip the contents.

Open jupyter Notebook and prepare: Install the libraries mentioned in the Tools & Libraries section.

Code Run: Run the all the cells in LCCDE_Model.ipynb

