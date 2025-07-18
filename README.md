# Clustering and Classification of League of Legends Pro Matches

This repository hosts a midterm project focused on analyzing League of Legends professional match data to uncover spatio-temporal patterns of jungle deaths. The project utilizes advanced data science techniques to provide strategic insights into competitive gameplay.

## Project Objectives

Our primary goals for this project include:

*   **Data Pipeline Development**: Building a robust system for extracting, cleaning, and preparing large-scale League of Legends match data.
*   **Advanced Clustering**: Implementing K-Medoids and K-Means clustering to identify meaningful spatio-temporal patterns of jungle deaths.
*   **Predictive Modeling**: Utilizing Random Forest for regression to predict continuous variables related to game outcomes or player performance.
*   **Technical Analysis**: Interpreting clustering and regression results, including scatter plots, to derive actionable strategic insights.

## Key Accomplishments

We have successfully:

*   Acquired and preprocessed a substantial dataset of professional League of Legends matches.
*   Implemented **K-Medoids and K-Means clustering**, optimizing parameters for spatio-temporal analysis and comparative evaluation.
*   Determined optimal cluster numbers using silhouette analysis and the elbow method for both clustering algorithms.
*   Applied **Random Forest for regression** to predict key game metrics based on analyzed patterns.
*   Performed detailed technical analysis of clustering and regression outcomes, focusing on death locations, temporal patterns, and predictive accuracy.
*   Documented our methodology and findings for reproducibility.

## Technical Insights

The K-Medoids clustering analysis revealed distinct spatio-temporal patterns in jungle deaths, with an optimal four-cluster solution consistently observed across different datasets (total, blue side, red side). This suggests four primary strategic scenarios for jungle deaths in professional play. The analysis highlighted:

*   **Spatial Concentration**: Deaths are concentrated in specific jungle areas, indicating strategic importance.
*   **Team-Specific Patterns**: Blue and red sides exhibit different spatial distributions due to map asymmetry.
*   **Temporal Clustering**: Deaths cluster around critical game timestamps.

Further analysis using **K-Means clustering** provided a comparative perspective on cluster formation and efficiency, while **Random Forest regression** offered insights into the predictive power of our features on game outcomes.

## Future Work

Potential improvements and extensions for this project include:

*   **Enhanced Feature Engineering**: Incorporating additional contextual features like champion types, specific in-game events (e.g., objective control, major team fights), and player roles to enrich the models.
*   **Temporal Weighting**: Implementing time-decay functions to emphasize recent events in the analysis, allowing the models to adapt to evolving game meta and strategies.
*   **Interactive Visualizations**: Developing dynamic and interactive tools for exploring clustering and regression results, enhancing interpretability and usability.
*   **Integration with Game Simulation**: Integrating the findings with a game simulation environment to test and validate strategic recommendations derived from the analysis.
*   **Broader Dataset Inclusion**: Expanding the dataset to include more professional matches from different patches and regions to identify broader trends and validate the generalizability of the findings.

## Job Market Relevance

This project demonstrates skills highly relevant to the data professional job market, including data preprocessing, **K-Means and K-Medoids clustering**, **Random Forest regression**, spatio-temporal analysis, Python programming, and version control. These skills are in high demand across various industries, particularly with the rise of AI and Machine Learning.

## References

*   **Midterm Project Document**: [Midterm Project - Version July 18, 2025](Mid-termproject-July_18.pdf)
*   **Jupyter Notebook**: [Clustering_K-Medoids_Jg-Spatio-temporal-deaths.ipynb](Clustering_K-Medoids_Jg-Spatio-temporal-deaths.ipynb)
*   **Research Paper (Inspiration)**: [TM_Rui_Roque.pdf](TM_Rui_Roque.pdf)
*   **GitHub Repository**: [ALOBlack19/Clustering-and-Classification-of-League-of-Legends-Pro-Matches](https://github.com/ALOBlack19/Clustering-and-Classification-of-League-of-Legends-Pro-Matches)
*   **Original Research Paper (Rui Roque)**: [https://repositorio.ulisboa.pt/handle/10451/61680?mode=simple](https://repositorio.ulisboa.pt/handle/10451/61680/1/TM_Rui_Roque.pdf)
*   **Original Research Paper PDF**: [https://repositorio.ulisboa.pt/bitstream/10451/61680/1/TM_Rui_Roque.pdf](https://repositorio.ulisboa.pt/bitstream/10451/61680/1/TM_Rui_Roque.pdf)
*   **Related GitHub Repository**: [Bambito9/Esports-Games-Data-Analysis](https://github.com/Bambito9/Esports-Games-Data-Analysis)
*   **GitHub Profile**: [Redck9](https://github.com/Redck9)


