# Result

## Hyperparameter
- NUM_OF_EPOCHS = 20
- BATCH_SIZE = 16
- LEARNING_RATE (Adam) = 1e-3

## Summary
| word-embedding        | architecture | accuracy | val_accuracy | loss  | val_loss | best_epoch | runtime |
|-----------------------|--------------|----------|--------------|-------|----------|------------|---------|
| Word2Vec ID Wiki 300  | Bi LSTM      | 0.806    | 0.828        | 0.618 | 0.608    | 8          | 50s     |
| Word2Vec ID Wiki 300  | Bi GRU       | 0.814    | 0.837        | 0.593 | 0.566    | 4          | 41s     |
| FastText ID Wiki 300  | Bi LSTM      | 0.802    | 0.797        | 0.622 | 0.694    | 8          | 50s     |
| FastText ID Wiki 300  | Bi GRU       | 0.809    | 0.830        | 0.616 | 0.564    | 8          | 49s     |
| Word2Vec ID Tweet 300 | Bi LSTM      | 0.817    | 0.835        | 0.580 | 0.584    | 4          | 49s     |
| Word2Vec ID Tweet 300 | Bi GRU       | 0.813    | 0.848        | 0.586 | 0.559    | 8          | 56s     |
| FastText ID Tweet 300 | Bi LSTM      | 0.813    | 0.828        | 0.593 | 0.606    | 8          | 1m 5s   |
| FastText ID Tweet 300 | Bi GRU       | 0.816    | 0.826        | 0.574 | 0.579    | 8          | 58s     |

## Best Model Metric
![alt text](https://raw.githubusercontent.com/ksnugroho/feel-in/main/assets/best-baseline-model-bilstm-metric.jpg)

## Training Report
https://wandb.ai/indoemobert/baseline-bilstm/reports/Baseline-Model-Report-Word-Embedding-Bi-LSTM-Bi-GRU--VmlldzoyMTA5MTEw?accessToken=qhxjx3xi37mv6xwk474ta9bnfpdgk0k79e2cqusrnm072mqmrlxdy7gxsxalq5k7
