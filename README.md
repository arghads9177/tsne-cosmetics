# t-SNE of Cosmetics Data

## Context

Choosing a new cosmetic item can be a daunting task, especially when faced with unfamiliar ingredient lists that are difficult to interpret without a background in chemistry. This project aims to address this challenge by creating a content-based recommendation system that leverages the chemical components of cosmetics. By processing the ingredient lists of 1,472 cosmetics from Sephora, we can visualize the similarity between products using a machine learning technique called t-SNE (t-distributed Stochastic Neighbor Embedding) and the interactive visualization library Bokeh.

## Content

The project focuses on the following key steps:

1. **Data Processing**: Ingredient lists for 1,472 cosmetic products are processed using word embedding techniques to quantify the similarity between different products based on their chemical components.

2. **t-SNE Visualization**: t-SNE, a powerful dimensionality reduction technique, is applied to the word embeddings to create a 2D representation of the ingredient similarities. This allows us to visualize how different products relate to each other in terms of their chemical composition.

3. **Interactive Visualization with Bokeh**: The results of the t-SNE analysis are visualized using Bokeh, an interactive visualization library. This enables users to explore the similarities between cosmetic products and make informed decisions based on their ingredient profiles.

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset of cosmetic ingredient lists used for analysis and modeling.
- `notebooks/`: Jupyter notebooks for data exploration, word embedding, t-SNE analysis, and visualization generation.
- `README.md`: Project overview and documentation.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/cosmetics-tsne.git
## Recommendation System

Based on the t-SNE visualizations, you can create a content-based recommendation system that suggests cosmetics with similar ingredient profiles, helping users choose products that are less likely to cause skin trouble.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact **Argha Dey Sarkar** at `email2argha@gamail.com`.
