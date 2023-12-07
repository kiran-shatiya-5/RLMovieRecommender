
# Enhancing Movie Recommendations with Reinforcement Learning and Collaborative Filtering

## Overview

This project implements and compares two movie recommender systems: Collaborative Filtering and a Deep Q-Network (DQN) based recommender system using TensorFlow Agents (TF-Agents). The goal is to recommend movies to users based on their preferences and interactions.

## Table of Contents

- [Collaborative Filtering](#collaborative-filtering)
- [TF-Agents Recommender System](#tf-agents-recommender-system)
- [Comparison](#comparison)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Collaborative Filtering

Collaborative Filtering is a classic recommendation technique that relies on user-item interactions. In this project, we implemented a Collaborative Filtering model using Singular Value Decomposition (SVD). The model achieved an RMSE of approximately 0.94 on the test data.

## TF-Agents Recommender System

The TF-Agents-based recommender system utilizes reinforcement learning techniques to make movie recommendations. A custom environment simulates user interactions with movie recommendations. We trained a DQN agent to learn a policy for selecting movies to recommend. The agent's performance is assessed using the average return metric.

## Comparison

Initially, the TF-Agents recommender system started with an average return of -1.55, indicating a suboptimal policy. Through hyperparameter tuning and training, the average return improved significantly, reaching a final value of 62.0. This represents a substantial enhancement in the agent's ability to make movie recommendations.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/yourusername/movie-recommender.git
   cd movie-recommender
   ```

2. Save the python notebook file (.ipynb) and import it on Google Colab.


3. Run the Collaborative Filtering and TF-Agents models as described in the Usage section.

## Usage

To use the Collaborative Filtering and TF-Agents models, follow the instructions in their respective directories:

- [Collaborative Filtering](collaborative-filtering/README.md)
- [TF-Agents Recommender System](tf-agents-recommender/README.md)

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This README provides an overview of your project, instructions for getting started, details about the two recommender systems, and information on how others can contribute to your project. You can further customize it to include specific installation instructions, usage examples, and other relevant details about your project. Don't forget to include any necessary images or screenshots to make your README more visually appealing.
