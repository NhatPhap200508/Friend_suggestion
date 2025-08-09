# Friend_suggestion
🔍 Graph Link Prediction using Node Similarity Metrics
📌 Objective
This project predicts the existence of a link (friendship) between two nodes (users) in a social network graph. By calculating similarity scores between pairs of nodes, we use machine learning to classify whether a relationship (edge) exists. The system supports multiple datasets in the format provided by SNAP (Stanford Network Analysis Project).

 👥 Team Members
- Student 1 - Pham Ngoc Hieu - 2430904
- Student 2 - Nguyen Nhat Phap - 2430911
- Instructor: Ph.D Bui Ha Duc - HCMUTE

🛠 Dataset Information

Default dataset: facebook_combine.txt (Facebook network)

Other supported datasets: SNAP Datasets (e.g., twitter_combine.txt, gplus_combine.txt)

You can also add your own dataset in the same format.

📁 Files Overview

sample_positive.txt: All positive relations (i.e., pairs with a connection in the graph)

sample_negative.txt: All negative relations (i.e., pairs without a connection)

training.txt: A mix of both positive and negative relations

features_combined_2.txt: Precomputed features for each relation used to train the model

🧠 Similarity Metrics for Feature Extraction
The following graph scoring methods are used to create features:

Common Neighbors

Resource Allocation Index

Jaccard Coefficient

Adamic-Adar Index

Preferential Attachment

These metrics quantify node similarity based on the graph structure and are used as input features for a classification model.
