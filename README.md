Markdown
# ML Group Project: Player Performance Prediction

A Machine Learning project focused on analyzing and predicting football player statistics for the 2025-2026 season.

## 📂 Repository Structure

* `.venv/` - Local Python virtual environment.
* `.gitignore` - Specifies intentionally untracked files to ignore.
* `file.ipynb` - Main Jupyter Notebook containing data cleaning and model implementation.
* `players_data-2025_2026.csv` - The primary dataset containing 2025-2026 season statistics.
* `requirements.txt` - Project dependencies and libraries.

## 🛠️ Technical Implementation

The project implements a custom machine learning pipeline as defined in `file.ipynb`:

1.  **Data Preprocessing:** * Filters the dataset to include only players with at least **90 minutes** (`Min >= 90`) of game time to ensure data reliability.
    * Encodes categorical features and scales numerical data for model stability.
2.  **Custom Model Architecture:** * Features a **Vectorized Linear Regression** class built from scratch.
    * Includes a manual implementation of **Gradient Descent** with weight and bias updates.
    * Tracks **Mean Squared Error (MSE)** through a cost history list to monitor convergence during training.

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python 3.x installed on your machine.

### 2. Installation
Clone this repository and set up the environment:

```bash
# Activate the virtual environment
# On macOS/Linux:
source .venv/bin/activate

# On Windows:
.\\.venv\\Scripts\\activate

# Install required dependencies
pip install -r requirements.txt
3. Usage
Open file.ipynb in VS Code or Jupyter Lab and run the cells sequentially to reproduce the training results and performance metrics.

👥 Contributors
Prabhakar – Linear Regression & Gradient Descent Implementation.

Sujan Magar – Hyperparameter Tuning & Model Evaluation.

Aayush KC – Data Preprocessing & Feature Engineering.
