To simulate actual manufacturing conditions, a synthetic supplier dataset comprising 16,000
records and nine key operational attributes was created. Three categories--Ahead, On-time,
and Late--were used to classify supplier delivery performance. Logistic Regression, Decision
Tree, Random Forest, Bagging, Multilayer Perceptron (MLP), XGBoost, and K-Nearest
Neighbors (KNN) were among the seven machine learning algorithms that were used.
According to experimental results, the Random Forest Classifier outperformed other models
in terms of predictive reliability, achieving the highest performance with a macro F1-score of
0.979.
With the goal to improve transparency, instance-level interpretability was generated using the
Local Interpretable Model-Agnostic Explanations (LIME) technique. According to LIME
visualizations, the factors that had the biggest effects on delivery class predictions were lead
time, supplier capacity utilization, and disruptive events. A transparent, scalable, and
datadriven decision-support tool for supplier risk management in complex supply chain
environments is offered by the suggested framework, which successfully closes the
accuracyinterpretability gap.
