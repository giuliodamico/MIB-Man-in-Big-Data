# MIB-Man-in-Big-Data

Team members: Giulio D'Amico - Alexis Mitracos - Marco Astrologo

## Reply Project: Classical vs Multi Agents

This project investigates two alternative approaches for transit anomaly detection in airport and border-control data: a classical machine learning pipeline and a multi-agent architecture. The main objective is to implement the same anomaly detection system twice and then compare the two solutions in order to understand which approach is more suitable under different operational conditions.

The application scenario is motivated by the need to move from reactive anomaly detection to a more proactive analytical system. Border control authorities and airport operators manage large volumes of passenger transit data every day, including information such as timestamps, gates, routes, nationality, document type, control outcomes, and security alerts. In this context, identifying unusual patterns early can help prevent operational issues and support security monitoring.

In the classical implementation, anomaly detection is performed through a structured pipeline including data preparation, feature engineering, historical baseline construction, anomaly detection algorithms, and rule-based post-processing. In the multi-agent implementation, the same logic is distributed across specialized agents, each responsible for a specific task such as querying data, building historical baselines, detecting outliers, applying risk rules, and generating a final report.

The goal of the project is not only to detect anomalies, but also to provide a comparative analysis of the two paradigms in terms of modularity, interpretability, scalability, flexibility, and practical usability. The final output is a transit anomaly report highlighting suspicious patterns and supporting the discussion on the advantages and limitations of each approach.
