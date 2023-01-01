# Result

## Summary
| dataset                  | method                  | Train    |          | Test     |          |
| ------------------------ | ----------------------- | -------- | -------- | -------- | -------- |
|                          |                         | accuracy | f1-score | accuracy | f1-score |
| human annotation         | DecisionTrain Clasifier | 0.9955   | 0.9955   | 0.784    | 0.7838   |
| ^                        | SVC                     | 0.9431   | 0.9438   | 0.7639   | 0.7651   |
|                         | MultinomialNB           | 0.8629   | 0.8665   | 0.6147   | 0.5704   |
|                         | KNeighborsClassifier    | 0.5167   | 0.4888   | 0.3497   | 0.2795   |
| lexicon-based annotation | DecisionTrain Clasifier | 0.9972   | 0.9972   | 0.6392   | 0.6403   |
| ^                        | SVC                     | 0.8813   | 0.8858   | 0.6125   | 0.6057   |
|                         | MultinomialNB           | 0.7152   | 0.7294   | 0.3808   | 0.3338   |
|                         | KNeighborsClassifier    | 0.5351   | 0.4809   | 0.3363   | 0.2548   |