# Individual Risk Assessment Metric (PhD Project)

## Overview
This repository contains the code for a PhD project by Boyan Markov focused on developing an individual risk assessment metric. The project aims to advance the methodology in risk assessment by providing a nuanced approach to evaluating risks at an individual level, which can be applied across various domains such as finance, healthcare, and security. The code is implemented in a Jupyter notebook and is designed to be accessible and modifiable for further research and application.

## Installation

### Prerequisites
To run this project, you will need:
- Python 3.6 or later
- Jupyter Notebook
- Libraries as specified in the `requirements.txt` file

### Setup
Clone the repository and install the required Python libraries using the following commands:
```bash
git clone https://your-repository-url.git
cd your-repository-directory
pip install -r requirements.txt
```

## Usage

### Running the Notebook
To explore and run the individual risk assessment metric code, open the Jupyter notebook as follows:
```bash
jupyter notebook BART_Code.ipynb
```
Ensure you follow the instructions within the notebook for setting up your environment, especially if using cloud services like Google Colab for execution.

### Modules Description
The notebook is structured into several sections, starting with the import of necessary libraries and dependencies. It progresses through data preprocessing, model training, and the computation of the risk assessment metric. Each section is accompanied by detailed markdown explanations to guide the user through the process.

## Data
The project utilizes three datasets (risktaskResults (1).xlsx, risktaskResults-retest.xlsx, risktaskResults.xlsx) containing individual responses to a series of risk assessment tasks. These datasets include demographic information (age, sex, specialty), and a detailed account of each participant's decisions across 50 trials, capturing metrics such as the number of times collected, whether the participant has fallen, the life count at each trial, the number of pumps per balloon, and the time taken for each decision.

Each dataset is structured to provide a comprehensive view of risk-taking behavior, with the following notable features:

Unique identifiers for participants (user ID or email)
Trials indexed from 0 to 49, with metrics for each trial
Additional attributes like datetime and tags in the retest dataset to categorize sessions or conditions
These datasets are crucial for replicating the study's findings and further experimenting with the risk assessment metric on similar datasets. Users interested in utilizing this data should ensure they carefully handle personal identifiers and comply with any relevant data protection regulations.

## Contributing
We welcome contributions to this project! If you have suggestions for improvements or encounter any issues, please feel free to submit an issue or pull request on GitHub.

## License
This project, including the code and datasets, is protected under a custom license that mandates specific conditions for its use, ensuring the original authors receive proper acknowledgment. Anyone wishing to utilize this project for any purpose is required to obtain direct permission from the creators and must cite and credit the following author and institution:

Author: Boyan Markov
Institution: University of National and World Economy (UNWE)
Conditions for Use:

For any form of utilization beyond personal review, including but not limited to commercial use, academic research, or educational purposes, direct permission must be sought from Boyan Markov.
Upon receiving permission, appropriate credit must be given in any publications or disseminations of the work derived from or incorporating elements of this project, with a formal citation to Boyan Markov and UNWE as specified by the author.
This license allows for the widespread use and modification of the project materials, subject to the aforementioned conditions, to foster academic collaboration, innovation, and respectful utilization of the original work.
How to Obtain Permission:

Please contact b.r.markov[at]gmail.com for permissions, licensing inquiries, or further information regarding the use of the project materials.
By using or engaging with the project in any capacity, you acknowledge and agree to these terms, ensuring the respectful and ethical use of the provided materials.


