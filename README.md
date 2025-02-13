# Steam Data Prediction

This repository contains a neural network prediction model for the thermodynamic properties of steam based on temperature and pressure inputs. The model predicts specific volume, density, specific internal energy, specific enthalpy, and specific entropy.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project combines datasets for compressed, saturated, and superheated steam to create a comprehensive phase diagram for steam. The neural network is trained using over 9,500 data points, providing accurate predictions for various thermodynamic properties.

## Dataset

The dataset includes temperature and pressure as input features with the following output properties:

- Specific Volume
- Density
- Specific Internal Energy
- Specific Enthalpy
- Specific Entropy

The data is consolidated from multiple sources to cover a wide range of steam conditions.

## Model

The neural network is trained using a dataset of 9,500+ data points and designed to generalize well for predicting steam properties across various phases. The key steps involved are:

1. Data Preprocessing: Cleaning, normalization, and splitting of data.
2. Model Training: Using a neural network to fit the thermodynamic property data.
3. Evaluation: Assessing the model's performance using appropriate metrics.

![Image](https://github.com/user-attachments/assets/76ae72c5-a063-4fdb-9e23-38d1685ca061)
![Image](https://github.com/user-attachments/assets/eb68112d-63f8-4b85-ac98-8c4deee308e5)

## Installation

To set up the project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/KadDenuwara/Steam_Data_Prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Steam_Data_Prediction
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the main script to predict steam properties:

```bash
python predict.py
```

You can modify the `predict.py` file to input custom temperature and pressure values for prediction.

## Results

The model demonstrates high accuracy in predicting steam properties across various phases. Detailed evaluation metrics are provided in the `results/` directory.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

For any questions or suggestions, please contact [Kavindu Denuwara](https://github.com/KadDenuwara).

