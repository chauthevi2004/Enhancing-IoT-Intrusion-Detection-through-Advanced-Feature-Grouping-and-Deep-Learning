# Enhancing IoT Intrusion Detection through Advanced Feature Grouping and Deep Learning

## Overview

This project focuses on improving Intrusion Detection Systems (IDS) for Internet of Things (IoT) environments by leveraging advanced feature grouping techniques combined with deep learning models. The goal is to enhance detection accuracy and efficiency in identifying potential security threats within IoT networks.

## Project Structure

The repository contains the following files:

- **Jupyter Notebooks:**
  - `bot-10k.ipynb`: Analysis and model training on a dataset of 10,000 botnet samples.
  - `bot-20k.ipynb`: Analysis and model training on a dataset of 20,000 botnet samples.
  - `bot-100k.ipynb`: Analysis and model training on a dataset of 100,000 botnet samples.
  - `mqqtt-20k.ipynb`: Analysis and model training on a dataset of 20,000 MQTT protocol samples.
  - `mqqtt-100k.ipynb`: Analysis and model training on a dataset of 100,000 MQTT protocol samples.
  - `mqqtt_iot.ipynb`: Comprehensive analysis and model training on MQTT IoT data.

- **Data Files:**
  - `openfe_tmp_data.feather`: Processed feature data used across various notebooks.

## Features

- **Advanced Feature Grouping:** Implements sophisticated techniques to group and select relevant features from IoT data, aiming to improve the performance of the IDS.

- **Deep Learning Models:** Utilizes deep learning architectures to accurately detect and classify potential intrusions within IoT networks.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (e.g., pandas, numpy, scikit-learn, tensorflow, etc.)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/chauthevi2004/Enhancing-IoT-Intrusion-Detection-through-Advanced-Feature-Grouping-and-Deep-Learning.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd Enhancing-IoT-Intrusion-Detection-through-Advanced-Feature-Grouping-and-Deep-Learning
   ```

3. **Install Dependencies:**

   It's recommended to use a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

   Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: Ensure that `requirements.txt` contains all necessary packages.*

### Usage

1. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

2. **Open Desired Notebook:**

   In the Jupyter interface, navigate to and open any of the provided `.ipynb` files to explore data analysis, feature grouping, and model training processes.

3. **Run the Notebook:**

   Execute the cells sequentially to reproduce the analyses and results.

## Data Preparation

Ensure that the `openfe_tmp_data.feather` file is present in the project directory, as it contains the processed feature data required for the notebooks. If this file is not available, you may need to preprocess the raw data accordingly.

## Results

Each notebook provides detailed insights into the performance of the deep learning models, including metrics such as accuracy, precision, recall, and F1-score. Visualizations of feature importance and model performance are also included to aid in understanding the effectiveness of the implemented techniques.

## Contributing

Contributions are welcome. Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request for review.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

Special thanks to the contributors and the open-source community for their support and resources.
