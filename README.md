# ECE4424 Advanced ML Course Project: A Comparative Study of ML Algorithms for Developing an Effective NIDS on UNSW-NB15 Dataset

In this project, we conducted experiments to explore the potential of various machine learning techniques to solve the problem of intrusion and anomaly detection in current 5G RANs. Our goal was to identify the best ML algorithms for our use case, and to analyze and shortlist the most significant features as part of the ablation analysis. We used a comprehensive dataset containing normal and abnormal behaviors of the RAN, and trained and tested decision tree models and generic linear models to achieve our objectives. The experiments were conducted as part of the ECE4424 Advanced ML course at Virginia Tech.

## Summary of Results

- Our results qualify that the best ML algorithms for our use case are decision tree models while the worst ones were generic linear models. We also analyzed and shortlisted the most significant features as part of the ablation analysis.
- On the RF classifier, the accuracy only drops 0.002 when comparing a model with all features and a model with the top 10 features.
- The final model (trained with the top 10 features) achieved good generalization: the accuracy for unseen examples is 0.962 (against 0.977 on the training dataset), with a slight drop of 0.015.
- It is feasible and practical to develop an anomaly detection model using a comprehensive dataset that contains normal and abnormal behaviors.
- For future work, we intend to integrate this model to an ORAN App respecting its architecture and time constraints

## Language and Tools Used

The project was implemented using Python. The dataset used for training and testing the models contained normal and abnormal behaviors of the RAN. 


## Acknowledgments

We would like to acknowledge the ECE4424 Advanced ML course instructors and teaching assistants for their guidance and support throughout the project. 

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

