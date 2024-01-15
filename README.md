Project title: Investigation
Project title: Investigation of the impact of planetary alignments, lunar phases, and economic growth rate on birth rates in the United States.

Overview:
As part of the skills pathway offered by Codecademy.org, this project involved an in-depth analysis to explore possible correlations between planetary alignments, lunar phases, and birth rates in the United States. Throughout the project, I was assisted by ChatGPT, an OpenAI AI language model, which provided guidance and analytical support.

Key steps and methodologies:

Data collection: The project began with the collection of planetary position data from NASA's JPL Horizons system, birth rate data from relevant U.S. databases from the Kaggle website, and finally economic growth data from S&P Global Market Intelligence's Monthly GDP Index. Moon phases were calculated using proprietary Python functions.

Planetary alignment analysis: planetary positions were analyzed to identify cases of alignment within a specified angular threshold. This analysis aimed to investigate whether planetary alignments have any correlation with changes in birth rates.

Consideration of lunar phases: The impact of lunar phases on birth rates was examined. The data were segmented into four groups based on the lunar cycle: new moon, first quarter, full moon, and last quarter. This division was intended to isolate the study by lunar phases.

Adjusting the data for birth rates: To focus on unscheduled spontaneous births, the difference between the mean number of weekday births (containing scheduled deliveries) and the mean number of unscheduled spontaneous weekend births was subtracted from the weekday data (the difference to be subtracted is approximately 4,300). This adjustment was made to account for the small number of unscheduled births.

Inclusion of economic data: Later in the study, economic growth data, specifically the U.S. GDP growth rate, was introduced as an additional variable. This inclusion was intended to explore the possible influence of economic factors on birth rates.

Model development: A machine learning model was developed with the scikit-learn devel

was developed using the Python scikit-learn library. The model combined Principal Component Analysis (PCA) and Linear Regression to predict birth rates as a function of planetary alignments, lunar phases and GDP growth rate. PCA was used to reduce the dimensionality of the data set and identify the most significant features.

Data normalization and model training: Before training the model, data normalization techniques were applied to ensure that the model accurately captured the underlying patterns in the data. The model was then trained with the fitted dataset, which reflected spontaneous birth rates, planetary alignments, lunar phases, and economic indicators.

Analysis and interpretation: The final step involved analyzing the model performance and interpreting the results. This included assessing the accuracy of the model and determining the importance of different features, such as the impact of lunar phases and planetary alignments on birth rates.

Throughout the project, ChatGPT provided assistance with coding, data analysis, and interpretation of the results, demonstrating the potential of AI to support data science projects.

Conclusions:
This project showed the intricate process of data analysis and model building in exploring complex relationships between astronomical events and human activities. It highlighted the importance of data preprocessing, feature engineering and the careful application of machine learning techniques to draw meaningful conclusions from the data. As a relevant fact found, it was verified that there is no correlation between the alignment of planets or lunar phases in the variation of births... so any opinion that, for example, there are more births when there is a full moon, is a full-fledged myth..
