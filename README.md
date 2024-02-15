# Self_Driving_ROAR

Welcome to the official repository for the Robot Open Autonomous Racing (ROAR) project at the University of California, Berkeley. This repository is dedicated to the development and testing of self-driving vehicles using advanced computer vision techniques.

Our primary focus is on training a Convolutional Neural Network (CNN) model for implementing behavior cloning and imitation learning algorithms to control autonomous vehicles. The datasets and models provided here are designed to simulate various driving conditions and scenarios, contributing to the development of robust autonomous driving systems.

## Repository Contents

This section outlines the structure of the Self_Driving_ROAR repository and provides a brief description of each component.

### Files and Directories

- `behaviour_cloning.ipynb`: This Jupyter notebook contains the code for the behavior cloning algorithm. It details the process of training the CNN model with the provided datasets to mimic human driving behavior.

- `datasets`: This directory holds the datasets used for training and testing the models. Each dataset consists of various driving scenarios to ensure comprehensive learning.

- `Figures`: This folder contains figures and visualizations related to the project. These may include model architecture diagrams, performance graphs, and other relevant images.

- `LICENSE`: The license file details the terms under which this project is made available. We use the MIT License, which allows for wide dissemination and use of the project with minimal restrictions.

- `models`: In this directory, you'll find the trained CNN models saved as `.pth` files. These models are ready to be used or further fine-tuned for specific self-driving car applications.

- `README.md`: The README file provides an overview of the project, instructions on how to use the repository, and additional information like the repository structure (this section), demos, documentation, etc.

- `train.ipynb`: Another Jupyter notebook, which focuses on the training aspect of the models. It guides you through the entire process of training the model, from data loading and preprocessing to model training and evaluation.

### Trained models

Below is a table detailing the available models, along with their respective training datasets and characteristics.

| Model              | Model File                     | Trained with Dataset      | Min-Max Labels   | Description                                     |
|--------------------|--------------------------------|---------------------------|------------------|-------------------------------------------------|
| `<Model_Name>.pth` | `models/<Model_Name>.pth`      | `datasets/dataset_14270124` | `[-3, 4.5]`     | Data of small curved roads, predominantly right turns |
| `Net_0127_1529.pth`| `models/Net_0127_1529.pth`     | `datasets/dataset_15270124` | `[-2.75, 4.25]` | Highway driving data                            |
| `Net_0128_1955.pth`| `models/Net_0128_1955.pth`     | `datasets/dataset_1949280124`| `[-7.0, 9.0]`  | Varied directions, includes in-town scenarios   |
| `Net_0203_1745.pth`| `models/Net_0203_1745.pth`     | `datasets/dataset_173953030224`| `[-9.75, 9.25]`| Comprehensive data covering different directions and town environments |

## Getting Started

To begin working with the Self_Driving_ROAR project:

1. Clone this repository to your local machine.
2. Install the required dependencies as listed in the `requirements.txt` file.
3. Explore the datasets and models to understand the scope and nature of the training data.
4. Use the models for behavior cloning and imitation learning in your self-driving car simulations or real-world applications.

## Demos

Explore our demo videos showcasing the performance of the trained models in various scenarios:

- [Demo Video 1](#)
- [Demo Video 2](#)
- [Demo Video 3](#)

Feel free to view these videos to get a better understanding of our models' capabilities and performance in different driving conditions.

## Documentation

Detailed documentation is available to help you understand and utilize the resources in this repository effectively. The documentation covers:

- Model architecture and design
- Training methodologies
- Data preprocessing techniques
- Implementation guides

You can find the documentation [here](#).

## Community and Contributions

Contributions to this project are welcome. If you have improvements or additions, please create a pull request or open an issue to discuss your ideas.

## Issues

For any issues or bugs, please report them in the [Issues](#) section. This helps us keep track of ongoing problems and resolve them in future updates.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is part of the ongoing efforts by the ROAR team at UC Berkeley. We extend our gratitude to all contributors and supporters of this initiative.

